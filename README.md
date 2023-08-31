# punnett_square
The [**Punnett square**](https://en.wikipedia.org/wiki/Punnett_square) is a square diagram that is used to predict the genotypes of a particular cross or breeding experiment.

## how does it work
This script first prompts you to input number of crosses. It then generates genes assuming two different forms per gene represented by upper-case and lower-case letters starting from 'Aa', 'Bb', etc.

Then it generates all possible allele combinations (gametes), initializes a DataFrame with these combinations as both row indices and column names, fills in this DataFrame with all possible combinations of these gametes, and writes this DataFrame to an Excel file.

You can color Excel cells that have the same gametes, or you can also calculate the phenotypic ratio.
