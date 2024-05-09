# Requirements

## User Needs
Users require a convenient way to find nearby community toilets.
### User stories
- As a user, I want to search for community toilets by name.
- As a user, I want to find community toilets closest to my location.
- As a user, I want to view all community toilets on my map.
- As a user, I want to find community toilets with changing places.
- As a user, I want to filter community toilets based on the wards.
- As a user, I want to find community toilets that have family toilets.
- As a user, I want to find community toilets with a baby change. 


### Actors
*Users
### Functional Requirements 
<li>FR1.1: The system should get user location from navigator.geolocation</li><li>FR1.2: The system must query the database for Community toilets locations from Open Data Bristol </li><li>FR1.3:The system must add markers for each Community Toilet</li><li>FR1.4: The system should find nearest toilets to user</li><li>FR2.1: The sytem must query the database for wards with community toilets</li><li>FR3.1: The system must query the database of community toilets with changing places, baby change, and family toilets</li>

### Use Cases


| UC1| UC1: Finding community toilets by Name| 
| -------------------------------------- | ------------------- |
| **Description** | As a user, I want to search for community toilets by name.|
| **Actors** | Users|
| **Assumptions** | No assumptions |
| **Steps** | <ol> <li> Click on the search bar</li><li>Type in the name of the community toilet</li><li>Select the desired community toilet from the search results</li></ol> |
| **Variations** |<ol><li>If the community toilet does not exist,</li><li>display "Community toilet not found."</li></ol> |
| **Non-functional** |<ol><li>NFR1: The search bar or icon must be visible at all times (usability)</li><li>NFR2: List of community toilets could be narrowed down with every letter typed in (Performance efficiency)</li><li>NFR3: List could always be in alphabetical order(Usability)</li><li>NFR4:The app should respond to the user within 5 seconds(Efficiency)</li><li>NFR5: The app should work on Chrome and Safari browsers</li></ol> |
| **Issues** |Entire name has to be entered to get result. Cannot display in alphabetical order |

| UC2| UC2: Finding community toilets closest to the user's location | 
| -------------------------------------- | ------------------- |
| **Description** | As a user i want to find community toilets closest to my location. |
| **Actors** | Users|
| **Assumptions** | Browser supports geo-location |
| **Steps** | <ol> <li> Choose to view community toilets in map</li><li>Select the option to find community toilets nearest to my location</li><li> Request permission to use location </li><li>Display community toilets nearest to user's location</li></ol>
| **Variations** | If the browser does not support geo-location: use Bristol city centre as the default location |
| **Non-functional** |<ol><li> NFR1: Location is only accessed if the user grants permission (security)</li></ol> |
| **Issues** |No Issues |

| UC3| UC3: Viewing all community toilets on the map | 
| -------------------------------------- | ------------------- |
| **Description** | As a user, I want to view all community toilets on my map. |
| **Actors** | Users|
| **Assumptions** | Browser supports geo-location |
| **Steps** | <ol> <li> Choose to view community toilets on map</li><li>Display all the community toilets in Bristol.</li></ol>
| **Variations** |No variations |
| **Non-functional** | <ol><li> NFR1: Each marker should be visible(Usability)</li><li> NFR2: Display the name of the community toilet after clicking the marker (Usability)</li></ol>|
| **Issues** | No Issues |

| UC4| UC4: Finding community toilets with changing places | 
| -------------------------------------- | ------------------- |
| **Description** | As a user, I want to find community toilets with changing places. |
| **Actors** | Users |
| **Assumptions** | No assumptions |
| **Steps** | <ol> <li>View community toilets on table</li><li>click on changing place</li><li>click on YES</li><li>Display all the community toilets with changing places</li></ol>
| **Variations** |<ol><li>click on NO</li><li>Display all the community toilets without changing places</li></ol>|
| **Non-functional** |<ol><li>NFR1: The buttons should be visible and distinguishable (Usability)</li>><li> NFR2: Desired criteria only has two choices 'yes' or 'no'(Efficiency)</li></ol> |
| **Issues** | No Issues|

| UC5| UC5: Filtering community toilets by wards | 
| -------------------------------------- | ------------------- |
| **Description** | As a user, I want to filter community toilets based on the wards. |
| **Actors** | Users |
| **Assumptions** | Browser supports geo-location |
| **Steps** | <ol> <li> Choose to view table of community toilets</li><li> Select the filter wards</li><li> Choose the ward to filter from</li><li>display the filtered list accordingly</li></ol>
| **Variations** | <ol><li> Choose to view map of community toilets</li><li> Turn on the desired criteria chosen</li><li> Display the desired criteria on the map</li></ol> |
| **Non-functional** |<ol><li> NFR1: Buttons for different wards should be distinguishable (usability)</li><li>NFR2: All toilets from the specific ward will be displayed(Efficiency)</li></ol> |
| **Issues** | There are too many wards to display all individually so only the ones with a certain number of toilets were used. |

| UC6| UC6: Filtering community toilets by Family Toilets| 
| -------------------------------------- | ------------------- |
| **Description** | As a user, I want to find community toilets that have family toilets. |
| **Actors** | Users |
| **Assumptions** | No Assumptions |
| **Steps** | <ol> <li> Choose to view a table of community toilets</li><li> select the filter family toilets</li><li>Click on YES</li><li>Display community toilets with family toilets</li></ol>
| **Variations** |<ol><li>Click on NO</li><li>Display community toilets without family toilets</li></ol>|
| **Non-functional** |<ol><li> NFR1: The buttons should be easily read and distinguished(Usability) </li> <li> NFR2: Desired criteria only has two choices 'yes' or 'no'(Efficiency)</li></ol>  |
| **Issues** | No issues|

| UC7| UC7: Filtering community toilets by Baby change| 
| -------------------------------------- | ------------------- |
| **Description** | As a user, I want to find community toilets with a baby change.  |
| **Actors** | Users |
| **Assumptions** | No Assumptions |
| **Steps** | <ol> <li> Choose to view a table of community toilets</li><li> select the filter Baby change</li><li>Click on YES</li><li>Display community toilets with Baby change</li></ol>
| **Variations** |<ol><li>Click on NO</li><li>Display community toilets without Baby change</li></ol>|
| **Non-functional** |<ol><li> NFR1: The buttons should be easily read and distinguished(Usability) </li> <li> NFR2: Desired criteria only has two choices 'yes' or 'no'(Efficiency)</li></ol>  |
| **Issues** | No issues|

![Mindmap 2](https://github.com/ZainabMB/ZainabMB.github.io/assets/148769002/7c6c41c5-2357-4a5d-8ce2-6619432697c2)


## Software Requirements Specification
### Functional requirements
Functional requirements:

<ol><li>FR1.1 The system should obtain permission to access the user's location via geolocation services.</li><li>FR1.2 The system should retrieve toilet locations from the community toilet database.</li><li>FR1.3 The system should display the map centered on the user's location.</li></ol> FR1.4 The system should place markers on the map for each community toilet location.</li><li>
  
### Non-Functional Requirements
Nonfunctional Requirements:

<ol><li>NFR1.1: The search bar or icon must be visible at all times (usability)</li><li>NFR2.2: List of community toilets should be narrowed down with every letter typed in (Performance efficiency)</li><li>NFR3.3: List should always be in alphabetical order(Usability)</li></ol> 
<ol><li> NFR4.4: Location is only accessed if the user grants permission (security)</li><li>NFR5.5: Show the 5 nearest community toilets to the user's location or the default location on the map(Usability)</li></ol>  <ol><li> NFR6.6: Each marker should be visible(Usability)</li><li> NFR7.7: Display the name of the community toilet after clicking the marker (Usability)</li></ol> <ol><li>NFR8.8: The buttons should be visible and distinguishable (Usability)</li>><li> NFR9.9: Desired criteria only has two choices 'yes' or 'no'(Efficiency)</li></ol> <ol><li> NFR10.10: Buttons for different wards should be distinguishable (usability)</li><li>NFR11.11: All toilets from the specific ward will be displayed(Efficiency)</li></ol> <ol><li> NFR12.12: The buttons should be easily read and distinguished(Usability) </li> <li> NFR13.13: Desired criteria only has two choices 'yes' or 'no'(Efficiency)</li></ol> <ol><li> NFR14.14: The buttons should be easily read and distinguished(Usability) </li> <li> NFR15.15: Desired criteria only has two choices 'yes' or 'no'(Efficiency)</li></ol> 



