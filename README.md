# StatCan_EcoVariables Extraction
Zhenzhen's SIX questions @ April 20, 2929 Day #17 file (questions being posted on April 21, 2020) 

Questions 1
what does the command actaully mean/do? "sc = StatsCan()" 

Question 2
Why print(df_n) shows nothing????
" 
df_n=df.rename(columns={"v65201210":"allindustries", "v65201229":"affh","v65201236":"mining","v65201263":"manufacturing", "v65201419":"realestate","v65201468":"accomfood"}, inplace=True)
print(df_n)
"

Question 3
How to view multiple months/years (not continuous years)? Say I want to view all columns in Year 2002, year 2013, and year 2016
I tried both df[''] and df.loc['']...but neither of them worked

Question 4:
the percentage format in the csv file doesn't show as expected... I want the format to be like, say 23.30% but "float_format = "%.2f"" doesn't gave me the desired results

Question 5:
How can I make the notes in excel file look NEAT - I only want the notes to be shown in one row only (now it's in every row)
"df_annual['notes']='Data Source: https://www150.statcan.gc.ca/n1/pub/13-607-x/2016001/230-eng.htm;Canada; Unit and Multiplier:Dollars, Millions, Seasonally adjusted at annual rate; Annual average; chained(2012) dollars'"

Question 6:
How to change one index lable? I tried the command below, but nothing changed...
df_annual.rename(index={'2020':'2020-Jan'}, inplace=True)
df_annual
