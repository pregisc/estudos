# Test Cases: Travel Plan

Priority: **High** = blocks the main use of the app · **Medium** = important, has a workaround · **Low** = cosmetic.

## Login

| ID | Title | Steps | Expected result | Priority | Automated |
| --- | --- | --- | --- | --- | --- |
| TC-LOG-01 | Login with valid credentials | 1. Open the login page 2. Enter a valid email and password 3. Click "Login" | User is redirected to the home page and sees their name | High | Planned |
| TC-LOG-02 | Login with wrong password | 1. Open the login page 2. Enter a valid email and a wrong password 3. Click "Login" | An error message is shown and the user stays on the login page | High | Planned |
| TC-LOG-03 | Login with empty fields | 1. Open the login page 2. Leave email and password empty 3. Click "Login" | Required field messages are shown | Medium | Planned |
| TC-LOG-04 | Logout | 1. Log in 2. Click "Logout" | User returns to the login page and cannot access private pages | High | Planned |

## Create a new route

| ID | Title | Steps | Expected result | Priority | Automated |
| --- | --- | --- | --- | --- | --- |
| TC-RTE-01 | Create a route with origin and destination | 1. Log in 2. Click "New route" 3. Enter origin and destination 4. Save | The route is saved and appears in the user's routes | High | Planned |
| TC-RTE-02 | Add a stop to a route | 1. Open a saved route 2. Add a point of interest as a stop 3. Save | The stop appears in the route, in the right order | High | Planned |
| TC-RTE-03 | Create a route without destination | 1. Click "New route" 2. Enter only the origin 3. Save | A message asks for the destination and the route is not saved | Medium | Planned |
| TC-RTE-04 | Delete a route | 1. Open a saved route 2. Click "Delete" 3. Confirm | The route no longer appears in the user's routes | Medium | Planned |

## Explore the map

| ID | Title | Steps | Expected result | Priority | Automated |
| --- | --- | --- | --- | --- | --- |
| TC-MAP-01 | Map loads with points of interest | 1. Open the map | The map loads and shows points of interest in the visible area | High | Planned |
| TC-MAP-02 | Open a point of interest | 1. Open the map 2. Click a point | A card shows name, location, phone number and social media links | High | Planned |
| TC-MAP-03 | Search for a place | 1. Open the map 2. Type a city name in the search 3. Select a result | The map moves to the selected city | Medium | Planned |
| TC-MAP-04 | Filter by category | 1. Open the map 2. Select a category filter | Only points of that category are shown | Medium | Planned |
