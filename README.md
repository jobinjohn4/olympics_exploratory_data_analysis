<h1>Olympics Exploratory Data Analysis</h1>
https://github.com/jobinjohn4/olympics_exploratory_data_analysis/blob/main/Olympic_exploratory_analysis.ipynb
<img src="https://i.postimg.cc/nzmFrKY2/flag-Olympic-Games.webp" height="60%" width="80%" />
<h2>Description</h2>
The Olympic dataset for exploratory data analysis encompasses comprehensive information on athletes, countries, sports, events, and historical performances across various Olympic Games editions from 1896 to 2016. It includes athlete details like names and ages, country information, sports, event specifics, and medal results. I have utilized this dataset to uncover patterns and trends through visualizations and statistical analyses. Exploring athlete demographics, performance trends, and country-specific achievements enhances our understanding of the dynamic history of the Olympic Games, providing valuable insights into the world of international sports competitions.

<br />


<h2>Language and Libraries Utilized</h2>

- <b>Python</b> 
- <b>Pandas</b>
- <b>matplotlib</b>
- <b>Seaborn</b>
- <b>Plotly</b>

<h2>Index</h2>

- <b>About the dataset</b> 
- <b>Data Cleaning and Transformation</b>
- <b>Major Insights</b>
- <b>Conclusion</b>

<h2>About the dataset</h2>
<b>
The Olympic dataset features several key columns, including "Athlete's Name," providing the names of individual athletes participating in the Games. The "Gender" column indicates whether the athlete is male or female. "Height" and "Age" offer insights into the physical attributes and age of the athletes, respectively. The "Season" column specifies the season of the Olympic Games (e.g., Summer or Winter). Finally, the "Medals" column records the type and quantity of medals (gold, silver, bronze) awarded to each athlete, offering a comprehensive overview of their performance in various events.</b>

<h2>Data Cleaning and Transformation</h2>
<b>I have dropped "Games" column from the dataset as it is not relevant for the analysis. I have renamed the column names to meaningfull names such as Team to Country. Also I have identified the duplicate values in the dataset and have removed them for better analysis. There are certain duplicate values in "Age","Weight","Heigh" and "Medal" which is not been removed as one person can have won multiple medal and have been participated in multiple oylmpic seasons.</b>

<h2>Major Insights</h2>
<b>From the analysis of the total number of participant from various country over the years states that there are large number of participation in olympics from North and South American and Europiean countries and less participants from Asian and African countries.</b>
<br>
<br>
<img src="https://i.postimg.cc/Y0mJW9bc/country.png" height="50%" width="50%" />
<br>
<b>From the graph of age distribution of athlete's along this years indicates that most number of athlete's participated in olympics are in the range of 20 to 30 years.</b>
<br>
<br>
<img src="https://i.postimg.cc/fbNm4g6Y/age.png" height="50%" width="50%" />
<br>
<b>From the graph of height distribution of athlete's we can find that the height of most of the athlete's participated in olympics are in the range of 170 to 190 cms.<br>
<br>
<img src="https://i.postimg.cc/GhD4cxPK/height.png" height="50%" width="50%" />
  <br>
  <br>
<b>This graph shows the age group from 20 to 25 years athlete's who have participated in olympics have very successful and won medals. This trend can be seen for all the three medal types .ie. Gold, Silver and Bronze medal.
  <br>
  <br>
<img src="https://i.postimg.cc/dVBG8cHD/agemedal.png" height="50%" width="50%" />
  <br>
  <br>
  <b>This graph shows that Height and Weight of athlete have some Linear Correlation among them in chances winning medals.
    <br>
    <br>
<img src="https://i.postimg.cc/SRFnBgTw/heightand-weight.png" height="50%" width="50%" />
    
<h2>Conclusion</h2>
<b>In conclusion, the Olympic dataset, with its informative columns such as athlete name, gender, height, age, season, and medals, serves as a valuable resource for in-depth exploratory data analysis. This dataset enables researchers to delve into the dynamics of Olympic Games over time, uncovering patterns and trends related to athlete demographics, performance, and medal achievements. The comprehensive nature of the dataset facilitates a holistic understanding of the global sports competition, contributing to insights that go beyond individual events and athletes, providing a nuanced perspective on the evolution of the Olympic Games.</b>

