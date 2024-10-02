# IITB-Assignment
I have read all the instructions properly and therefore did not use any framework so I managed to make the UI in a single HTML file but I have used basic bootstrap component for some styling. All the Javascript and CSS in in the HTML file only. 
It does not look exaclty the same but it performs all the functions which were mentioned in the document. I have tried to make it look as similar as possible to the original image provided. I have used emoticons as buttion icons.
I have also deployed it as a web page using Vercel (Cloud platform to deploy frontends). I have not used any other library or other third party stuff for deployment. I have just cloned my original repositery and used it in vercel for deployment purpose. 
Link for deployed page - https://deployementiitbassignment.vercel.app/

Bootstrap Component: (CDN) Used for styling the table (edit functionality).
Each column header is clickable to sort the data in ascending order.
Load Data: The loadTableData() function dynamically loads the table rows from the data array.
Function sortTable(columnIndex) is responsible for sorting the table rows based on the column index.
Editing: Click the Edit button to open a modal and update the row data.
Dynamic Table Data: The chemicalData array holds all the initial chemical data, which is then dynamically loaded into the table on page load.
Add/Delete Rows: The user can add new rows with blank data or delete the selected row.
Sorting Columns: Clicking on a column header sorts the data in ascending or descending order. The sorting toggles each time a header is clicked.
Save Data: The save functionality currently logs the updated data to the console only as it has no backend or API calls.
Row Selection: Added a selectRow function that allows users to select a row by clicking on it. The selected row will be highlighted. If the same row is clicked again, it will deselect.
Moving Rows: The moveUp and moveDown functions correctly swap the selected row with the row above or below it.
