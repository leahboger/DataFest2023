<h1>American Bar Association Data Visualization Insights</h1>
Acheivement: Best Use of External Data

<h2>Description</h2>
For Data Fest 2023, the American Bar Association shared data from an online portal where low-income status participants can get pro bono legal services. Due to the nature of the data, it was deleted from data fest participants computers after the duration of the compition. For this reason, in lieu of a knitted HTML, I will share screenshots of code and interactive plots. We sought to better understand which counties had the longest average time from question to answer on the portal. In addition, we wanted to understand how number of questions asked, as well as average response time, corresponded to a heat map of poverty in the US to inform the ABA of future areas of outreach and where to allocate resources. 
<br />


<h2>Language and Packages Used</h2>

- <b>R using RStudio</b> 
  - <b>tidyverse</b>
  - <b>lubridate</b>
  - <b>stringr</b>
  - <b>mdsr</b>
  
  

<h2>Project walk-through:</h2>

<p align="center">
Data Wrangling: <br/>
<img src="https://i.imgur.com/9jqvLh0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
(Date class/formatting, creating a variable for time it took for a question to be answered, join with client data, and formatting State and County variables)
<br />
<br />
<br />
Average Time to Answer a Question By State/County:  <br/>
<img src="https://i.imgur.com/6Gdah4C.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
(Finds the average time to answer a question(grouped by state/county), find the category of question type most commonly asked in that county, and finds that categorys # of questions asked for that state/county)
<br />
<br />
<br />
Data Frame of Texas's Values By County: <br/>
<img src="https://i.imgur.com/jlssz5B.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
(Filtering for Texas, cleaning issues with county names)
<br />
<br />
<br />
Cleaning up Data More(Comparing with Map Data):  <br/>
<img src="https://i.imgur.com/NuMCOLL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
(Cleaning up county names further, joining with map data, making "mean time" an integer)
<br />
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/IfiU5tM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Heat Map of Texas Countys:  <br/>
<img src="https://i.imgur.com/C2Ruasf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
(Darkest counties are counties that had the longest question to answer time)
<br />
<br />
<br />
Wrangling for US Data from ABA and Map Data:  <br/>
<img src="https://i.imgur.com/aJBzO4z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating Interactive US Map:  <br/>
<img src="https://i.imgur.com/0PAw9mM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Heat Map for Question Frequency by State:  <br/>
<img src="https://i.imgur.com/tv6Qi0m.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br />
  
  [Click Here](https://leahboger.github.io/DataFest2023) for interactive map with "number of questions asked", "category with most questions", and "average question to answer time" for each state












