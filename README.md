
# ParkEasy

Group members:

-   Michał Michalski
    
-   Marcin Michalak
    
-   Sławomir Mendyka
    
-   Wojciech Michalak
    

  

## Introduction
    

ParkEasy is a user-friendly online platform that simplifies the process of finding and booking parking spots. This service is ideal for drivers seeking a stress-free parking experience in urban centers, shopping malls, and near large events. It is also tailored for property managers who aim to maximize the efficiency and profitability of their parking facilities.

What It Does:

-   For Drivers: Enables drivers to search for and book parking spots in advance, showing real-time availability of spaces. It provides options for online payment to facilitate easy transactions.
    
-   For Property Managers: Allows property managers to manage their parking inventory effectively, ensuring that spaces are efficiently utilized and accessible to drivers.
    

Who It’s For:

-   Drivers looking for a hassle-free way to secure parking in busy areas.
    
-   Property Managers want to fill up their parking spaces and manage them better.
    

Goals and Benefits:

-   For Drivers: Save time and reduce stress by booking parking spots ahead of time.
    
-   For Property Managers: Make more money from parking spaces and improve how these spaces are used.


## User interface design  
The user interface design for ParkEasy has been crafted using Figma, ensuring a visually appealing and user-friendly experience for both drivers and property managers. The mockups encompass all critical user stories, providing comprehensive views and interactions for the main functionalities of the platform.

The mockups cover the following key screens and functionalities:

1.  Home Page: The home page, allowing users to quickly access the primary functions of the platform.
    
2.  Search Results Page: This screen displays a list of available parking spots based on the user’s search criteria.
    

  

3.  Parking Spot Details Page: Users can view detailed information about a selected parking spot, including pricing and availability.
    
4.  Booking Page: A streamlined process for booking a parking spot, including date and time selection and payment options.
    
5.  User Account Page: Users can manage their profiles, view past bookings, and access past transactions information.
    
6.  Property Manager Dashboard: This section allows property managers to oversee and manage their parking lots, including setting and adjusting rates, creating promotional codes, and assigning moderators.  
      
    

  
  
Mockups published at URL: [https://www.figma.com/design/Lt24mHhvhvak6C14ONXyDo/ParkEasy?m=auto&t=5TVOHQ8BGTd8D8nm-6](https://www.figma.com/design/Lt24mHhvhvak6C14ONXyDo/ParkEasy?m=auto&t=5TVOHQ8BGTd8D8nm-6)

  

## System implementation

Here's a breakdown of the technology stack and tools we used to bring ParkEasy to life:

Programming Languages:

-   C#: We used C# for the backend, taking advantage of the .NET framework's capabilities to handle server-side logic, data processing, and integration with other services.
    
-   JavaScript: The frontend is primarily built using JavaScript (React as framework), which helps us create dynamic and responsive user interfaces.
    

Frameworks and Libraries:

-   ASP.NET Core: This is our backbone for the web application. It provides a solid foundation for building web apps and APIs, ensuring everything runs smoothly on the server side.
    
-   Entity Framework Core: This library helps us interact with the database in a more intuitive way, simplifying the process of querying and saving data.
    
-   React: On the frontend, React allows us to build reusable components and manage the user interface efficiently.
    
-   React Router: For navigating between pages in our single-page application, ensuring smooth transitions and a better user experience.
    

  
  

Testing:

-   xUnit: We use xUnit for testing the backend in C#. xUnit provides a rich set of testing features and is well-suited for our needs.
    
-   React Testing Library and Jest: For the frontend, we use React Testing Library along with Jest. These tools help us ensure that our components and overall user interface work as expected, providing robust testing capabilities for our React-based frontend.
    

Comments:

While we have made some progress on the ParkEasy platform, there are many features that have not been implemented yet but are planned for future development:

-   Database - LiteSQL: We chose LiteSQL for its simplicity and efficiency, which fits our needs perfectly. It handles our data storage and querying with ease.
    

-   Hosting and Deployment - Microsoft Azure: Although our documentation includes plans for hosting on Microsoft Azure to benefit from its reliability, scalability, and array of services (such as Azure SQL Database and Azure App Service), this has not been implemented yet.
    
-   Payment Integration - Przelewy24: The integration for handling payments, which would allow users to book parking spots and pay online securely, is also not implemented yet but is documented for future inclusion.
    
-   Internationalization: While we have basic support for English, we're working on fully localizing all UI elements and text for the Polish language.
    

- TypeScript: As a future plan, we intend to use TypeScript to add static typing to our JavaScript code. This will help catch errors early and make the codebase more maintainable.
