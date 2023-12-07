# MIST4610_Proj2
# Team Members:
1. John Hulsey | @J-Hulsey
2. Carson Whitt | @whittcarson
   Repo: https://github.com/whittcarson/MIST4610GroupProject2
3. Jack Mathison | @JackMathison
   Repo: https://github.com/JackMathison/Project-2-MIST-4610
4. Justin Sullivan | @Justin7ime
   Repo: https://github.com/Justn7ime/MIST-Project-2
5. Hayes Herzog | @purwplhaze

# Description of Dataset
This dataset represents Battery Electric Vehicles (BEV) and Plug-in Hybrid Electric Vehicles (PHEV) that are currently registered through the Washington Department of Licensing. We obtained the dataset from the website provided: (https://catalog.data.gov/dataset/electric-vehicle-population-data). The varying datatypes include the make and model of the car, VIN number,and electric vehicle type; these data types are string. Numeric measurements such as the electric vehicle range and base MSRP are of datatype number(whole), with the date of the model of the car being of datatype date & time. This dataset helps us depict the reality of electric vehicles within the state of Washington within the period of 1997 to present day and draw conclusions for consumers based upon this dataset.

# Question 1
Is there a correlation between newer PHEV models and BEV models and longer electric car ranges? If so, how significant is that correlation?

Significance:

This question is important because it helps someone better understand their options based on which cars and their ranges best suit their needs. The answer and its visualization are especially useful when considering questions like “How far am I driving in a given day?” and ”How often am I stopping long enough to charge the battery if needed?” This will help consumers determine what model years have lower average driving ranges and learn to avoid them in search of newer models that are shown to have increasingly improved distance capabilities. This question also enables one to see how BEV efficiency development is growing at a much faster rate than that of the PHEVs.

![image](https://github.com/purwplhaze/MIST4610_Proj2/assets/148249080/b6eb4279-274d-4b25-be6a-23af5350f9f1)

After analyzing the average electric range of cars from this dataset by manufacturing year and type, we can infer that there is a general significant increase in the electric range of BEV models created from 2000 to 2010 of over 240 miles on average. Post 2010 there was actually a sharp decline in average electric range temporarily, with a steady recovery to the rate we saw in 2010 models. We can also see that by 2020, the average electric range of new BEV’s surpassed that of any year in Washington. Also included and labeled in orange are PHEV. Although we want to focus on the fully electric cars labeled in blue, it is interesting to note that the average electric range of hybrids also declined for models after 2010 yet did not experience the same recovery in 2020 model in the state.

<img width="624" alt="AvgRangeBy Year" src="https://github.com/whittcarson/MIST4610GroupProject2/assets/131502055/e523276f-b4bf-4d67-8a8a-17866cbaeadd">

After viewing the results of the first diagram, we filtered the data to include only the top 20 makes of cars with model year 2008 or later. This change aided in eliminating outliers and void space on the visual from the years 1996-2007. Our results show a similar trend to the initial graph for each vehicle type. BEVs have a large uptick in their average range starting in 2008 and peaking at 245 average miles in 2010. Then 2011 still showed a steep decline in efficiency, followed by a positive trend until peaking again in 2020 at approximately 278 miles average for Battery Electric Vehicles. The Plug-In Hybrid Electric Vehicles are not nearly as efficient in terms of average range, but, notably, their data mirrors the spike in 2010 with a following drop. Also, as in the first visual, the data shows that PHEVs never received the attention in development to exceed that previous peak as the BEV trend shows. A separate detail on the tail end of the diagram after 2020. PHEVS’ continue their slight up-and-down trend, but there is very little or zero data for BEVs. This is mainly due to a lack of owners buying newer vehicles around this time.

# Question 2
Which make of car has the highest rate of purchases for each type of electric vehicle in Washington?

Significance:

This question and the relevant data are signifigant as it allows one to understand who the market leaders are for both PHEV's and BEV's. By understanding who the market leaders are in the electric car market, consumers can make more informed decisions on what kind of electric vehicle to purchase. In the mind of many consumers, BEV's and PHEV's with more marketshare maybe better options than BEV's and PHEV's with less marketshare as there must be a reason that more of one kind of car is bought over others.

PHEV:
![image](https://github.com/purwplhaze/MIST4610_Proj2/assets/148249080/e9c351fa-af13-4e38-93a5-8f02e0251719)
![image](https://github.com/purwplhaze/MIST4610_Proj2/assets/148249080/41514104-c38b-4a16-a2b9-ee520f9e0b54)

BEV:
![image](https://github.com/purwplhaze/MIST4610_Proj2/assets/148249080/09bc91c9-92bd-4de9-97fb-e0d522722b29)
![image](https://github.com/purwplhaze/MIST4610_Proj2/assets/148249080/06e80934-4b5d-456f-9122-e88908a0b384)

# Manipulations to the dataset for Analysis
We did not manipulate any raw data, but we did filter out irrelevant data and apply measurable functions to certain columns. In Q1, we filtered data to only include the top 20 makes of EVs with model year 2008 or later. We also applied the average function to "Electric Range" in order to set a standard for comparing the electric range of electric vehicle types year-after-year. For Q2, we applied the count function to "Electric Vehicle Type" in order to compare the amount of EV types manufactured for each make. All filters/marks applied to the data are solely intended to show the viewer quantifiable information related to the questions. In regards to integrity, our data has no inaccuracies, irrelevancies, or 3rd party imports.

# Tableau Packaged Workbook
The tableau packaged workbook featuring these visualizations and the dataset is attached to this repository.
