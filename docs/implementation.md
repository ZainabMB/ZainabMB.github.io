# Implementation

## Introduction
The community toilets app aims to provide a platform for users to find nearby community toilet facilities within the Bristol area. The app utilizes data obtained from the Bristol Open Data API, which includes information about toilet locations, name of the toilets, toilets with changing places, toilets based on wards, family toilets, toilets with baby change. It involves building a web application using  HTML, CSS, JavaScript.
### Known Issues
- The data from the Bristol Open Data API may not be up to date.
- Some toilet locations may lack facility information.
### Configuration Data
-
-

## Project Structure

### Folder Structure
- /docs: Contains all the HTML, CSS, and JavaScript files for the website.

### File Roles
</ol><li>Baby.html: This file contains information or features related to baby change facilities in the community toilets app.
</li><li>type.html: This file contains information or features related to filtering wards with community toilets
</li><li>style2.css: This CSS file provides styling for the HTML files in the /docs folder, including the home page, search page, map page, etc.
</li><li>search.html: This HTML file includes a search functionality for finding specific information or facilities related to community toilets.
</li><li>script.js: This JavaScript file provides interactivity and functionality to the HTML pages, such as handling user input, making API calls, or updating the DOM dynamically.
</li><li>map.html: This HTML file displays a map interface related to the website's content,showing the locations of toilets.
</li><li>homePage.html: This file is the homepage of the website, providing an overview or introduction to the community toilets app.
</li><li>family.html: This HTML file contains information or features specific to family-friendly facilities.
</li><li>distance.html: This file contains features or functionality related to calculating distances or finding nearby facilities.
</li><li>changing.html: This HTML file contains information or features related to changing places facilities.
</li><li>Index2.html: This file is an alternate or additional version of the homepage, containing variations or updates to the content.</li><ol>

### JSLint Reports
-
-
## Software Architecture
The software architecture consists of the following major components:

<img width="661" alt="Screenshot 2024-05-09 at 00 39 32" src="https://github.com/ZainabMB/ZainabMB.github.io/assets/148769002/8691ed9e-60b4-4b49-a590-a86420833a5c">

-Client: Represents the frontend HTML, CSS, and JavaScript responsible for user interaction.
-Bristol Open Data API: Provides data about toilet locations and facilities.
-Browser: Renders the HTML, CSS, and JavaScript to the user's browser.

## Bristol Open Data API
Query 1: Get All Toilet Locations

Endpoint: /api/toilets
Description: Retrieves a list of all toilet locations within the Bristol area.
Parameters: None
Query 2: Get Toilet Details

Endpoint: /api/toilets/:name
Description: Retrieves detailed information about a specific toilet location.
Parameters: id (Toilet name)

<img width="750" alt="Screenshot 2024-05-09 at 03 27 55" src="https://github.com/ZainabMB/ZainabMB.github.io/assets/148769002/e3dbfb7f-707d-4932-8945-36d5161138b3">

