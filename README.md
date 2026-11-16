# Notes App (Node.js + Express)

A small full-stack app: a REST API built with Node.js and Express, plus a simple HTML/JavaScript frontend.

## API endpoints
- `GET /api/notes`: list all notes
- `POST /api/notes`: create a note (JSON body: `{ "text": "..." }`)
- `DELETE /api/notes/:id`: delete a note

## Run locally
1. Install [Node.js](https://nodejs.org)
2. Run `npm install`
3. Run `npm start`
4. Open http://localhost:3000

## Technologies
Node.js, Express, JavaScript, HTML, CSS