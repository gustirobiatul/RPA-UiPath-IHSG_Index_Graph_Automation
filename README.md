# RPA-UiPath-IHSG_Index_Graph_Automation
In this project, i made an automation to download and create a graph based by IHSG Index on idx.com 

Step:

1. Build datatable to duplicate the result of IHSG Index data scrapping and change the format into object (To change to number format in excel)
2. Open Idx.com
3. Data Scrapping IHSG Index to get the data (Datatable format: datatable)
4. Change format into number and write into table (Using for each, and convert one row by one row into decimal type. 
   The variable need to be replaced before to be the right format* and write in excel using number type)
5. Create graph and save excel.


*The format which downloaded from idx is= 8.200,90 
And the format for decimal is = 8200,90 so the comma (,) and dot (.) need to be replace first, which will result = 8200.90
then convert into decimal type, and write in excel which will written = 8200,90
