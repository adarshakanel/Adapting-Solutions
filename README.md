# Group-9: Adapting-Solutions

Group members: Harprabh Gill, Ahad Hamirani, Manjot Khangura, Jiaxin Guo, Adarsha Kanel

## How to run the code
1. Please ensure you have Visual Studio 2022 downloaded for Windows 10 or Visual Studio 2022 Beta for MacOS. The following instructions assume the Windows 10 version. 
2. Open up the Blazor project by navigating in Visual Studio by going to File > Open > Project/Solution and open `BlazorApp1.sln` located in `BlazorApp1\BlazorApp1.sln`. 
3. To run the application please hit the green play button which should bring up a webpage running at https://localhost:7289/. 

## Relevant file structure
/BlazorApp1.Client 
|__
    /wwwroot
    |__
        contains images for our pages
    /Pages
    |__
        Appointment.razor
            Appointment.razor.css
        Compare.razor
            Compare.razor.css
        Favourites.razor
            Favourites.razor.css
        Homepage.razor
            Homepage.razor.css
        Mortgage.razor
            Mortgage.razor.css
        Price_Results.razor
        PropertyDetail.razor
            PropertyDetail.razor.css
        PropertyDetail1.razor
            PropertyDetail1.razor.css
        PropertyDetail2.razor
            PropertyDetail2.razor.css
        PropertyDetail3.razor
            PropertyDetail3.razor.css
        PropertyDetail4.razor
            PropertyDetail3.razor.css
        PropertyDetail5.razor
            PropertyDetail3.razor.css
        PropertyDetail6.razor
            PropertyDetail3.razor.css
        PropertyMortgage.razor
            PropertyDetail3.razor.css
        Search_Results2.razor
            PropertyDetail3.razor.css
        SearchResults.razor
        Sort_Search_Results.razor
        TrackedListings.razor
            TrackedListings.razor.css
        Tracking.razor
    /Shared
    |__
        MainLayout.razor
        NavMenu.razor
            NavMenu.razor.css

## Cases/functions implemented
1. Property details
   a. Property description
   b. Schedule viewings
   c. Booking appointments with realtor
   e. Integrated mortgage calculator
   f. Map of nearby amentities
   g. Tracking listing
   h. Favourite properties
   i. Track neighbourhood
2. Homepage
   a. Icons for different property type, search type by clicking on icon
   b. Featured properties
3. Search page
   a. Filter options by property categorty, location price and square ft
   b. Search bar
   c. Sorting by price, relevance, square ft and date listed
   e. Compare function to compare properties
4. Appointments
   a. View/cancel upcoming appointments
5. Favourites
   a. View/remove favourited properties
6. Track neightbourhoods
   a. View trends in the neighbourhood
   b. Retains active filters to show results of those filters within the neighbourhood
7. Login
   a. login, signup, logout

## Walkthrough instructions
1. Navigate to `Homepage`
2. Click `Duplex`
3. Search `Calgary`
4. Sort `Price (High to Low)`
5. Remove `Location: Calgary` from active filters
6. Click on first, second and fifth `Compare` button
7. Click `Compare Properties`
8. Click `View this listing` of the third property
9. On the property details page, you may enter in information to book an appoinment and also enter in numeric values to calculate mortgage
10. You can also click on the maps to see the nearby amentities
11. Click `Track Neighbourhood` to view the trackings page




