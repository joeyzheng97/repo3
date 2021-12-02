# 141Bpj
141B final Group Project

Contributions:
    Zuer Zheng 
    Jinghan Xu
    Xueyin Zhu
    Fengshen Zhou

Introduction:
On January 30, 2020, the WHO declared the COVID-19 outbreak a global health emergency. On March 11, 2020, the WHO declared COVID-19 a global pandemic, pointing to the over 118,000 cases of the Coronavirus illness in over 110 countries and territories around the world at the time. The COVID-19 event is a full-blown outbreak in a short period of time worldwide. Even today, the coronavirus remains a major threat to human existence. 
Our main goal of this project is to observe the timing and location of major outbreaks of the coronavirus.
Analyze whether various external factors had an impact on the outbreak such as vaccine accepted rate, and probably we can make predictions of the trends in the development of the viruse.

Description of the dataset:
    Source:
        Report Coronavirus disease 2019 (COVID-19) confirmed cases, deaths and reported recoveries with time series.         Data is disaggregated by country (and sometimes subregion).
        Data is in CSV format and updated daily. It is sourced from this upstream repository maintained by the               amazing team at Johns Hopkins University Center for Systems Science and Engineering (CSSE) who have been             doing a great public service from an early point by collating data from around the world.
    The website to the dataset is the following:
        https://datahub.io/core/covid-19#data-cli
        https://data.chhs.ca.gov/dataset/e283ee5a-cf18-4f20-a92c-ee94a2866ccd/resource/130d7ba2-b6eb-438d-a412-741bde207e1c/download/covid19vaccinesbycounty.csv


Question of interest:
    1.
    2.

Methodologies:
    1. Using Web API, parse HTML and json to get the dataset, since the covid dataset is updating every single day.
    2. Using the munging tools in pandas,grouping, joining the dataset we want. 
    3. Storing dataset through SQL queries.
    4. Using different kind of plot to make data visual. 
    5. 


/Data/:
We will convert json into dataframe and also convert data into sqlite for convenience of doung further analysis.
Ane there has no dataset in this folder since  we will use web API get the dataset. Becase the dataset is updated daily.

/Code/:


/notebooks/:
We stores the ipynb file in the notebooks direction, which contains our display notebook. 


