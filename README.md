# province of cambodia data
This is a Scrapping data of all provinces of Cambodia and also include some such as ISO , Capital, District.

## Objective 
I created to help developer who want to using data of province , district of cambodia by provide on json file. and also sharing the source code of python file.
I help this project can make you easy for your work.
## Installation
Install the requirement and run the project.

```sh
pip install requests
pip install beautifulsoup4
```

## Data in json file
- Province name as English language 
- Province name as Khmer language 
-  Capital 
-  Population 
-  Area (Km*2)
-  Density 
-  ISO 
-  District Name as Khmer Language 
-  District Name as English Langauge 
-  Population of People in District
## Json File
```json
{
    "Province_EN": "Banteay Meanchey",
    "Province_KH": "បន្ទាយមានជ័យ",
    "Capital": "Serei Saophoan",
    "Population(2019)": "861,883",
    "Area": "6,679",
    "Density": "129",
    "ISO": "KH-1",
    "District": [
      {
        "ISO_Code": "01-02",
        "District_Name_EN": "Mongkol Borey",
        "District_Name_KH": "ស្រុកមង្គលបូរី",
        "Population(2019)": "187,286"
      },
      {
        "ISO_Code": "01-03",
        "District_Name_EN": "Phnom Srok",
        "District_Name_KH": "ស្រុកភ្នំស្រុក",
        "Population(2019)": "65,945"
      },
      .....
      .....
}
```
## Resource 
- https://en.wikipedia.org/wiki/Provinces_of_Cambodia
