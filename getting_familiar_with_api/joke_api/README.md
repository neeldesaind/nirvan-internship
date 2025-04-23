# Random Joke - Web Application

## Overview

The **Random Joke** web application fetches and displays random programming-related jokes using the [JokeAPI](https://v2.jokeapi.dev/). It provides users with a simple interface to view jokes and get new jokes with a button click. The app uses JavaScript to make API requests and displays the jokes in a styled container.

## Features

- **Random Joke Generator**: Displays a random joke from the JokeAPI.
- **Programming and Miscellaneous Jokes**: Fetches jokes related to programming and other categories.
- **Error Handling**: Provides user-friendly error messages if the joke fails to load or if there is an issue with the network.
- **Button to Fetch New Joke**: A button that allows the user to get a new joke when clicked.

## Tech Stack

- **HTML**: Structure of the webpage.
- **CSS**: Styling for a simple and clean user interface.
- **JavaScript**: Handles fetching jokes from the JokeAPI and dynamically updating the page.
- **XMLHttpRequest**: Used to make asynchronous requests to the JokeAPI.

## Installation

1. Clone or download the repository.
2. Open the `random_joke_generator.html` file in a browser to start the application.

## Usage

When the page loads, a random joke is displayed. The user can click the **"Get Another Joke"** button to fetch a new joke.

## Screenshots

![image](https://github.com/user-attachments/assets/af492dcd-8c44-492f-a4e4-41f10bf98192)



## API Integration

This app uses the [JokeAPI](https://v2.jokeapi.dev/) to fetch jokes. The request URL includes the programming and miscellaneous categories while excluding inappropriate content like nsfw, racist, sexist, and explicit jokes.

### API Endpoint:
https://v2.jokeapi.dev/joke/Programming,Miscellaneous?blacklistFlags=nsfw,racist,sexist,explicit


## Contributing

Feel free to fork the repository and improve the app. If you find bugs or issues, please open an issue in the GitHub repository.

## License

This project is open-source and available under the [MIT License](https://github.com/neeldesaind/Joke-Api/blob/main/LICENSE).
