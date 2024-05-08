# Testing

## Test Plan
TODO: Describe any manual and automated (unit) tests. Uniquely identify each test case. Include prerequisites and test data.

Test Runs
| Test case ID | Test type | Description | Scenario | Status |
|--------------|-----------|-------------|----------|--------|
| TF1.1        | UAT       | Searching for community toilets | User clicks on the search bar. User types the desired community toilet. | Pass  |
| TF1.2       | UAT       | Finding community toilets closest to user location | User clicks "Find on Map". User grants permission. User clicks on "Find nearest toilet". User grants permission. Toilets closest to user's location or bristol city centre appear | pass  |
| TF1.3      | UAT       | Markers added to the map for each community toilet | User clicks "Find on Map". User grants permission. Map shows markers for each community toilet in the area. |  pass |
| TF1.4     | UAT       | Finding community toilets with changing places | User clicks "changing place". User views community toilets with or without changing place |  pass |
| TF1.5    | UAT       | Finding community toilets with Family toilets | User clicks "family toilets". User views community toilets with or without family toilets |  pass |
| TF1.6    | UAT       | Finding community toilets by wards | User clicks "find by wards". User views community toilets by wards |  pass |
| TF1.7    | UAT       | Finding community toilets with Baby change | User clicks "Baby change". User views community toilets with or without a Baby change |  pass |
| TNF1.1     | UAT       | Defaults to Bristol City Centre | User clicks "Find on Map". User denies permission. Map centred on Bristol City Centre. |   |
| TNF1.5a      | UAT       | The app should respond to the user within 5 seconds | User clicks "Find on Map". Map appears within 5 seconds. |   |
| TNF1.5b      | UAT       | The app should respond to the user within 5 seconds | User clicks "Find by Type". Table appears within 5 seconds. |   |
| TNF1.6       | UAT       | The app should work on Chrome and Safari browsers | Perform all tests on Chrome / Safari. |    |
| TNF1.8       | UAT       | The data should be up-to-date; less than one year old | Confirm last update on community toilets dataset. |   |
Create a requirements traceability matrix to validate the completeness of the product.

| Use-Case ID | Requirement ID | Software Module| Test Case  | Status |
| ----------- | -------------- | -------------- |  --------- | ------ |
| UC1         | FR1.1          |                |  TF1.1     |        |
| UC1         | FR1.3          |                |  TF1.3     |        |
| UC1         | FR1.4          |                |  TF1.4     |        |
| UC1         | NFR1.1         |                |  TNF1.1    |        |
| UC1         | NFR1.5         |                |  TNF1.5a   |        |
| UC2         | NFR1.5         |                |   TNF1.5b  |        |
| UC1         | NFR1.6         |                |  TNF1.6    |        |
| UC1         | NFR1.8         |                |  TNF1.8    |        |
TODO: Add rows for each test, current status is eg. pass/fail
