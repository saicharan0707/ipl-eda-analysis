# IPL Matches - Data Analysis

so i was trying to find a good dataset to do eda on and ended up picking ipl 
because i follow cricket and thought it would be more interesting than 
doing it on some random dataset.

the dataset has 900 matches from 2008 to 2022 with details like teams, 
venue, toss result, win margin etc.

## what questions i tried to answer

- which team has won the most matches overall?
- does winning the toss actually help in winning the match?
- which venues hosted the most matches?
- do teams prefer batting or fielding after winning toss?
- how do teams usually win - by runs or by wickets?
- which players won player of the match the most times?
- how did match counts change across seasons?

## what i found

- winning toss doesnt guarantee winning the match - its almost 50/50
- most teams prefer to field first after winning toss
- wins by wickets are more common than wins by runs
- average win margin is around 30-40 runs when batting side wins

## tools and libraries

- python 3.12
- pandas - for loading and cleaning data
- numpy - for calculations
- matplotlib and seaborn - for all the charts
- jupyter notebook - for writing the analysis

## how to run
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook
then open eda.ipynb and run all cells one by one

## files

- eda.ipynb - main analysis notebook with all charts
- ipl_matches.csv - the dataset i used

made by saicharan | rgukt basar
