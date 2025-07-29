# UKTMembantaiDM


## Tutorial setting

1. Register atau login ke website CDS

https://cds.climate.copernicus.eu/how-to-api

2. Ambillah url dan API key dari website di atas juga dari dalam black box. 
    
    Format:
    ```
    url: https://cds.climate.copernicus.eu/api
    key: <PERSONAL-ACCESS-TOKEN>
    ```


3. Setelah login, buatlah file `.cdsapirs` di direktori `/Users/{username}/` dan paste kan url dan key yang telah di copy ke dalam file tersebut.

    Tips: Cara membuat file `.cdsapirs` adalah dengan membuat new text file lalu save as nama `.cdsapirs` dengan save as type nya `all type`


4. Install dependencies lainnya dengan run notebook. 