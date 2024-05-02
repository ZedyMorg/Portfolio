# Pet project
Project I made for myself to improve my data analysis and coding skills


I started by generating a database for a fictional mechanic's shop. The code and description of how I generated the database is in the "Preparation" file.

I have created two dataframes :
  - Dataframe on users information
  - Dataframe on transactions information

Between 01-01-2022 and 01-07-2022, our theoretical mechanic's shop released a promotion where if you recommend someone, you and the person you recommened receive a free oil changes, maximum once per client. We want to perform analysis on the result of this promotion.

# Dataframe descriptions
## User Dataframe :
 - **customer_id** : 5000 unique id for each customer :
   - **String**
 - **date_registered** : 5000 random dates between 2021-01-01 and 2024-01-01 :
   - **DateTime**
 - **car_make** : 6 unique car make (Hyundai, Honda, Volkswagen, BMW, Volvo, Ford) assigned randomly to each customer, along with their possible model and year :
   - **String**
 - **car_model** : 27 unique car model corresponding to the car make :
   - **String**   
 - **car_year** : 8 possible year for each car :
   - **String**
 - **recommended_someone** : Information on either the customer recommended someone for the purpose of our test, either True or False :
   - **Boolean**
 - **is_recommended** : Information on either the customer was recommended by someone for the purpose of our test, either True or False :
   - **Boolean**

## Transaction Dataframe :

- **customer_id** : unique id of the cutomer who requested the service :
  - **String**
- **transaction_date** : Transaction date for each unique transaction :
  - **DateTime**
- **transaction_id** : Transaction ID for each transaction (random number of transaction based on the amount of customers) :
  - **String**
- **field_of_service** : The kind of service that was done on the vehicule (ex. brakes, suspension, AC/Heating, etc) :
  - **String**
- **service** : What exactly was done on the vehicule, related to the field of service (ex. -brakes- replacement, -suspension- strut, -suspension- control arm, etc) :
  - **String**
- **price_$** : The price paid by the customer for the full service, in CAD$ :
  - **Integer**


