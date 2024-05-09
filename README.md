1.OBJECTIVE :
This project aims to study the coffee production trends in Malaysia from 2016-2022 and compare to other countries to identify any opportunity for partnership and new market expansion for coffee producers in Malaysia. This analysis involves the process of data collection from (FAOSTAT) Food and Algriculture Organization for the United Nation database ,data preparation and analysis and report presentation to underpin the decision-making process to venture into new market opportunity. 


2.PROBLEM STATEMENT:
The global agricultural sector is vast and varied, offering numerous opportunities and challenges for agribusiness companies aiming to scale their operations across borders. To successfully navigate this landscape, it's crucial to leverage a data-driven approach that analyzes factors such as crop production, market demands, regulatory environments, and environmental sustainability. This project aims to pinpoint countries with high growth potential in the agricultural sector-(we will focus on Coffee green bean for this analysis), taking into account the viability of sustainable practices and the favorability of business climate.


3.INTRODUCTION:
The market for specialty coffee has witnessed an ascelarating growth not only in the Europe and America continents but love for coffee is spreading to Asia in un unprecedented level taking over the market share for other beverages like pearl milk tea in Asia. For the pass 10 years , we can see the opening of cafes all over Malaysia and local style of kopitian is now facing strong competition from cafe as consumer nowsadays is seeking unique and high-quality coffee experience rather than just the instant energy boosting induced by caffeine . 


" Specialty coffee is a coffee or coffee experience that is recognized for its distintive attribute, resulting in a higher value in the market place " - (SCA,2021). 

To justify the above SCA's definition of Specialty coffe , its production usually follows a strict standard and it must achieve a minimum marking scale to be labeled as specialty coffee. unlikes many other agriculture produce , coffee bean is not graded by its physical attribute only , but undergo a serious of revolution from the "cupping" system in the 1800s , later the introduction of "sensory" protocal in 1980s  , and eventually SCA codified all of these grading protocol into  into the first Specialty Coffee Association (of America) Cupping 
Protocol and Scoring Syste in 1999m (SCA,2023)
And today , SCA continues to review and reiterate the grading protocol as the industry has progressed and matured, as other attributes has became increasingly impactful to the buyer's choice , especially the environmental impact entailed the coffee production. 

![specialty coffee market trend by region_grand_view_research](https://github.com/kimberlytew/portfolio_1/assets/116537017/b9eb72a5-09a9-42e8-a688-2df2d502ce0f)


To entitle a higher grading, its requires a fully-integrated supply chain, from "seed to cup"where all stakeholders playan importantt role that impacts the quality of the that cup of coff and minimum compromise to mistakee . There ia s market analysis report that forcasted an annual growth of 11% from 2022 to 2030 on coffee comsumption and estimate a global value of more than $100 billion(Grand View Research) . In short, coffee market is huge and it is still growing.This presents a vast oppoortunity for Malaysia to expand its coffee bean production.  


METHODOLOGY :

Agriculture Dataset is collected from FAOSTAT website. The dataset encompasses a broad range of countries and agricultural items, indicating a wide geographic and product coverage.
Data spans from 2016 to 2022, offering a recent historical perspective on agricultural production and trends.
The Value column, which likely represents production volume or other quantitative metrics, varies significantly, with a minimum of 0 to a maximum of approximately 439 million units, highlighting the diverse scale of agricultural outputs across different entrie  All numerical columns have 58,606 entries, indicating no missing values in these columns.However for the purpose of this analysis , we will only focus on one product ; Coffee, green. 


ANALYSIS FINDINGS:

We perform groupby fuctions and only filter out the unique producers of coffee, green (result ; 16 countries). Then we drop a few colummns which are not needed in this analysis to make the dataframe cleaner and neat.We plot a scatterplot to better illustrate the ranking of those producer countries as attached below.


![coffee_prod_byCountry](https://github.com/kimberlytew/portfolio_1/assets/116537017/8801d5d3-a60e-42e1-b377-656ba719e519)




From tbar chart belowaset, we realised that for the conservative 2 years from 2016-2017, Malaysia was at the top 10th coffee producer , but was later taken over by other coutries. Vietnam stands as the biggest producer for the 6 years, followed by Indonesia and India 

![Production_2016](https://github.com/kimberlytew/portfolio_1/assets/116537017/6fe08d5b-a5ba-49b3-a33c-c1151ac895b2)
![Production_2017](https://github.com/kimberlytew/portfolio_1/assets/116537017/ef37d08c-3359-4993-bf2b-b24e6f4764e9)
![Production_2018](https://github.com/kimberlytew/portfolio_1/assets/116537017/629117fa-92cf-4bf6-9355-5945922ea8fd)
![Production_2019](https://github.com/kimberlytew/portfolio_1/assets/116537017/8997dde3-6929-40a7-8678-3d0141b1bbf4)
![Production_2020](https://github.com/kimberlytew/portfolio_1/assets/116537017/409f40f8-3c1e-4672-8839-6f7845eed17a)
![Production_2021](https://github.com/kimberlytew/portfolio_1/assets/116537017/05a9e3ea-e929-4e78-abe8-1cf5577dced3)
![Production_2022](https://github.com/kimberlytew/portfolio_1/assets/116537017/34ed9b3c-2c07-4671-a491-503dcc717b83)


However , after comparing the area havested and production yield , Malaysia was initially at the highest yield for year 2016 and 2017 , but was then over taken by China and Vietnam. The Yield scatter plot produce an insightful on how effective and effecient a country manage its coffee production as yield is calculated by 100g production / hectar of land used . 


![prod_yield](https://github.com/kimberlytew/portfolio_1/assets/116537017/12991b62-9ef0-4026-b13b-77ba7f09c6df)



![Msia_yield](https://github.com/kimberlytew/portfolio_1/assets/116537017/a91db13f-1efb-4de9-bc47-ff9f882b4b24)  
![Msia_area_harvest](https://github.com/kimberlytew/portfolio_1/assets/116537017/253fa15c-2ad0-4fd6-b2e3-5e694a31b8d1)




As based on research carried by researchers at MARDI, Malaysia's coffee production faces challenges stretched from limted high land for coffee plantation , to lack of financial support from the governm The reduced in area for coffee harvesting is abvious in the bar chart we ploted from the dataset as show in the above. nt . Malaysia farmers are seen to be less interested in coffee and more inclined to other corp like palm oil and rubber. The fluatuation of coffee price discouraged local farmer from investing time and effort into coffee cultivation(more complicated processing method involved). The decline on the coffee production has led to mass increase of coffee bean import to meet the growing local demand. The MARDI research dictated that Malaysia import 97% of coffee bean to meet domestic demand every year and the rising of global coffee price will be a bad news to us. 


Nevertheless, eventhough the area used for coffee cultivation was significant reduced since 2017 , we still withness some kind of improvement on the production yield value from 2020-2022. We suspect that those coffee farmer is improving themself in term of their knowledge and expertise about coffee bproduction as well as upgrade of their machinery used. Therefore, we believe Malaysia has the potential in the cultivation and production of coffee bean if government could extend support to coffee farment like how the support is given to palm oil farmer. 
RecommendatioHYPOTHESIS TESTING

Referring to the scatterplot earlier , ( "Coffee Production by Countries from 2016 to 2022") , we found that Vietnam ranks as the top coffee producer for all the years of analysis with increasing product year on year. Vietnam is in SouthEast Asia, which means it is nearer to us, does it suggest any potential for partnership or technology transfer to boost our coffee production? To reaffirm our expectation we run the analysis to plot out the Coffee Production Yield by Countries from 2016 to 2022 below:



![prod_yield](https://github.com/kimberlytew/portfolio_1/assets/116537017/c3336e06-99da-49f6-9a38-b0f6c558bf44)



By plotting all the countries production yield on the scatterplot, it presents an interesting result, where Vietnam is ranked at 3rd after China and Malaysia for year 2016 and 2017 and 2nd place after China for the remaining years. We are surprised to see China taking a leap from 5th place (as shown in the previous yearly bar chart for Coffee Production by Countries from 2016 to 2022) to the top of hthe list in the production yield analysis above. 


In order to be convinced that China will be a better country for investment than other , we run a linear regression test on China, Vietnam and Malaysia production yield , to test on our hypothesis

Hypothesis  = China and Vietnam 's production yield will have a linear increment year on year from 2016 to 2022
Hypothesis  - China has a higher mean that Vietnam

The result of this hypothesis testing should will underpin our next step. However if the result fails to support this hypothesis, we will continue seeking other county for opportunit 
The result is shown in a fitted linear regression chart below .  


![china_fitLR](https://github.com/kimberlytew/portfolio_1/assets/116537017/4554d522-c733-40f0-af80-e89e6cc591cc)

![viet_fitLR](https://github.com/kimberlytew/portfolio_1/assets/116537017/1c343c16-0ab9-4816-a4f0-f32da426b96b)


![msia_fitLR](https://github.com/kimberlytew/portfolio_1/assets/116537017/ad3befdd-7f8a-4572-b122-70f4124425c2)
 

From the model result, we get 95% of confidence level (p-value <0.05) that China and Vietnam have linear increment to their production yield. However , China has a right-skewed of 1.330 while Vietnam is slightly left-skewed at -0.097 which tell us that China has a higher mean than Vietnam. This result proves that China is showing a impressive efficient in their coffee production . 

Looking on the impressive yield value , China market is good role model that we can spend some time to study on how China improvises their method in cultivation and processing. From economic data , Yunan in China contributed the biggest export for coffe bean from China, from geographical perspective , Yunan has highland and cool temperature during the night to cultivate good coffee bes. Futhermore , Malaysia and China has had a long-established diplomat relationship where both are very important trading partners in the export and import business. We foresee a great opportunity for any form of direct-investment, joint-venture with the local coffee farmer , and leverage on their competitive advantage.


We suggest a joint-venture model with both Malaysia and China will specialize on each strenght , with China focuses on cultivatuon and production line, Malaysia will handle the branding and marketing segment, with this distribution of specialization ,we expect a shorter timeline for research and development stage and hence substantial cost reduction could be achieved. Following the increase of disposable income and changes in the lifestyle preferences, more people will willing to spend for a good cup of coffee , as demand continue to spike , with supply still lagging behind , we foresee further rising momentum for global coffee price. Malaysia coffee producers should turn around this into an opportunty.

95% of the coffee export from Vietnam belongs to the Robusta species , which is mostly used in the instant coffee and local vietnamese coffee .Their coffee has more bitter and woody flavor to meet their local taste , and this may not be as attractive to younger consumer as to older generation. Meanwhile, Malaysia already has its own renown local hainam-style coffee to cater one segment of customer that prefer coffee that has strong bitterness ,nutty and smoked flavor, yet we are still lack behind in term of competing  for market share of specialty coffee( arabica coffee provides different tasting note, from flowerish , fruity to chocolote-like ). In this we believe China is better partner than Vietnam.   
 



APPENDICES

1.(Specialty Coffee Association,2021),Specialty Coffee Association, Towards a Definition of Specialty Coffee: Building an Understanding Based on 
Attributes , https://sca.coffee/sca-news/just-released-newsca-white-paper-tow
Market Analysis for Coffee Producer

2.(Specialty Coffee Association,2022),A New System to Access Coffe Value ,Introducing the Beta Version of SCA"s Coffee Value Assessment, 2023),https://sca.coffee/value-assessment

3.(Grand View Research,2023),Specialty Coffee Market Size, Share & Trends Analysis Report By Age Group (18-24, 25-39, 40-59, Above 60), By Application, By Distribution Channel, By Region, And Segment Forecasts, 2023 - 2030.

4.(Nik Rahimah N.O et al,2022),Coffee industry in Malaysia: An overview and potential,Economic and Technology Management Review, Vol,19,MARDI.


 
