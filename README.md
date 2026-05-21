# Exploring the Effects of Pollutants on Asthma ER Visits across NYC
## Questions
 *We identify significant factors and scope of the project*

**1. What does your dataset explore?** 
- How air pollution affects respiratory health across NYC neighborhoods

**2. What is your dependent variable in the data you are pulling from?**
- Asthma ER visit rate caused by PM2.5 pollution

**3. Is this variable categorical or quantitative?**
- Quantitative (count of Asthma ER visits)

**4. What are your independent variables?**
- See table below.

**5. Are these variables quantitative or categorical? (you should have a good mix of both types, i.e. not all categorical)**
- See table below.

| Independent Variables | Type |
| -------- | -------- |
| Pollutant (*PM2.5* or *O3*)  | Categorical 
| Geographical Area (*UHF42*)  | Categorical
| Borough   | Categorical
| Year     | Quantitative
| *PM2.5* Concentration Level (*μg/m<sup>3</sup>*) | Quantitative
| *O3* Concentration Level   | Quantitative
| Neighborhood Poverty Level | Quantitative


**6. How many independent variables do you have? (you should have more than 5 independent variables)**
- There are 7 independenet variables. 

**7. How large is your dataset? (it should be larger than 1000 rows, but the more the better the power)**
- An estimated 1000+ rows pulling from 42 NYC neighborhoods over multiple years; the NYC Air Community survey has been running since 2008. There are 42 neighborhoods, 4 seasons collected quarterly. 42 x 4 = 168 rows per year.
