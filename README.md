**The python code can't be uploaded because of data authority issue**

# 2020 Seoul Big Data Campus Contest
- Period for the preliminary : 2020.09.20 ~ 10.14
- Mentoring period for qualifying candidates: 2020.10.30
- Period for the finals: 2020.10.23 ~ 2020.11.16

## Why did we analyze the data?
- There are many complaints from Seoul citizens that there is no personal mobility parking lot.
  - (ref: Seoul City Hall Complaint Website)
- In 2020 Korea, The market for shared electric mobility is growing bigger and bigger.
  - (ref: Korea Transport Institute)
- So, We want to help the policymakers to choose a proper parking lot for personal mobility by using data analysis.
- What is personal mobility?
  - <img src="https://user-images.githubusercontent.com/102137580/160078259-e01e4f1f-b7ad-449d-8ec7-5b011a85eaa4.png" width="200">


  - This is personal mobility. Especially we used the "kickboard" data for analysis. 


## Analysis Process Description

**1. Preliminary investigation**
- We read the paper about shared electric kickboards and categorized users according to their purpose.
  - Paper : Empirical analysis of the factors affecting the satisfaction and behavior of individuals using shared electric kickboards. -A Case study of Seoul- (Daeun Ahn, Gongju University, 2020)
  1. Commuting type 
  2. Individual lifestyle type
  <img src="https://user-images.githubusercontent.com/102137580/160080753-01c43066-e5cf-4de5-a2bd-321abcef261a.png" width="500">
  - We planned to analyze parking lots based on residential, subway stations, work areas and commercial areas.
 

**2. Data Preprocessing**
- Used data 
  - [*Residence*] Resident population data at the administrative "Dong" unit in Seoul(.txt) 
  - [*Subway station*] Information on the number of people getting on and off by station by subway line in Seoul.(.csv) 
  - [*Subway station*] Metropolitan subway spatial data (.shp) 
  - [*Commercial space*] Commercial district data of Seoul(.csv) 
  - [*Workplace*] Workplace population data(.shp)
  - [*Workplace*] Seoul Business district development individual index data(.shp)
  - Current Status of major parks in Seoul(.csv) 
  - Building Space Data Based on Road Name Address in Seoul(.shp) 
- Data in Seoul were filtered and merged into the same unit .

**3. Exploratory Data Analysis**
- We used QGIS program.
- Since users(shared kickboard users) travel 1.6 km on average and the distance suitable for walking for general purposes is 700m, we extracted 0.7 km to 1.6 km sections from subway stations.
  - (ref: Comparing the Service Coverages of Subways and Buses and Estimating the Walking Distances of Their Users, Kyung Whan Kim et al. 2010)
  - (ref: Report that analyzed usage data from Elecle, shared kickboard service company)
  - <img src="https://user-images.githubusercontent.com/102137580/160127663-1637ab62-870a-47fd-9419-b70ad5f04091.png" width="300">
- And We overlapped the top workplace, residence, commercial space to that subway area respectively.
  -  <img src="https://user-images.githubusercontent.com/102137580/160129187-5e119174-d1b3-422b-8ce7-c92be134f44c.png" width="300">
  - <img src="https://user-images.githubusercontent.com/102137580/160129622-b273a987-4711-431b-a41e-b837431af915.png" width="300">
  - <img src="https://user-images.githubusercontent.com/102137580/160130034-2e2af587-ae5c-47ca-be30-e2b0d058a427.png" width="300">
- We put all the extracted area together.
  - <img src="https://user-images.githubusercontent.com/102137580/160130847-16b17f50-ef65-41b7-9931-e0b9d535c895.png" width="300">


**4. Conclusion**
- We proposed the parking lot with public land and parks.
  - <img src="https://user-images.githubusercontent.com/102137580/160224175-fb64fa59-5c5d-47f0-8562-4ff7df71d59a.png" width="300"> 
  
  
## What I felt.

- This is my first time leading a team. When I was just participating in another contest, I didn't feel a huge responsibility. (It means I didn't mind about the award.) But I am a team leader and I want us all to face a good result.
- I think a data analyst has a role as a storyteller in society. We must detect an uncomfortable thing in living a life and find the solution by analyzing data. For data scientists, It is important to tell analysis results for other people who don't know about analysis skills as well as analysis.
- I can learn a variety of analysis skills from final presentations in others. The team that won 1st prize applied EM algorithms. That was interesting! Someday, I will study EM algorithms and apply them to real-world datasets.
- I need to imporove my presentation skill.
  - My presentation video link in Korean: https://www.youtube.com/watch?v=cAdtNeOy7UQ

## The point that need to improvement
- It's a shame not to process modeling. With the modeling process, We could apply a statistical method and understand the knowledge deeply.
- We can use a data about informs bicycle storage or Ttareungi, the formal shared bicycle administered by Seoul.
  > At first, we considered the data, but we thought there is a different purpose between shared bicycles and shared kickboards. Shared kickboard is often said as "last-mile mobility" which means the final step for going destination. So, the mobility takes a short distance. But the shared bicycles take more long distances. For example, a person who uses a shared kickboard for going to work takes the service from home to the subway station. The other person who uses a shared bicycle takes the service from home to the workplace. We said this to juror for the contest, but some of them didn't agree with our opinion and some of them agree with us. 



