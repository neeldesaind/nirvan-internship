# News API - Web Application

## Overview

The **News API** web application displays the latest news articles fetched from the [NewsData.io API](https://newsdata.io/). It allows users to view articles related to various topics from different sources. The app dynamically loads the news content and displays it in an organized format, providing a brief summary along with a link to the full article.

## Features

- **Fetch Latest News**: Displays the latest news articles from the U.S.
- **Article Details**: Each article includes a title, description (if available), and the source of the news.
- **External Links**: Users can click on the article titles to open the full article in a new tab.
- **Error Handling**: Displays an error message if the API request fails or if no articles are available.

## Tech Stack

- **HTML**: Provides the structure for the webpage.
- **CSS**: Styles the news container and individual news items.
- **JavaScript**: Handles fetching news data from the NewsData.io API and dynamically displaying it on the page.
- **XMLHttpRequest**: Used to make an asynchronous request to the NewsData.io API.

## Installation

1. Clone or download the repository.
2. Replace the `apiKey` variable in the `script` tag with your own NewsData.io API key. You can sign up for an API key on the [NewsData.io website](https://newsdata.io/).
3. Open the `index.html` file in a browser to view the application.

## Usage

When the page loads, the latest news articles from the U.S. are displayed. Each article shows its title, description (if available), and source information. Users can click on the title of any article to view the full article on the source website.

## Screenshots
![image](https://github.com/user-attachments/assets/cd9604ed-c5d0-48c2-b70f-8226f5e7708b)

## API Integration

This app uses the [NewsData.io API](https://newsdata.io/) to fetch the latest news. The API key is required to access the service.

### API Endpoint:
https://newsdata.io/api/1/news?apikey=YOUR_API_KEY&country=us


Replace `YOUR_API_KEY` with your actual API key.

## Contributing

Feel free to fork the repository and contribute to improving the app. If you encounter any bugs or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is open-source and available under the [MIT License](https://github.com/neeldesaind/news-api/blob/main/LICENSE).
