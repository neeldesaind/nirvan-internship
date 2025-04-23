# Upcoming IPOs - Web Application

## Overview

This project is a simple web application that displays information about upcoming IPOs (Initial Public Offerings) using an external API. The application fetches IPO data from an API and displays it in a table format with columns for Symbol, Name, Status, SME (Small and Medium Enterprises), and Additional Info.

## Features

- Displays a list of upcoming IPOs.
- Fetches data from the [Indian Stock Exchange API](https://rapidapi.com/).
- Information displayed in a responsive table format.
- Each row contains details about a specific IPO, such as:
  - **Symbol**: The stock symbol of the IPO.
  - **Name**: The name of the company going public.
  - **Status**: The current status of the IPO (e.g., upcoming, active).
  - **SME**: Indicates whether the IPO is for a small or medium enterprise.
  - **Additional Info**: Extra information about the IPO (if available).

## Tech Stack

- **HTML5**: Markup for structuring the web page.
- **CSS3**: Styling to make the table visually appealing and responsive.
- **JavaScript**: Handles the logic for fetching and displaying the IPO data.
- **XMLHttpRequest**: Used for making asynchronous requests to the API.

## Installation

1. Clone or download the repository.
2. Open the `index.html` file in a browser.

## API Integration

This application fetches IPO data from the [Indian Stock Exchange API](https://rapidapi.com/). To use this API, you'll need an API key from [RapidAPI](https://rapidapi.com/).

### Setting Up API Key

1. Go to the [Indian Stock Exchange API](https://rapidapi.com/).
2. Sign up or log in to your RapidAPI account.
3. Subscribe to the **Indian Stock Exchange API** and get your API key.
4. Replace `"YOUR_X_RAPID_API_KEY"` in the `xhr.setRequestHeader("x-rapidapi-key", "YOUR_X_RAPID_API_KEY");` line in the script with your actual API key.

### ScreenShot
![image](https://github.com/user-attachments/assets/f6abfccf-8d6d-434a-b618-ac502bea8b59)

## Usage

- Upon loading the webpage, an AJAX request is made to fetch IPO data.
- If the request is successful and returns an array of IPOs, the data is displayed in a table.
- Each row of the table represents an upcoming IPO.

## Contributing

Feel free to fork this repository and make improvements. If you find any bugs or issues, please open an issue in the GitHub repository.

## License

This project is open-source and available under the [MIT License](https://github.com/neeldesaind/ipo-api/blob/main/LICENSE).
