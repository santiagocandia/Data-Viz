# Berlin's ZIP codes

## Motivation
The lack of an official (or unofficial) dataset that groups ZIP codes by boroughs and neighborhoods has motivated me to search for this information and develop a database.

## Target:
1) Develop a dataset of ZIP codes grouped by Boroughs and Neighborhoods of the Berlin city.
2) Build a dashboard that simplifies the identification of ZIP codes, Boroughs and Neiborhoods of Berlin city.

## Visit the interactive dashboard at Tableau Public 
https://public.tableau.com/app/profile/santiago.candia/viz/BerlinsZIPcodes/BerlinsZIPcodes

## Dashboard
![image](https://github.com/santiagocandia/data-viz/assets/16913295/64d5a3e7-8915-4bb2-af11-46ffd24d21be)


## The dataset
- To develop the datasets different Internet sources have been consulted and the results have been controlled by analyzing each zip code individually. There are two csv files: 
- The BerlinZipCodes1.csv file includes all neighborhoods in the same column, so you will find repeated zip codes for different neighborhoods. 
- The BerlinZipCodes2.csv file has separate columns for the main neighborhood and the other neighborhoods. In some cases, the same zip code is valid for more than 3 different neighborhoods, but this project only includes the top 3 neighborhoods by zip code.
- In all cases, the criterion for choosing the main neighborhood was to assign the zip code according to the geographical space it covers. The zip code was assigned to the neighborhood in which it covers the largest geographic space.
- There are also ZIP codes that completely cover more than 1 neighborhood. These are the cases of Kladow and Gatow in Spandau, Buch and Karow in Pankow and Grünau and Schmöckwitz in Treptow-Köpenik

![map](https://github.com/santiagocandia/data-viz/assets/16913295/253d9a7a-1586-4d0b-b8dc-271d505c62e0)

## Main sources
https://www.suche-postleitzahl.org/land/berlin.13f#modal

https://en.wikipedia.org/wiki/Boroughs_and_neighborhoods_of_Berlin

https://de.wikipedia.org/wiki/Verwaltungsgliederung_Berlins




