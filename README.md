# Forex Anaylsis Platfrom

Hello!

Welcome to Bar's Forex Analysis Platform. The Forex rates are extracted from Fixer.io API.

The platform was first populated with two months worth of Forex rates using the dag: "populating_platform". 
After the first batch of data, the pipeline "insert_new_data" is scheduled to run once a day and insert new data.

All the rates are compared vs a US Dollar base rate. 

### populating_platform
![workflow](https://user-images.githubusercontent.com/65648983/209153010-170cfa40-1cc0-4908-9bd6-1f87e6e01eb1.png)




### The home page
![home](https://user-images.githubusercontent.com/65648983/209152417-dd3d6ad9-1cd4-4425-b26c-6f560913950b.png)


### Available Currencies
![symbols](https://user-images.githubusercontent.com/65648983/209988258-fbde2d07-9627-46b0-96ee-39c5dad45b91.png)


### Interactive Graphs
![Analysis](https://user-images.githubusercontent.com/65648983/209988511-d285aa2b-3fc1-42a0-9c10-ff7ae38da4f1.png)