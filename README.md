# AngularJS Recruitment task

## Requirements

1. Add Bootstrap 3 and AngularStrap libraries to the application  
2. Using Typeahead control from AngularStrap bind countryList to Typeahead, so users can search 
and choose country (form model value of this input should be Country code not name)
3. Create custom directive and wrap latitude and longitude inputs with it. 
Directive should prevent users from entering incorrect latitude/longitude values.  
4. Style the form so it looks like typical Bootstrap 3 form.
5. Clicking on "+ Add new destination" button should add new destination object to the destinations array
6. Destinations should be displayed in a table under "Destinations" header with columns: 'Country', 'Latitude', 'Longitude' and 'Actions'
7. Add 'Remove' button in Actions column for removing given rows from the table.
8. Place this application on your github account
9. Add possibility to edit table row in modal window (use AngularStrap modal)
10. (optional) Use local storage for storing table data
11. (optional) Add column for bulk operations with a checkbox for each row. 
Column header should have checkbox to select/deselect all rows. 
After selecting at least one row, button 'Remove destinations' should appear somewhere above the table. 
After clicking on 'Remove destinations' button, selected rows should be removed. 

## Useful links

- [Bootstrap](https://getbootstrap.com/docs/3.3/)
- [AngularStrap](https://mgcrea.github.io/angular-strap/)
