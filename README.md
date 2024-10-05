# Spotify Album Search

## Description

Spotify Album Search is a web application that allows users to search for artists and view their albums using the Spotify API. Users can search for an artist, view their albums, and sort the results by release date.

## Features

- Search for artists using the Spotify API
- Display albums for the searched artist
- Sort albums by release date (latest or oldest)
- View album details including cover art, name, and release date
- Direct link to open albums in Spotify

## Technologies Used

- React
- Vite
- React Bootstrap
- Spotify Web API

## Setup and Installation

1. Clone the repository:

   ```
   git clone https://github.com/your-username/spotify-album-search.git
   cd spotify-album-search
   ```

2. Install dependencies:

   ```
   npm install
   ```

3. Create a `.env` file in the root directory and add your Spotify API credentials:

   ```
   VITE_SPOTIFY_CLIENT_ID=your_client_id_here
   VITE_SPOTIFY_CLIENT_SECRET=your_client_secret_here
   ```

4. Start the development server:

   ```
   npm run dev
   ```

5. Open your browser and navigate to `http://localhost:5173` (or the port specified by Vite).

## Usage

1. Enter an artist name in the search bar and press Enter or click the Search button.
2. View the artist's albums displayed as cards.
3. Use the "Sort by" dropdown to sort albums by latest or oldest release date.
4. Click on the "Album Link" button on any album card to open it in Spotify.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.

## Acknowledgements

- Spotify for providing the Web API
- React Bootstrap for UI components
