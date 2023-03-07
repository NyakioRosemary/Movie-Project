# Phase 1 Project

Business Problem
Exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

## Introduction 
Films industry is an entertainment entity . Movies is one way that a company can make money, market, advertise and lure investors and customers.
For this project, we are analysis data to generate insights for a business stakeholder for them to understand which films they should venture into .
In this data set we will be digesting on the 3 provided datasets to try and understand them and come up with recommendations through findings. This is a shallow digestion and massaging of the dataset i will be working on.

# Table of content 
*  loading Libraries 
*  Loading data structure 
*  Concat tables
*  ste_index
*  Data Preprocessing
*  Dropping column 
*  Missing Values 
*  Relacing values 
*  Change data type 
*  EDA 
   *  Outliers values 
   *  Scatter matrix
   *  Univariate annalysis categorical data
        *Groupying value_count and and bar plots 
   *  Bivariate annalysis numerical data
        * Groupying by mean 
        *  Correlation 
        *  Scatter

 Ibjectives / Questions to Answer
* Genre with the value count
* Genre of movie with the highest and lowest runtime minutes
* Genre with the highest rating
* Genre withe the highest domestic gross and foreign gross### Objectives


### The Data

In the folder `zippedData` are movie datasets from:
* imdb.title.basics
* imdb.title.ratings
* bom.movie_gross

## Getting Started 
Loading Libraries
![image](https://user-images.githubusercontent.com/121230138/218148002-92a863a1-5de1-43d7-a4dd-ad0093cf3fe4.png)

Loading data structure
![image](https://user-images.githubusercontent.com/121230138/218148221-1d50af06-b4bf-444e-b877-9a6a7616e85e.png)

Concat tables
![image](https://user-images.githubusercontent.com/121230138/218148306-9c3b75a5-9ddb-4ac6-879e-d8d9207081c1.png)

![image](https://user-images.githubusercontent.com/121230138/218150373-780429f8-be83-4fc0-9116-12937180f6d3.png)
 # Observation from above data 
 ![image](https://user-images.githubusercontent.com/121230138/218150535-3cf9d459-dc2d-4aaa-bb0e-e94c63605775.png)
Joining the tables together 
![image](https://user-images.githubusercontent.com/121230138/218150769-ea1a943d-6280-42dd-8196-4c7f4324a8bb.png)

set_index
![image](https://user-images.githubusercontent.com/121230138/218152187-7b7199c4-25a0-4e5e-b635-acdb7553f8e2.png)

Data Preprocessing
Dropping column
![image](https://user-images.githubusercontent.com/121230138/218152309-6849acb5-d1da-4433-8eb1-7e6e768ef052.png)

Missing Values
![image](https://user-images.githubusercontent.com/121230138/218152410-61938972-5116-4139-83ca-fa01a1be0812.png)

![image](https://user-images.githubusercontent.com/121230138/218152584-a93c408a-e735-42a8-aa2b-96fcfdb7273c.png)

Replacing characters
![image](https://user-images.githubusercontent.com/121230138/218152669-7258c470-7cae-429d-85d0-90af5f6a42b3.png)

Change data type
changing data type and getting statistical data foreign gross has been added 
![image](https://user-images.githubusercontent.com/121230138/218153231-2437d495-db87-43cf-8623-01cfb7360c75.png)
Dealing with missing values 
![image](https://user-images.githubusercontent.com/121230138/218154829-41d5e618-e165-4274-80c1-219600e598fd.png)
 Filling with mean and having an over view of the data frame 
 ![image](https://user-images.githubusercontent.com/121230138/218156848-d9a13fda-443c-4900-b63f-742848bdb528.png)

EDA
Using visualization to understand the dataset 
Outliers values
![image](https://user-images.githubusercontent.com/121230138/218158545-e7260f3d-a980-47b5-83eb-2574bab2a8d0.png)
![image](https://user-images.githubusercontent.com/121230138/218158631-1ed454d0-d652-496c-ba17-896b29b4ef05.png)

Scatter matrix
![image](https://user-images.githubusercontent.com/121230138/218158772-ce550ab5-32d9-4c81-be65-d5b8ae08c177.png)

Univariate annalysis categorical data *Groupying value_count and and bar plots
Genre distribution 
Exploding genre 
![image](https://user-images.githubusercontent.com/121230138/218159487-19f434ab-65d3-463b-b6e2-b14a0dfc4f5e.png)

Grouping by and getting the value_counts()
![image](https://user-images.githubusercontent.com/121230138/218159699-5dc2263c-0433-4b36-85b3-94ca42ddeb09.png)

Value count distribution 
![image](https://user-images.githubusercontent.com/121230138/218159923-4bc2f982-460d-42e5-bf37-50125e935520.png)
 Question 2 
 Bivariate annalysis numerical data
Groupying by mean
Correlation
Scatter
 Genre with the highest runtime minutes 
![image](https://user-images.githubusercontent.com/121230138/218160911-d29a16c6-843f-495c-a1ea-78655ce6ebbc.png)

sorting the column
![image](https://user-images.githubusercontent.com/121230138/218161017-156c28ab-d703-4ea7-b541-5b627332c744.png)
Annalysis with average rating 
![image](https://user-images.githubusercontent.com/121230138/218161175-e2798e16-4a00-49dd-b36c-2235b3cbf4b7.png)

Graph overview by sorting
![image](https://user-images.githubusercontent.com/121230138/218161310-8aa1b0ce-c0a1-49a4-a5e8-02281012e361.png)

![image](https://user-images.githubusercontent.com/121230138/218161385-6c446f7c-5e7f-4364-946a-1e47aa20f1e1.png)

Question 3
![image](https://user-images.githubusercontent.com/121230138/218161520-4a682ba5-84be-47e1-a531-e02677ff0fd8.png)

Sorting by domestic 
![image](https://user-images.githubusercontent.com/121230138/218161663-925cdfd1-98ec-460b-bc3f-7bf77ae513f8.png)

Sorting by Foreign 
![image](https://user-images.githubusercontent.com/121230138/218161752-cffcb0fb-85b8-4832-a95a-31c8ce8e1401.png)

Visualizing Domestic and Foreign Gross 
![image](https://user-images.githubusercontent.com/121230138/218161960-9639135e-e902-4adf-9c53-5b018b94f6e8.png)

Correlation with scatter plot between Domestic and Foreign gross 
![image](https://user-images.githubusercontent.com/121230138/218162183-cc782a71-f88f-4b37-8225-d01d358ffa81.png)

Question 5 
How does runtime affect domestic and Foreign gross 

![image](https://user-images.githubusercontent.com/121230138/218162473-013b6059-b975-4d2b-a874-099ec6b8e748.png)

## Conclusion
     *Drama has the highest count
*Thefore people love drama
     *Genre moie with the highest runtime minutes Action and the lowest is Reality Tv
     *Genre with the highest rating is Reality Tv
*Therefore the lower the minutes the higher the rating
     *Domestic gross scifi is making profits
     *Foreign Gross we see War leading with making profit
*Therefore movies that are doing well domestically are not doing well foreign as gross is concerned

## Limitation
    *we see 0 data clastures at the bottom because i did not remove the values which if i did would have clusters the data set
## Recommendation
    *based on the rating it will be fir if Microsoft focusses on short films
    *Venture into Drama as is the most watched when runtime minutes are reduced profits will be made
    *Introduce rating in your software to see what customers are saying through Rating
    *When it comes to local and foreign genres prioritize on both to give the same outcome
