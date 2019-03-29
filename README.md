# JS-Coding-Challenge

### Please create an application that will display a filtered and ordered list of team members at a fictitious company.  Your new application will need to call an established REST API to get a complete listing of the company’s teams and their associated rosters. From the data returned by the REST API call, display the list of team members on the page according to the following criteria:
*   Only include members from teams located in the state of VA
* 	Only include members in either the “Technical Lead” or the “Software Engineer” role
* 	Sort by member last name (ascending) then by member first name (ascending)
* 	Concatenate the member first and last name values into a single full name value

**On the page:**
* 	Center the list of names horizontally on the page
* 	The list of names should smoothly fade in when added to the page
* 	The names should be displayed using a sans serif font with a default color of #6a6a6a
* 	When the cursor hovers over an individual name, that name should smoothly transition to #212121 and increase in size by about 20%         without causing the other names to shift their position.  When the cursor is no longer hovering over that name, that name should           smoothly transition back to its original color and size.

**Other requirements:**
* 	Create the new application with your choice of front-end framework (e.g. Angular.js, Angular, Vue.js, etc.).
* 	Use “vanilla” JavaScript to build the list of team members – do not leverage an external library such as or lodash.js.
* 	Upload all files and instructions for building the project (if necessary) to GitHub and provide a link to us for review.

### Extra Credit
* 	Write a unit test to verify the logic for building the list of team members.

## The REST API that you will use to get the team list is: https://h93rvy36y7.execute-api.us-east-1.amazonaws.com/teams

The teams request will return JSON in the following format:

``` 
   [
     {
       "name": "…",
       "city": "…",
       "state": "…",
       "members": [
         {
           "firstName": "…",
           "lastName": "…",
           "role": "…"
         }
       ]
     }
   ]
