# README.md

## The Enchantment's Lottery

The Enchantments are a protected area of the Alpine Lakes Wilderness in Washington state. The USFS has [published data for a few years now](https://www.fs.usda.gov/detail/okawen/passes-permits/recreation/?cid=fsbdev3_053607) of the lottery results. 

This repository uses the results data to perform a series of statistical calculations to determine the probability of winning a permit given the options applied for. In addition to the probabilities, data is provided on general stats (i.e., total applications, total awarded).

There are folders for each year that contain the original data file used for the year as well as `.ipynb` files for cleaning and analyzing. The most friendly files in each year's folder is the `analysis.ipynb` file for that year. It contains the analysis of the data results for that year. 

## Setting Up Repository

Clone the repository, just like any other, to a local folder. In your command line application, navigate to the repository folder and run `$ pip install -r requirements.txt`.

The project was created using Python version 3.12.2. So you _may_ need to upgrade Python. 

You should now be able to execute the cells in the notebook files.

## Additional Reading

Below is a list of posts I've written and published in regards to to the lottery data and analysis:

- [Avoiding Bad Advice on Winning the Enchantment's Lottery (Part I)](https://retz.blog/posts/avoiding-bad-advice-on-winning-the-enchantments-lottery)
- [Avoiding Bad Advice on Winning the Enchantment's Lottery (Part II)](https://retz.blog/posts/avoiding-bad-advice-on-winning-the-enchantments-lottery-part-ii)
- [Evaluating Enchantment Lottery Performance: Awarded-to-Skipped Ratio](https://retz.blog/posts/evaluating-enchantment-lottery-performance-awarded-to-skipped-ratio)
- [Extracting 2023 Enchantments Lottery PDF-to-CSV](https://retz.dev/blog/extracting-2023-enchantments-lottery-pdf-to-csv)
- [Advice on Winning the Enchantment's Lottery (2023 Data Update)](https://retz.blog/posts/advice-on-winning-the-enchantments-lottery-2023-update)
