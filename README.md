![image](https://user-images.githubusercontent.com/110699702/186933478-746d378b-73c0-43d4-955b-bbd89dbcdeda.png)



Flatiron consulting:
Stefano Caruso Director of Data
Andrew Boucher Principle Data Science
Samuel Robins Lead Data scientist

 Microsoft's New Movie series will be a block buster!
 

Task: Present to Microsoft on how they can penetrate the movie industry successfully. We analyzed the data and found previous movies financial records. 


# Business Problem

Microsoft is interested in the movie industry. Their lack of experience has led them to source
out a specialist in the field. I will inform Microsoft of the proper steps and strategy while 
using visualization tools, looking at historic data will allow us a clear vision and path. Becoming profitable with a reasonable production budget will be revealed in the data. 
Questions being considered:
What are the top films with the most financial success based on genre?
Runtime with high revenue ?
Understand the film industry through data?


# Data
We've chosen to analyze two datasets (tmdb.movies.csv.gz, tn.movie_budgets.csv.gz). After review we cleaned and combined them into one main dataframe clean_df“”. 
Missing data appears to be an issue and will be omitted because it is useless and minimal data points. runtime missing data does not have a overall revenue that falls into the top 20.
The most valuable dataset is “tn.movie_budgets” because it provides budget and gross revenue.  This resource is highly recognized for revenue across many dimensions, combined we have over 30 thousands data points



## Methods
Created roi and foreign column to evaluate which movie is having he most success.  
creating dataframes to compensate for the lack of data provided.
Runetime median by top 5 genre revenue.
Analysis of finances for both domestic and foreign to capture which market makes more moeny and where we should invest our marketing budget



## Results
Production budget should mostly be used towars foreign markets 2
run_time above the median for the top 5 genres will make more money.
The Foreign market will be necessary to reach our revenue goal. 
![image](https://user-images.githubusercontent.com/110699702/194668124-7e115fa4-da39-40d1-97de-ec26503d4ea2.png)
![image](https://user-images.githubusercontent.com/110699702/194668136-4415a59f-75c4-4061-ba90-d5a341971afc.png)
![image](https://user-images.githubusercontent.com/110699702/194668176-7de64ac6-8033-4586-a9ea-36bba328fc20.png)



## Conclusions

Conclusions
Global Gross Income 195        151       84     73    53
1. Genres         Animation Adventure Fantasy Action Sci-Fi
3. Market         Focus Foreign Foreign Foreign Foreign Domestic
4. Runtime (mins) >       93 >  104   >   107  >   107  >  106




## Future Investigations
Insufficient data on film series and streaming platforms
Create streaming application within Xbox console where users can watch
Microsoft films for free



## For More Information

Contact:
Stefano caurso: github/StefanoCaruso456/
Andrew Boucher: github/Andrew-Boucher/
Samuel Robins: github/SamuelRobins/

You are in the README.md. 'The Final Notebook' contains the jupyter notebook code and visual assessment. 
Our 'Project 1 slide final .pptm' contains power point slides presentation 
In 'ZippedData' you will be able to see the dataset we worked with. 
'README.md' 

```
├── README.md <- README information
├── Project ‘ <- PDF version of project presentation
├── ZippedData  <- contains development notebook and datasets
└── Final notebook<- contains the final working jupyter notebook                           
```
