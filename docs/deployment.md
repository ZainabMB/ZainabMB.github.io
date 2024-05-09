# Deployment

## Release Notes
### Version 1.0

#### System Overview
This release marks the initial version of the community toilets app. It is built using  HTML, CSS, JavaScript.

#### System Dependencies
-HTML
-CSS
-JavaScript

#### Known Issues

- The data from the Bristol Open Data API may not be up to date.
- Some toilet locations may lack facility information.
  



<img width="1440" alt="Screenshot 2024-05-09 at 11 26 16" src="https://github.com/ZainabMB/ZainabMB.github.io/assets/148768903/918c88a9-a9cc-46e1-a0c1-004839cb5ae4">

# User guide
UC1: Finding community toilets by Name

Description:
As a user, you want to search for community toilets by name.

Steps:
Click on the search bar.
Type in the name of the community toilet.
Select the desired community toilet from the search results.

Variations:
If the community toilet does not exist, display "Community toilet not found."

Non-functional:
NFR1: The search bar or icon must be visible at all times (usability).
NFR2: List of community toilets could be narrowed down with every letter typed in (Performance efficiency).
NFR3: List could always be in alphabetical order (Usability).
NFR4: The app should respond to the user within 5 seconds (Efficiency).
NFR5: The app should work on Chrome and Safari browsers.

Issues:
Entire name has to be entered to get result. Cannot display in alphabetical order.
<img width="1440" alt="Screenshot 2024-05-09 at 11 40 07" src="https://github.com/ZainabMB/ZainabMB.github.io/assets/148768903/88b94416-f686-4aa5-914d-2ea196ce9614">
<img width="1440" alt="Screenshot 2024-05-09 at 11 40 20" src="https://github.com/ZainabMB/ZainabMB.github.io/assets/148768903/6920b593-ff59-4074-8fb7-5e0e6efa5218">




UC2: Finding community toilets closest to the user's location

Description:
As a user, you want to find community toilets closest to your location.

Steps:
Choose to view community toilets in map.
Select the option to find community toilets nearest to my location.
Request permission to use location.
Display community toilets nearest to user's location.

Variations:
If the browser does not support geo-location: use Bristol city centre as the default location.

Non-functional:
NFR1: Location is only accessed if the user grants permission (security).
<img width="1440" alt="Screenshot 2024-05-09 at 11 34 49" src="https://github.com/ZainabMB/ZainabMB.github.io/assets/148768903/eb856435-1665-4dc9-9d15-183f9838705e">



UC3: Viewing all community toilets on the map

Description:
As a user, you want to view all community toilets on your map.

Steps:
Choose to view community toilets on map.
Display all the community toilets in Bristol.

Variations:
No variations.

Non-functional:
NFR1: Each marker should be visible (Usability).
NFR2: Display the name of the community toilet after clicking the marker (Usability).
<img width="1440" alt="Screenshot 2024-05-09 at 11 42 18" src="https://github.com/ZainabMB/ZainabMB.github.io/assets/148768903/e54b5531-cdfd-424c-bab0-94062ec61687">





UC4: Finding community toilets with changing places

Description:
As a user, you want to find community toilets with changing places.

Steps:
View community toilets on table.
Click on changing place.
Click on YES.
Display all the community toilets with changing places.

Variations:
Click on NO: Display all the community toilets without changing places.

Non-functional:
NFR1: The buttons should be visible and distinguishable (Usability).
NFR2: Desired criteria only has two choices 'yes' or 'no' (Efficiency).

<img width="1440" alt="Screenshot 2024-05-09 at 11 32 46" src="https://github.com/ZainabMB/ZainabMB.github.io/assets/148768903/d5186e2f-a643-49d9-b4a6-2655c513e587">



UC5: Filtering community toilets by wards

Description:
As a user, you want to filter community toilets based on the wards.

Steps:
Choose to view table of community toilets.
Select the filter wards.
Choose the ward to filter from.
Display the filtered list accordingly.

Variations:
Choose to view map of community toilets.
Turn on the desired criteria chosen.
Display the desired criteria on the map.

Non-functional:
NFR1: Buttons for different wards should be distinguishable (Usability).
NFR2: All toilets from the specific ward will be displayed (Efficiency).

<img width="1440" alt="Screenshot 2024-05-09 at 11 32 31" src="https://github.com/ZainabMB/ZainabMB.github.io/assets/148768903/45789a62-3503-4ba0-aacd-8b6f4287d7ee">



UC6: Filtering community toilets by Family Toilets

Description:
As a user, you want to find community toilets that have family toilets.

Steps:
Choose to view a table of community toilets.
Select the filter family toilets.
Click on YES.
Display community toilets with family toilets.

Variations:
Click on NO: Display community toilets without family toilets.

Non-functional:
NFR1: The buttons should be easily read and distinguished (Usability).
NFR2: Desired criteria only has two choices 'yes' or 'no' (Efficiency).
<img width="1440" alt="Screenshot 2024-05-09 at 11 32 38" src="https://github.com/ZainabMB/ZainabMB.github.io/assets/148768903/3e903bf1-6fe3-42c9-9d2e-e5a0b3031971">




UC7: Filtering community toilets by Baby change

Description:
As a user, you want to find community toilets with a baby change.

Steps:
Choose to view a table of community toilets.
Select the filter Baby change.
Click on YES.
Display community toilets with Baby change.

Variations:
Click on NO: Display community toilets without Baby change.

Non-functional:
NFR1: The buttons should be easily read and distinguished (Usability).
NFR2: Desired criteria only has two choices 'yes' or 'no' (Efficiency).

<img width="1440" alt="Screenshot 2024-05-09 at 11 32 56" src="https://github.com/ZainabMB/ZainabMB.github.io/assets/148768903/b7c50b25-0d56-47cb-8434-74433e59a6e2">





