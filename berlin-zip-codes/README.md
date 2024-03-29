# Berlin's ZIP codes

## Motivation
The lack of an official (or unofficial) dataset that groups postal codes by boroughs and neighborhoods of Berlin has motivated me to search for this information and develop a dataset.

## Target:
1) Develop a dataset of postal codes grouped by boroughs and neighborhoods of the Berlin.
2) Build a dashboard that simplifies the identification of ZIP codes, boroughs and neiborhoods of the city.

## Visit the interactive dashboard at Tableau Public 
https://public.tableau.com/app/profile/santiago.candia/viz/Berlinspostalcodes/Berlinspostalcodes

## Dashboard
![image](https://github.com/santiagocandia/data-viz/assets/16913295/bba7ea71-24b4-40c9-a6c9-cd16332052f7)



## The dataset
- To develop the datasets different internet sources have been consulted and the results have been controlled by analyzing each zip code individually. There are two csv files: 
- The BerlinZipCodes1.csv file includes all neighborhoods in the same column, so you will find repeated postal codes for different neighborhoods. 
- The BerlinZipCodes2.csv file has separate columns for the main neighborhood and the other neighborhoods. In some cases, the same zip code is valid for more than 3 different neighborhoods, but this project only includes the top 3 neighborhoods by postal code.
- In all cases, the criteria for choosing the main neighborhood was to assign the zip code according to the geographical space it covers. The zip code was assigned to the neighborhood in which it covers the largest geographic space.
- There are also ZIP codes that completely cover more than 1 neighborhood. These are the cases of Kladow and Gatow in Spandau, Buch and Karow in Pankow and Grünau and Schmöckwitz in Treptow-Köpenik

![map](https://github.com/santiagocandia/data-viz/assets/16913295/253d9a7a-1586-4d0b-b8dc-271d505c62e0)

## Main sources
https://www.suche-postleitzahl.org/land/berlin.13f#modal

https://en.wikipedia.org/wiki/Boroughs_and_neighborhoods_of_Berlin

https://de.wikipedia.org/wiki/Verwaltungsgliederung_Berlins




