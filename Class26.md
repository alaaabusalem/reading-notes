# Intro to MVC

MVC stands for Model-View-Controller, and it is a software architectural pattern commonly used in the design and development of user interfaces and applications. The MVC pattern separates an application into three interconnected components, each with its own distinct responsibility:

1. Model:
The Model represents the application's data and business logic. It is responsible for managing the data, performing calculations, and enforcing business rules. The Model component abstracts the underlying data and provides an interface for the other components (View and Controller) to interact with it.

2. View:
The View represents the presentation and user interface of the application. It displays the data from the Model to the user and handles user interactions such as input and output. The View component is responsible for how the data is presented and does not contain the application's logic.

3. Controller:
The Controller acts as an intermediary between the Model and the View. It handles user input, processes requests, and updates the Model and View accordingly. The Controller component contains the application's logic and determines how the Model and View should interact with each other. It ensures that changes in the Model are reflected in the View and vice versa.

## Tag Helpers
Tag Helpers are a feature in ASP.NET Core, a popular web framework developed by Microsoft. They provide a way to create reusable components that simplify the process of generating HTML elements in Razor views. Razor is a view engine used in ASP.NET Core for creating dynamic web content.

In traditional ASP.NET MVC, developers often use HTML helpers to generate HTML elements and apply logic to them. However, HTML helpers can sometimes lead to less readable and maintainable code, especially when dealing with complex HTML structures or integrating client-side libraries. Tag Helpers were introduced in ASP.NET Core to address these issues.

## BootStrap
Bootstrap is a free, open source front-end development framework for the creation of websites and web apps. Designed to enable responsive development of mobile-first websites, Bootstrap provides a collection of syntax for template designs.