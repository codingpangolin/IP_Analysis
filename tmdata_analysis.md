---
title: hello
---

# Geographical distribution of United Kingdom trademark applications

The data visualisations presented here were created from a [set of data scraped](https://raw.githubusercontent.com/codingpangolin/IP_Analysis/master/tmscrape_jan_june2018.csv) from the [UK’s trademark register](https://www.gov.uk/search-for-trademark). The dataset records the basic details of every application for a trademark made in the UK from the start of January 2018 to the end of June that same year.  One of the main details the register shows is the address of the applicant attempting to register the trademark; this analysis examines this datum in order to show how the locations of applicants for UK trademarks are distributed. 

Mapping the country given in the applicant’s address on the trademark register on to a choropleth map shows that a large number of countries from around the world have made at least one trademark application in the UK in the first six months of 2018.  Only two countries however, China and the USA, have made more than 250, while the largest number of applications were made by addresses within the UK itself.

![world_choro](/assets/world_choro.png)

The preponderance of UK addresses in the application data can be better seen on the pie chart below. A huge majority of the trademark applications were made using addresses in the UK while only 18.6% were made from locations outside it.

![apps_country_pie](/assets/apps_country_pie.png)

The below map shows the UK divided into its various post code areas. It indicates the areas with the greatest concentration of applications based on the post code included in the applicant’s address on the trademark register. It indicates that the greatest numbers of applications had addresses within Birmingham, Manchester or the various areas which make up London.

![uk_choro](/assets/uk_choro.png)

The dominance of London as an address for making trademark applications can be seen more clearly in the below pie chart. More than a quarter of all trademark applications made in England were from the region of London.

![uk_region_pie](/assets/uk_region_pie.png)

Part of the reason for London’s dominance in trademark applications can be seen by mapping the number of applications made in each region to each region’s Gross Value Added (GVA), the total amount of output it contributes to the UK’s GDP, [based on the latest ONS data](http://researchbriefings.files.parliament.uk/documents/SN05795/SN05795.pdf). This shows a strong correlation between a region’s economic output and the number of trademark applications made from inside it. The huge amount of the UK’s economic activity that takes place in London would seem to account for the level of applications which it makes.

![scatter_apps_gva](/assets/scatter_apps_gva.png)
