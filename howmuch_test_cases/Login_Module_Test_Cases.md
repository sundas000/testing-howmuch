| Test Case ID   | Module           | Test Case Description                         | Expected Result                                   | Status   | Priority   | Notes                           |
|:---------------|:-----------------|:----------------------------------------------|:--------------------------------------------------|:---------|:-----------|:--------------------------------|
| LOGIN_TC_001   | Login Screen     | User enters the correct login ID and password | User should be logged in successfully             | Pass     | High       |                                 |
| LOGIN_TC_002   | Login Screen     | User enters wrong credentials                 | Error message should appear and deny access       | Pass     | High       |                                 |
| LOGIN_TC_003   | Logout           | User clicks logout button                     | User should be logged out and redirected to login | Pass     | High       |                                 |
| LOGIN_TC_004   | Save Credentials | User clicks “save credentials” option         | Login credentials should be saved securely        | Pass     | Medium     |                                 |
| LOGIN_TC_005   | Remember Me      | User clicks “remember me” option              | User session remains or ID is prefilled next time | Pass     | Medium     |                                 |
| LOGIN_TC_006   | Arabic           | User changes language to Arabic               | UI should update to Arabic correctly              | Pass     | Medium     | Initially failed in some builds |
