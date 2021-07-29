# Live stats from the National Judicial Data Grid (NJDG)

### Objective

To capture the value of six counter widgets that are present on the NJDG dashboard. 

### What's inside cases.txt ?

1. Total Civil Cases
2. Total Criminal Cases
3. Total Cases
4. Civil Cases more than 1 year old
5. Criminal Cases more than 1 year old
6. Total Cases more than one year old

### Note

- The numbers will be updated on a set frequency. Currently the script runs twice a day to check if the numbers are updated on the NJDG portal.
- The script only checks the numbers for the District Courts and not the High Courts. Though one can follow the exact same logic to capture those values as well.

This work from inspired from [Simon Wilson's](https://github.com/simonw) post about `git-scraping`. You can read it [here](https://simonwillison.net/2020/Oct/9/git-scraping/)
