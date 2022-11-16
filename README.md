# zomato_analysis

Zomato API Analysis is one of the most useful analysis for foodies who want to taste the best cuisines of every part of the world which lies in their budget. This analysis is also for those who want to find the value for money restaurants in various parts of the country for the cuisines. Additionally, this analysis caters the needs of people who are striving to get the best cuisine of the country and which locality of that country serves that cuisines with maximum number of restaurants.♨️

For more information on Zomato API and Zomato API key
• Visit : https://developers.zomato.com/api#headline1
• Data Collection: https://developers.zomato.com/documentation

Data
Fetching the data:
• Data has been collected from the Zomato API in the form of .json files(raw data) using the url=https://developers.zomato.com/api/v2.1/search?entity_id=1&entity_type=city&start=1&count=20
• Raw data can be seen here
Data Collection:
Data collected can be seen as a raw .json file here

Dataset: https://www.kaggle.com/datasets/shrutimehta/zomato-restaurants-data
Data Storage:
The collected data has been stored in the Comma Separated Value file Zomato.csv. Each restaurant in the dataset is uniquely identified by its Restaurant Id. Every Restaurant contains the following variables:

• Restaurant Id: Unique id of every restaurant across various cities of the world<br>
• Restaurant Name: Name of the restaurant<br>
• Country Code: Country in which restaurant is located<br>
• City: City in which restaurant is located<br>
• Address: Address of the restaurant<br>
• Locality: Location in the city<br>
• Locality Verbose: Detailed description of the locality<br>
• Longitude: Longitude coordinate of the restaurant's location<br>
• Latitude: Latitude coordinate of the restaurant's location<br>
• Cuisines: Cuisines offered by the restaurant<br>
• Average Cost for two: Cost for two people in different currencies<br>
• Currency: Currency of the country<br>
• Has Table booking: yes/no<br>
• Has Online delivery: yes/ no<br>
• Is delivering: yes/ no<br>
• Switch to order menu: yes/no<br>
• Price range: range of price of food<br>
• Aggregate Rating: Average rating out of 5<br>
• Rating color: depending upon the average rating color<br>
• Rating text: text on the basis of rating of rating<br>
• Votes: Number of ratings casted by people<br>

#Observation
Observing the Ratings: <br>
When rating is 1.8 to 2.4 it is Poor <br>
When rating is 2.5 to 3.4 it is Average<br>
When rating is 3.5 to 3.9 it is Good<br>
When rating is 4.0 to 4.4 it is Very Good<br>
When rating is 4.5 to 4.9 it is Excellent<br>



![aggregate_rating](https://user-images.githubusercontent.com/67755812/202264003-ba444b56-6da7-4d4a-a248-070efd2f349c.png)

Not Rated count is Very High as we can see in blue.<br>
Maximum number of ratings are between 2.5 to 4.1<br>

![ratings](https://user-images.githubusercontent.com/67755812/202264752-2a12d993-dc0d-48ba-9372-563082741735.png)


Top 5 StateWise Zomato users<br>
![pie](https://user-images.githubusercontent.com/67755812/202264276-1c399168-ce1f-45af-a376-7562ba712ed0.png)

Top 10 Cuisines <br>
![cuisines](https://user-images.githubusercontent.com/67755812/202264657-e622170f-cf6b-43db-a508-91b8145f6483.png)



