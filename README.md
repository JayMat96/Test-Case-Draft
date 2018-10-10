# Test-Case-Draft

## Requirements Covered

#### Test Case ID:
01

#### Test Case Name:
Database Connection Requirements

#### Component:
The database used for PLEX's "build mode." Handles all the connectivity with the database. It also fetches and returns query results. 

#### Test Game Designer:
Jade

#### Creation Date:
12/2008

#### Modified By:
Jalen Mojica

#### Modified Date:
10/09/2018

#### Requirements Covered:
* Database should only work in "build mode"
* Players must be able to connect to the database
* Return query results in string format
* Return query results in an integer/boolean format

#### Test Description/Purpose:
* Online is not necssary in "story mode" so the database should be active in "build mode" only
* Must be able to connect to the database so players can play with each other in "build mode"
* Must be able to return a string result from a query
* Must be able to return an integer result from a query

#### Pre-Test Conditions:
* At least 5 consoles/computers running PLEX
* At least 5 testers
* A room big enough for the testers and their testing systems
* A playable version of PLEX


## Requirements Covered

#### Test Case ID:
03

#### Test Case Name:
Menu Driver Requirements

#### Component:
Menu Driver that is in charge of all of PLEX's menu screens

#### Test Game Designer:
Jade

#### Creation Date:
12/2008

#### Modified By:
Jalen Mojica

#### Modified Date:
10/09/2018

#### Requirements Covered:
* Loading the appropriate menu when asked
* Keeping track of where the selector is

#### Test Description/Purpose:
* To ensure that the game will always bring up the correct menu at the correct time
* The game and the player both know what option is being selected at all times

#### Pre-Test Conditions:
* A computer/console to run PLEX on
* At least one tester (can be developer)
* All needed menus added into PLEX
* A way to open up menus in PLEX
