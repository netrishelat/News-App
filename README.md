# News App

This is a simple News App that fetches and displays news articles using the News API. Users can search for news articles by entering a query in the search bar.

## Project Structure

```
News-App-main/
    News App/
        index.html
        script.js
        style.css
```

## Files

- `index.html`: The main HTML file that contains the structure of the web page.
- `script.js`: The JavaScript file that handles fetching news articles and updating the DOM.
- `style.css`: The CSS file that styles the web page.

## Features

- Fetches and displays top headlines from the News API.
- Allows users to search for news articles by entering a query.
- Displays news articles in a card format with images, titles, and descriptions.
- Clicking on a news article opens the full article in a new tab.

## Setup

1. Clone the repository to your local machine.
2. Open the `News App` folder.
3. Open `index.html` in your web browser.

## Usage

1. Open the app in your web browser.
2. The app will display the top headlines by default.
3. To search for news articles, enter a query in the search bar and click the "Search" button.
4. The app will display the search results in the form of news cards.

## API Key

To use the News API, you need to obtain an API key from [News API](https://newsapi.org/). Once you have the API key, add it to the `script.js` file:

```js
const apiKey = 'YOUR_API_KEY_HERE';
```

## License

This project is licensed under the MIT License.
