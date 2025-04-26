# Vibe-Recommender

Discover new things based on your current interests. Vibe-Recommender is a simple, single-page web application that takes three items you provide (like bands, foods, movies, etc.), analyzes their common characteristics using the Gemini API, and suggests three alternative items that align with your vibe.

## Features

* Intuitive Form: Easily input three items.
* AI-Powered Analysis: Uses the Gemini API for suggestions.
* Personalized Suggestions: Get recommendations based on your input.
* Single-Page App: Clean and modern interface with Bootstrap.
* Responsive Design: Works on various screen sizes.
* API Key Instructions: Guidance on getting a free key included.

## Getting Started

You need a modern web browser and a Gemini API key.

### Obtaining a Gemini API Key

Get a free key from Google AI Studio: <https://aistudio.google.com/>

**Security Warning:** Embedding API keys in client-side code is **not secure for production**. Use a backend for production.

### Installation and Running

1.  Get the `index.html` file.
2.  Open `index.html` in your browser.

For local development (to avoid CORS issues), run a simple web server:

* **Python:** `python -m http.server` (then go to `http://localhost:8000`)
* **Node.js:** `npm install -g serve` then `serve` (then go to the provided address)

### How to Use

1.  Open the app.
2.  Enter your Gemini API Key.
3.  Enter Three Items (e.g., "Jazz Music", "Italian Food", "Noir Films").
4.  Click "Analyze and Suggest".
5.  View the results and suggestions.

## Technologies Used

* HTML5
* CSS3
* JavaScript
* Bootstrap 5
* Google Gemini API

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

* Built with Bootstrap.
* Powered by the Google Gemini API.
