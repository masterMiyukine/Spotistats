# Spotify Stats Server

Your spotify profile's top artists and tracks with charts and playlist creator.

## Installing

1. Register an application with [Spotify](https://developer.spotify.com/documentation/web-api/quick-start).

2. Set client keys for Spotify, redirect and callback url here.

   ```bash
   cp .env.example .env
   ```

3. Install dependencies

   ```bash
   npm install
   ```

4. Fire up the server and watch files

   ```bash
   npm start
   ```

## Built with

- [Express](https://expressjs.com/)
- [Netlify Lambda](https://github.com/netlify/netlify-lambda)
- [Serverless Http](https://github.com/dougmoscrop/serverless-http)

## Acknowledgments

* Hat tip to anyone whose code was used