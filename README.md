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

Women are more likely to attempt suicide and be diagnosed with depression. However, for nearly 20 years, men's suicide rates have been much higher and the reason why is still confounding the experts and people who work to prevent them. 
 
In California from 2000 to 2017, men have committed suicides at a rate more than three times that of women per a population of 100,000, according to [Let's Get Healthy California](https://data.ca.gov/dataset/suicide-deaths-per-100000-population-lghc-indicator), a state government task force that aggregated statistical datasets gathered from California death records.
 
Educators and community workers have pointed to several causes for the high rates among males. 
 
Dr. Eric Caine founded the University of Rochester Center for the Study and Prevention of Suicide in 1998, where he served as its Co-Director up until 2021. Through his research, he has focused on males' high suicide rates compared to females. 
 
Caine recognized that women were attempting suicide at a higher rate but saw that men were often killing themselves more often. 
 
"When you think about suicide, you're thinking about, at a statistical level, what it comes down to is the dead. It's a product of the number of attempts and what's called the case fatality rate, or case fatality percent of each attempt," Caine said. 
 
While women were attempting suicide 1.5 times more than men, according to the [2018 National Survey of Drug Use]( https://www.samhsa.gov/data/release/2018-national-survey-drug-use-and-health-nsduh-releases), it was about what method they were choosing and its fatality rate compared to what way men were choosing. 
 
"You take something like a firearm, right, a gun? And the case fatality is 85 or 90%, or something like that. You take an overdose. Someone goes to the bathroom medicine cabinet and grabs a bunch of pills; the case fatality rate of that is less than 2%," Caine said. 
 
Men own guns at a [higher rate]( https://www.pewresearch.org/social-trends/2017/06/22/the-demographics-of-gun-ownership/) than women, 48% for men compared to 39% for women, according to Pew Research data. Men often chose this method much more than women primarily because of their access to firearms. 
 
"When men attempted, even though collectively they attempted less often than their female peers, they more often used firearms. The case fatality percent was much higher. When you look across the life course, what you see is that men use much more lethal methods. And now, suicides are higher in rural areas, and there are lots of firearms in rural areas," Caine said. 
 
Now, the method used in suicide is one answer for this higher rate. However, when examining areas where the same method is used, it is still more common for men to commit suicide than women. 
 
"[Studies out of Taiwan]( https://bmcpublichealth.biomedcentral.com/articles/10.1186/1471-2458-10-480), for example, where they were interested in charcoal burning as a method because it gives off a lot of carbon monoxide. And what they find, in general, is that when men and women attempt the same amount, men have a higher case fatality rate, even with the same method," Caine said. 
 
One possible correlation between high suicide rates among males in the U.S. could be the high number of men joining the military and the high rates of suicides among veterans. In 2021, women comprised 17.3% of the active-duty military force, according to the [Department of Defense]( https://www.defense.gov/News/Releases/Release/Article/3246268/department-of-defense-releases-annual-demographics-report-upward-trend-in-numbe/).
 
Molly Scott works in Sonoma County for Nation's Finest, which provides support to veterans and their families in California, Arizona and Nevada. One of the services offered is mental health support, including a suicide hotline, which is one of Scott's duties. 
 
"I have talked to a lot of veterans really going through a lot. It is hard to hear from someone who has given so much to their country who feels that level of despair on an everyday basis," Scott said. 
 
Scott sometimes speaks with dozens of veterans daily dealing with mental health issues that range a large spectrum.
 
"Sometimes I think it's someone who just needs to talk, but a lot of times, this is someone going through a severe crisis. I try to do as much as I can for them, but often it feels like we aren't equipped in this country to provide for them," Scott said. 
 
Though Scott does speak to many men, she is surprised how many women call in, considering the large ratio of males compared to females in the military. 
 
In [2017](https://www.mentalhealth.va.gov/docs/data-sheets/2019/2019_National_Veteran_Suicide_Prevention_Annual_Report_508.pdf), 6,139 veterans committed suicide out of the 24 million veterans, according to the National Veterans Suicide Prevention annual report. But Caine points out that it cannot be one of the driving causes. He said that out of the total number of suicides, which was [47,173]( https://intheforefront.org/resources/suicide-data/) in 2017 in the U.S., the number of veterans is only a fraction of that population. 
 
Caine is concerned that not enough people are doing something to end the high suicide rates among males. He said people are more concerned about young people in schools committing suicide as a whole rather than the older population. 
 
"People have been drawn to the schools and the attempts on kids or young people, and I do not want to say devalued people who are adults, but undervalued," Caine said. "If you want to make the national suicide rate go down, you really need to struggle with that challenge of how do I deal with the big populations that account for most of it?"


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
