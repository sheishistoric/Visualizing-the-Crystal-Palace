# Visualizing-the-Crystal-Palace
The 1853 New York Crystal Palace, also known as the Exhibition of the Industry of All Nations, was America’s first world fair. Modeled on the Great Exhibition held at the Crystal Palace in London, the exhibition sought to “draw forth such a representation of the world’s industry and resources as would enable us to measure the strength and value of our own, while it indicated new aims for our enterprise and skill.” 
This dataset, produced from the OCR of [Cornell University’s digitized record of the official catalogue of the exhibition](https://babel.hathitrust.org/cgi/pt?id=coo1.ark:/13960/t4zg76w7k)represents over 3,000 objects on display at the exhibition. In an effort to make this data available for study, analysis, and reuse, Steven Lubar, along with Emily Esten, Steffani Gomez, and Brown’s Center for Digital Scholarship (Brian Croxall, Eli Mylonas, and Patrick Rashleigh) reformatted the data as a CSV.
## Considerations
For the “longitude” and “latitude” of objects in New York City, more exact coordinates are provided down to a street or address level. 
Please note that the catalogue and the subsequent dataset have been extensively researched and cleaned, but still include errors. Anyone who may detect omissions or mistakes of any kind - please, send in your corrections. 
To read more about the history of the New York Crystal Palace’s catalog, please go to[Cataloging History, Part 2.](https://medium.com/@lubar/the-new-york-crystal-palace-catalogs-b09d1f2bd20e)
To see detailed information about our internal descriptive standards and the project behind this data, please go to our [Medium posts.](https://medium.com/@lubar/the-new-york-crystal-palace-catalogs-b09d1f2bd20e)
## Repository Contents 
The data is currently available in CSV format. **The fields are as follows:**

|     **Field**    | **Description**                                                                                                                                                                                                                                                                                                             |
|:----------------:|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| division         | Location within the Crystal Palace building (A, B, C, D, Gallery)                                                                                                                                                                                                                                                           |
| court            | Location with the Crystal Palace divisions                                                                                                                                                                                                                                                                                  |
| country          | Geographic location of object (Countries are identified by their contemporary name. For example, the Netherlands is identified in the data as Holland. Ireland is listed as part of Great Britain, despite the separation.)                                                                                                 |
| class            | All objects in the catalogue are separated into distinct classes for grouping within the exhibition (1-31)                                                                                                                                                                                                                  |
| product          | Description of the product                                                                                                                                                                                                                                                                                                  |
| person           | First-Name Last-Name OR Institution OR Company, when known                                                                                                                                                                                                                                                                  |
| agent            | First-Name Last-Name OR Institution OR Company, if applicable                                                                                                                                                                                                                                                               |
| role             | Refers to the position of the “person” submitting the item to the exhibition. Various abbreviations are used: manu. refers to manufacturer; prop. refers to proprietor, prod. refers to producer, imp. refers to importer; des. refers to designer; inv. refers to inventor. Multiple roles may be applicable to an object. |
| country-or-state | Geographic location of object, on a regional or state level. (Regions are identified by their contemporary name. For example, the Czech Republic is identified in the data as Germany.)                                                                                                                                     |
| town-or-city     | Geographic location of object, on a town or city. (Towns/cities are identified by their contemporary name and location. For example, the town of Ridgewood, New Jersey, is identified in the data as Godwinville.)                                                                                                          |
| longitude        | Coordinates reflective of the town-or-city location                                                                                                                                                                                                                                                                         |
| latitude         | Coordinates reflective of the town-or-city location                                                                                                                                                                                                                                                                         |

## Hello my name is
Emily Esten, MA Student in Public Humanities & Digital Projects Assistant for Steven Lubar at Brown University. [This is my website](http://emilyesten.com/) and I tweet at [@sheishistoric](http://www.twitter.com/sheishistoric).

--