# Projects
*** Author: Vikram Bhaktha
    Date: 05/26/2025
    Description: Price Tracker for Flights
***    

Need to create an app that stores the desired max amount a user would be willing to purchase a ticket at. The app will systematically track the price fluctuations and notify the user that the ticket has reached a price point that they would be comfortable purchasing it at.

Users can choose what vacation they can afford with focus centered around a buget.

// target is Plane tickets, cruise tickets, rental cars, hotel accomodations, and any permutations that will yeild an ideal trip. 
// Idea is that we wont simply look at the airport nearest to us, we will systematically offer up airports within a drivable distance as well. 
// So that users wont have to compare prices searching individually.
// Need to include hotels as well
// Potentially may need to include cruises as well




REQs:

1. We will need a way to have a list of all airport locations and air line carriers.
2. Guest will pick a region of the world that they would like to explore or a region of the US that they would like to experience.
3. We will need a way to then store the user's desired destinations and desired budget.
4. If the cheapest fares are unavailible via nearest airport, we will need to factor in a driving cost calculator.
5. Parking will def be a factor if it is cheaper than an uber.
6. Factor in Tolls (will need to consider if user has Toll Pass vs Toll By Plate)
7. We will need a way to then search websites for the current price of the tickets
8. We will need a way to dynamically compare the current price vs the target price
9. If CP <= TP then notify the user that the ticket has reached the desired price
10. Store trip info and res details in one area so that users do not have to track across multiple apps.
11. If buget is not sufficient, calculate what minimum buget should be for targeted.
12. Need to consider if user is travelling in a group or solo. 
