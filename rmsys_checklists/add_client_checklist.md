# Add Client Checklist

| ID | Description | Status | Comments |
|----|-------------|--------|----------|
| 1 | Client tab> Add client |  |  |
| 1.1 | Verify clicking "Add" button opens the "New Client" window |  |  |
| 1.2 | Verify system allows adding a new client to the system database |  |  |
| 1.3 | Verify newly added client is displayed in the "Client List" after successful save |  |  |
| 2 | Client tab> Add client > "New Client" window |  |  |
| 2.1 | Verify "New Client" window can be opened |  |  |
| 2.2 | Verify window contains the following elements: "Name" field, "Start Date" field, "End Date" field, Inactive "Project" tab, Inactive "Contact" tab, "Inactive Info" tab, "Save" button, "Cancel" button, "Close" button |  |  |
| 3 | Client tab> Add client > Name field |  |  |
| 3.1 | Verify Name field is required |  |  |
| 3.2 | Verify lowercase letters (a–z) are accepted |  |  |
| 3.3 | Verify uppercase letters (A–Z) are accepted |  |  |
| 3.4 | Verify digits (0–9) are accepted |  |  |
| 3.5 | Verify Name field accepts mixed case letters and digits (e.g., Client123) |  |  |
| 3.6 | Verify special characters (e.g., @, #, !) are rejected |  |  |
| 3.7 | Verify input with 1 character is accepted |  |  |
| 3.8 | Verify input with exactly 50 characters is accepted |  |  |
| 3.9 | Verify input with 51 characters is rejected |  |  |
| 3.10 | Verify error message is displayed if Name field is empty |  |  |
| 3.11 | Verify red error icon appears near Name field in case of validation error |  |  |
| 3.12 | Verify pop-up message appears when hovering over error icon |  |  |
| 3.13 | Verify copy-paste input with valid characters is accepted (e.g., Client123) |  |  |
| 3.14 | Verify error icon disappears after entering a valid Name value |  |  |
| 4 | Client tab> Add client > Start Date field |  |  |
| 4.1 | Verify Start Date field is optional |  |  |
| 4.2 | Verify manual entry in format mm/dd/yyyy is accepted |  |  |
| 4.3 | Verify wrong format (dd/mm/yyyy, yyyy-mm-dd) is rejected |  |  |
| 4.4 | Verify letters or symbols are rejected |  |  |
| 4.5 | Verify non-existent dates are rejected |  |  |
| 4.6 | Verify calendar icon opens calendar widget |  |  |
| 4.7 | Verify valid date selection works correctly |  |  |
| 4.8 | Verify invalid calendar date selection is impossible |  |  |
| 4.9 | Verify red error icon appears on invalid format |  |  |
| 4.10 | Verify error message "Start Date is not correct format" is displayed |  | Based on screenshot: "Start Date is not correct format" |
| 4.11 | Verify tooltip appears on hover over error icon |  |  |
| 4.12 | Verify pasting invalid format triggers validation |  |  |
| 4.13 | Verify clearing field does not trigger error |  |  |
| 4.14 | Verify only digits and "/" allowed |  |  |
| 4.15 | Verify calendar auto-fills mm/dd/yyyy format |  |  |
| 5 | Client tab> Add client > End Date field |  |  |
| 5.1 | Verify End Date field is optional |  |  |
| 5.2 | Verify correct format mm/dd/yyyy is accepted |  |  |
| 5.3 | Verify wrong format is rejected |  |  |
| 5.4 | Verify letters/symbols are rejected |  |  |
| 5.5 | Verify invalid dates are rejected |  |  |
| 5.6 | Verify calendar icon opens widget |  |  |
| 5.7 | Verify valid date selection works correctly |  |  |
| 5.8 | Verify invalid calendar selection is impossible |  |  |
| 5.9 | Verify red error icon appears on invalid input |  |  |
| 5.10 | Verify error message "End Date is not correct format" is displayed | | Validation behavior assumed similar to Start Date based on format requirement. |
| 5.11 | Verify tooltip appears on hover |  |  |
| 5.12 | Verify paste validation works |  |  |
| 5.13 | Verify clearing field does not trigger error |  |  |
| 5.14 | Verify only digits and "/" allowed |  |  |
| 5.15 | Verify calendar auto-fills mm/dd/yyyy format |  |  |
| 6 | Client tab> Add client > Project tab |  |  |
| 6.1 | Verify "Inactive Project" tab is displayed |  |  |
| 6.2 | Verify "Inactive Project" tab is disabled |  |  |
| 7 | Client tab> Add client > Contact tab |  |  |
| 7.1 | Verify "Inactive Contact" tab is displayed |  |  |
| 7.2 | Verify "Inactive Contact" tab is disabled |  |  |
| 8 | Client tab> Add client > Info tab |  |  |
| 8.1 | Verify "Inactive Info" tab is displayed |  |  |
| 8.2 | Verify "Inactive Info" tab is disabled |  |  |
| 9 | Client tab> Add client > Save button |  |  |
| 9.1 | Verify "Save" button is displayed |  |  |
| 9.2 | Verify clicking Save triggers validation |  |  |
| 9.3 | Verify data is saved after validation |  |  |
| 9.4 | Verify window closes after successful save |  |  |
| 9.5 | Verify client appears in Client List |  |  |
| 9.6 | Verify saved data matches input |  |  |
| 9.7 | Verify validation triggers for invalid fields |  |  |
| 9.8 | Verify red error icons appear for errors |  |  |
| 9.9 | Verify error icons only appear for invalid fields |  |  |
| 9.10 | Verify no save if validation fails |  |  |
| 9.11 | Verify window remains open if validation fails |  |  |
| 9.12 | Verify tooltip appears on error hover |  |  |
| 9.13 | Verify tooltip contains fix instructions |  |  |
| 9.14 | Verify tooltip matches field error |  |  |
| 9.15 | Verify error icon disappears after fix |  |  |
| 9.16 | Verify save succeeds after correction |  |  |
| 9.17 | Verify no duplicate clients on multiple clicks |  |  |
| 10 | Client tab> Add client > Cancel button |  |  |
| 10.1 | Verify Cancel button is displayed |  |  |
| 10.2 | Verify Cancel button is clickable |  |  |
| 10.3 | Verify hover/click behavior |  |  |
| 10.4 | Verify Cancel works with empty fields |  |  |
| 10.5 | Verify Cancel works with filled fields |  |  |
| 10.6 | Verify Cancel closes window |  |  |
| 10.7 | Verify no data is saved |  |  |
| 10.8 | Verify no client is added |  |  |
| 11 | Client tab> Add client > Close button |  |  |
| 11.1 | Verify Close button is displayed |  |  |
| 11.2 | Verify Close button is clickable |  |  |
| 11.3 | Verify Close button is top-right positioned |  |  |
| 11.4 | Verify Close works with empty fields |  |  |
| 11.5 | Verify Close works with filled fields |  |  |
| 11.6 | Verify Close closes window |  |  |
| 11.7 | Verify no data is saved |  |  |
| 11.8 | Verify no client is added |  |  |
