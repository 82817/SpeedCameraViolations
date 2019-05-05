# SpeedCameraViolations
MSIS 2629 Spring 2019

[Link to Tableau Public Project](https://public.tableau.com/profile/jason1420#!/vizhome/ChicagoSpeedCameraViolationandCrashes_revised/Dashboard)

### Background
Chicago experiences roughly 3,000 crashes annually between motor vehicles and pedestrians, about 800 of which involve children.

The Children’s Safety Zone Program protects children and other pedestrians by reminding motorists to slow down and obey speed laws – especially in school and park zones. Safety zones are designated as a 1/8th of a mile boundary around any Chicago parks or schools.

The enforcement hours will be limited from 7 a.m. to 7 p.m. in safety zones around schools on school days (Monday through Friday)
7 a.m. to 4 p.m.: 20 miles per hour (mph) speed limit when children are present; and the posted speed limit when no children are present ([Source](https://www.chicago.gov/city/en/depts/cdot/supp_info/children_s_safetyzoneporgramautomaticspeedenforcement.html))

### Approach
Since the whole program is established around pedestrians safety, specifically child safety, I want to look further into this aspect of  the data. 

I found a [data set](https://data.cityofchicago.org/Transportation/Traffic-Crashes-People/u6pd-qa9d) that contains information about people involved in a crash and filtered to contain only information in Chicago. Comparing this data set to previous assignment, I've found a couple interesting information.

### Finding 1

**While number of violations decline over time, number of crashes seem to go up.**

The first cameras were installed in August 2013 and the data begin from July 1, 2014 until present. There seems to be a steady incline of crashes starting from July 2015.

This could be the case that people are more aware of the location of the cameras. Also, the location of the crash might not necessarily be by a camera location. Regardless, it is concerning to see number of crashes go up


![](https://github.com/82817/SpeedCameraViolations/blob/master/Images/IMG1_R.png?raw=true)
![](https://github.com/82817/SpeedCameraViolations/blob/master/Images/IMG2_R.png?raw=true)

_Revision notes: I've removed 2014 data so that both charts start from the same time. I've also found a way to smooth out a line and added a trend line_

### Finding 2

**While looking at top 10 cameras with the most violation captured, the area around those cameras seem to have less accidents.**

The first graph shows the camera locations.

![](https://github.com/82817/SpeedCameraViolations/blob/master/Images/IMG3_R.png?raw=true)

This graph below shows crash locations. Camera indicates camera location from the previous chart; compare with the first graph, we can see that locations around speed camera has relatively low number of crashes.

![](https://github.com/82817/SpeedCameraViolations/blob/master/Images/IMG4_R.png?raw=true)

_Revision notes: I figured it is difficult for readers to cross-reference both charts, so I decided to annotate the crash location chart with camera locations for better visibility._

### Finding 3

I'm also interested to see if number of crashes might decrease during speed camera's hour of operations from 7 AM to 4 PM. It turns out that those hours are actually when number of crashes are high. I suspect that this is also the time people commute to and from work, so I cannot make any implication to the effectiveness of the program simply from this chart. 

![](https://github.com/82817/SpeedCameraViolations/blob/master/Images/IMG5_R.png?raw=true)

However, I want to look at the age of people that were involved in the crashes because I believe this will be a better proxy at looking at the effectiveness of the program.

Looking at the crash data, **number of children involved in accident seem to go up year over year.** 

![](https://github.com/82817/SpeedCameraViolations/blob/master/Images/IMG6_R.png?raw=true)

_Revision notes: For the crash hour chart, I've highlighted the hours of operation for this program, and turned it to a bar chart. For the age chart, I've taken out ages > 18 to strictly look at underage kids._
