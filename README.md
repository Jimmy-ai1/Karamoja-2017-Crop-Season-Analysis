# Karamoja-2017-Season-Analysis

![Crop_fields](https://github.com/user-attachments/assets/d51c0583-3ed6-4f28-87af-5d7241b564cf)

## Overview

[Karamoja](https://en.wikipedia.org/wiki/Karamoja) is the **most food-insecure** region of Uganda mainly as a result of low productivity level of the crops due to intense droughts as well as pest and disease outbreaks.

Several NGOs **provide technical support as well as farm inputs** to local farmers but their **efforts are hindered by limited visibility into the overall state of the region.** They rely heavily on fragmented local sources of information, making it difficult to target interventions effectively. In response, Dalberg Data Insights (DDI) applied a satellite-based methodology to remotely estimate crop yields for the region's two staple crops (sorghum and maize) during the 2017 season.

This project focuses on **creating an interactive visualizations of these results**, which will serve as a first mockup of the Food Security Monitoring Tool to guide future NGO activities.

## Business Objectives

The main objective of this project is to **develop an interactive visualization tool that supports NGOs in monitoring food security** conditions across Karamoja. Specifically, the project seeks to:
- Integrate population and production data to **highlight areas where food availabilty is critically low.**
- **Visualize crop yield and production for sorghum and maize** using satellite-based estimates at both district and subcounty levels..
- **Identify priority areas for NGO intervention** by revealing patterns of low productivity and high vulnerabilty.
- **Enable interactive exploration** through maps, charts and filters that allow users to compare regions and crop performance.

## Data Understanding

The data used in this analysis consists of **two datasets** which provide information concerning **yield and production of staple crops** (maize and sorghum) for **districts** and **sub-counties** in Uganda. The data provides the farming area in hectares, crop yield of both crops in hectares, productivity of both crops individually in kilograms as well as the population of the districts and sub-counties.

## Results

The chart highlights Kotido's dominance in sorghum production, suggesting that sorghum is likely the best performing in that district. Maize production is relatively stronger in Nakapiripirit and Napak compared to other districts. The disparity in production volumes points to differences in land area, soil suitability, or farmer preference for crop type across districts.

<img width="990" height="472" alt="Crop Contribution" src="https://github.com/user-attachments/assets/c9ae74de-20e7-428c-b9a8-e408c4413737" />

Kabong and Nakapiripirit perform well in maize yields (13,851 kg/Ha and 9,353 kg/Ha resp.), far surpassing other districts. Sorghum yields are genereally lower across all districts, with Kaabang (3,664 kg/Ha) and Abim (2,582 kg/Ha) showing the strongest performance for sorghum. Moroto has the lowest yields for both crops indicating poor perfomance.

Although Kotido leads in production volumes, its yield per hectare is lower than Kaabang's and Nakapiripirit's. This suggests that Kotido has a large area of cultivation but lower efficiency, while Kaabang achieves better productivity per unit area. Sorghum appears less productive than maize overall, possibly due to lower inputs, poor agronomic practices, or environmental limitations.

<img width="991" height="481" alt="Total Crop Yield" src="https://github.com/user-attachments/assets/155b9df3-fbcd-48d5-9bcb-ab417be610d1" />

**Kotido has the largest sorghum planting area** (~50,000 Ha), dwarfing maize cultivation. Kaabong and Nakupiripirit also favour sorghum cultivation over maize cultivation with both having close to 20,000 Ha for its cultivation. **Napak has a more balanced planting mix** with sorghum slightly ahead. **Abim, Amudat and Moroto have very small planting areas** (< 5,000 Ha) for both crops, with sorghum slightly higher.

Districts reveal **distinct crop specialization patterns**. **Kotido, Kaabong and Nakupiripirit are sorghum-heavy systems**, indicating strong **agro-ecological suitability and farmer
preference for drought resistance cereals**. **Napak's balanced planting strategy** reflects **diversification**, possibly as a risk management approach against climate variability. On
the other hand, **Abim, Amudat, and Moroto have limited cultivated land**, suggesting either **land constraints, lower agricultural investment, or greater reliance on external food
supplies.**

<img width="987" height="470" alt="Total Crop Area by District" src="https://github.com/user-attachments/assets/3e301522-f539-4fbd-841d-6598a1ed88cd" />

**Nakupiripirit and Kotido lead in per capita production** (101.99 and 76.67) respectively, indicating that **relative to population, these districts produce a surplu**s. **Kaabong and
especially Moroto** are the **lowest** (20.28 and 8.05 resp.), showing **significant production pressure relative to population**.

**Nakupiripirit and Kotido** are **better positioned to meet household food needs** and may even have surplases. On the other hand, **Moroto shows critical underproduction**, raising
concerns about food shortages. **Kaabang's low production per capita value, despite high yields**, suggests **population pressure.

<img width="987" height="471" alt="True Prod  per Capita" src="https://github.com/user-attachments/assets/2a808de0-3ad3-4eb8-8bee-938243841c38" />

Kotido and Nakupiripirit emerge as surplus-producing districts, capable of supporting their own populations and potentially supplying neighbouring areas. Napak, Amudat and Kaabong appear
self-sufficient but with less surplus, while Moroto and Abim represent low-scale systems with minimal contribution to regional food stocks likely due to lower cultivated areas or less
favourable growing conditions.

<img width="989" height="469" alt="Total POP vs Total Prod" src="https://github.com/user-attachments/assets/0aae4003-34fb-4950-bbb0-c531154e913a" />

## Conclusions
- Most districts such as **Kotido** heavily rely on sorghum production than maize production.
- **Sorghum and maize yields and production vary significantly across districts** and subcounties, with some areas such as **Moroto District** consistently underperfoming due to harsher drought effects.
- Moroto, Abim and Amudat contribute less to the regional food basket, with both **low crop area and production**.
- Districts like Kotido and Nakupiripirit consistently produce surplus relative to population making them **regional supply hubs.**
- Some districts such as Kaabong show good yields but low production per capita due to higher population relative to farmland, stressing the need to integrate demographic trends.

## Recommendations
- **Prioritize high-risk sub-counties.** Direct NGO interventions (farm inputs, drought-resistant seeds) to sub-counties with the lowest food production per capita such as Kaabong East and Kaabong Town Council.
- **Promote crop diversification.** Encourage farmers to balance maize and sorghum cultivation or even introduce legumes such as beans or root crops such as cassava to reduce risk from crop-specific shocks. 
- **Apply Targeted Resource Allocation.** Use yield maps to distribute resources e.g fertilizers, more effectively rather than evenly across districts.
- **Early warning systems.** Develop a monitoring framework that updates yield estimates annually or seasonally to detect emerging food security risks early.
- **Promote soil health programs** such as use of organic manure, crop rotation, and soil conservation practices to improve yields sustainably.
- **Market development**. Support farmers with market linkages and cooperative models so surplus is not wasted and farmers earn fair value.
- **Introduce mordern farming methods** such as irrigation and use of greenhouses to improve crop yields in the region
