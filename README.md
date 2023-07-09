# land-economics
Repo contains project information for group project for AGEC 422- Land Economics (TAMU)

**Project Description:** 

The class was split into groups of 4/5 people. We were asked by the professor and analysts for the City of College Station to take a set of raw data and use it to tell a story about 5 different topics for a specific location: Demographics, property taxes, crime, tax revenue, and tax/non-taxable properties. We were allowed to pull additional information from other reliable resources if we wanted. 

**Data provided:**

- Burleson county CAD information (BCAD)
- Crime information (crime type, date, location, resolution, etc.)
- Property information (property type, value, tax informaiton, etc.)
- List of BCAD codes for reference

**Additional data gathered:**

- Demogrpahic information (education level, age, race) for the location based on the 2010 and 2020 US census info
- Texas A&M University population information (pulled from TAMUs website)

**My contribution:**

I was extremely excited about this project becuase I thought it would be a great opportunity to analyze some data, tell a story with visualizations, and get valuable feedback from individuals who did data analysis everyday. Since I was so excited, I took more of a leading role for the project. When I was reviewing the raw data, which was provided in excel format across different files, I realized it was going to be very difficult to extract any valuable information from the excels. I decided to throw the excel documents into a basic (non-relational) database, so I could use SQL to pull relevant information from different sources, eventually building data sets for each topic mentioned above. I then shared what data I had pulled with my teammates and cordinated with them on who would do each topic. 

**Data I extracted for the team to pick and choose from:**

- The number of properties built each year from 1935 to 2018
- The number of each property type
- The total number of individual CAD Listings for the area
- The average number of acres and average number of square feet for each property type
- The average number of acres and average number of square feet for build year
- Summary of property type and taxable/non-taxable status
- Average revenue per land acre for each property type (Year = 2021)
- The number of each police case type for each street in the area of interest
- The average time to close each police case type for each street in the area of interest
- Demographics for 2010 and 2020
  - Total population
  - population of one race (white)
  - population of one race (African American)
  - population of one race (Asian)
  - population of one race (Native Hawaiian and Other Pacific Islanders)
  - Population of one race (Other)
  - Population of two or more races
- Texas A&M Enrollment per year 2010-2021

**Contributions continued:**

I decided to take the demogrpahic slide becuase I thoght it would be interesting to see how demogrpahics changed as the university population changed over time. I then created the slide below: 
![Demogrpahic Slide](https://github.com/kp-catalena/land-economics/assets/139026712/5397752a-eb9f-4060-b29e-5d64aa7995a7)

Unfortunately, my group was not as interested in the project as I was. I had to contact them over and over in order to get them to spend time looking at the data and even then they did not finish their visualizations until right before the due date. 


**Conclusions gathered regarding demographics:**

Northgate Population and Housing Units
* According to the census dayta College Station grew by 30.8% between 2010 and 2020 and as for the Northgate district, the population has increased by 147 percent in that same time frame. 
* This is due to the increased number of housing units that have been built in this time, which has increased by nearly 200%. 

Northgate Population by Race
* I would not expect the distribution across races to change much with the increase in population since the area is geared towards students. You would only see a drastic change in the breakdown of race in the Northgate district, if the distribution of races among students at Texas A&M changed drastically.
* The majority of those who filled out the census identified as 1 race and you can see that the distribution among races was, in general, pretty consistent between 2010 and 2020. 

Texas A&M Enrollment by Year
* Since 2010, Texas A&M Enrollment has increased by almost 50% from around 50,000 students to now nearly 75,000 students. 
* I believe This increase could be the main driving force for the jump in your housing units in the Northgate district. 
*  Texas A&M will continue to expand in the coming years. I believe if we did this analysis in another 10 years we would see more of the Northgate district being developed with apartments to support the demand for housing.


**Overall thoughts on project:**

I really enjoyed the project. I think it gave me the opportunity to practice using unorganized data to extract an interesting and useful story. It gave me a chance to use SQL to extract data across different original sources that were related. I also had the opportunity to extract data from the Census website, which was a little challenging to understand at first, but after extracting the wrong data a few times, I finally got the data I was looking for, which added an additional layer or useful information to my analysis. 
