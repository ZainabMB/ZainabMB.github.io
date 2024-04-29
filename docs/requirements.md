# Requirements

## User Needs
Users require a convenient way to find nearby community toilets.
### User stories
- As a user, I want to search for community toilets by name.
- As a user, I want to find community toilets closest to my location.
- As a user, I want to select a community toilet and find other nearby toilets.
- As a user, I want to find all toilets along my journey.
- As a user, I want to filter community toilets based on specific criteria.
- As a user, I want to find toilets based on the direction of my journey.


### Actors
* user

### Use Cases


| UC1| UC1: Finding Community Toilets by Name| 
| -------------------------------------- | ------------------- |
| **Description** | As a driver, I want to find community toilets by name.|
| **Actors** | Users|
| **Assumptions** | No assumptions |
| **Steps** | <ol> <li> Click on the search bar</li><li>Type in the name of the community toilet</li><li>Select the desired community toilet from the search results</li></ol> |
| **Variations** |<ol><li>If the community toilet does not exist,</li><li>display "Community toilet not found."</li></ol> |
| **Non-functional** |<ol><li>NFR1: The search bar or icon must be visible at all times (usability)</li><li>NFR2: List of community toilets should be narrowed down with every letter typed in (Performance efficiency)</li><li>NFR3: List should always be in alphabetical order(Usability)</li></ol> |
| **Issues** |No Issues |

| UC2| UC2: Finding journey links closest to the driver's location | 
| -------------------------------------- | ------------------- |
| **Description** | As a driver i want to find journey links closest to my location. |
| **Actors** | Drivers|
| **Assumptions** | Browser supports geo-location |
| **Steps** | <ol> <li> Choose to view journey links in map</li><li>Choose to find journey links nearest to the user's location</li><li> Request permission to use location </li><li>Display Journey link nearest to user's location</li></ol>
| **Variations** | The browser does not support geo-location: use bristol city centre as default location |
| **Non-functional** |<ol><li> NFR1: Locaion is only accessed if user grants permisiion (security)</li><li>NFR1: show the 5 nearest jouney links to the user's location or the default location on the map(Usability)</li></ol> |
| **Issues** |No Issues |

| UC3| UC3: Selecting journey links and finding closest cameras for the selected link | 
| -------------------------------------- | ------------------- |
| **Description** | As a driver i want to select journey links and find the closest cameras for the selected link. |
| **Actors** | Drivers|
| **Assumptions** | Browser supports geo-location |
| **Steps** | <ol> <li> Choose to view Journey Links in a table</li><li> select a journey link</li><li>choose option to show other journey links close to the selected one </li><li>Display nearest Journey links to the selected journey link</li></ol>
| **Variations** |No variations|
| **Non-functional** | <ol><li> NFR1: List should be displayed in alphabetical order at all times(Efficiency)</li> NFR2: display only the three closest journey links (Usability)</li></ol>|
| **Issues** | No Issues |

| UC4| UC4: Finding every camera on the driver's journey | 
| -------------------------------------- | ------------------- |
| **Description** | As a driver i want to find every camera on my journey. |
| **Actors** | Drivers|
| **Assumptions** | Browser supports geo-location |
| **Steps** | <ol> <li>View journey links on map</li><li>Request to access user's location and use as start point</li><li>Request user's destination</li><li>Display the shortest route to destination</li><li>Display all the ANPR on the journey</li></ol>
| **Variations** | The browser does not support geo-location: choose Bristol city centre as start point|
| **Non-functional** |<ol><li>NFR1: Automatically choose the shortest route to the destination (Usability)</li><li>NFR2: NFR2: Display ANPR points visibly on the map (Usablity)</li></ol> |
| **Issues** | Can't display or create journies yet|

| UC5| UC5: Filtering journey links by KPI Priority | 
| -------------------------------------- | ------------------- |
| **Description** | As a driver i want to filter journey links by KPI Priority . |
| **Actors** | Drivers|
| **Assumptions** | Browser supports geo-location |
| **Steps** | <ol> <li> Choose to view table of journey links</li><li> select filter list</li><li> choose to filter by KPI Priority </li><li> choose from KPI Priority</li><li>display list accordingly</li></ol>
| **Variations** | <ol><li> Choose to view map of journey links</li><li> Turn on KPI priority</li><li> Display KPI priority on map</li></ol> |
| **Non-functional** |<ol><li> NFR1: KPI priority only has two choices 'yes' or 'no'(Efficiency)</li><li>NFR2: Once the button is turned on, the two KPI priority types should be easily distinguishable on the map using different colours</li></ol> |
| **Issues** | No Issues |

| UC6| UC6: Filtering journey links by journey start direction  | 
| -------------------------------------- | ------------------- |
| **Description** | As a driver i want to find journey links by journey start direction. |
| **Actors** | Drivers|
| **Assumptions** | No Assumptions |
| **Steps** | <ol> <li> Choose to view table of journey links</li><li> select filter list</li><li> choose to filter by start direction</li><li> choose from start direction type</li><li>display list accordingly</li></ol>
| **Variations** | No Variations|
| **Non-functional** |<ol><li> NFR1: List should be displayed in alphabetical order at all times(Efficiency) </li> </ol>  |
| **Issues** | No issues  |



TODO: Your Use-Case diagram should include all use-cases.

![JOURNEY LINKS](https://github.com/ZainabMB/ZainabMB.github.io/assets/148768903/047af72d-2d26-485a-9abe-7853bf8bd24a)

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


