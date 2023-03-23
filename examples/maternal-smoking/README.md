# Maternal Smoking and Birth Weight

![Maternal Smoking](images/smoking.jpeg)

Maternal smoking has been shown to have harmful effects on the newborn, including reduced birth weight. This [dataset](smoking.tsv) is a subset of a much larger study by the Child Health and Development Study (CHDS) that was conducted over several years.

The columns included in the subset described in the table below:

| Column | Description |
| -- | -- |
| `id` | id number |
| `date` | birth date |
| `gestation` | gestation days |
| `weight` | birth weight in ounce (999 unknown) |
| `parity` | 0=first born |
| `mom.race` | mom race |
| `mom.age` | mom age in years |
| `mom.edu` | mom eduction 0=(<8), 1=(8-<12), 2=12, 3=12+trade, 4=12+some college, 5=16, 6, 7 trade (hs unclear), 9 = unknown |
| `mom.height` | mom height in inches |
| `mom.weight` | mom prepreganncy weight in pounds |
| `dad.race` | dad race |
| `dad.age` | dad age |
| `dad.edu` | dad eduction |
| `dad.height` | dad height |
| `dad.weight` | dad weight |
| `marital` | 1=married, 2=seperated, 3=divorced, 4=widowed, 5=never married |
| `income` | total income in 2500 increements 0=under 2500, 1=2500-4999, ...., 9=15000+, 98=unknown, 99=not asked |
| `smoke` | mom smoking
| `quit.time` | how long ago quit 0=never, 1=still, 2=during preggancy, 3=1 year, 4=2 years, 5=3 years, 6=4 years, 7=5-9 years, 8=10+ years, 9=quit and don't know when, 98=unknown |
| `cigs` | number of cigs smoked a day for past and current smokers 0=never, 1=1-4, 2=5-9, 3=10-14, 4=15-19, 5=20-29, 6=30-39, 7=40-60, 8=60+, 9=smoke but don't know, 98=unknown |

Given the [dataset](smoking.tsv), address the following questions visually and numerically, if possible, and state your conclusion:

<img src="images/baby.jpeg" width="300px" align="right" style="border-radius: 30px;">

- **Q1.** Does the mom's smoking pattern affect the newborn birth weight?
- **Q2.** Does the mom’s race affect the newborn birth weight?
- **Q3.** Is there a correlation between the mom’s weight and the baby’s weight?
- **Q4.** Is there a correlation between the dad’s weight and the baby’s weight?
- **Q5.** From Q3 and Q4, which is a stronger correlation?
- **Q6.** Is there a correlation between the mom’s weight and the dad’s weight?
- **Q7.** On average, does the mom’s weight change across the races?
- **Q8.** Does mom’s smoking pattern change with the mom’s education?
- **Q9.** Does mom’s smoking pattern change with the family income?
- **Q10.** Is there a relationship between the mom’s race and the dad’s race?

You can start by **copying** [this notebook](smoking.ipynb) into your Google Colaboratory.

## Resources
Here are some cheat sheets that might be helpful:
- [Pandas Cheat Sheet](resources/Python_Pandas_Cheat_Sheet.pdf)
- [Matplotlib Visualization](resources/Python_Matplotlib_Cheat_Sheet.pdf)
- [Seaborn Visualization](resources/Python_Seaborn_Cheat_Sheet.pdf)
- [Visual Vocabulary](resources/visual-vocabulary.pdf)

