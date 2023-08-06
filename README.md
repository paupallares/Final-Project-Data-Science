![header](src/dataBRIDGE_logo_black.png)

#  Google maps + Yelp! 🗺️ 🚀

## Context 🌍

The opinion of the users has become an invaluable data in the planning of commercial strategies. Review platforms like Yelp and Google Maps provide a lot of information about the
user perception regarding various businesses, including restaurants, hotels, aesthetics and other related services. This feedback is essential for companies, since it allows them to evaluate their performance, identify areas for improvement and understand how they are perceived by users. As part of a data consultancy, we have been hired to perform a detailed analysis of user opinion on Yelp and Google Maps for businesses related to personal care and aesthetics in the US market. The beauty category covers a wide range of services and establishments related to personal care and aesthetics. Some examples of businesses within this category are beauty salons, spas, hairdressers, barbershops, nail salons, beauty salons, massage parlors, and beauty supply stores.

## Content

* [Description + Objective](#description--objective-)
* [Demo](#demo-)
* [KPIs](#kpis-)
* [Tech Stack](#tech-stack-)
* [Methodology + Schedule](#methodology--schedule-)
* [ER Model](#er-model)
* [Visualizations](#visualizations)
* [Machine Learning](#machine-learning-)
* [User App](#user-app)
* [Conclusions](#conslusiones)
* [Team](#team-)

## Description + Objective 🏆

Our project consists of collecting, cleaning and analyzing data from Yelp and Google Maps reviews, using sentiment analysis techniques and machine learning to determine the most suitable locations to establish new business premises and discover investment opportunities by investigating aspects such as market growth. , the demand for beauty services, existing competition and emerging trends. Based on the analysis carried out, we will generate clear and well-founded recommendations for the investor. These recommendations will showcase the most compelling investment opportunities in the beauty industry, highlighting the key aspects that support the viability and growth potential of each opportunity. Although we will focus mainly on the aesthetics sector, the methodology can be applied to other types of businesses.

**The main objective of the project** is to provide our investment client from the Latin American aesthetic industry with an overview of the US market in order to make the most informed and intelligent decisions to become a competitor in that market. Thanks to an exhaustive analysis of user opinion on Yelp and Google Maps, we will be able to identify trends, predict the growth or decline of business lines, and make informed strategic decisions to improve business management and investment.

## Demo 🔌

<p align='center'>
<img alt="stack" src="src/demo.gif" width="95%">
</p>

# KPIs 📈📉

In our dashboard we can visualize 5 KPIs of different kinds:

- ***Average Review Score*** indicates information according to the filters, aiming for a minimum rating of 4.2 stars.

- ***Number of Reviews*** refers to the average according to the filters. This data is important since it must exceed a minimum of 20 reviews, since if it is lower, it may mean that, beyond the fact that the average number of reviews is high, the amount of sample data is low, therefore unreliable.

- ***Variability*** KPIs refer to the volatility of the data referred to the score, the less variation the better (since the scores are more predictable) with a minimum of 0.5 variation.

- The KPI ***Reliability*** is a calculation based on the product of the standardization of the first and second KPI, showing a more accurate data of how reliable in statistical terms the selected market filter is.

- Finally the KPI ***Average change in review score across two different time divisions***, months and quarters. With a minimum of 0.4% increase in reviews compared to the previous period.

***It should be noted that the objectives were concluded, not only from a market context judgment, but also based on the distribution of data***

## Tech Stack 💻

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)
 ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
   ![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black) ![Apache Spark](https://img.shields.io/badge/Apache%20Spark-FDEE21?style=flat-square&logo=apachespark&logoColor=black) 
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white) ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![macOS](https://img.shields.io/badge/mac%20os-000000?style=for-the-badge&logo=macos&logoColor=F0F0F0) ![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)


![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white) ![ChatGPT](https://img.shields.io/badge/chatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white) ![Google Chrome](https://img.shields.io/badge/Google%20Chrome-4285F4?style=for-the-badge&logo=GoogleChrome&logoColor=white) ![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white) ![Microsoft Word](https://img.shields.io/badge/Microsoft_Word-2B579A?style=for-the-badge&logo=microsoft-word&logoColor=white) ![Stack Overflow](https://img.shields.io/badge/-Stackoverflow-FE7A16?style=for-the-badge&logo=stack-overflow&logoColor=white) ![Adobe](https://img.shields.io/badge/adobe-%23FF0000.svg?style=for-the-badge&logo=adobe&logoColor=white) ![Adobe Illustrator](https://img.shields.io/badge/adobe%20illustrator-%23FF9A00.svg?style=for-the-badge&logo=adobe%20illustrator&logoColor=white) ![Adobe Photoshop](https://img.shields.io/badge/adobe%20photoshop-%2331A8FF.svg?style=for-the-badge&logo=adobe%20photoshop&logoColor=white) ![Adobe Premiere Pro](https://img.shields.io/badge/Adobe%20Premiere%20Pro-9999FF.svg?style=for-the-badge&logo=Adobe%20Premiere%20Pro&logoColor=white)



![Google Meet](https://img.shields.io/badge/Google%20Meet-00897B?style=for-the-badge&logo=google-meet&logoColor=white) ![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white) ![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)

<p align='center'>
<img alt="stack" src="src/stackfinal.png" width="75%">
</p>

## Methodology + Schedule 📆

<p align='center'>
<img alt="stack" src="src/modelo-scrum_BLACK_solo.png" width="75%">
</p>

We worked following the **SCHEDULE** below:

<p align='center'>
<img alt="stack" src="src/GANTT.png" width="75%">
</p>

## ER Model

<p align='center'>
<img alt="stack" src="src/Modelo_ER2.png" width="75%">
</p>

## Visualizations 

POWER BI

<p align='center'>
<img alt="stack" src="src/Menu.png" width="95%">
</p>

<p align='center'>
<img alt="stack" src="src/MGoogle.png" width="95%">
</p>

<p align='center'>
<img alt="stack" src="src/MYelp1.png" width="95%">
</p>

<h1 align="center">Machine Learning 🤖</h1>
<h1 align="center"></h1>
<h1 align="center">Sentiment Analysis</h1>

Application of natural language processing (NLP) techniques to analyze the sentiment of reviews and classify them as positive, negative or neutral. Making use of the "SentimentIntensityAnalyzer" library from the "nltk.sentiment" set which generates a new column where each review is classified, thus replacing/translating the review itself to its representative category.

This is how we can order and filter to reveal which States are more happy with the service and which are not.

## Google Maps

### Resulting Table:

<p align='center'>
<img alt="stack" src="src/GmapTable_Análisis de Sentimientos -  Example.png" width="60%">
</p>

This fact table represents the characteristics and results of each of the reviews, filtered from the beauty and aesthetics category, together with a new column called Sentiment where it is expressed whether the review was Positive, Neutral or Negative.

It should be noted that in the following graph it was not decided to take into account the "Neutrals" since they represented less than 1%.

<h3 align="center">Top 5 States with the most positive reviews</h3>

<p align='center'>
<img alt="stack" src="src/GmapPOS.png" width="60%">
</p>

<h3 align="center">Top 5 States with the most negative reviews</h3>

<p align='center'>
<img alt="stack" src="src/GmapNEG.png" width="60%">
</p>

## Yelp

### Resulting Table:

<p align='center'>
<img alt="stack" src="src/YelpTable_Análisis de Sentimientos -  Example.png" width="60%">
</p>

The description of this table is identical to the previous one, Google Maps, it only varies from where the data was extracted; in this case the Yelp dataset.

<h3 align="center">Top 5 States with the most positive reviews</h3>

<p align='center'>
<img alt="stack" src="src/YelpPOS.png" width="60%">
</p>

<h3 align="center">Top 5 States with the most negative reviews</h3>

<p align='center'>
<img alt="stack" src="src/YelpNEG.png" width="60%">
</p>

<h1 align="center">Clustering</h1>

Through a three-dimensional clustering model (latitude, longitude and average rating), businesses are investigated and grouped. This is geared towards their specific geographic locations (State and County) along with their rating trends. Thus complementing the current competition in each location; ordered from the element with the highest rating to the lowest.
In it, the sklearn library was used, where the StandardScaler sub-libraries were extracted to standardize the data, KMeans for the clustering process and finally a second library called geodesic from the geopy set to identify the counties and states of the investigated locations.

### Resulting Table:

Thanks to the process involved in clustering by extracting the central points of each cluster, we have an exact geographical location of said set. This is how this data is translated into the "State" and "County" columns; adding in turn the average of the scores of the reviews of said area.
On the other hand we can see at the same time a comparison between the Number of Businesses present vs the number of Competitor Businesses, referring to a common item; the last column expresses the relationship of this competition, that is, the higher the percentage, the more competition is present in this location.
Thanks to this set of data as decision parameters, it can be made known to which States and Counties it is convenient to invest depending on the Rating average, as well as taking into account the percentage of competition present in each area. Since if the client wants a business environment with little competition, then it is convenient to look for an area with little competition compared to the others. Otherwise, if the client wants to join the group of competent people in the present areas, it is also feasible since it symbolizes that the business bears fruit in said place.

<p align='center'>
<img alt="stack" src="src/Clusters_Results_Table.png" width="60%">
</p>

<h3 align="center">Elbow Graph</h3>

<p align='center'>
<img alt="stack" src="src/Elbow - Graph.png" width="60%">
</p>

We can see that the graph indicates that the optimal number of clusters to apply is approximately 5. But the business context of this project requires us to classify the locations with the largest partitions. For this reason, it was decided to use the amount of 50 clusters; so we can have 50 different locations.

<h3 align="center">3D graph of clustering</h3>

In this graph you can initially see the three-dimensional shape of the United States, where the colors represent the clusters together with their contents (points).

<p align='center'>
<img alt="stack" src="src/Clustering - Graph.png" width="60%">
</p>

Finally, this visualization shows the distribution of the data geographically, expressed in colors depending on the rating of each review. It can be seen that the reviews above 4 (green) are the most abundant.

<p align='center'>
<img alt="stack" src="img/Mapa_Imagen_Clustering.png" width="60%">
</p>

####

# User App

[STREAMLIT APP](https://databrick-app-ro1106uif3t.streamlit.app/Proyecto)

<p align='center'>
<img alt="stack" src="src/app-mockup.png" width="95%">
</p>

The application can be accessed through: [https://databrick-app-ro1106uif3t.streamlit.app/Proyecto](https://databrick-app-ro1106uif3t.streamlit.app/Proyecto)

## Team 🫂

| Name   | LinkedIn ↘️ | GitHub                | Role |
|------------|---|-----------------------|------------|
| Paula Pallares | [linkedin.com/in/paupallares/](https://www.linkedin.com/in/paupallares/) | [paupallares](https://github.com/paupallares) | Functional Analyst |
| Benjamín Zambelli	| [linkedin.com/in/benjamin-zambelli/](https://www.linkedin.com/in/benjamin-zambelli/) | [BenJokek](https://github.com/BenJokek) | Data Engineer |
| Beder Rivera | [linkedin.com/in/beder-rivera/](https://www.linkedin.com/in/beder-rivera/) | [cullanco-huaman](https://github.com/cullanco-huaman) | Data Engineer | 
| Claritzo Pérez Marcano | [linkedin.com/in/claritzoperez/](https://www.linkedin.com/in/claritzoperez) | [Claritzo](https://github.com/Claritzo) | Data Analyst | 
| Gonzalo Schwerdt | [linkedin.com/in/gonzalo-schwerdt/](https://www.linkedin.com/in/gonzalo-schwerdt-84641a214/) | [GonzaloSchwerdt](https://github.com/GonzaloSchwerdt) | ML Engineer | 

