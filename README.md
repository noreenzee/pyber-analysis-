* pyber-analysis
* Overview of the Challenge 
                            The main purpose of this project is to visualize data in order to provide access and understanding of ridesharing services in city and neighbourhood. The city data and ride data was provided in csv file type in order to visualize data, both files are merged and then find different outcomes. Following paragraph will depict the summary of this challenge in discription and screenshort form
 *Summary of DataFrame 
                        Total number of rides were divided in three different types the "rural, Suburban and urban" and by using groupby and count function we find that there were "urban rides" on top of rural and suburban. As it shows in this screenshot
                        ![image](https://user-images.githubusercontent.com/112978144/206255548-0b7ca532-7f4d-47f9-8559-291624211867.png)


 *Total Drivers
                As there were Urban rides the most we find that Urban Drivers were most as well and it's obvious because where there are most rides most drivers are needed as well. Data shows that for 1625 urban rides there are 2405 urban drivers are available as shown in this picture
                ![image](https://user-images.githubusercontent.com/112978144/206257572-2be62716-c050-435d-95fd-73791c0e4c61.png)
                
                
                

 *Total amount of Fare for each city type
                                          Data shows that there is a huge difference in each city type fare. There is lowest fare in rural areas and highest fare in urban city type as shown here:
                                          ![image](https://user-images.githubusercontent.com/112978144/206259834-45772653-7460-4c90-9786-6b809b48cb76.png)
                                          
                                          
                                          
* Average fare per ride
                        As there are most rides in urban city type when we try to find the averge fare per ride it shows that there less fare in urban city type. That means where there are more rides there is less fare for a ride as we can compare both total rides in each city type and average fare per ride. 
  *Total rides, total fare and Average fare:
  
                        ![image](https://user-images.githubusercontent.com/112978144/206261231-faec836b-67af-47c0-813f-b35670a3034e.png)
 Pivot table:
              Pivot table is created to find the total fares for each type of city by the date and it shows following data:
              ![image](https://user-images.githubusercontent.com/112978144/206263151-26a034e5-debb-47a2-b017-0b75abd0b078.png)

* Resample Data
                New DataFrame is created to get the sum of the fare for each week
                
                
                ![image](https://user-images.githubusercontent.com/112978144/206292401-229eaf82-4870-4d9c-a303-8e6949fca240.png)

                          
         


          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          than resampled data is plotted using df.plot function and in plot format all above findings look like this
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          ![image](https://user-images.githubusercontent.com/112978144/206264350-aaa18a8c-ca1e-4998-a4f9-6a4315c5f90b.png)
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                than resampled data is plotted using df.plot function and in plot format all above findings look like this
                
                
                ![image](https://user-images.githubusercontent.com/112978144/206270608-a375587e-d7de-4b18-92cd-a5950ae11bd6.png)

                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
                
The above chart shows that the money made by the ride_service is fairly steady from Jan to about mid Feb and then it little spike at the end of Feb than it slow down again. Urban cities generate the most total revenue, followed by suburban and rural areas. 

The observed outcomes are not surprising, given that cities are expected to generate more revenue because they have more rides than suburban or rural areas taht ends up in most revenue. It can be infer that most drivers likely prefer to work in urban city type to generate more money. 
* More rides = more revenue.

                
                


                        


