# bond-api-codespace
A repo to use as a PHP API James Bond Film Web Service CodeSpace
Use this to practice consuming a web service via a GitHub Page, etc.

## Getting Started

1. Fork this repo to your GitHub account.
2. Click the `Code` dropdown and choose `Open with Codespaces > New Codespace`.
3. Wait for Codespaces to initialize.
4. The PHP server will start automatically on port 3000.
5. Click the "Ports" tab in Codespaces and "Open in Browser".
6. View raw Release date sorted JSON data by providing the url >> api.php
7. View raw Box Office sorted JSON data by providing the url >> api.php?cat=box

Now you're ready to consume a web service using a JS enabled web page!

## Using your web service on a different server

In order to use your web service from a different server, such as from a GitHub page, in your Codespace, look for the "Ports" tab in the bottom panel.

On the right-hand side, under the "Visibility" column, if it says "Private", click the dropdown and choose "Public".

## What's Included

- PHP 8.2 (via Docker)
- Built-in server on port 3000
- Forwarded port for testing
- PHP API to be consumed as a web service

# Bond API Client

A web client for browsing James Bond films using a PHP API web service. This client fetches and displays Bond film data, allowing sorting by release date or box office.

## Features
- Fetches Bond film data from a PHP API (see below for setup)
- Toggle between sorting by release date or box office
- Displays film thumbnails from the local `/thumbnails` directory
- Clean, white-themed UI
- CSS spinner for loading state

## Getting Started

1. **Clone or fork this repo** to your GitHub account.
2. **Ensure the Bond API (PHP) server is running** (see the API repo for setup instructions).
3. **Make the API port public** in Codespaces so your client can access it.
4. **Update the API endpoint in `index.html` if needed** (currently set for local use).
5. **Open `index.html` in your browser** to use the client locally, or deploy to GitHub Pages (see below).

## Using the Client
- Click "Browse by Year" to view films sorted by release date.
- Click "Sort by Box Office" to view films sorted by box office.
- Thumbnails are loaded from the `/thumbnails` directory for each film.

## Deployment
- You can deploy this client to GitHub Pages for public access.
- Ensure your API endpoint is accessible from the deployed site (public Codespace port).

## Customization
- The UI uses a pure white background for a clean look.
- A CSS spinner is used for loading feedback.
- Film images are loaded from the local `/thumbnails` directory for fast performance.

## Credits
- Bond film data and images for educational use only.

---

*For any issues or questions, please contact the repo maintainer.*
