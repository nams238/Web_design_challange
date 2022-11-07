# Web_design_challange

Web-Design-Challenge
The objective of the web-design homework is to create a website by using the visualizations that were created in the Python-API-Chalenge.

Bootstrap themes was used to customize some of the pages.

created individual pages for each plot and with a way to navigate between them. These pages contain the visualizations and des. It also has a landing page to provide a comparison of all the plots, along with another page to present the data used to build them.

Website Requirements The website consist of seven pages in total, including:

A landing page containing the following elements:

An explanation of the project

Links to each visualizations page. There should be a sidebar containing preview images of each plot. Clicking an image should take the user to that visualization.

Four visualization pages, stored in the visualizations folder, each with the following elements:

A descriptive title and heading tag.

The plot or visualization for the selected comparison (latitude vs: max temperature, humidity, cloudiness, or wind speed). The images displayed on these pages should be stored in the assets/images folder.

A paragraph describing the plot and its significance.

A "Comparisons" page that does the following:

Contains all of the visualizations on the same page so they can easily be compared with each other.

Uses a Bootstrap grid for the visualizations.

The grid is two visualizations across medium and large screens, and its one visualization across on extra-small or small screens.

A "Data" page displays a responsive table containing the data used in the visualizations.

The table is a Bootstrap table component.

The data come from exporting the .csv file as HTML or by converted it to HTML. Used Pandas method, appropriately called to_html, that allows one to generate an HTML table from a Pandas DataFrame. To learn more, review the documentation.

At the top of every page, the website have a navigation menu with the following elements:

Have the name of the site on the left of the navigation bar, allowing users to return to the landing page from any page.

It contain a dropdown menu on the right of the navigation bar, named "Plots," to provide links to each individual visualization page.

It provide two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.

Its a responsive (using media queries). The navigation bar is similar to the screenshots in the "Navigation Menu" section.