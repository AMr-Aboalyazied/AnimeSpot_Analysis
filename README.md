# AnimeSpot_Analysis
AnimeSpot Data is an Excel Workbook contains sales Data Collected Monthly about Retail invoice data Which is 4 Sheets (Sales – Stores – Product – Reps)

First, Gather Data in one sheet then use excel power pivot to do some calculations to answer business questions after that start to design the Data Warehouse (Fact & Dims) + Date Dim

Second, Create Database and use SQL Server Integration Service (SSIS) to fill database with excel sheets then create Star Schema Diagram

Finally, make a connection with database from Power BI to make a Descriptive Analysis Dashboard Which contain 4 Pages

1- Sales >> it's 4 Cards (Total Revenue - Total Sold Quantity - Total Orders - Average Revenue Per Transaction) and 4 Charts for Total Revenue Per (Each Day - Each Quarter - Each Month - Each ProductCode)

2- Product >> it's 4 Cards (Total Brands - Total Category - Total Sub_Category - Total Products) and 4 Charts for Total Revenue Per (Top 10 Brand and Their Total Orders - Top 10 Categories and Their Total Orders - Hierarchy for brands - Top 5 Product According to each stores)

3- Performance >> it's 3 Cards (Total Stores - Total Representors - Regions) and 5 Charts for Total Revenue Per (Each Representor - by month for each store - Each Store and Their total Orders - 2 Dounts Chart for Most Total Orders and revenue in the 3 regions)

4- Returned >> it's 3 Cards (Total Purchase return - Returned Quantity - Returned Orders) and 4 Charts for Total Purchase return Per (Each Reason and Their Quantity - ProductCode - Each Store and Their Quantity - Each Brand and Their Quantity)
Power Pivot Calculations ScreenShoots
![260791871-cee07343-c69c-4eb7-a3d7-c3ed12ddd76f](https://github.com/AMr-Aboalyazied/AnimeSpot_Analysis/assets/69647895/e1b025ba-90b0-457b-ae9b-3cff706d436e)
SSIS ScreenShots
![260792175-2feaf1e7-bfad-49a5-a118-5e30dc22f822](https://github.com/AMr-Aboalyazied/AnimeSpot_Analysis/assets/69647895/5a43587f-2afd-4493-8f2d-d005c307afc9)

Project screenshots
![Screenshot 2024-02-15 153011](https://github.com/AMr-Aboalyazied/AnimeSpot_Analysis/assets/69647895/198cde11-f9ac-424b-a278-ef53e67df91e)
![Screenshot 2024-02-15 153101](https://github.com/AMr-Aboalyazied/AnimeSpot_Analysis/assets/69647895/fbb8167a-624c-45dc-90ea-77e13f3d2525)
![Screenshot 2024-02-15 153148](https://github.com/AMr-Aboalyazied/AnimeSpot_Analysis/assets/69647895/69123660-cfc0-4ba8-8ce7-61297cddee57)
![Screenshot 2024-02-15 153251](https://github.com/AMr-Aboalyazied/AnimeSpot_Analysis/assets/69647895/bb5a2981-0f7b-499a-90aa-b19fbf8f73b7)
![Screenshot 2024-02-15 153218](https://github.com/AMr-Aboalyazied/AnimeSpot_Analysis/assets/69647895/4f850079-40fe-44ce-ba17-752856a59cc3)
