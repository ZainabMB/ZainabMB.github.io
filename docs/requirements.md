# Requirements

## User Needs

### User stories
user stories capture the needs and wants of my user base
* find the longest or shortest cycling routes
* search routes by name 
* searching routes that intersect with selected route
* view all in  map
* most difficult routes
* find routes that take the longest or shortest time
* view particular route types 


### Actors
* driver

### Use Cases


| UC1| UC1: Finding journey links by name | 
| -------------------------------------- | ------------------- |
| **Description** | As a driver i want to find journey links by name. |
| **Actors** | Drivers|
| **Assumptions** | Browser supports geo-location |
| **Steps** | <ol> <li> Choose to view table of journey links</li><li> select filter list</li><li> choose to filter by name </li><li> choose from ID link number</li><li>display list accordingly</li></ol>
| **Variations** | The browser does not support geo-location: use bristol city centre as default location |
| **Non-functional** | It should display the journey link ID according to the user's selection |
| **Issues** | TODO: OPTIONAL - List of issues that remain to be resolved |

| UC2| UC2: Finding journey links closest to the driver's location | 
| -------------------------------------- | ------------------- |
| **Description** | As a driver i want to find journey links closest to my location. |
| **Actors** | Drivers|
| **Assumptions** | Browser supports geo-location |
| **Steps** | <ol> <li> Choose to view table of journey links</li><li> select filter list</li><li> choose to filter closest to location </li><li> choose from closest to location</li><li>display list accordingly</li></ol>
| **Variations** | The browser does not support geo-location: use bristol city centre as default location |
| **Non-functional** | It should display up to 10 of the nearest cameras on one page |
| **Issues** | TODO: OPTIONAL - List of issues that remain to be resolved |

| UC3| UC3: Selecting journey links and finding closest cameras for the selected link | 
| -------------------------------------- | ------------------- |
| **Description** | As a driver i want to select journey links and find the closest cameras for the selected link. |
| **Actors** | Drivers|
| **Assumptions** | Browser supports geo-location |
| **Steps** | <ol> <li> Choose to view table of closest cameras for the selected link </li><li> select filter list</li><li> choose to filter by closest cameras for the selected link </li><li> choose from closest cameras for the selected link</li><li>display list accordingly</li></ol>
| **Variations** | The browser does not support geo-location: use bristol city centre as default location |
| **Non-functional** | It should display all of the cameras closest to the selected journey link |
| **Issues** | TODO: OPTIONAL - List of issues that remain to be resolved |

| UC4| UC4: Finding every camera on the driver's journey | 
| -------------------------------------- | ------------------- |
| **Description** | As a driver i want to find every camera on my journey. |
| **Actors** | Drivers|
| **Assumptions** | Browser supports geo-location |
| **Steps** | <ol> <li> Choose to view table of every camera</li><li> select filter list</li><li> choose to filter by  </li><li> choose from </li><li>display list accordingly</li></ol>
| **Variations** | The browser does not support geo-location: use bristol city centre as default location |
| **Non-functional** | It should display all the cameras on the driver's selected journey |
| **Issues** | TODO: OPTIONAL - List of issues that remain to be resolved |

| UC5| UC5: Filtering journey links by KPI Priority | 
| -------------------------------------- | ------------------- |
| **Description** | As a driver i want to filter journey links by KPI Priority . |
| **Actors** | Drivers|
| **Assumptions** | Browser supports geo-location |
| **Steps** | <ol> <li> Choose to view table of journey links</li><li> select filter list</li><li> choose to filter by KPI Priority </li><li> choose from KPI Priority</li><li>display list accordingly</li></ol>
| **Variations** | The browser does not support geo-location: use bristol city centre as default location |
| **Non-functional** | It should display all the journey links that have KPI Priority|
| **Issues** | TODO: OPTIONAL - List of issues that remain to be resolved |

| UC6| UC6: Filtering journey links by journey start direction  | 
| -------------------------------------- | ------------------- |
| **Description** | As a driver i want to find journey links by journey start direction. |
| **Actors** | Drivers|
| **Assumptions** | Browser supports geo-location |
| **Steps** | <ol> <li> Choose to view table of journey links</li><li> select filter list</li><li> choose to filter by start direction</li><li> choose from start direction type</li><li>display list accordingly</li></ol>
| **Variations** | The browser does not support geo-location: use bristol city centre as default location |
| **Non-functional** | It should display all the jorney links according to the chosen journey start direction type  |
| **Issues** | TODO: OPTIONAL - List of issues that remain to be resolved |



TODO: Your Use-Case diagram should include all use-cases.

![UseCase Diagram0](https://github.com/ZainabMB/ZainabMB.github.io/assets/148768903/a5ed772a-521d-49fd-b99e-9f93eb281bff)

## Software Requirements Specification
### Functional requirements
TODO: create a list of functional requirements. 
    e.g. "The system shall ..."
    Give each functional requirement a unique ID. e.g. FR1, FR2, ...
    Indicate which UC the requirement comes from.


### Non-Functional Requirements
TODO: Consider one or more [quality attributes](https://en.wikipedia.org/wiki/ISO/IEC_9126) to suggest a small number of non-functional requirements.
Give each non-functional requirement a unique ID. e.g. NFR1, NFR2, ...

Indicate which UC the requirement comes from.

