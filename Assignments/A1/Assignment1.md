# Assignment 1

## Patrick Pfenning

1. Define data mining in your own words and explain why it is important in today's world.

> Data mining is the act of obtaining knowledge from vast, often disorganized and seemingly unrelated data sources.
> Every recorded action creates data.
> Each image we take, text we send, every time we move our cursors, data is created.
> Automated systems create metadata with each interation they have.
> Real time and batch data are consumed and transferred at the peta scales or larger on a daily basis. 
> Sets such as this are far too myriad for humans to consume effectively.
> These amalgamous structures provide little insight on their own, however when mined correctly vast amounts of repeatable behavior can be discovered.

2. What are the main stages of the data mining process? Briefly explain each stage.

- Business Understanding: 

> Akin to hypothesis development, we propose a question we wish for the data to solve. 
> We design plans around data extraction and transformational steps which will help us solve this problem.

- Data Understanding:

> Here we develop knowledge about the data.
> We use this step answer many questions, including the following:
>> - How is/are our source(s) structured?
>> - Is it relational?
>> - How is the data obtained? 
>> - Is it compressed?
>> - Are the raw features qualitative or quantitative?
>> - What data types are used and what should they be?
>> - Is the data streamed or batched?
>> - Is there a true primary key?
>> - Does this data need preliminary cleaning (preprocessing)?
>> 
> This step often results in a feature store of some sort, which provides metadata around segments of the data itself.

- Data Preparation:

> Once the raw data is properly stored in a lake/warehouse, we must begin building a pipeline to push our data to our models.
> This step includes actions like:
> >- Filling or dropping null data
> >- Transforming features to correct data types (string to int/bool).
> >- Splitting features into sub-features.
> >- Combing multiple features to develop new ones (PCA).
> >- Normalization.
> >- Outlier removal.

- Modeling:

> Here data scientists select features from our prepared data.
> Parameters are optimized to fit each model uniquely.

- Evaluation:

> 



3. In the context of data mining, what is the difference between predictive and descriptive tasks? Provide examples of each.

4. Describe the concept of clustering and its significance in data mining. Give at least two real-world examples where clustering is applied.

5. Choose  one  of  the  applications  discussed  in  the  slides,  either  market  segmentation  or  fraud detection, and explain the approach and goal of that application. Include the steps involved and the benefits it brings to businesses or organizations.

6. Explain  the  concept  of  regression  in  data  mining  and  provide  examples  of  its  applications  in different domains.

7. Explain the process of clustering and how it is applied in market segmentation.

8. Discuss the concept of document clustering. What approach is used to cluster similar documents together?

9. Define Association Rule Discovery in your own words and provide an example of its application in any industry of your choice.

10. A  lung  cancer  dataset  revealed  a  significant  Subspace  Differential  Coexpression  Pattern.  This pattern was related to the TNF/NFB signaling pathway with a P-value of 1.4*10^-5. Explain what this means in the context of association analysis.

11. Define  anomaly  detection. How  is  it  used  in  credit  card  fraud  detection and  network intrusion detection?

12. Discuss the following challenges in data mining: scalability, high dimensionality, heterogeneous and complex data, data ownership and distribution, non-traditional analysis. Provide a potential solution or strategy foreach.

13. Based on the topics discussed, why is data mining important in today's data-driven world? Include specific examples from the course material in your answer.

14. Discuss whether or not each of the following activities is a data mining task. 

    1. Dividing the customers of a company according to their gender.
    2. Dividing the customers of a company according to their profitability.
    3. Computing the total sales of a company.
    4. Sorting a student database based on student identification numbers.
    5. Predicting the outcomes of tossing a (fair) pair of dice.
    6. Predicting the future stock price of a company using historical records.
    7. Monitoring the heart rate of a patient for abnormalities.
    8. Monitoring seismic waves for earthquake activities.
    9. Extracting the frequencies of a sound wave.
15. Suppose  that  you  are  employed  as  a  data  mining  consultant  for  an  Internetsearch  engine company. Describe  how  data mining  can  help  the company bygiving specific  examples of how techniques, such as clustering, classification,association rule mining, and anomaly detection can be applied.
16. For each of the following data sets, explain whether or not data privacy isan important issue.
    1. Census data collected from 1900–1950.
    2. IP addresses and visit times of web users who visit your website.
    3. Images from Earth-orbiting satellites.
    4. Names and addresses of people from the telephone book.
    5. Names and email addresses collected from the Web.