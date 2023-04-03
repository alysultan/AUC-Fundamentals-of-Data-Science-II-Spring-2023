# Glioma Grading Clinical and Genetic Mutation

![Glioma](https://newsnetwork.mayoclinic.org/n7-mcnn/7bcc9724adf7b803/uploads/2018/06/a-medical-illustration-of-glioma-original.jpg)

Gliomas are the most common type of primary brain tumor. Depending on the histological/imaging criteria, they can be classified as LGG (Lower-Grade Glioma) or GBM (Glioblastoma Multiforme). Clinical and molecular/mutation factors are also important for grading. Molecular tests to aid in the accurate diagnosis of glioma patients are costly. The most frequently mutated five genes and three clinical features from the TCGA-LGG and TCGA-GBM brain glioma projects are included in this [dataset](glioma.tsv).

The following is the description of the different columns in the dataset:

| Column | Description |
| - | - |
| ID | Patient ID |
| Grade | Glioma grade class information (1 = GBM; 0 = LGG) |
| Sex | Sex (0 = male; 1 = female) |
| Age_at_diagnosis | Age at diagnosis |
| Race | Race (0 = white; 1 = black or african American; 2 = asian; 3 = american indian or alaska native) |
| TP53 |  tumor protein p53 (0 = NOT_MUTATED; 1 = MUTATED) |
| PTEN |  phosphatase and tensin homolog (0 = NOT_MUTATED; 1 = MUTATED) |
| EGFR |  epidermal growth factor receptor (0 = NOT_MUTATED; 1 = MUTATED) |
| NF1 |  neurofibromin 1 (0 = NOT_MUTATED; 1 = MUTATED) |
| NOTCH1 |  notch receptor 1 (0 = NOT_MUTATED; 1 = MUTATED) |

After loading the dataset as shown in this notebook, answering the following questions:

- Q1: What is the median age at diagnosis for both Glioblastoma Multiforme (GBM) and Low-Grade Glioma (LGG)? (5 points numerical answer + 5 points graphical answer)
- Q2: Which glioma grade has a higher prevalence in males compared to females? (5 points numerical answer + 5 points graphical answer)
- Q3: What is the median age at diagnosis for Glioblastoma Multiforme (GBM) and Low-Grade Glioma (LGG) when considering sex? (5 points numerical answer + 5 points graphical answer)
- Q4: Is there a difference in age at diagnosis based on the patient's race? (5 points numerical answer + 5 points graphical answer)
- Q5: Among the five mentioned genes, which one is more frequently mutated in each glioma grade? (5 points numerical  + 5 points graphical answer)
- Q6: Do mutation frequencies of the mentioned genes vary according to the patient's race? (5 points numerical answer + 5 points graphical answer)
- Q7: In individual patients, who has the highest number of mutations across all the mentioned genes? (5 *bonus* points numerical answer)

## Instructions:
To begin, open this [notebook](glioma.ipynb) in Google Colab, make a copy in your Google Drive, and then rename it using the following format: `firstname_lastname_glioma.ipynb`.

The data has already been loaded into the notebook, and the necessary packages have been imported. You are welcome to import additional packages if required.

Once you have completed your work, download the `.ipynb` file by going to the menu: File > Download > `.ipynb`. 

Please ensure that you submit your notebook to Google Classroom before the deadline.

Good luck!