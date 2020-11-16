# Study_materials
This repository includes a Dialogflow agent named "Studyagent.zip" and Annex A that describe the intents that this agent contains:

## Annex A-Description of intents: 

| Intent           |Description of intents |Required slots  | 
|:-------------:|:-----:|:-----:|
| ReserveRoundtripFlights |Search for round-trip flights to the destination of choice and  return a set of available offers |-	originLocation <br/> -	destinationLocation <br/> -	departureDate <br/> -	returnDate <br/> -	number of travelers | 
| SearchHotel |Search for hotels and return a set of available offers.| -	CheckInDate <br/> -	CheckoutDate <br/> -	City| 
| ReserveCar |Reserve a car  and return a confirmation message| -	pickup_city <br/> -	pickup_date <br/> -	pickup_time <br/> -	dropoff_date|
| GetWeather  |provides current conditions and forecasts for a given location| - Location | -	Weather description |
| SearchBusiness |returns details about a restaurants:  restaurant name , phone number , address, Business id| - type of food <br/> - location|
| BookTaxi | book a taxi to a destination of choice|-	dropoffAddress <br/> -	pickupAddress <br/> -	pickupDate <br/> -	pickupTime|
| SearchCinema | Search for cinemas in a given location|-	Location | 
| MakePayment | Send money to friends| -	amount <br/> -	receiver|
| SendMsg |Send a message to friends| -	Message <br/> -	Recipient| 

## Video: 
This [video](https://drive.google.com/file/d/1cfa-wo8EINSpELaEHMZ2wv9xkQ5H9ZWx/view?usp=sharing) demonstrates the steps to create an agent, restore from exiting one, and share it with us by entreing this email "brabra.hayeet@gmail.com" and add us as Reviewer. 

