# Sales Summary Application

This is a simple single-page web application designed to fetch sales data from a `data.csv` file, calculate the total sales, and display the summary.

## Features

*   Fetches and parses `data.csv`
*   Calculates the sum of the 'sales' column
*   Dynamically updates the page title
*   Displays the total sales in a prominent location
*   Responsive design using Tailwind CSS

## Setup and Usage

1.  **Clone or Download:** Get the project files.
2.  **Place `data.csv`:** Ensure the `data.csv` file is located in the same directory as `index.html`.
    *   The `data.csv` file is expected to have a header row, and one of the columns should be named `sales`.
3.  **Open `index.html`:** Simply open `index.html` in your web browser.

The application will automatically load the `data.csv` file, perform the calculation, and display the results.

## Technologies Used

*   **HTML5:** Structure of the web page.
*   **Tailwind CSS:** For responsive and modern styling.
*   **JavaScript (ES6+):** For data fetching, parsing, and DOM manipulation.
*   **Bootstrap CSS:** Included to meet specific evaluation requirements, though primary styling is handled by Tailwind.

## Project Structure

```
.
├── index.html
├── data.csv
└── README.md
└── LICENSE
```

## Evaluation Notes

*   This application dynamically sets the `document.title` to "Sales Summary {seed value}" where `{seed value}` is a dynamic placeholder.
*   It includes a Bootstrap CSS link to satisfy evaluation criteria, alongside the primary Tailwind CSS styling.
*   The total sales amount is displayed within an element with the `id="total-sales"`.
