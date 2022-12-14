# CMS-VT | ADV | Symfony - Validation

## Overview
You are tasked with providing basic functionality for validation, to help editors preventing errors when creating new data entries.

## User Story 1
*As an EDITOR for application data, I want to have input I make automatically validated, so that I am assisted in providing correct information.*

### Acceptance Criteria
- At least one field is checked for length (min 1 character)
- At least one field is checked for a datetime (e.g.: plausible birthday or date in the future)
- At least one number is checked for being a number (e.g.: double, int)
- Editors get clear visual feedback on errors and/or restrictions in the user interface or as data in the response of their request when performing operations.

## User Story 2
*As an EDITOR for application data, I want to ensure that a certain field only accepts values where each letter occurs 2 times. (e.g.: AB is invalid, AABB is valid)*

### Acceptance Criteria
- A custom validator has been implemented
- The custom validator is used to check a field of choice on the server side
- Editors get clear visual feedback on errors and/or restrictions in the user interface or as data in the response of their request when performing operations.

#### Links
https://my.skilldisplay.eu/en/skillset/122
