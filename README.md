# Sales Summary Test Web App

## Summary
This static web application fetches data from a CSV file, calculates the total sales amount, and displays it on a single-page site. It utilizes Bootstrap 5 from jsdelivr for styling.

## Setup
To deploy the application on GitHub Pages, follow these steps:
1. Create a new repository on GitHub.
2. Commit your HTML, CSS, JavaScript files, and the `data.csv` to the main branch.
3. Go to the repository settings.
4. Scroll down to the GitHub Pages section.
5. Choose the main branch as the source.
6. Your site will be published at: `https://<your-username>.github.io/<repository-name>`

## Usage
- Access the page by visiting the published GitHub Pages URL.
- No query parameters or configuration options are needed.
- Key Features:
  - Fetches data from `data.csv`.
  - Calculates the total sales.
  - Displays the total sales amount in the `#total-sales` element.

## Code Explanation
The app consists of an HTML file that fetches the CSV data, a JavaScript file for processing the data, and optionally includes Bootstrap 5 for styling. Key points:
- Uses `fetch` API to get `data.csv` asynchronously.
- Parses the CSV file to calculate the sum of the sales column.
- Updates the DOM to display the total sales amount.

**Libraries Used:**
- Bootstrap 5 from jsdelivr

**License:** MIT License.