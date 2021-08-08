## Analyzing NYC High School Data

### About:

We will do investigation into relationships between demographics and SAT scores. 

New York City has published data on [student SAT scores](https://data.cityofnewyork.us/Education/SAT-Results/f9bf-2cp4) by high school, along with additional demographic data sets. Over the last three missions, we combined the following data sets into a single, clean pandas dataframe:

  * [SAT scores by school](https://data.cityofnewyork.us/Education/SAT-Results/f9bf-2cp4) - SAT scores for each high school in New York City
  * [School attendance](https://data.cityofnewyork.us/Education/School-Attendance-and-Enrollment-Statistics-by-Dis/7z8d-msnt) - Attendance information for each school in New York City
  * [Class size](https://data.cityofnewyork.us/Education/2010-2011-Class-Size-School-level-detail/urz7-pzb3)e - Information on class size for each school
  * [AP test results](https://data.cityofnewyork.us/Education/AP-College-Board-2010-School-Level-Results/itfs-ms3e) - Advanced Placement (AP) exam results for each high school (passing an [optional AP exam in a particular subject can earn a student college credit in that subject)
  * [Graduation outcomes](https://data.cityofnewyork.us/Education/Graduation-Outcomes-Classes-Of-2005-2010-School-Le/vh2h-md7a) - The percentage of students who graduated, and other outcome information
  * [Demographics](https://data.cityofnewyork.us/Education/School-Demographics-and-Accountability-Snapshot-20/ihfw-zy9j) - Demographic information for each school
  * [School survey](https://data.cityofnewyork.us/Education/NYC-School-Survey-2011/mnz3-dyi8) - Surveys of parents, teachers, and students at each school


### Steps:

  1. Loading the data
  2. Converting columns to numeric
  3. Combining the datasets
  4. Adding a school district column for mapping
  5. Finding & Plotting survey correlations
  6. Exploring Safety and SAT Scores
  7. Exploring Race and SAT Score
  8. Exploring Gender and SAT Scores
  9. Exploring AP Scores vs SAT Scores

### Built With :

  * Python 3
  * Pandas
  * Numpy
  * Matplotlib
  * Jupyter Notebook