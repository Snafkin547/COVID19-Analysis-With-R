# COVID19-Analysis

### Project Overview
This project aims to visualize the progress of vaccinations against notoriously prevailing COVID-19.

Instead of showing just pure numbers of doses given to citizens in those countries, this analysis factors in their population, vaccination/combination types, geographical regions (Asia/America etc.), and income levels (High/middle etc.).

To do so, I combined the following three different datasets/data-sources into a dataframe:

World Vaccination Progress (As of 19 Feb) from Kaggle
Population-by-Country from Datahub
Income Level from World Bank
In addition, we will see more statistical experiments on data in the dataset, as the report progress toward the end of the report.

### Data Profile
In this analysis, we will look into vaccination progress of 86 countries of countries from 7 regions

## 
##        East Asia & Pacific      Europe & Central Asia 
##                          7                         41 
##  Latin America & Caribbean Middle East & North Africa 
##                         15                         11 
##              North America                 South Asia 
##                          3                          6 
##         Sub-Saharan Africa 
##                          3
Amongst those who started vaccinating, there are three groups of income level; High income, Upper middle income, and Lower middle income. This also shows that countries of low income profile have not been able to start vaccinating yet.

## 
##         High income Lower middle income Upper middle income 
##                  56                  11                  19
Following table demonstrates the number of countries that adopted each vaccine combination. Each country chose their own combination of vacine types - Some chose just one type; others chose even 5 different types. The most popular combination is Pfizer/BioNTech, followed by the combination of Moderna, Oxford/AstraZeneca, Pfizer/BioNTech just by 1 country.

## 
##                                                        Covaxin, Oxford/AstraZeneca 
##                                                                                  1 
##                                                                    Johnson&Johnson 
##                                                                                  1 
##                                       Moderna, Oxford/AstraZeneca, Pfizer/BioNTech 
##                                                                                 20 
##                                                           Moderna, Pfizer/BioNTech 
##                                                                                  7 
##                                                                 Oxford/AstraZeneca 
##                                                                                  9 
##                                                Oxford/AstraZeneca, Pfizer/BioNTech 
##                                                                                  6 
## Oxford/AstraZeneca, Pfizer/BioNTech, Sinopharm/Beijing, Sinopharm/Wuhan, Sputnik V 
##                                                                                  1 
##                                              Oxford/AstraZeneca, Sinopharm/Beijing 
##                                                                                  2 
##                                   Oxford/AstraZeneca, Sinopharm/Beijing, Sputnik V 
##                                                                                  1 
##                                                        Oxford/AstraZeneca, Sinovac 
##                                                                                  1 
##                                                      Oxford/AstraZeneca, Sputnik V 
##                                                                                  1 
##                                                                    Pfizer/BioNTech 
##                                                                                 21 
##                                                 Pfizer/BioNTech, Sinopharm/Beijing 
##                                                                                  1 
##                                      Pfizer/BioNTech, Sinopharm/Beijing, Sputnik V 
##                                                                                  1 
##                                                           Pfizer/BioNTech, Sinovac 
##                                                                                  2 
##                                                                  Sinopharm/Beijing 
##                                                                                  4 
##                                        Sinopharm/Beijing, Sinopharm/Wuhan, Sinovac 
##                                                                                  1 
##                                                                            Sinovac 
##                                                                                  2 
##                                                                          Sputnik V 
##                                                                                  4

### Data Visualisation
Using the above mentioned datasets, this section will visualize vaccination progresses from several angles to find out more relevant facts.

The following histogram and pie chart are to show the numbers/% of countries using each of those vaccine combinations - same as the last table. It visually shows that Pfizer/BioNTech and Moderna/AstraZeneca/Pfizer/BioNTech are neck-to-neck and Oxfort/Astra Zeneca vaccine is used in many countries, as of 19 Feb.

In terms of the doses provided to people, on the other hand, the data shows a different landscape. In this bar chart, you can see that Moderna + Pfizer vaccines are given to people most, and Sinopharm + Sinovac vaccines came in the second place. The latter combination must surprise you because this combination is adopted only by 1 country in the world, China, and it, standalone is beating the rest of the combinations in the numbers of doses given. This appears to me how fast China's action toward vaccinations has been so far.

The following chronological bar graph shows the global vaccination progress so far.

The above-mentioned progress has been driven largely by USA, China, UK, India, and Israel, as the data shows.

It is also crucial to be mindful of vaccination progress in a ratio to population size, because obtainment of social immunity is one of major reasons of this human effort to vaccinate their citizens. The more people get immunity against the virus in a society, the less would the virus spread be, broadly speaking.

In this context, those small countries like Gibraltar, Israel, Seychelles, and UAE, are prominent and outstanding.

I hypothesized that this contrast rooted in the shortage of vaccine productions/availabilities. The bigger the population is, the more difficult presumably would the security of vaccines for their entire population.





### Random Sampling & Central Limit Theorem
The following histograms are to demonstrate the Central Limit Theorem, using three datasets; Total Vaccination, Vaccination Progress, and Population of each countries.

It visually proves that the more samples are taken, the narrower would the standard deviations be, whilst mean value stay the same.

Random Sampling on Total Vaccination
Random Sampling on Vaccination Progress
Random Sampling on Population(in 10ks)
Sampling methods
In this section, we will run four sampling methods, Simple Random Sampling WITH replacement, Systematic Sampling, Stratified Sampling WITH replacement, and Cluster Sampling, and compare the distributions with original histogram.

We can infer from this analysis that, even if these samples were used, instead of the whole dataset, the average of samples would have stayed the same, whereas the standard deviation would have been narrower than the whole original dataset.

### Bootstrap estimate of the bias
Lastly, I ran analysis of Bootstrap estimate of the bias.

As the sample size grew, bias decreased, whereas standard deviation stayed in a relatively same range.






