# Testing

## Test Plan
TODO: Describe any manual and automated (unit) tests. Uniquely identify each test case. Include prerequisites and test data.

###Test Runs
| Test case ID | Test type | Description | Scenario | Status |
|--------------|-----------|-------------|----------|--------|
| TF1.1        | UAT       | The system should get user location from navigator.geolocation | User clicks "Find on Map".Confirmation box appears, requesting permission. | Pass  |
| TF1.2       | UAT       | The system must query the database for Community toilets locations from Open Data Bristol  | User clicks "view map on table". All community toilets must display. | pass  |
| TF1.3      | UAT       | The system must add markers for each Community Toilet | User clicks "Find on Map". User grants permission. Map shows markers for each community toilet. |  pass |
| TF1.4      | UAT       | The system should find nearest toilets to user | User clicks "Find on Map" then "find nearest toilets". User grants permission. Table shows nearest toilets. |  pass |
| TF3.1    | UAT       | Finding community toilets with changing places, family toilets, and baby change. | User clicks on the button for the specific one. User views community toilets with or without the chosen one|  pass |
| TF2.1   | UAT       | Finding community toilets by wards | User clicks "find by wards". User views community toilets by wards |  pass |
| TNF3.1    | UAT       | Defaults to Bristol City Centre | User clicks "Find nearest toilet". User denies permission. Table should default to Bristol City Centre. |  pass |
| TNF1.4a      | UAT       | The app should respond to the user within 5 seconds | User clicks "Find on Map". Map appears within 5 seconds. |  pass |
| TNF1.4b      | UAT       | The app should respond to the user within 5 seconds | User clicks "Find by Type". Table appears within 5 seconds. | pass  |
| TNF1.5       | UAT       | The app should work on Chrome and Safari browsers | Perform all tests on Chrome / Safari. |  pass  |
| TNF3.2      | UAT       |  Display the name of the community toilet after clicking the marker |  The names of each community toilet should be attached |    pass |

###Requirements Traceability Matrix
| Use-Case ID | Requirement ID | Software Module| Test Case  | Status |
| ----------- | -------------- | -------------- |  --------- | ------ |
| UC1         | FR1.1          |   map.html     |  TF1.1     |    pass    |
| UC1         | FR1.2          |  index2.html   |  TF1.2     |      pass  |
| UC1         | FR1.3         |     map.html       |  TF1.3 |      pass  |
| UC1         | FR1.4         |  distance.html |  TF1.4     |   pass  |
| UC2         | FR2.1       |     type.html      |  TF2.1     |  pass   |
| UC3         | FR3.1   | Baby.html changing.html family.html      |  TF3.1     |  pass      |
| UC3         | NFR3.1         |    distance            |  TNF3.1   |  pass      |
| UC1         | NFR1.4a        |       map.html         |  TNF1.4a   | pass       |
| UC1         | NFR1.4b         |   index2.html    |   TNF1.4b  |    pass    |
| UC1         | NFR1.5         |    ALL          |  TNF1.5   |     pass   |
| UC3         | NFR3.2        |    map.html     |  TNF3.2   |  pass      |

