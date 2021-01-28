Before you turn this problem in, make sure everything runs as expected. First, **restart the kernel** (in the menubar, select Kernel$\rightarrow$Restart) and then **run all cells** (in the menubar, select Cell$\rightarrow$Run All).

Make sure you fill in any place that says `YOUR CODE HERE` or "YOUR ANSWER HERE", as well as your name and collaborators below:


```python
NAME = "Athanasios Vourtsis Murat"
COLLABORATORS = ""
```

---

|Name|SNR|ANR|
|----|---|----|
|Athanasios Vourtsis Murat|2062843|u312241|

# Research question


Could there be a second-order index (composite index {Wellbeing and Human Development} of composite indexes of categories vital to the former {Education, Environment, Health, Infrastructure, Labor, Social Conditions}) that formulate in an as transparent as possible manner, the parameters that set the basis for societal cohesion, apart from the relatively easily accessible quantitively monetary measure of GDP?

# Motivation

The latest societal, environmental, and humanitarian developments indicate that the use of GDP as the sole indicator of economic and social prosperity may be misleading and lead to uninformed and partially effective policymaking, being incompatible with the betterment of qualitative parameters that constitute the overall wellbeing. Based on the above premise, it would be of great value if one or more compounded indexes that encapsulate the different societal facets were in place, not by necessarily substituting, but complementing the strictly quantitative and general economic performance measures. Thus, the analysis of this assignment is focused on developing a complementary to the GDP Wellbeing and Development Index.

Starting this venture of scientific inquiry, we shall distinguish the categories of most importance that are not directly assumed by the GDP measure. For example, it could be the case that the quality of life in a relatively higher income country is on average higher than a lower-income country. Nevertheless, there may still be some structural societal irregularities that obstruct the given society to reach its full potential from a perspective of cohesion and wellbeing. In other words, the total wealth produced from an economy does not equate necessarily with the state of societal integration.


# Data and Methods



## Information Concerning the Data and their Respective Sources

One of the most crucial categories that has been disturbingly left out of the growth models and has been the subject of intense debate and radical proposals, is that of environmental sustainability and biodiversity. At this point, it is an indisputable fact that the ecosystems of the earth are heading to a tipping point of no return due to the footprint of the reckless production methods that humanity has been adopting and continues to pursue. The main variables used to characterize this category are the Emissions per Capita (1), Pesticide Use (2), and the Percentage of Electricity Produced from Renewable Energy Sources (3). Then categories as Education, Labor, and Infrastructure Conditions can prove of great importance. Respectively, the variables used for the identification of those categories are second and tertiary education enrollment rates (4),(5), mean years of education (6), youth (7), and general unemployment (8), yearly working hours (9), mobile cellular subscriptions per 100 people (10), internet use (11), and access to electricity (12).

The last two main and most broad categories are those of Health and Social Conditions. The former pillar of an orderly societal functioning consists of the variables of air pollution deaths as a proportion of total deaths (13), the proportion of the population that presents alcohol and substance use disorders (14), life expectancy (15), the prevalence of HIV (16), hospital beds per 1000 people (17), the age-standardized prevalence of mental health disorders (18), the proportion of the population being overweight (19), the proportion of pregnant women facing anemia (20), the per capita protein supply (21), and the proportion of deaths caused by unsafe sanitation (22) and water sources (23). Then, for the latter one, variables and scores of corruption (24), political stability (25), rule of law (26), and the human rights conditions (27), the Gini index (28), Female-to-Male Ratio in the Labor Market (29), the income share of the bottom 10% (30), the share of deaths from homicide (31), deaths from disasters (32), and the share of deaths from suicide were used (33). 


(1): https://databank.worldbank.org/reports.aspx?source=2&series=EN.ATM.CO2E.PC&country=
(2): https://ourworldindata.org/grapher/pesticide-use-tonnes?tab=table
(3): https://ourworldindata.org/grapher/share-electricity-renewables?time=2019
(4): https://databank.worldbank.org/reports.aspx?source=2&series=SE.SEC.ENRR&country=
(5): https://databank.worldbank.org/reports.aspx?source=2&series=SE.TER.ENRR&country=
(6): https://ourworldindata.org/grapher/mean-years-of-schooling-1?time=2017
(7): https://databank.worldbank.org/reports.aspx?source=2&series=SL.UEM.1524.ZS&country=
(8): https://data.worldbank.org/indicator/SL.UEM.TOTL.ZS
(9): https://ourworldindata.org/grapher/annual-working-hours-per-worker?tab=chart&stackMode=absolute&time=1870..latest&region=World
(10): https://databank.worldbank.org/reports.aspx?source=2&series=IT.CEL.SETS.P2&country=
(11): https://ourworldindata.org/grapher/number-of-internet-users-by-country?time=2017
(12): https://ourworldindata.org/grapher/share-of-the-population-with-access-to-electricity?region=World
(13): https://ourworldindata.org/grapher/share-deaths-air-pollution?time=2017
(14): https://ourworldindata.org/grapher/share-of-population-with-drug-use-disorders?time=2016
(15): https://ourworldindata.org/grapher/life-expectancy?tab=table&time=1917..2015&region=World
(16): https://databank.worldbank.org/reports.aspx?source=2&series=SH.DYN.AIDS.ZS&country=
(17): https://databank.worldbank.org/reports.aspx?source=2&series=SH.MED.BEDS.ZS&country=
(18): https://ourworldindata.org/grapher/share-with-mental-health-or-development-disorder?time=2016
(19): https://databank.worldbank.org/reports.aspx?source=311&series=SH.STA.OWAD.ZS
(20): https://ourworldindata.org/grapher/prevalence-of-anemia-in-pregnant-women?time=2016
(21): https://ourworldindata.org/grapher/daily-per-capita-protein-supply?time=2017
(22): https://ourworldindata.org/grapher/death-rate-from-unsafe-sanitation?time=2017
(23): https://ourworldindata.org/grapher/death-rates-unsafe-water?time=2017
(24), (25), (26): https://databank.worldbank.org/source/worldwide-governance-indicators/preview/on
(27): https://ourworldindata.org/grapher/human-rights-scores
(28): https://databank.worldbank.org/reports.aspx?source=2&series=SI.POV.GINI&country=
(29): https://databank.worldbank.org/reports.aspx?source=2&series=SL.TLF.CACT.FM.ZS&country=
(30): https://databank.worldbank.org/reports.aspx?source=2&series=SI.DST.FRST.10&country=
(31): https://ourworldindata.org/grapher/share-of-deaths-homicides?time=2017
(32): https://ourworldindata.org/grapher/share-deaths-from-natural-disasters?tab=table
(33): https://ourworldindata.org/grapher/share-deaths-suicide?time=2017



## Data Manipulation Process

 
All of the time series data mentioned above were placed in different folders based on their characteristics commonly attributed to them in the bibliography and other frameworks. Thus, the very first and brief procedure, that of the differentiation of the variables to be used, was a manual one and led to the location and creation of six different data characterizations. As already mentioned above, those are Education, Environment, Health, Infrastructure, Labor, and Social Conditions (Path Example; Shortened: Variables\\Category Type {6}\\Time_Series_Data.csv {33}).


At the beginning of the algorithm a for-loop is being employed to access the folders and then the data seperately located in the major "Variable" folder to collect and append their respective paths in a dedicated list. In turn, that list was used in another for-loop to import the datasets as dataframes and append them to a list. 


Then, for-loops were used to the above list of dataframes to extract the exact names of the variables included and the intersection of the countries included in all of the datasets (achieving consistency across the large number of variables), eventually appending them to their separate lists as strings. The procedure of "distillation", shortly on will prove useful, as the lists of countries and variables occuring could function as masks. 


To further improve the structure of the data, a mask of the years to be used in the final analysis was being developed and implemented. Also, all the data points across the different data frames were assigned an index of date formatting based on their year information. Eventually, the intersecting countries list was used to create a list of data frames with a for-loop of each country yearly data for each of the variables (i.e. List Dimension=1650 (: {33 Variables}x{50 Countries}), Data Frames Dimensions={16,5} (: rows=16 years, col=Country, Country Code, Year, Variable, Value). Then, the list was split into 50 different arrays that contained the yearly data of each country and every variable, to be used right after in a for-loop to interpolate and fill the missing values, and their respective column information. Finally, for this final list, a for-loop removed all of the redundant columns, achieving a perfect uniformity across the Data Frames, which would eventually help to construct a merged data frame containing all data points (i.e. 26400; 16 x 33 x 50). 


That merged, filtered, uniformed, and cleaned data frame, functions as a basis/starting point to the designing of all data frames to be used in the statistical analyses. For example, that of a list of a 16 data frames based on the number of years of the series, which contain cross-sectional data for the 50 countries and across 33 variables. That list practically consitutes a panel.


It shall be noted that an additional technical step took place during the analysis, that of reverse scoring. Reverse scoring is a procedure that reconfigures the direction of variables that run in the opposite direction of the remaining ones, qualitatively. The number of deaths or the per capita emissions is qualitatively opposite to, for example, life expectancy and use of renewables. Alternatively, an increasing number of deaths from various causes is unanimously considered a negative occurrence, while an increase in life expectancy is an undoubtedly positive development. The simplest and most efficient method used to reverse the direction of a variable is by deducting from a value of a given observation the maximum value presented among all the observations of the variable. Thus, the maximum value becomes the lowest possible and the lowest becomes the highest in the dataset. Reverse scoring is a crucial and essential step, in the absence of which the statistical analyses are seriously flawed (e.g. negative values for the Cronbach's Coefficient).


## Statistical Methods


The main statistical method used is that of Factor Analysis, and supplementary, the statistical measure of Cronbach's Coefficient Alpha. 
The latter one is used to check on the internal consistency of a set of variables that embark on approximating a hypothesized and initially qualitative variable. The main components of its' formula are the number of the variables used to construct an individual score, and most importantly, the one with the mean correlations among the variables. The mean correlation is a parameter occurring from the sum of all correlation values among all variables, divided by the number of variable combinations (i.e. for a set of 5 variables, we would get the correlations of variable 1 with the variables 2 to 5, then the correlations of variable 2 with the variables 3 to 5, the correlation of variable 3 with the variables 4 and 5, and finally, the correlation of variable 4 with 5, which totals 2 x (# of variables) => 2 x 5 = 10). Eventually, a high correlation among the variables produces a high alpha coefficient and indicates the internal consistency of the given compounded construct. A satisfactory value of the coefficient may start at as low as the low 60s, and a more than satisfactory one could be over 90. However, an alpha coefficient that is too high (>>95) could indicate redundancy of one or a set of variables used. 


From the brief explanation of Cronbach's Coefficient Alpha, it is clear that the measure carries no information on the dimensionality of the compounded score and the total variance, and which variable constitutes it, and to what extent.


What Factor Analysis is mainly good for, is the reduction of dimensions in cases of high dimensionality, by locating underlying variables (factors) based on the shared variances that the multiple variables used present. Then the number of factors is determined by the chosen criterion (e.g. Kaiser, Horn's Parallel Analysis, etc), which (based on the test number of factors) yields some values, or more precisely, eigenvalues. Usually, the number of factors that are eventually used have an eigenvalue of at least one.


After determining the suggested number of factors based on the criterion used, we run a factor analysis that yields a matrix of n(Variables) x m(# Factors), where for each variable and factor, a value is assigned, or alternatively a loading. What that indicates is the extent that a given variable contributes to the variance of a given factor, and thus, the extent that it is related. The loading value could be either negative or positive, and it ranges from -1 to 1. High enough loadings for a given factor and a set of variables (both positive and negative; in this case, the item is subtracted from the score rather than added) constitute a compounded underlying variable. Furthermore, it could be the case that a factor eventually has no explanatory value based on the variables' loadings, regardless of having an eigenvalue equal to or higher than one in the first step of the analysis.




# Preview of the answers

The first-order Cronbach’s Coefficient measures used to check the inner validity of the individual indexes per year yielded the following results. For the first year, “education” has an alpha of 0.88, “environment” has an alpha of 0.5, “health” has an alpha of 0.6, “infrastructure” has an alpha of 0.8, “labor” alpha has an alpha of 0.47, and “social conditions” has an alpha of 0.72. Eventually, the manually constructed categories’ alphas, averaged over 16 years of available data, are 0.87, 0.42, 0.59, 0.82, 0.43, and 0.71, respectively. That means the categories of education, infrastructure and that of social conditions present an adequate to very good internal validity, while the health category presents a marginally efficient one. The remaining categories of environment and infrastructure have poor internal validity, and thus, they may not be appropriate for our analysis.


The first-order factor analysis for a fixed number of three factors per manually determined category per year yielded the following results. For the first year, education’s loadings indicate two underlying variables. That result was expected as in this category just 3 variables can be found, while the two of them relate to enrollment rates (for secondary and tertiary education). Then, the environment’s loadings technically indicate 3 different factors, which equal the exact number of variables available in this category. Thus, each one of them will act as a factor of themselves, that is, staying unchanged in the analysis. Health’s loadings effectively indicate three different factors that include {Life Expectancy (-0.68), Prevalence of Overweight People (-0.6), Protein Supply (-0.56), Unsafe Sanitation (0.99) and Unsafe Water Sources (0.98)}, {Air Pollution (-0.69), Drug Abuse (0.34), Prevalence of HIV (-0.38), Pregnant Anemia (-0.68)}, {Hospital Beds per 1000 people (-0.54), Prevalence of Mental Health Issues (0.64)}. Infrastructure and Labor Loadings do not strongly differentiate any underlying factors (low number of variables; 3 for both categories), and finally, the category of the social conditions locate the factors {Corruption Control (0.82), Female-to-Male Labor (0.89), Prevalence of Homicides (0.63), Deaths by Disasters (0.9), Prevalence of Suicides (0.81), Human Rights Conditions (0.21)}, {Gini Index (0.9), Income Share of the Bottom 10% (-0.89)}, {Political Stability (-0.49), Rule of Law (-0.45)}. It should be noted that these results vary greatly across the years of the available data, producing a state of inconclusiveness. That state is being further substantiated, as the eigenvalues for each of the categories give results of no value (the number of factors proposed is almost 1:1 to the variables available for each category).  


Also, when it comes to the factors of the variables with more than 3 variables, the variables’ loadings constituting each of the factors present as having the opposite direction of the compounded variable/variance of the factor. In our case, it seems like the loadings of the factors for each variable have unexpected values and constitute a construct that cannot be generalized to a certain quality. Alternatively, some factors based on the “participating” variables, assign negative loadings to variables that should be of the opposite direction qualitatively, and vice versa. The procedure of factor constructing, in this case, does not lead to results that make sense based on the frameworks that each of the variables, and possible effective combinations of them, come from, as there is a mix of conflicting constructs. Thus, at this first-order analysis, equal weights were assigned to each of the manually constructed categories.


Then, the same procedure was repeated, and equivalent results were drawn. The “second-order” Cronbach’s Alpha, or the internal consistency of the index of interest (that of Wellbeing and Development), is too low to be considered reliable (0.47: average alpha across the 16 years of available data). Also, the eigenvalues of the “second-order” computation, seem to not suggest an effective lower dimensionality construct, as almost all the eigenvalues are higher than one. Finally, based on the results of the above factor analysis criterion, that of 5 factors for the six variables available, the loadings of each of the six variables for the 5 different factors suggests a clustering that leads to the grouping of “Education” (0.84), with the categories of “Infrastructure” (0.73), and that of “Social Conditions” (0.62), and with the remaining variables being assigned 1:1 to the second, third, and fourth factor {i.e., “Labor” (0.71), “Environment” (0.63), and Health (0,61)}. The above loadings apply for the first year of the available data, but the same pattern with some slight variation holds for the following years as well. Based on the underwhelming consistency results, an equal weights procedure was chosen for the “second-order” step.

It should be noted that the “first-order” analysis (i.e., the aggregation by averaging over the variables across the categories) was in part effective because all the measures used were relative to the population of the countries, and thus, comparable in level.

To depict the answer to the posed research question as clearly as possible, data regarding the GDP per capita were imported. Then, out of the 50 countries, 16 of them were chosen as examples, ranging from low to high income. The final graphs, presenting the trend of the Wellbeing and Development Indicator in juxtaposition to the trend of the GDP per capita for each of the 16 countries, suggest on average that in countries considered as high income, the state of social cohesion and the adequacy of services decreases or remains constant, while in the medium or low-income countries it increases alongside the monetary measure of GDP per capita. 

# Main assumptions

When it comes to the main assumptions that need to govern the data, while using the factor analysis statistical method and the statistical measure of Cronbach’s Alpha, are, for the former, that the correlations among the variables are not too high, that there are no outliers (due to its inability as a method to produce robust results), that there is a uniformity of the variables scale and their scale type need not be anything else other than interval or ratio, that there are linear correlations (an assumption that is too hard to be accepted as true for large groups of variables), and last but not least,  that there is no multicollinearity. Then, when it comes to the latter, there needs to be a unidimensionality for the variables used to construct a compounded index, in the absence of which a great underestimation of the reliability of the index could take place. Also, this underestimation applies in the presence (or more accurately absence) of a high enough number of items.

# Python Code

## Data Processing, Filtering and Cleaning


```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import os
import statistics as st
import itertools as it
from sklearn.preprocessing import MinMaxScaler
from sklearn.linear_model import Ridge
from sklearn import preprocessing
from factor_analyzer import FactorAnalyzer


os.getcwd()


path_to_parent= "C:\\Users\\Nassos_R\\Desktop\\Applied Economic Analysis 1\\Final Assignment\\Variables\\"
paths=[]
dfs=[]




for folder in os.listdir(path_to_parent):
    folder_name=folder
    for csv_file in os.listdir(os.path.join(path_to_parent, folder)):
        path=path_to_parent+folder_name+"\\"+csv_file
        paths.append(path)




for path in paths:
    df=pd.read_csv(path)
    dfs.append(df)



variables=[]
for df in dfs:
    variables.append(set(df['Variable']))



variables_list=[]
for var_set in variables:
    var_set=list(var_set)
    variables_list.append(var_set)




total_var=[]
for setv in variables:
 for i in setv:
  total_var.append(i)



num_set=[]
for setv in variables:
  num_set.append(len(setv))



countries=[]
for df in dfs:
    countries.append(set(df['Country']))




list_countries=[]
for setc in countries:
    for i in setc:
     list_countries.append(i)




inter_list=[]
inter=set.intersection(*map(set,countries))
for i in inter:
 inter_list.append(i)


inter_list.sort()



filtered_by_country=[]
for df in dfs:
    df=df[df['Country'].isin(inter_list)]
    filtered_by_country.append(df)




years=range(2000,2016,1)
filtered=[]
for df in filtered_by_country:
    df=df[df['Year'].isin(years)]
    filtered.append(df)
 



dfs_index =[]
for df in filtered:
    date_var=pd.to_datetime(df['Year'], format='%Y')
    dfs_index.append(df.set_index(date_var))




iso_c=[]
for countr in inter_list:
 for df in dfs_index:
     df=df.loc[df['Country']==countr]
     iso_c.append(df)




var_cat=np.array_split(iso_c,50)



var_dfs=[]
for arr in var_cat:
 for df in arr:
  df=df.resample('Y').ffill(limit=1).interpolate()
  df['Country'].fillna(method='ffill',inplace=True)
  df['Variable'].fillna(method='ffill',inplace=True)
  var_dfs.append(df)




for df in var_dfs:
 for col in df.columns:
  if col=='Country Code':
   del df[col]
  elif col=='Series Code':
   del df[col] 
  elif col=='Time Code':
   del df[col]
  elif col=='Code':
   del df[col]
  elif col=='Year Code':
   del df[col]
  else:
   pass



merged=pd.concat(var_dfs)
```


    ---------------------------------------------------------------------------

    ModuleNotFoundError                       Traceback (most recent call last)

    <ipython-input-19-e6993050c482> in <module>
          8 from sklearn.linear_model import Ridge
          9 from sklearn import preprocessing
    ---> 10 from factor_analyzer import FactorAnalyzer
         11 
         12 


    ModuleNotFoundError: No module named 'factor_analyzer'


## Categorization of Data


```python
init_form=pd.DataFrame(index=inter_list,columns=total_var)
yearly_data=[]
for i in range(1,17):
    yearly_data.append(init_form.copy())



for index, row in merged.iterrows():
  if row['Year']==2000:
    yearly_data[0].loc[yearly_data[0].index==row['Country'],row['Variable']]=row['Value']
  elif row['Year']==2001:  
    yearly_data[1].loc[yearly_data[1].index==row['Country'],row['Variable']]=row['Value']
  elif row['Year']==2002:  
    yearly_data[2].loc[yearly_data[2].index==row['Country'],row['Variable']]=row['Value']
  elif row['Year']==2003:  
    yearly_data[3].loc[yearly_data[3].index==row['Country'],row['Variable']]=row['Value']
  elif row['Year']==2004:  
    yearly_data[4].loc[yearly_data[4].index==row['Country'],row['Variable']]=row['Value'] 
  elif row['Year']==2005:  
    yearly_data[5].loc[yearly_data[5].index==row['Country'],row['Variable']]=row['Value']
  elif row['Year']==2006:  
    yearly_data[6].loc[yearly_data[6].index==row['Country'],row['Variable']]=row['Value']
  elif row['Year']==2007:  
    yearly_data[7].loc[yearly_data[7].index==row['Country'],row['Variable']]=row['Value']
  elif row['Year']==2008:  
    yearly_data[8].loc[yearly_data[8].index==row['Country'],row['Variable']]=row['Value']
  elif row['Year']==2009:  
    yearly_data[9].loc[yearly_data[9].index==row['Country'],row['Variable']]=row['Value']
  elif row['Year']==2010:  
    yearly_data[10].loc[yearly_data[10].index==row['Country'],row['Variable']]=row['Value']
  elif row['Year']==2011:  
    yearly_data[11].loc[yearly_data[11].index==row['Country'],row['Variable']]=row['Value']
  elif row['Year']==2012:  
    yearly_data[12].loc[yearly_data[12].index==row['Country'],row['Variable']]=row['Value']
  elif row['Year']==2013:  
    yearly_data[13].loc[yearly_data[13].index==row['Country'],row['Variable']]=row['Value']
  elif row['Year']==2014:  
    yearly_data[14].loc[yearly_data[14].index==row['Country'],row['Variable']]=row['Value']
  else:
    yearly_data[15].loc[yearly_data[15].index==row['Country'],row['Variable']]=row['Value']

```

## Descriptives


```python
sorted_dfs_yv=merged.sort_index().sort_values('Variable', kind='mergesort')
new_arr=np.array_split(sorted_dfs_yv,528)
init_arr=np.ones([528,50])
for arr,x in it.product(new_arr,range(0,len(new_arr))):
    for pos,y in it.product(arr,range(0,len(arr))):
        new_p=new_arr[x]['Value'][y]
        init_arr[x][y]=new_p

        
        


mean_table={'Year':[],'Variable':[],'Mean':[]}


for arr in new_arr:
    mean_table['Mean'].append(arr['Value'].mean())
    mean_table['Variable'].append(arr['Variable'][1])
    mean_table['Year'].append(arr['Year'][1])


mean_df=pd.DataFrame(mean_table)



var_table={'Year':[],'Variable':[],'Variance':[]}



for arr in new_arr:
    var_table['Variance'].append(arr['Value'].var())
    var_table['Variable'].append(arr['Variable'][1])
    var_table['Year'].append(arr['Year'][1])



var_df=pd.DataFrame(var_table)



sd_table={'Year':[],'Variable':[],'Standard Deviation':[]}



for arr in new_arr:
    sd_table['Standard Deviation'].append(arr['Value'].std())
    sd_table['Variable'].append(arr['Variable'][1])
    sd_table['Year'].append(arr['Year'][1])



sd_df=pd.DataFrame(sd_table)
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    <ipython-input-20-25944cd91a77> in <module>
    ----> 1 sorted_dfs_yv=merged.sort_index().sort_values('Variable', kind='mergesort')
          2 new_arr=np.array_split(sorted_dfs_yv,528)
          3 init_arr=np.ones([528,50])
          4 for arr,x in it.product(new_arr,range(0,len(new_arr))):
          5     for pos,y in it.product(arr,range(0,len(arr))):


    NameError: name 'merged' is not defined


## Cronbach's Coefficient Alpha and Reverse Scoring (Individual Indexes/"First-order")


```python
oposs=[False, False, False, True, True, False, True, True, False, True, False, True, True, True, False, True,
True, False, False, False, True, True, True, False, True, True, False, False, False, False, False, False, True] 


totvar_arr=np.array(total_var)

oposs_arr=np.array(oposs)

rev_arr=totvar_arr[oposs_arr]



yearly_oposs=yearly_data.copy()


for df in yearly_oposs:
 for colum in rev_arr:
  max_var=df[colum]
  for index, row in df.iterrows():
     row[colum]=max(max_var)-row[colum]



cat_yearly=[]
for i in range(0,len(yearly_data)):
    edu=yearly_oposs[i].iloc[:,0:3]
    envi=yearly_oposs[i].iloc[:,3:6]
    health=yearly_oposs[i].iloc[:,6:17]
    inf=yearly_oposs[i].iloc[:,17:20]
    lab=yearly_oposs[i].iloc[:,20:23]
    social=yearly_oposs[i].iloc[:,23:33]
    wellb_indi=[edu,envi,health,inf,lab,social]
    cat_yearly.append(wellb_indi)
    
    


correl=[]
N=[]
for year in cat_yearly:
  for indi in year:
    correl.append(indi.astype(float).corr())
    N.append(indi.shape[1])


correl=np.array_split(correl,16)
N=np.array_split(N,16)


alpha_ind=[]
for x in range(0,len(cat_yearly)):
 for k in range(0,len(cat_yearly[x])):
   sum_arr = np.array([])
   for i, col in enumerate(correl[x][k].columns):
        interm = correl[x][k][col][i+1:].values
        sum_arr = np.append(interm, sum_arr)        
   mean_corr = np.mean(sum_arr)
   c_alpha = (N[x][k]*mean_corr)/(1+(N[x][k]-1)*mean_corr)
   alpha_ind.append(c_alpha)


alpha_ind=np.array_split(alpha_ind,16)

mean_alpha=[]
for i in range(0,6):
  mean=(alpha_ind[0][i]+alpha_ind[1][i]+alpha_ind[2][i]+alpha_ind[3][i]+alpha_ind[4][i]+alpha_ind[5][i]+alpha_ind[6][i]+alpha_ind[7][i]+alpha_ind[8][i]+alpha_ind[9][i]+alpha_ind[10][i]+alpha_ind[11][i]+alpha_ind[12][i]+alpha_ind[13][i]+alpha_ind[14][i]+alpha_ind[15][i])/16
  mean_alpha.append(mean)  
```

## Factor Analysis (Individual Indexes/"First-order")


```python
def eigenvalues(df,x):
    fa=FactorAnalyzer(x, rotation=None)
    fa.fit(df)
    eigen, val=fa.get_eigenvalues()
    return(val)



eigenval=[]
for year in cat_yearly:
 for indi in year:
    eigenval.append(eigenvalues(indi,32))


eigen_split=np.array_split(np.array(eigenval),16)
    

loadings=[]
for year in cat_yearly:
 for indi in year:
     fa=FactorAnalyzer(3, rotation='varimax')
     fa.fit(indi)
     loadings.append(fa.loadings_)
    
    
    
load_split=np.array_split(np.array(loadings),16)
```

## "First-order" Compound Indexes (Equal Weights)


```python
single_index=pd.DataFrame(index=cat_yearly[0][0].index,columns=['Education','Environment','Health','Infrastructure','Labor','Social Conditions'])



fo_index_yearly=[]
for i in range(0,16):
     fo_index_yearly.append(single_index.copy())


for x in range(0,16):
 for y in range(0,6):   
  for index, row in cat_yearly[x][y].iterrows():
          if y==0:
              mean=st.mean(row)
              fo_index_yearly[x].loc[fo_index_yearly[x].index==row.name,'Education']=mean
          elif y==1:
              mean=st.mean(row)
              fo_index_yearly[x].loc[fo_index_yearly[x].index==row.name,'Environment']=mean
          elif y==2:
              mean=st.mean(row)
              fo_index_yearly[x].loc[fo_index_yearly[x].index==row.name,'Health']=mean
          elif y==3:
              mean=st.mean(row)
              fo_index_yearly[x].loc[fo_index_yearly[x].index==row.name,'Infrastructure']=mean
          elif y==4:
              mean=st.mean(row)
              fo_index_yearly[x].loc[fo_index_yearly[x].index==row.name,'Labor']=mean
          else:
              mean=st.mean(row)
              fo_index_yearly[x].loc[fo_index_yearly[x].index==row.name,'Social Conditions']=mean



```

## "Second-order" Conbrach's Coefficient Alpha


```python
oposs_final=[False, True, True, False, False, False]

final_var=['Education','Environment','Health','Infrastructure','Labor','Social Conditions']

totvar_arr=np.array(final_var)

oposs_arr=np.array(oposs_final)

rev_arr=totvar_arr[oposs_arr]



yearly_oposs_final=fo_index_yearly.copy()


for df in yearly_oposs_final:
 for colum in rev_arr:
  max_var=df[colum]
  for index, row in df.iterrows():
     row[colum]=max(max_var)-row[colum]



correl_oposs_final=[]
N=[]
for indi in yearly_oposs_final:
    correl_oposs_final.append(indi.astype(float).corr())
    N.append(indi.shape[1])



alpha_ind_final=[]
for k in range(0,len(yearly_oposs_final)):
 sum_arr = np.array([])
 for i, col in enumerate(correl_oposs_final[k].columns):
        interm = correl_oposs_final[k][col][i+1:].values
        sum_arr = np.append(interm, sum_arr)        
 mean_corr = np.mean(sum_arr)
 c_alpha = (N[k]*mean_corr)/(1+(N[k]-1)*mean_corr)
 alpha_ind_final.append(c_alpha)





mean_alpha_final=(alpha_ind_final[0]+alpha_ind_final[1]+alpha_ind_final[2]+alpha_ind_final[3]+alpha_ind_final[4]+alpha_ind_final[5]+alpha_ind_final[6]+alpha_ind_final[7]+alpha_ind_final[8]+alpha_ind_final[9]+alpha_ind_final[10]+alpha_ind_final[11]+alpha_ind_final[12]+alpha_ind_final[13]+alpha_ind_final[14]+alpha_ind_final[15])/16
print(mean_alpha_final)
```

## "Second-order" Factor Analysis


```python
eigenval_final=[]
for year in yearly_oposs_final:
    eigenval_final.append(eigenvalues(year,20))


eigen_split_final=np.array_split(np.array(eigenval_final),16)
    

loadings_final=[]

for year in yearly_oposs_final:
     fa=FactorAnalyzer(5, rotation='varimax')
     fa.fit(year)
     loadings_final.append(fa.loadings_)


    
load_split_final=np.array_split(np.array(loadings_final),16)
```

## Second-order Index: Wellbeing and Development Indicator (Equal Weights)


```python
wellb_table=pd.DataFrame(index=cat_yearly[0][0].index,columns=['2000','2001','2002','2003','2004','2005','2006','2007','2008','2009','2010','2011','2012','2013','2014','2015'])



for x in range(0,16):   
  for index, row in yearly_oposs_final[x].iterrows():
          if x==0:
              mean=st.mean(row)
              wellb_table.loc[wellb_table.index==row.name,'2000']=mean
          elif x==1:
              mean=st.mean(row)
              wellb_table.loc[wellb_table.index==row.name,'2001']=mean
          elif x==2:
              mean=st.mean(row)
              wellb_table.loc[wellb_table.index==row.name,'2002']=mean
          elif x==3:
              mean=st.mean(row)
              wellb_table.loc[wellb_table.index==row.name,'2003']=mean
          elif x==4:
              mean=st.mean(row)
              wellb_table.loc[wellb_table.index==row.name,'2004']=mean
          elif x==5:
              mean=st.mean(row)
              wellb_table.loc[wellb_table.index==row.name,'2005']=mean
          elif x==6:
              mean=st.mean(row)
              wellb_table.loc[wellb_table.index==row.name,'2006']=mean
          elif x==7:
              mean=st.mean(row)
              wellb_table.loc[wellb_table.index==row.name,'2007']=mean
          elif x==8:
              mean=st.mean(row)
              wellb_table.loc[wellb_table.index==row.name,'2008']=mean
          elif x==9:
              mean=st.mean(row)
              wellb_table.loc[wellb_table.index==row.name,'2009']=mean
          elif x==10:
              mean=st.mean(row)
              wellb_table.loc[wellb_table.index==row.name,'2010']=mean
          elif x==11:
              mean=st.mean(row)
              wellb_table.loc[wellb_table.index==row.name,'2011']=mean
          elif x==12:
              mean=st.mean(row)
              wellb_table.loc[wellb_table.index==row.name,'2012']=mean
          elif x==13:
              mean=st.mean(row)
              wellb_table.loc[wellb_table.index==row.name,'2013']=mean
          elif x==14:
              mean=st.mean(row)
              wellb_table.loc[wellb_table.index==row.name,'2014']=mean              
          else:
              mean=st.mean(row)
              wellb_table.loc[wellb_table.index==row.name,'2015']=mean
            
            
            
            
wellb_table=wellb_table.T           
            
gdp=pd.read_csv("C:\\Users\\Nassos_R\\Desktop\\Applied Economic Analysis 1\\Final Assignment\\GDPpercapitaPPP.csv")         
            
gdp_df=pd.DataFrame(index=range(2000,2016))

for country in inter_list:
    gdp_df[country]=None





for index, row in gdp.iterrows():
          if row.Year==2000:
              gdp_df.loc[gdp_df.index==2000,row['Country']]=row.Value
          elif row.Year==2001:
              gdp_df.loc[gdp_df.index==2001,row['Country']]=row.Value
          elif row.Year==2002:
              gdp_df.loc[gdp_df.index==2002,row['Country']]=row.Value
          elif row.Year==2003:
              gdp_df.loc[gdp_df.index==2003,row['Country']]=row.Value
          elif row.Year==2004:
              gdp_df.loc[gdp_df.index==2004,row['Country']]=row.Value
          elif row.Year==2005:
              gdp_df.loc[gdp_df.index==2005,row['Country']]=row.Value
          elif row.Year==2006:
              gdp_df.loc[gdp_df.index==2006,row['Country']]=row.Value
          elif row.Year==2007:
              gdp_df.loc[gdp_df.index==2007,row['Country']]=row.Value
          elif row.Year==2008:
              gdp_df.loc[gdp_df.index==2008,row['Country']]=row.Value
          elif row.Year==2009:
              gdp_df.loc[gdp_df.index==2009,row['Country']]=row.Value
          elif row.Year==2010:
              gdp_df.loc[gdp_df.index==2010,row['Country']]=row.Value
          elif row.Year==2011:
              gdp_df.loc[gdp_df.index==2011,row['Country']]=row.Value
          elif row.Year==2012:
              gdp_df.loc[gdp_df.index==2012,row['Country']]=row.Value
          elif row.Year==2013:
              gdp_df.loc[gdp_df.index==2013,row['Country']]=row.Value
          elif row.Year==2014:
              gdp_df.loc[gdp_df.index==2014,row['Country']]=row.Value             
          else:
              gdp_df.loc[gdp_df.index==2015,row['Country']]=row.Value


                
            
wellb_table = wellb_table.set_index(pd.to_datetime(wellb_table.index))            
gdp_df = gdp_df.set_index(wellb_table.index)         
    
    
    
fig, axs = plt.subplots(4, 4)
fig.tight_layout()


plt.subplot(441)
plt.xlabel('Argentina')         
gdp_df.Argentina.plot(grid=True, label="GDP", legend=True)
wellb_table.Argentina.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(442)
plt.xlabel('Brazil')         
gdp_df.Brazil.plot(grid=True, label="GDP", legend=True)
wellb_table.Brazil.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(443)
plt.xlabel('Chile')         
gdp_df.Chile.plot(grid=True, label="GDP", legend=True)
wellb_table.Chile.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(444)
plt.xlabel('France')         
gdp_df.France.plot(grid=True, label="GDP", legend=True)
wellb_table.France.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(445)
plt.xlabel('Ireland')         
gdp_df.Ireland.plot(grid=True, label="GDP", legend=True)
wellb_table.Ireland.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(446)
plt.xlabel('Italy')         
gdp_df.Italy.plot(grid=True, label="GDP", legend=True)
wellb_table.Italy.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(447)
plt.xlabel('Latvia')         
gdp_df.Latvia.plot(grid=True, label="GDP", legend=True)
wellb_table.Latvia.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(448)
plt.xlabel('Lithuania')         
gdp_df.Lithuania.plot(grid=True, label="GDP", legend=True)
wellb_table.Lithuania.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(4,4,9)
plt.xlabel('Malaysia')         
gdp_df.Malaysia.plot(grid=True, label="GDP", legend=True)
wellb_table.Malaysia.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(4,4,10)
plt.xlabel('Netherlands')         
gdp_df.Netherlands.plot(grid=True, label="GDP", legend=True)
wellb_table.Netherlands.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(4,4,11)
plt.xlabel('Pakistan')         
gdp_df.Pakistan.plot(grid=True, label="GDP", legend=True)
wellb_table.Pakistan.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(4,4,12)
plt.xlabel('Peru')         
gdp_df.Peru.plot(grid=True, label="GDP", legend=True)
wellb_table.Peru.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(4,4,13)
plt.xlabel('Spain')         
gdp_df.Spain.plot(grid=True, label="GDP", legend=True)
wellb_table.Spain.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(4,4,14)
plt.xlabel('Switzerland')         
gdp_df.Switzerland.plot(grid=True, label="GDP", legend=True)
wellb_table.Switzerland.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(4,4,15)
plt.xlabel('Thailand')         
gdp_df.Thailand.plot(grid=True, label="GDP", legend=True)
wellb_table.Thailand.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)

plt.subplot(4,4,16)
plt.xlabel('United States')         
gdp_df['United States'].plot(grid=True, label="GDP", legend=True)
wellb_table['United States'].plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.show()
            
            

```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    <ipython-input-21-eb305fdea6c5> in <module>
    ----> 1 wellb_table=pd.DataFrame(index=cat_yearly[0][0].index,columns=['2000','2001','2002','2003','2004','2005','2006','2007','2008','2009','2010','2011','2012','2013','2014','2015'])
          2 
          3 
          4 
          5 for x in range(0,16):


    NameError: name 'cat_yearly' is not defined


# Sensitivity analysis


To test for the sensitivity of the final results, each of the first-order indexes was removed incrementally, to construct six new tables containing the respective values of the second-order index, or, in other words, the Wellbeing and Development Index. The sensitivity test suggests that the category of most importance is the Labor Conditions, while for all the remaining categories, the trend remains almost unchanged. In the following paragraph of Discussion and Conclusions, it is suggested that several crucial reconfigurations should take place if the present analysis was to be revisited.


```python

yearly_noedu=[]
yearly_noenvi=[]
yearly_nohealth=[]
yearly_noinf=[]
yearly_nolab=[]
yearly_nosoc=[]





copy_final1=yearly_oposs_final[0].copy(deep=True)
copy_final2=yearly_oposs_final[1].copy(deep=True)
copy_final3=yearly_oposs_final[2].copy(deep=True)
copy_final4=yearly_oposs_final[3].copy(deep=True)
copy_final5=yearly_oposs_final[4].copy(deep=True)
copy_final6=yearly_oposs_final[5].copy(deep=True)
copy_final7=yearly_oposs_final[6].copy(deep=True)
copy_final8=yearly_oposs_final[7].copy(deep=True)
copy_final9=yearly_oposs_final[8].copy(deep=True)
copy_final10=yearly_oposs_final[9].copy(deep=True)
copy_final11=yearly_oposs_final[10].copy(deep=True)
copy_final12=yearly_oposs_final[11].copy(deep=True)
copy_final13=yearly_oposs_final[12].copy(deep=True)
copy_final14=yearly_oposs_final[13].copy(deep=True)
copy_final15=yearly_oposs_final[14].copy(deep=True)
copy_final16=yearly_oposs_final[15].copy(deep=True)


copy_agg=[copy_final1,copy_final2,copy_final3,copy_final4,copy_final5,copy_final6,copy_final7,copy_final8,copy_final9,copy_final10,copy_final11,copy_final12,
          copy_final13,copy_final14,copy_final15,copy_final16]


copy_final=copy_agg.copy()




for df in copy_final:
    del(df['Education'])
    yearly_noedu.append(df)







copy_final1=yearly_oposs_final[0].copy(deep=True)
copy_final2=yearly_oposs_final[1].copy(deep=True)
copy_final3=yearly_oposs_final[2].copy(deep=True)
copy_final4=yearly_oposs_final[3].copy(deep=True)
copy_final5=yearly_oposs_final[4].copy(deep=True)
copy_final6=yearly_oposs_final[5].copy(deep=True)
copy_final7=yearly_oposs_final[6].copy(deep=True)
copy_final8=yearly_oposs_final[7].copy(deep=True)
copy_final9=yearly_oposs_final[8].copy(deep=True)
copy_final10=yearly_oposs_final[9].copy(deep=True)
copy_final11=yearly_oposs_final[10].copy(deep=True)
copy_final12=yearly_oposs_final[11].copy(deep=True)
copy_final13=yearly_oposs_final[12].copy(deep=True)
copy_final14=yearly_oposs_final[13].copy(deep=True)
copy_final15=yearly_oposs_final[14].copy(deep=True)
copy_final16=yearly_oposs_final[15].copy(deep=True)


copy_agg=[copy_final1,copy_final2,copy_final3,copy_final4,copy_final5,copy_final6,copy_final7,copy_final8,copy_final9,copy_final10,copy_final11,copy_final12,
          copy_final13,copy_final14,copy_final15,copy_final16]


copy_final=copy_agg.copy()


for df in copy_final:
    del(df['Environment'])
    yearly_noenvi.append(df)







copy_final1=yearly_oposs_final[0].copy(deep=True)
copy_final2=yearly_oposs_final[1].copy(deep=True)
copy_final3=yearly_oposs_final[2].copy(deep=True)
copy_final4=yearly_oposs_final[3].copy(deep=True)
copy_final5=yearly_oposs_final[4].copy(deep=True)
copy_final6=yearly_oposs_final[5].copy(deep=True)
copy_final7=yearly_oposs_final[6].copy(deep=True)
copy_final8=yearly_oposs_final[7].copy(deep=True)
copy_final9=yearly_oposs_final[8].copy(deep=True)
copy_final10=yearly_oposs_final[9].copy(deep=True)
copy_final11=yearly_oposs_final[10].copy(deep=True)
copy_final12=yearly_oposs_final[11].copy(deep=True)
copy_final13=yearly_oposs_final[12].copy(deep=True)
copy_final14=yearly_oposs_final[13].copy(deep=True)
copy_final15=yearly_oposs_final[14].copy(deep=True)
copy_final16=yearly_oposs_final[15].copy(deep=True)


copy_agg=[copy_final1,copy_final2,copy_final3,copy_final4,copy_final5,copy_final6,copy_final7,copy_final8,copy_final9,copy_final10,copy_final11,copy_final12,
          copy_final13,copy_final14,copy_final15,copy_final16]


copy_final=copy_agg.copy()

for df in copy_final:
    del(df['Health'])
    yearly_nohealth.append(df)








copy_final1=yearly_oposs_final[0].copy(deep=True)
copy_final2=yearly_oposs_final[1].copy(deep=True)
copy_final3=yearly_oposs_final[2].copy(deep=True)
copy_final4=yearly_oposs_final[3].copy(deep=True)
copy_final5=yearly_oposs_final[4].copy(deep=True)
copy_final6=yearly_oposs_final[5].copy(deep=True)
copy_final7=yearly_oposs_final[6].copy(deep=True)
copy_final8=yearly_oposs_final[7].copy(deep=True)
copy_final9=yearly_oposs_final[8].copy(deep=True)
copy_final10=yearly_oposs_final[9].copy(deep=True)
copy_final11=yearly_oposs_final[10].copy(deep=True)
copy_final12=yearly_oposs_final[11].copy(deep=True)
copy_final13=yearly_oposs_final[12].copy(deep=True)
copy_final14=yearly_oposs_final[13].copy(deep=True)
copy_final15=yearly_oposs_final[14].copy(deep=True)
copy_final16=yearly_oposs_final[15].copy(deep=True)


copy_agg=[copy_final1,copy_final2,copy_final3,copy_final4,copy_final5,copy_final6,copy_final7,copy_final8,copy_final9,copy_final10,copy_final11,copy_final12,
          copy_final13,copy_final14,copy_final15,copy_final16]


copy_final=copy_agg.copy()



for df in copy_final:
    del(df['Infrastructure'])
    yearly_noinf.append(df)







copy_final1=yearly_oposs_final[0].copy(deep=True)
copy_final2=yearly_oposs_final[1].copy(deep=True)
copy_final3=yearly_oposs_final[2].copy(deep=True)
copy_final4=yearly_oposs_final[3].copy(deep=True)
copy_final5=yearly_oposs_final[4].copy(deep=True)
copy_final6=yearly_oposs_final[5].copy(deep=True)
copy_final7=yearly_oposs_final[6].copy(deep=True)
copy_final8=yearly_oposs_final[7].copy(deep=True)
copy_final9=yearly_oposs_final[8].copy(deep=True)
copy_final10=yearly_oposs_final[9].copy(deep=True)
copy_final11=yearly_oposs_final[10].copy(deep=True)
copy_final12=yearly_oposs_final[11].copy(deep=True)
copy_final13=yearly_oposs_final[12].copy(deep=True)
copy_final14=yearly_oposs_final[13].copy(deep=True)
copy_final15=yearly_oposs_final[14].copy(deep=True)
copy_final16=yearly_oposs_final[15].copy(deep=True)


copy_agg=[copy_final1,copy_final2,copy_final3,copy_final4,copy_final5,copy_final6,copy_final7,copy_final8,copy_final9,copy_final10,copy_final11,copy_final12,
          copy_final13,copy_final14,copy_final15,copy_final16]


copy_final=copy_agg.copy()

for df in copy_final:
    del(df['Labor'])
    yearly_nolab.append(df)






copy_final1=yearly_oposs_final[0].copy(deep=True)
copy_final2=yearly_oposs_final[1].copy(deep=True)
copy_final3=yearly_oposs_final[2].copy(deep=True)
copy_final4=yearly_oposs_final[3].copy(deep=True)
copy_final5=yearly_oposs_final[4].copy(deep=True)
copy_final6=yearly_oposs_final[5].copy(deep=True)
copy_final7=yearly_oposs_final[6].copy(deep=True)
copy_final8=yearly_oposs_final[7].copy(deep=True)
copy_final9=yearly_oposs_final[8].copy(deep=True)
copy_final10=yearly_oposs_final[9].copy(deep=True)
copy_final11=yearly_oposs_final[10].copy(deep=True)
copy_final12=yearly_oposs_final[11].copy(deep=True)
copy_final13=yearly_oposs_final[12].copy(deep=True)
copy_final14=yearly_oposs_final[13].copy(deep=True)
copy_final15=yearly_oposs_final[14].copy(deep=True)
copy_final16=yearly_oposs_final[15].copy(deep=True)


copy_agg=[copy_final1,copy_final2,copy_final3,copy_final4,copy_final5,copy_final6,copy_final7,copy_final8,copy_final9,copy_final10,copy_final11,copy_final12,
          copy_final13,copy_final14,copy_final15,copy_final16]


copy_final=copy_agg.copy()

for df in copy_final:
    del(df['Social Conditions'])
    yearly_nosoc.append(df)
```

## Combination 1 (No Education)


```python
noedu_table=pd.DataFrame(index=cat_yearly[0][0].index,columns=['2000','2001','2002','2003','2004','2005','2006','2007','2008','2009','2010','2011','2012','2013','2014','2015'])



for x in range(0,16):   
  for index, row in yearly_noedu[x].iterrows():
          if x==0:
              mean=st.mean(row)
              noedu_table.loc[noedu_table.index==row.name,'2000']=mean
          elif x==1:
              mean=st.mean(row)
              noedu_table.loc[noedu_table.index==row.name,'2001']=mean
          elif x==2:
              mean=st.mean(row)
              noedu_table.loc[noedu_table.index==row.name,'2002']=mean
          elif x==3:
              mean=st.mean(row)
              noedu_table.loc[noedu_table.index==row.name,'2003']=mean
          elif x==4:
              mean=st.mean(row)
              noedu_table.loc[noedu_table.index==row.name,'2004']=mean
          elif x==5:
              mean=st.mean(row)
              noedu_table.loc[noedu_table.index==row.name,'2005']=mean
          elif x==6:
              mean=st.mean(row)
              noedu_table.loc[noedu_table.index==row.name,'2006']=mean
          elif x==7:
              mean=st.mean(row)
              noedu_table.loc[noedu_table.index==row.name,'2007']=mean
          elif x==8:
              mean=st.mean(row)
              noedu_table.loc[noedu_table.index==row.name,'2008']=mean
          elif x==9:
              mean=st.mean(row)
              noedu_table.loc[noedu_table.index==row.name,'2009']=mean
          elif x==10:
              mean=st.mean(row)
              noedu_table.loc[noedu_table.index==row.name,'2010']=mean
          elif x==11:
              mean=st.mean(row)
              noedu_table.loc[noedu_table.index==row.name,'2011']=mean
          elif x==12:
              mean=st.mean(row)
              noedu_table.loc[noedu_table.index==row.name,'2012']=mean
          elif x==13:
              mean=st.mean(row)
              noedu_table.loc[noedu_table.index==row.name,'2013']=mean
          elif x==14:
              mean=st.mean(row)
              noedu_table.loc[noedu_table.index==row.name,'2014']=mean              
          else:
              mean=st.mean(row)
              noedu_table.loc[noedu_table.index==row.name,'2015']=mean
            
            
            
            
noedu_table=noedu_table.T           


                
            
noedu_table = noedu_table.set_index(pd.to_datetime(noedu_table.index))            

    
    
fig, axs = plt.subplots(4, 4)
fig.tight_layout()


plt.subplot(441)
plt.xlabel('Argentina')         
gdp_df.Argentina.plot(grid=True, label="GDP", legend=True)
noedu_table.Argentina.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(442)
plt.xlabel('Brazil')         
gdp_df.Brazil.plot(grid=True, label="GDP", legend=True)
noedu_table.Brazil.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(443)
plt.xlabel('Chile')         
gdp_df.Chile.plot(grid=True, label="GDP", legend=True)
noedu_table.Chile.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(444)
plt.xlabel('France')         
gdp_df.France.plot(grid=True, label="GDP", legend=True)
noedu_table.France.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(445)
plt.xlabel('Ireland')         
gdp_df.Ireland.plot(grid=True, label="GDP", legend=True)
noedu_table.Ireland.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(446)
plt.xlabel('Italy')         
gdp_df.Italy.plot(grid=True, label="GDP", legend=True)
noedu_table.Italy.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(447)
plt.xlabel('Latvia')         
gdp_df.Latvia.plot(grid=True, label="GDP", legend=True)
noedu_table.Latvia.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(448)
plt.xlabel('Lithuania')         
gdp_df.Lithuania.plot(grid=True, label="GDP", legend=True)
noedu_table.Lithuania.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(4,4,9)
plt.xlabel('Malaysia')         
gdp_df.Malaysia.plot(grid=True, label="GDP", legend=True)
noedu_table.Malaysia.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(4,4,10)
plt.xlabel('Netherlands')         
gdp_df.Netherlands.plot(grid=True, label="GDP", legend=True)
noedu_table.Netherlands.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(4,4,11)
plt.xlabel('Pakistan')         
gdp_df.Pakistan.plot(grid=True, label="GDP", legend=True)
noedu_table.Pakistan.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(4,4,12)
plt.xlabel('Peru')         
gdp_df.Peru.plot(grid=True, label="GDP", legend=True)
noedu_table.Peru.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(4,4,13)
plt.xlabel('Spain')         
gdp_df.Spain.plot(grid=True, label="GDP", legend=True)
noedu_table.Spain.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(4,4,14)
plt.xlabel('Switzerland')         
gdp_df.Switzerland.plot(grid=True, label="GDP", legend=True)
noedu_table.Switzerland.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(4,4,15)
plt.xlabel('Thailand')         
gdp_df.Thailand.plot(grid=True, label="GDP", legend=True)
noedu_table.Thailand.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)

plt.subplot(4,4,16)
plt.xlabel('United States')         
gdp_df['United States'].plot(grid=True, label="GDP", legend=True)
noedu_table['United States'].plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.show()
```

## Combination 2 (No Environmental Conditions)


```python


noenvi_table=pd.DataFrame(index=cat_yearly[0][0].index,columns=['2000','2001','2002','2003','2004','2005','2006','2007','2008','2009','2010','2011','2012','2013','2014','2015'])



for x in range(0,16):   
  for index, row in yearly_noenvi[x].iterrows():
          if x==0:
              mean=st.mean(row)
              noenvi_table.loc[noenvi_table.index==row.name,'2000']=mean
          elif x==1:
              mean=st.mean(row)
              noenvi_table.loc[noenvi_table.index==row.name,'2001']=mean
          elif x==2:
              mean=st.mean(row)
              noenvi_table.loc[noenvi_table.index==row.name,'2002']=mean
          elif x==3:
              mean=st.mean(row)
              noenvi_table.loc[noenvi_table.index==row.name,'2003']=mean
          elif x==4:
              mean=st.mean(row)
              noenvi_table.loc[noenvi_table.index==row.name,'2004']=mean
          elif x==5:
              mean=st.mean(row)
              noenvi_table.loc[noenvi_table.index==row.name,'2005']=mean
          elif x==6:
              mean=st.mean(row)
              noenvi_table.loc[noenvi_table.index==row.name,'2006']=mean
          elif x==7:
              mean=st.mean(row)
              noenvi_table.loc[noenvi_table.index==row.name,'2007']=mean
          elif x==8:
              mean=st.mean(row)
              noenvi_table.loc[noenvi_table.index==row.name,'2008']=mean
          elif x==9:
              mean=st.mean(row)
              noenvi_table.loc[noenvi_table.index==row.name,'2009']=mean
          elif x==10:
              mean=st.mean(row)
              noenvi_table.loc[noenvi_table.index==row.name,'2010']=mean
          elif x==11:
              mean=st.mean(row)
              noenvi_table.loc[noenvi_table.index==row.name,'2011']=mean
          elif x==12:
              mean=st.mean(row)
              noenvi_table.loc[noenvi_table.index==row.name,'2012']=mean
          elif x==13:
              mean=st.mean(row)
              noenvi_table.loc[noenvi_table.index==row.name,'2013']=mean
          elif x==14:
              mean=st.mean(row)
              noenvi_table.loc[noenvi_table.index==row.name,'2014']=mean              
          else:
              mean=st.mean(row)
              noenvi_table.loc[noenvi_table.index==row.name,'2015']=mean
            
            
            
            
noenvi_table=noenvi_table.T           


                
            
noenvi_table = noenvi_table.set_index(pd.to_datetime(noenvi_table.index))            

    
    
fig, axs = plt.subplots(4, 4)
fig.tight_layout()


plt.subplot(441)
plt.xlabel('Argentina')         
gdp_df.Argentina.plot(grid=True, label="GDP", legend=True)
noenvi_table.Argentina.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(442)
plt.xlabel('Brazil')         
gdp_df.Brazil.plot(grid=True, label="GDP", legend=True)
noenvi_table.Brazil.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(443)
plt.xlabel('Chile')         
gdp_df.Chile.plot(grid=True, label="GDP", legend=True)
noenvi_table.Chile.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(444)
plt.xlabel('France')         
gdp_df.France.plot(grid=True, label="GDP", legend=True)
noenvi_table.France.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(445)
plt.xlabel('Ireland')         
gdp_df.Ireland.plot(grid=True, label="GDP", legend=True)
noenvi_table.Ireland.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(446)
plt.xlabel('Italy')         
gdp_df.Italy.plot(grid=True, label="GDP", legend=True)
noenvi_table.Italy.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(447)
plt.xlabel('Latvia')         
gdp_df.Latvia.plot(grid=True, label="GDP", legend=True)
noenvi_table.Latvia.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(448)
plt.xlabel('Lithuania')         
gdp_df.Lithuania.plot(grid=True, label="GDP", legend=True)
noenvi_table.Lithuania.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(4,4,9)
plt.xlabel('Malaysia')         
gdp_df.Malaysia.plot(grid=True, label="GDP", legend=True)
noenvi_table.Malaysia.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(4,4,10)
plt.xlabel('Netherlands')         
gdp_df.Netherlands.plot(grid=True, label="GDP", legend=True)
noenvi_table.Netherlands.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(4,4,11)
plt.xlabel('Pakistan')         
gdp_df.Pakistan.plot(grid=True, label="GDP", legend=True)
noenvi_table.Pakistan.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(4,4,12)
plt.xlabel('Peru')         
gdp_df.Peru.plot(grid=True, label="GDP", legend=True)
noenvi_table.Peru.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(4,4,13)
plt.xlabel('Spain')         
gdp_df.Spain.plot(grid=True, label="GDP", legend=True)
noenvi_table.Spain.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(4,4,14)
plt.xlabel('Switzerland')         
gdp_df.Switzerland.plot(grid=True, label="GDP", legend=True)
noenvi_table.Switzerland.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(4,4,15)
plt.xlabel('Thailand')         
gdp_df.Thailand.plot(grid=True, label="GDP", legend=True)
noenvi_table.Thailand.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)

plt.subplot(4,4,16)
plt.xlabel('United States')         
gdp_df['United States'].plot(grid=True, label="GDP", legend=True)
noenvi_table['United States'].plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.show()
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    <ipython-input-22-47f44993cb47> in <module>
    ----> 1 noenvi_table=pd.DataFrame(index=cat_yearly[0][0].index,columns=['2000','2001','2002','2003','2004','2005','2006','2007','2008','2009','2010','2011','2012','2013','2014','2015'])
          2 
          3 
          4 
          5 for x in range(0,16):


    NameError: name 'cat_yearly' is not defined


## Combination 3 (No Health Conditions)


```python


nohealth_table=pd.DataFrame(index=cat_yearly[0][0].index,columns=['2000','2001','2002','2003','2004','2005','2006','2007','2008','2009','2010','2011','2012','2013','2014','2015'])



for x in range(0,16):   
  for index, row in yearly_nohealth[x].iterrows():
          if x==0:
              mean=st.mean(row)
              nohealth_table.loc[nohealth_table.index==row.name,'2000']=mean
          elif x==1:
              mean=st.mean(row)
              nohealth_table.loc[nohealth_table.index==row.name,'2001']=mean
          elif x==2:
              mean=st.mean(row)
              nohealth_table.loc[nohealth_table.index==row.name,'2002']=mean
          elif x==3:
              mean=st.mean(row)
              nohealth_table.loc[nohealth_table.index==row.name,'2003']=mean
          elif x==4:
              mean=st.mean(row)
              nohealth_table.loc[nohealth_table.index==row.name,'2004']=mean
          elif x==5:
              mean=st.mean(row)
              nohealth_table.loc[nohealth_table.index==row.name,'2005']=mean
          elif x==6:
              mean=st.mean(row)
              nohealth_table.loc[nohealth_table.index==row.name,'2006']=mean
          elif x==7:
              mean=st.mean(row)
              nohealth_table.loc[nohealth_table.index==row.name,'2007']=mean
          elif x==8:
              mean=st.mean(row)
              nohealth_table.loc[nohealth_table.index==row.name,'2008']=mean
          elif x==9:
              mean=st.mean(row)
              nohealth_table.loc[nohealth_table.index==row.name,'2009']=mean
          elif x==10:
              mean=st.mean(row)
              nohealth_table.loc[nohealth_table.index==row.name,'2010']=mean
          elif x==11:
              mean=st.mean(row)
              nohealth_table.loc[nohealth_table.index==row.name,'2011']=mean
          elif x==12:
              mean=st.mean(row)
              nohealth_table.loc[nohealth_table.index==row.name,'2012']=mean
          elif x==13:
              mean=st.mean(row)
              nohealth_table.loc[nohealth_table.index==row.name,'2013']=mean
          elif x==14:
              mean=st.mean(row)
              nohealth_table.loc[nohealth_table.index==row.name,'2014']=mean              
          else:
              mean=st.mean(row)
              nohealth_table.loc[nohealth_table.index==row.name,'2015']=mean
            
            
            
            
nohealth_table=nohealth_table.T           


                
            
nohealth_table = nohealth_table.set_index(pd.to_datetime(nohealth_table.index))            

    
    
fig, axs = plt.subplots(4, 4)
fig.tight_layout()


plt.subplot(441)
plt.xlabel('Argentina')         
gdp_df.Argentina.plot(grid=True, label="GDP", legend=True)
nohealth_table.Argentina.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(442)
plt.xlabel('Brazil')         
gdp_df.Brazil.plot(grid=True, label="GDP", legend=True)
nohealth_table.Brazil.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(443)
plt.xlabel('Chile')         
gdp_df.Chile.plot(grid=True, label="GDP", legend=True)
nohealth_table.Chile.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(444)
plt.xlabel('France')         
gdp_df.France.plot(grid=True, label="GDP", legend=True)
nohealth_table.France.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(445)
plt.xlabel('Ireland')         
gdp_df.Ireland.plot(grid=True, label="GDP", legend=True)
nohealth_table.Ireland.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(446)
plt.xlabel('Italy')         
gdp_df.Italy.plot(grid=True, label="GDP", legend=True)
nohealth_table.Italy.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(447)
plt.xlabel('Latvia')         
gdp_df.Latvia.plot(grid=True, label="GDP", legend=True)
nohealth_table.Latvia.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(448)
plt.xlabel('Lithuania')         
gdp_df.Lithuania.plot(grid=True, label="GDP", legend=True)
nohealth_table.Lithuania.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(4,4,9)
plt.xlabel('Malaysia')         
gdp_df.Malaysia.plot(grid=True, label="GDP", legend=True)
nohealth_table.Malaysia.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(4,4,10)
plt.xlabel('Netherlands')         
gdp_df.Netherlands.plot(grid=True, label="GDP", legend=True)
nohealth_table.Netherlands.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(4,4,11)
plt.xlabel('Pakistan')         
gdp_df.Pakistan.plot(grid=True, label="GDP", legend=True)
nohealth_table.Pakistan.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(4,4,12)
plt.xlabel('Peru')         
gdp_df.Peru.plot(grid=True, label="GDP", legend=True)
nohealth_table.Peru.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(4,4,13)
plt.xlabel('Spain')         
gdp_df.Spain.plot(grid=True, label="GDP", legend=True)
nohealth_table.Spain.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(4,4,14)
plt.xlabel('Switzerland')         
gdp_df.Switzerland.plot(grid=True, label="GDP", legend=True)
nohealth_table.Switzerland.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(4,4,15)
plt.xlabel('Thailand')         
gdp_df.Thailand.plot(grid=True, label="GDP", legend=True)
nohealth_table.Thailand.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)

plt.subplot(4,4,16)
plt.xlabel('United States')         
gdp_df['United States'].plot(grid=True, label="GDP", legend=True)
nohealth_table['United States'].plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.show()
```

## Combination 4 (No Infrastructure)


```python



noinf_table=pd.DataFrame(index=cat_yearly[0][0].index,columns=['2000','2001','2002','2003','2004','2005','2006','2007','2008','2009','2010','2011','2012','2013','2014','2015'])



for x in range(0,16):   
  for index, row in yearly_noinf[x].iterrows():
          if x==0:
              mean=st.mean(row)
              noinf_table.loc[noinf_table.index==row.name,'2000']=mean
          elif x==1:
              mean=st.mean(row)
              noinf_table.loc[noinf_table.index==row.name,'2001']=mean
          elif x==2:
              mean=st.mean(row)
              noinf_table.loc[noinf_table.index==row.name,'2002']=mean
          elif x==3:
              mean=st.mean(row)
              noinf_table.loc[noinf_table.index==row.name,'2003']=mean
          elif x==4:
              mean=st.mean(row)
              noinf_table.loc[noinf_table.index==row.name,'2004']=mean
          elif x==5:
              mean=st.mean(row)
              noinf_table.loc[noinf_table.index==row.name,'2005']=mean
          elif x==6:
              mean=st.mean(row)
              noinf_table.loc[noinf_table.index==row.name,'2006']=mean
          elif x==7:
              mean=st.mean(row)
              noinf_table.loc[noinf_table.index==row.name,'2007']=mean
          elif x==8:
              mean=st.mean(row)
              noinf_table.loc[noinf_table.index==row.name,'2008']=mean
          elif x==9:
              mean=st.mean(row)
              noinf_table.loc[noinf_table.index==row.name,'2009']=mean
          elif x==10:
              mean=st.mean(row)
              noinf_table.loc[noinf_table.index==row.name,'2010']=mean
          elif x==11:
              mean=st.mean(row)
              noinf_table.loc[noinf_table.index==row.name,'2011']=mean
          elif x==12:
              mean=st.mean(row)
              noinf_table.loc[noinf_table.index==row.name,'2012']=mean
          elif x==13:
              mean=st.mean(row)
              noinf_table.loc[noinf_table.index==row.name,'2013']=mean
          elif x==14:
              mean=st.mean(row)
              noinf_table.loc[noinf_table.index==row.name,'2014']=mean              
          else:
              mean=st.mean(row)
              noinf_table.loc[noinf_table.index==row.name,'2015']=mean
            
            
            
            
noinf_table=noinf_table.T           


                
            
noinf_table = noinf_table.set_index(pd.to_datetime(noinf_table.index))            

    
    
fig, axs = plt.subplots(4, 4)
fig.tight_layout()


plt.subplot(441)
plt.xlabel('Argentina')         
gdp_df.Argentina.plot(grid=True, label="GDP", legend=True)
noinf_table.Argentina.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(442)
plt.xlabel('Brazil')         
gdp_df.Brazil.plot(grid=True, label="GDP", legend=True)
noinf_table.Brazil.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(443)
plt.xlabel('Chile')         
gdp_df.Chile.plot(grid=True, label="GDP", legend=True)
noinf_table.Chile.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(444)
plt.xlabel('France')         
gdp_df.France.plot(grid=True, label="GDP", legend=True)
noinf_table.France.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(445)
plt.xlabel('Ireland')         
gdp_df.Ireland.plot(grid=True, label="GDP", legend=True)
noinf_table.Ireland.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(446)
plt.xlabel('Italy')         
gdp_df.Italy.plot(grid=True, label="GDP", legend=True)
noinf_table.Italy.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(447)
plt.xlabel('Latvia')         
gdp_df.Latvia.plot(grid=True, label="GDP", legend=True)
noinf_table.Latvia.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(448)
plt.xlabel('Lithuania')         
gdp_df.Lithuania.plot(grid=True, label="GDP", legend=True)
noinf_table.Lithuania.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(4,4,9)
plt.xlabel('Malaysia')         
gdp_df.Malaysia.plot(grid=True, label="GDP", legend=True)
noinf_table.Malaysia.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(4,4,10)
plt.xlabel('Netherlands')         
gdp_df.Netherlands.plot(grid=True, label="GDP", legend=True)
noinf_table.Netherlands.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(4,4,11)
plt.xlabel('Pakistan')         
gdp_df.Pakistan.plot(grid=True, label="GDP", legend=True)
noinf_table.Pakistan.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(4,4,12)
plt.xlabel('Peru')         
gdp_df.Peru.plot(grid=True, label="GDP", legend=True)
noinf_table.Peru.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(4,4,13)
plt.xlabel('Spain')         
gdp_df.Spain.plot(grid=True, label="GDP", legend=True)
noinf_table.Spain.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(4,4,14)
plt.xlabel('Switzerland')         
gdp_df.Switzerland.plot(grid=True, label="GDP", legend=True)
noinf_table.Switzerland.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(4,4,15)
plt.xlabel('Thailand')         
gdp_df.Thailand.plot(grid=True, label="GDP", legend=True)
noinf_table.Thailand.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)

plt.subplot(4,4,16)
plt.xlabel('United States')         
gdp_df['United States'].plot(grid=True, label="GDP", legend=True)
noinf_table['United States'].plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)




plt.show()
```

## Combination 5 (No Labor Conditions)


```python


nolab_table=pd.DataFrame(index=cat_yearly[0][0].index,columns=['2000','2001','2002','2003','2004','2005','2006','2007','2008','2009','2010','2011','2012','2013','2014','2015'])



for x in range(0,16):   
  for index, row in yearly_nolab[x].iterrows():
          if x==0:
              mean=st.mean(row)
              nolab_table.loc[nolab_table.index==row.name,'2000']=mean
          elif x==1:
              mean=st.mean(row)
              nolab_table.loc[nolab_table.index==row.name,'2001']=mean
          elif x==2:
              mean=st.mean(row)
              nolab_table.loc[nolab_table.index==row.name,'2002']=mean
          elif x==3:
              mean=st.mean(row)
              nolab_table.loc[nolab_table.index==row.name,'2003']=mean
          elif x==4:
              mean=st.mean(row)
              nolab_table.loc[nolab_table.index==row.name,'2004']=mean
          elif x==5:
              mean=st.mean(row)
              nolab_table.loc[nolab_table.index==row.name,'2005']=mean
          elif x==6:
              mean=st.mean(row)
              nolab_table.loc[nolab_table.index==row.name,'2006']=mean
          elif x==7:
              mean=st.mean(row)
              nolab_table.loc[nolab_table.index==row.name,'2007']=mean
          elif x==8:
              mean=st.mean(row)
              nolab_table.loc[nolab_table.index==row.name,'2008']=mean
          elif x==9:
              mean=st.mean(row)
              nolab_table.loc[nolab_table.index==row.name,'2009']=mean
          elif x==10:
              mean=st.mean(row)
              nolab_table.loc[nolab_table.index==row.name,'2010']=mean
          elif x==11:
              mean=st.mean(row)
              nolab_table.loc[nolab_table.index==row.name,'2011']=mean
          elif x==12:
              mean=st.mean(row)
              nolab_table.loc[nolab_table.index==row.name,'2012']=mean
          elif x==13:
              mean=st.mean(row)
              nolab_table.loc[nolab_table.index==row.name,'2013']=mean
          elif x==14:
              mean=st.mean(row)
              nolab_table.loc[nolab_table.index==row.name,'2014']=mean              
          else:
              mean=st.mean(row)
              nolab_table.loc[nolab_table.index==row.name,'2015']=mean
            
            
            
            
nolab_table=nolab_table.T           


                
            
nolab_table = nolab_table.set_index(pd.to_datetime(nolab_table.index))            

    
    
fig, axs = plt.subplots(4, 4)
fig.tight_layout()


plt.subplot(441)
plt.xlabel('Argentina')         
gdp_df.Argentina.plot(grid=True, label="GDP", legend=True)
nolab_table.Argentina.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(442)
plt.xlabel('Brazil')         
gdp_df.Brazil.plot(grid=True, label="GDP", legend=True)
nolab_table.Brazil.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(443)
plt.xlabel('Chile')         
gdp_df.Chile.plot(grid=True, label="GDP", legend=True)
nolab_table.Chile.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(444)
plt.xlabel('France')         
gdp_df.France.plot(grid=True, label="GDP", legend=True)
nolab_table.France.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(445)
plt.xlabel('Ireland')         
gdp_df.Ireland.plot(grid=True, label="GDP", legend=True)
nolab_table.Ireland.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(446)
plt.xlabel('Italy')         
gdp_df.Italy.plot(grid=True, label="GDP", legend=True)
nolab_table.Italy.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(447)
plt.xlabel('Latvia')         
gdp_df.Latvia.plot(grid=True, label="GDP", legend=True)
nolab_table.Latvia.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(448)
plt.xlabel('Lithuania')         
gdp_df.Lithuania.plot(grid=True, label="GDP", legend=True)
nolab_table.Lithuania.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(4,4,9)
plt.xlabel('Malaysia')         
gdp_df.Malaysia.plot(grid=True, label="GDP", legend=True)
nolab_table.Malaysia.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(4,4,10)
plt.xlabel('Netherlands')         
gdp_df.Netherlands.plot(grid=True, label="GDP", legend=True)
nolab_table.Netherlands.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(4,4,11)
plt.xlabel('Pakistan')         
gdp_df.Pakistan.plot(grid=True, label="GDP", legend=True)
nolab_table.Pakistan.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(4,4,12)
plt.xlabel('Peru')         
gdp_df.Peru.plot(grid=True, label="GDP", legend=True)
nolab_table.Peru.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(4,4,13)
plt.xlabel('Spain')         
gdp_df.Spain.plot(grid=True, label="GDP", legend=True)
nolab_table.Spain.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(4,4,14)
plt.xlabel('Switzerland')         
gdp_df.Switzerland.plot(grid=True, label="GDP", legend=True)
nolab_table.Switzerland.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(4,4,15)
plt.xlabel('Thailand')         
gdp_df.Thailand.plot(grid=True, label="GDP", legend=True)
nolab_table.Thailand.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)

plt.subplot(4,4,16)
plt.xlabel('United States')         
gdp_df['United States'].plot(grid=True, label="GDP", legend=True)
nolab_table['United States'].plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)




plt.show()
```

## Combination 6 (No Social Conditions)


```python
nosoc_table=pd.DataFrame(index=cat_yearly[0][0].index,columns=['2000','2001','2002','2003','2004','2005','2006','2007','2008','2009','2010','2011','2012','2013','2014','2015'])



for x in range(0,16):   
  for index, row in yearly_nosoc[x].iterrows():
          if x==0:
              mean=st.mean(row)
              nosoc_table.loc[nosoc_table.index==row.name,'2000']=mean
          elif x==1:
              mean=st.mean(row)
              nosoc_table.loc[nosoc_table.index==row.name,'2001']=mean
          elif x==2:
              mean=st.mean(row)
              nosoc_table.loc[nosoc_table.index==row.name,'2002']=mean
          elif x==3:
              mean=st.mean(row)
              nosoc_table.loc[nosoc_table.index==row.name,'2003']=mean
          elif x==4:
              mean=st.mean(row)
              nosoc_table.loc[nosoc_table.index==row.name,'2004']=mean
          elif x==5:
              mean=st.mean(row)
              nosoc_table.loc[nosoc_table.index==row.name,'2005']=mean
          elif x==6:
              mean=st.mean(row)
              nosoc_table.loc[nosoc_table.index==row.name,'2006']=mean
          elif x==7:
              mean=st.mean(row)
              nosoc_table.loc[nosoc_table.index==row.name,'2007']=mean
          elif x==8:
              mean=st.mean(row)
              nosoc_table.loc[nosoc_table.index==row.name,'2008']=mean
          elif x==9:
              mean=st.mean(row)
              nosoc_table.loc[nosoc_table.index==row.name,'2009']=mean
          elif x==10:
              mean=st.mean(row)
              nosoc_table.loc[nosoc_table.index==row.name,'2010']=mean
          elif x==11:
              mean=st.mean(row)
              nosoc_table.loc[nosoc_table.index==row.name,'2011']=mean
          elif x==12:
              mean=st.mean(row)
              nosoc_table.loc[nosoc_table.index==row.name,'2012']=mean
          elif x==13:
              mean=st.mean(row)
              nosoc_table.loc[nosoc_table.index==row.name,'2013']=mean
          elif x==14:
              mean=st.mean(row)
              nosoc_table.loc[nosoc_table.index==row.name,'2014']=mean              
          else:
              mean=st.mean(row)
              nosoc_table.loc[nosoc_table.index==row.name,'2015']=mean
            
            
            
            
nosoc_table=nosoc_table.T           


                
            
nosoc_table = nosoc_table.set_index(pd.to_datetime(nosoc_table.index))            

    
    
fig, axs = plt.subplots(4, 4)
fig.tight_layout()


plt.subplot(441)
plt.xlabel('Argentina')         
gdp_df.Argentina.plot(grid=True, label="GDP", legend=True)
nosoc_table.Argentina.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(442)
plt.xlabel('Brazil')         
gdp_df.Brazil.plot(grid=True, label="GDP", legend=True)
nosoc_table.Brazil.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(443)
plt.xlabel('Chile')         
gdp_df.Chile.plot(grid=True, label="GDP", legend=True)
nosoc_table.Chile.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(444)
plt.xlabel('France')         
gdp_df.France.plot(grid=True, label="GDP", legend=True)
nosoc_table.France.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(445)
plt.xlabel('Ireland')         
gdp_df.Ireland.plot(grid=True, label="GDP", legend=True)
nosoc_table.Ireland.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(446)
plt.xlabel('Italy')         
gdp_df.Italy.plot(grid=True, label="GDP", legend=True)
nosoc_table.Italy.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(447)
plt.xlabel('Latvia')         
gdp_df.Latvia.plot(grid=True, label="GDP", legend=True)
nosoc_table.Latvia.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(448)
plt.xlabel('Lithuania')         
gdp_df.Lithuania.plot(grid=True, label="GDP", legend=True)
nosoc_table.Lithuania.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(4,4,9)
plt.xlabel('Malaysia')         
gdp_df.Malaysia.plot(grid=True, label="GDP", legend=True)
nosoc_table.Malaysia.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(4,4,10)
plt.xlabel('Netherlands')         
gdp_df.Netherlands.plot(grid=True, label="GDP", legend=True)
nosoc_table.Netherlands.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(4,4,11)
plt.xlabel('Pakistan')         
gdp_df.Pakistan.plot(grid=True, label="GDP", legend=True)
nosoc_table.Pakistan.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.subplot(4,4,12)
plt.xlabel('Peru')         
gdp_df.Peru.plot(grid=True, label="GDP", legend=True)
nosoc_table.Peru.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(4,4,13)
plt.xlabel('Spain')         
gdp_df.Spain.plot(grid=True, label="GDP", legend=True)
nosoc_table.Spain.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(4,4,14)
plt.xlabel('Switzerland')         
gdp_df.Switzerland.plot(grid=True, label="GDP", legend=True)
nosoc_table.Switzerland.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)


plt.subplot(4,4,15)
plt.xlabel('Thailand')         
gdp_df.Thailand.plot(grid=True, label="GDP", legend=True)
nosoc_table.Thailand.plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)

plt.subplot(4,4,16)
plt.xlabel('United States')         
gdp_df['United States'].plot(grid=True, label="GDP", legend=True)
nosoc_table['United States'].plot(secondary_y=True, label="Wellbeing Index", legend=True)
plt.xticks(rotation=90)



plt.show()
```

# Discussion and conclusion


A growing number of researchers in an interdisciplinary social sciences framework have proved and believe that the marginal benefits of a further increase in GDP when a certain value threshold has been based, are minuscule, and thus, the economically developed countries should focus their attention on phenomena of social pathologies, instead of growth.

What the present analysis tried to investigate was based on the claim above, but taken one step further, hypothesis-wise. That is the implied impact of not diverting the focus to these social pathologies when you have passed a given wealth threshold. Thus, the goal was to contribute to proving the importance of maintaining healthy institutions, and most importantly, the trust of the general public towards them.

Unfortunately, based on the statistical methods and measures employed, the Wellbeing and Development Construct, in this case, is not credible enough to be considered a useful tool in a policy-maker toolbox. What may have gone wrong, starts from the unavailability of data, and thus, of variables across the countries, leading to a hardly representative sample and low dimensionality. The above condition resulted in a low number of variables used in the majority of the manually constructed categories, which probably were not enough to represent their quality as a compounded factor. Also, the manual construction itself may have proved problematic, as there may have been an overlapping of qualities among several variables, and their predominant one may have been different than the one hypothesized. Moreover, the qualities expected could have also been different, and a more advanced classification algorithm could have been used. Finally, there could have been other types of relations among the variables used across the categories, concerning their group effect (i.e., multiplicative instead of additive).

But let us interpret the results as they came up. Firstly, it should be noted that the aggregate levels of the average values of the major categories of Education, Environment, Health, Labor, and Social Conditions across those countries vary greatly. That means, the observed decrease in high-income countries is being actualized in a relatively high level of the index (e.g., in the Netherlands, the index ranges from 80 to 90, and the decrease takes place inside this high range), while in the low-income countries, an increase takes place in a relatively low level (e.g., in Thailand an increase can be spotted, but in the low range of 25 to 35). Theoretically, it should be expected that a decrease in a high range country may not present a threat to social cohesion, but for the low range countries, it may have detrimental effects. Also, the gains, if they were to take place, are decreasing as time goes, and they are characterized by a range of maximum values, that is, not occurring indefinitely.

In conclusion, based on the literal results of the analysis, it can be drawn that the GDP is indeed incapable of embodying the complexity of societies and oversimplifies their ontology to an easily computable measure, that acts as a mere heuristic and inadequate proxy of societal health and efficiency.
