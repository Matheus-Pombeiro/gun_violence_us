# Gun Violence in the US

## 1. Introduction

<p align='justify'>Gun Violence in the US is a Data Science authorial project developed in Pandas to analyze criminal indices based on gun shooting violence in the United States of America. Next there are some information about the dataset used in this project and questions, which will be answered through this project.</p>

### 1.1 Dataset information

<p align='justify'><a href="https://www.kaggle.com/datasets/whisperingkahuna/gunviolence1/data" target="_blank" rel="noopener noreferrer">Gun Violence in US</a> dataset comes from Kaggle and has data from January 1, 2024 to October 20, 2024 about gun shooting violence in the US. The meaning of the dataset’s data are described next:</p>

<ul>
  <li>Incident ID: A unique identifier for each incident</li>
  <li>Date: The date of the incident.</li>
  <li>State: The US state where the incident occurred.</li>
  <li>City or County: The city or county within the state.</li>
  <li>Address: The specific address of the incident.</li>
  <li>Number of Killed: The number of people killed in the incident.</li>
  <li>Number of Injured: The number of people injured in the incident.</li> 
  <li>Number of Arrested: The number of people arrested in the incident.</li> 
  <li>Latitude: The latitude coordinate of the incident location.</li>
  <li>Longitude: The longitude coordinate of the incident location.</li>
</ul>

### 1.2 Questions to be answered

<p align='justify'>Next, there is a list containing questions which will be answered along the project development. These questions are based on the dataset possibilities and concerns about security in the US by the project’s author.</p>

<ul>
  <li>What state and city have the most incident records? And during which month did the most of those incidents happen?</li>
  <li>What’s the number of victims and suspects killed in the city with the highest number of records? Are these numbers related in any way?</li>
  <li>Are there more suspects killed, injured or arrested? Are the results good?</li>
  <li>What’s the relation between victims killed and suspects arrested in each occurrence?</li>
  <li>Which state has the highest number of victims killed? And about suspects killed?</li>
  <li>Among the records, is there any address (street, avenue or road) that appears more than once? And, if so, what’s the number of victims killed and injured there?</li>
</ul>

## 2. Data analysis

### 2.1 Places and month with most incidents

<p align='justify'>Exploring the dataset, it was possible to realize that there are a state and a city which most appear throughout it. But who are they? Illinois is the state where there are the most records of incidents and one of its cities, called Chicago, it’s the city where there are the most records.</p>

<p align='justify'>During the ten first months of 2024, it happened, at least, thirty-two (32) incidents of gun violence in Illinois. And, at least, twenty-five (25) ones in Chicago. Which means that around 78.13% of the incidents recorded in Illinois happened in Chicago.</p>

<p align='justify'>About the months, when these incidents in Illinois happened, the one with the most part of records is July. Next, it’s possible to observe a graph which shows the timeline of incidents in this state.</p>

<div align="center">
  <img src="assets/graphs/timeline_illinois.png" alt="Illinois Timeline graph"/>
</div>
<br>

<p align='justify'>There is an increase in terms of the number of incidents throughout the months in Illinois. At the end, it’s possible to see that there was a decrease.</p>

<p align='justify'>Next, there is a graph which shows the timeline of incidents in Chicago. About it, it’s possible to analyze the increasing and decreasing of incident records.</p>

<div align="center">
  <img src="assets/graphs/timeline_chicago.png" alt="Chicago Timeline graph"/>
</div>
<br>

<p align='justify'>Analyzing the previous graph, it’s possible to observe differences and similarities about its numbers in comparison to the Illinois graph. The two graphs present different numbers for some months. The month with the most part of incidents in Illinois presented six (6) records, but in Chicago this same month presented five (5) ones. And they show a similar increase of incidents until the seventh month, and, after that, a decrease.</p>
