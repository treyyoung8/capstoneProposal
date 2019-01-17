##Project proposal

MyGarage

##Project Description

Did you ever have a problem figuring out what type of oil your car needs? How much PSI your tires require? What type and length your windshield wipers are? This app is for you! This app will scan your vin number and pull information for all wearable parts for your convenience.

##Problem statement

It's a common problem in the real world and there are many types of wearable parts causing confusion to car owners. This app will give them a piece of mind, knowing that they are getting the right item for their vehicle.

##How will your project solve this problem?

The vin number will tell the app what make, model, and year the car is. The database will then provide the required information the user needs.

##Map the user experience

Scan the vin number onto your app. The app will pull the information of the vehicle. Choose which part you need to find more information on. For example, if you need to figure out the size of the tires or recomended PSI for the tires, you can choose tires category. Then the app will provide all information for tires, including the size and recomended PSI.

##What technologies do you plan to use?

Flutter for front end.
MongoDB/Express, Knex, SQL for back end.
Tesseract.js OCR for the ability to see a picture of vin number and convert the characters in the image to text.
Stretch: Python for language.
Possible API: Edmunds Vehicle API looks like a good start. It have Make, Model, Year, Style, Vin Decoding, maintenence schedules. Below is the link to the api further information.

https://edmundsapi-preprod.github.io/api-documentation/vehicle/#sec-4

I believe I would have to provide some seeds personally to add more information like part type, number, size, etc to provide neccessary information for the app. So, I will start small, using my car as a test model. I believe in the potential of this app and if a single car manufacture likes it and provide the neccessary api to extend the app to a full single car manufacture vehicles list. Then a 2nd manufacture sees it building popularity and provide their api, then it's a snowball effect after that. 