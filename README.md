# Boston Top Earners Display

This project displays the top 5 earners from the Boston dataset, with their names and salaries. The data is imported from an external JavaScript file (`boston.js`), and the top earners are dynamically displayed in the HTML `div` element with the `id="app"`.

## Features

- **Data Filtering**: Extracts employees with salaries under 20 million from the dataset.
- **Sorting**: Sorts the employees by their salaries in descending order.
- **Top 5 Earners**: Only the top 5 highest earners are selected and displayed.
- **Dynamic Content**: The list of top earners is dynamically added to the webpage using JavaScript.

## Code Breakdown

### External JavaScript (Boston Data)

The data is imported from the `boston.js` file, which contains an object with employee information. The salary information is located in the 12th column of each employee's data entry.

