# Testing

## Test Plan
TODO: Describe any manual and automated (unit) tests. Uniquely identify each test case. Include prerequisites and test data.

Test Runs
| Test case ID | Test type | Description | Scenario | Status |
|--------------|-----------|-------------|----------|--------|
| TF1.1        | UAT       | Requests permission to access user location | User clicks "Find on Map". Confirmation box appears, requesting permission. |   |
| TF1.3        | UAT       | Map centred on user location | User clicks "Find on Map". User grants permission. Map appears centred on user location. |   |
| TF1.4        | UAT       | Markers added to the map for each community toilet | User clicks "Find on Map". User grants permission. Map shows markers for each community toilet in the area. |   |
| TNF1.1       | UAT       | Defaults to Bristol City Centre | User clicks "Find on Map". User denies permission. Map centred on Bristol City Centre. |   |
| TNF1.5a      | UAT       | The app should respond to the user within 5 seconds | User clicks "Find on Map". Map appears within 5 seconds. |   |
| TNF1.5b      | UAT       | The app should respond to the user within 5 seconds | User clicks "Find by Type". Table appears within 5 seconds. |   |
| TNF1.6       | UAT       | The app should work on Chrome and Safari browsers | Perform all tests on Chrome / Safari. |    |
| TNF1.8       | UAT       | The data should be up-to-date; less than one year old | Confirm last update on community toilets dataset. |   |
Create a requirements traceability matrix to validate the completeness of the product.

| Use-Case ID | Requirement ID | Test Case | Status |
| ----------- | -------------- | --------- | ------ |

TODO: Add rows for each test, current status is eg. pass/fail
