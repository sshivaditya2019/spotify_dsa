# Song Recommender System

This is a song recommender system for a website that uses abstract data types, such as priority queue and doubly linked list, and the Spotify API to recommend music tracks to users based on their preferences, history, and context. The system is developed using HTML, CSS, and JavaScript and is integrated into a website that provides music streaming and discovery services.

## Prerequisites

Before you start using the song recommender system, you need to have the following:

- A Spotify account and a Spotify developer account. You can create a Spotify account and a developer account for free at [https://www.spotify.com/](https://www.spotify.com/) and [https://developer.spotify.com/](https://developer.spotify.com/), respectively.

- A Spotify application. You can create a Spotify application by following these steps:
  1. Log in to your Spotify developer account.
  2. Go to the [My Applications](https://developer.spotify.com/dashboard/applications) page.
  3. Click on the "Create an App" button.
  4. Fill in the required information, such as the name and description of the app, and agree to the terms and conditions.
  5. Click on the "Create" button.

- A website that integrates with the song recommender system. You can use the provided HTML, CSS, and JavaScript files as a starting point for your website.

## Configuration

To configure the song recommender system, you need to add your Spotify application's client ID, client secret, and redirect URI to the appropriate locations in the code. You can find these values in the "Edit Settings" page of your Spotify application.

1. Open the index.html file in a text editor.
2. Look for the following line of code:


```
const CLIENT_ID = '';
const CLIENT_SECRET = '';
const REDIRECT_URI = '';
```

3. Replace the empty strings with your Spotify application's client ID, client secret, and redirect URI, respectively.
4. Save the file.

## Usage
To use the song recommender system, you need to do the following:

1. Open the website that integrates with the song recommender system in a web browser.
2. Click on the "Sign in with Spotify" button.
3. Follow the prompts to authorize the song recommender system to access your Spotify account.
4. Once you are signed in, you can start using the song recommender system by playing the songs.
5. The song recommender system will use your preferences and history to recommend relevant and personalized songs to you.

## Troubleshooting
If you encounter any issues or errors while using the song recommender system, you can try the following:

1. Make sure that you have followed the prerequisites and configuration steps correctly.
2. Check the console log of your web browser for any error messages or warnings.
3. Check the [Spotify Developer]([https://developer.spotify.com/]) Documentation for any updates or changes to the API or the authentication process.
4. Contact the developer of the song recommender system for further assistance.

## Contact
If you have any questions or suggestions about the song recommender system, you can contact the developer by raising an issue.