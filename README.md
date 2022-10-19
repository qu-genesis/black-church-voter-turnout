# Black Church Voter Turnout Analysis

Spring 2021, Republicans in the state of Georgia had proposed a new elections [law](https://www.washingtonpost.com/politics/2021/02/24/new-georgia-legislation-would-curb-souls-polls/) that would eliminate Sunday voting. This proposal would effectively do away with “souls to the polls”, a pillar in how African-American communities organize and vote in the South which developed in reaction to historical voter suppression. While Republicans ended up dropping the proposal at the end, it's still worth understanding how these institutions strengthen voting turnout of Black constituents in the South and hypothesize how curbs to Sunday voting would dismantle voting access.

Acknowledgements: The religion census data comes from the Association of Religious Data Archives, and the state level election data comes from the respective Secretary of State offices.

We only want data on predominantly African-American religious institutions to analyze the effects of Black Churches on voter turnout in the South. And we will narrow the data to a few states in the deep south: South Carolina, Georgia, Louisiana, Alabama, and Mississippi.

To understand what churches have the greatest impact, the Conference of National Black Churches provides a starting point. The organization said it represents more than 80% of African-American Christians, or around 20 million people in the U.S. It is made up of seven predominantly African-American Churches:

- African Methodist Episcopal Church (AME)
- African Methodist Episcopal Zion Church (AMEZ)
- Christian Methodist Episcopal Church (CME)
- Church of God In Christ (COGIC)
- National Baptist Convention of America, Inc., International (NBCA)
- National Baptist Convention, U. S. A. Inc. (NBC USA)
- Progressive National Baptist Convention, Inc. (PNBC) 

Because of limited county-level election data from the secretary of state offices, I was only able to extract granular county-level data from Louisiana. So here is a case study on Black churchs' relationship with voting turnout and partisanship in Louisiana. 

![Louisiana_pres_results](https://user-images.githubusercontent.com/60377132/196599771-6ecabf55-fa6a-47b0-8eef-543ea2d8fb11.png)

After extracting the number of predominently African-American church adherents from the religion census dataset and running that against the vote share of the Democratic Party, we find that while the data is noisy, higher number of Black church adherents in a county is typically associated with a higher vote share for Barack Obama in the 2008 and 2016 presidential elections. (I opted for these two elections because the data is collected in 2010 and data drift could become a issue for later elections). 

This point is relatively easy to wrap one's head around. African-American voters, as a demographic, has generally leaned Democratic over the past few decades.

The more interesting part comes when we factor voter turnout in the equation.

![louisiana_turnout](https://user-images.githubusercontent.com/60377132/196600647-defcb53d-1b06-4582-977c-cc75f0c7cf8f.png)

We would hypothesize that a larger share of Black church adherents in a county would help mobilize the county's voters to show up at the polls, leading to a higher voter turnout in that county. However, the trend does not appear to support that hypothesis in our data. 

Trends persist when we break the data down by party affiliations.

![louisiana_turnout_dem](https://user-images.githubusercontent.com/60377132/196600957-5dc99863-d13e-4743-a4b8-0f7fe4a346d3.png)

![louisiana_turnout_rep](https://user-images.githubusercontent.com/60377132/196600994-653d6e59-af50-4285-804f-aa235fcd0a15.png)

![louisiana_turnout_third](https://user-images.githubusercontent.com/60377132/196601065-f6b0e809-7245-45b6-ad67-f867ce5c7927.png)

Voter turnout even trended down for higher proportions of Black church adherents for voters that affiliate with the Republican Party. This is interesting results that should lead to further analysis, incorporating data on more states. The 2022 data for the religion census is also slated to come out soon, which could be useful for additional research. 

