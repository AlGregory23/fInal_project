# Final Project for Data Journalism (J296) at UC Berkeley
By Albert Gregory
<br>
<br>
Data Analysis:
* Download the 'Suicide, Deaths per 100,000 Population (LGHC Indicator)' [data sheets](https://data.ca.gov/dataset/suicide-deaths-per-100000-population-lghc-indicator) as .csv files, upload it to Google Drive, and open with Google Sheets. 
<br>
Here are five questions and step-by-step instructions to the answers based on the data sets:
<br>

Question 1: What is the rate of suicide for men compared to women in CA from 2000-17?
<br>
Step-by-step answer:
1. Insert Pivot table (while selection A1 through I55) and title it Question 1. men v women rates 2000-17
![step-1_q1](/step-1_q1.png)
* Add rate as value
* Add Strata Name as rows
<br>

!['Q1 pivot table'](/q1-pivot-table.png)
<br>
Answer: The suicide rate among men from 2000 to 2017 in California is 275.14 per 100,000, which is more than three times the rate among women of 80.826 per 100,000 over that same period of time. 

Question 2: How do suicide rates compare among different races in CA?
<br>
Step-by-step answer:
1. Copy column headers, create a new sheet title 'race' and paste column headers
* select A56:I675 to select all data with race listed as strata, copy and paste to sheet titled 'race'
!['Q2 screenshot'](/step-1_q2.png)
* Go to 'race' tab and insert pivot table of all data from 'race' sheet
* Select values as rate
* Select rows as strata name

!['Q2 pivot table'](/q2-pivot-table.png)

Answer: The suicde rate among white people is much higher than other races per 100,000 at 5342.74. The next closest rates are 760.463 for the hispanic population and 579.219 for the Asian population per 100,000. But this does not take into account that the white population is much higher than other races. For example the white population was more than five times the asian population in 2020, according to the [US Census Bureau](https://www.census.gov/quickfacts/CA). 

Question 3: Have suicides increased from 2000 to 2017? By how much?
<br>
Step-by-step answer:
1. Insert Pivot table (while selection A1 through I55) and title it Question 3. rate increase over time
* add rate as value 
* add strata name and year to rows

!['Q3 pivot table'](/q3-pivot-table.png)

Answer: The rate of suicides among both men and women has seen an increase of 1.5 per 100,000 from 2000 to 2017. While the rate has steadily increased there have been slight dips, in 2004, 2007, 2012, 2015, and 2017, but nothing significant. 

Question 4: What county has the highest rate of suicides in CA?
<br>
Step-by-step answer:

1. Copy column headers, create a new sheet title 'counties' and paste column headers
* Selected A56 through I1405 to just highlight the rows with counties listed in geography column and paste it to sheet titled 'counties'
!['Q4 spreadsheet'](/counties-spreadsheet)

* Insert Pivot table and title it 'rate in counties'
* Insert rate as vaues and geography as rows
* copy the data, without the headers, and paste into column j and k of 'counties' spreadsheet
* In row k above the rates select sort z to a 
 
!['Q4 pivot table'](/q4-pivot-table)

Answer: The California counties with the highest suicide rates from 2000-17 per 100,000 are: Humboldt (554.248), Shasta (550.98), Sacramento (483.08), Lake (471.64) and San Diego (465.277). 

Question 5: What county has the lowest rate of suicides in CA?
<br> 
Step-by-step answer:
1. Copy the first five steps for Question 4. 
* For the final step instead sort column k in the 'counties' spreadsheet a to z. 

!['Q4 pivot table'](/q5-pivot-table)

Answer: The California counties with the lowest suicide rates from 2000-17 per 100,000 are: Colusa (24.28), San Benito (27.795), Glenn (142.61), Kings (148.781) and Del Norte (177.82) 

Story:



Data Viz 1:

* Bolded top row and froze it
* formatted numbers for denominators in column G
* Move column d (strata) over two columns 
* Highlight columns c (year) d (strata name) e (numerator) down to row 55 and copy and paste into datawrapper to make chart showing growth in suicides among men

!['DatavizMale suicide Trend'](/male-suicides-dataviz.png)

[Dataviz 1 live link](https://datawrapper.dwcdn.net/aJdOX/2/)

Data Viz 2:
* Move column f (strata) back so it's in column d again
* Seperate male and female suicides into seperate columns and put on new sheet data viz data 2
* Copy data from data viz data 2 and paste into datawrapper to make line chart comparing male and female suicides

!['DatavizMale and Female suicide Trend'](/2-male-female-suicides-dataviz.png)

[Dataviz 2 live link](https://datawrapper.dwcdn.net/MWs9S/3/)


[Dataset analyzed](https://docs.google.com/spreadsheets/d/1-W3WrXAEqoO6KBDbLzdc2-r_3dP60MH7vkxq_1YCff8/edit?usp=sharing)
