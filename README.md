-1) Installations:

     No special installations are necessary, Jupiter Notebook 6.5.4 ist used.

-2) Motivation for the Two-Step Bed-Price Zipcode Model:

    This Project is part of my Udacity Data Scientist Nanodegree. I decided to use the Boston Project, 
    since I lived in Cambridge for a year during my university time.
    
    The idea was to find a price prediction for most (or representative) of the data presented by Airbnb
    and following the old Real-Estate Wisdom “Location, Location, Location”. 
    The result ist called Two-Step Bed-Price Zipcode Model.
    
-3) Conclusion:

    The result is called "Two-Step Bed-Price Zipcode Model". 
    The model data base is cleaned for outliers (high number of beds, very expensive ones) and low numbers in zip-areas.
    The Zipcode is used instead of the city name, 
    since the zipcode represents a smaller area based on postmen distribution and not on historical city names.
    In addition, the new parameter "Price per Bed" instead of the total price of the aparment (with a control parameter Beds per Bedrooms > 1) is defined.
    This combination is following the old Real-Estate Wisdom “Location, Location, Location” quite well and leads to a very good location decision.
    For an appropriate  price prediction the room- and apartment tye information is included in the model. 
    The problem of the wide apartment size (0 to 9 beds, splitted at 3 or 4 beds, since the price per bed decreases) is solved by a two-step model (small and large accommodations). 
    For more detailed infomation see
    https://medium.com/@emmerich.weissenbek/the-two-step-boston-bed-price-zip-code-model-de653085a954
  
-4) File description:
  
      The basic data used boston_listing.csv and the notebook Boston_two_step_bedprice_zipcode_model.ipynb are available here.

-5 ) Acknowledgements:
  
    Thanks to udacity and airbnb for the datasets used in this project.

-6 ) Licencing:
  
    No special licensing is necessary.


  

<!---
emmerich66/emmerich66 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
