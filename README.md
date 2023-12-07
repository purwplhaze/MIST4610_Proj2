# MIST4610_Proj2
# Team Members:

1. John Hulsey | @J-Hulsey
2. Carson Whitt | @JackMathison
3. Jack Mathison | @whittcarson
4. Justin Sullivan | @Justin7ime
6. Hayes Herzog | @purwplhaze

# Description of Dataset

# Question 1
Is there a correlation between newer Plug-In Hybrid Electric Vehicle (PHEV) models and Battery Electric Vehicle (BEV) models and longer electric car ranges? If so, how significant is that correlation?

Significance:

This question is important because it helps someone better understand their options based on which cars and their ranges best suit their needs. The answer and its visualization are especially useful when considering questions like “How far am I driving in a given day?” and ”How often am I stopping long enough to charge the battery if needed?” This will help consumers determine what model years have lower average driving ranges and learn to avoid them in search of newer models that are shown to have increasingly improved distance capabilities. This question also enables one to see how BEV efficiency development is growing at a much faster rate than that of the PHEVs.

<img width="624" alt="AvgRangeBy Year" src="https://github.com/whittcarson/MIST4610GroupProject2/assets/131502055/e523276f-b4bf-4d67-8a8a-17866cbaeadd">

After viewing the results of the first diagram, we filtered the data to include only the top 20 makes of cars with model year 2008 or later. This change aided in eliminating outliers and void space on the visual from the years 1996-2007. Our results show a similar trend to the initial graph for each vehicle type. BEVs have a large uptick in their average range starting in 2008 and peaking at 245 average miles in 2010. Then 2011 still showed a steep decline in efficiency, followed by a positive trend until peaking again in 2020 at approximately 278 miles average for Battery Electric Vehicles. The Plug-In Hybrid Electric Vehicles are not nearly as efficient in terms of average range, but, notably, their data mirrors the spike in 2010 with a following drop. Also, as in the first visual, the data shows that PHEVs never received the attention in development to exceed that previous peak as the BEV trend shows. A separate detail on the tail end of the diagram after 2020. PHEVS’ continue their slight up-and-down trend, but there is very little or zero data for BEVs. This is mainly due to a lack of owners buying newer vehicles around this time.

# Manipulations to the dataset for Analysis
We did not manipulate any raw data, but we did filter out irrelevant data and apply measurable functions to certain columns. In Q1, we filtered data to only include the top 20 makes of EVs with model year 2008 or later. We also applied the average function to "Electric Range" in order to set a standard for comparing the electric range of electric vehicle types year-after-year. For Q2, we applied the count function to "Electric Vehicle Type" in order to compare the amount of EV types manufactured for each make. All filters/marks applied to the data are solely intended to show the viewer quantifiable information related to the questions. In regards to integrity, our data has no inaccuracies, irrelevancies, or 3rd party imports.
