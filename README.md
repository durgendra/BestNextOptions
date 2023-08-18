# Best Next Options

AI-assisted option exploration app with a React frontend and an Express/Mongoose backend.

## About

This project presents a decision-support workflow where users can submit prompts, compare generated options, and review summaries in a browser UI. The client uses a Create React App stack with Firebase and PDF viewing components, while the server handles chat, summaries, option evaluation, and user flows.

## Key Features

- Option generation and evaluation routes
- Summary and chat workflows
- Firebase-backed client configuration
- Mongoose-backed server with OpenAI and LangChain dependencies
- PDF and document rendering components in the frontend

## Architecture

- `client-front/` is the React UI
- `server/` is the Node/Express API
- `server/index.js` connects to MongoDB and registers the route groups
- `client-front/src/main/` contains the feature pages, actions, and Firebase setup

## Tech Stack

- React 18
- Create React App
- Node.js + Express
- MongoDB + Mongoose
- Firebase
- OpenAI / LangChain

## Prerequisites

- Node.js
- MongoDB

## Installation

```bash
cd server && npm install
cd ../client-front && npm install
```

## Configuration

- Server: `PORT`, `CLIENT_URL`, `MONGO_CONNECT`
- Client: `REACT_APP_SERVER_URL`, `REACT_APP_API_KEY`, `REACT_APP_AUTH_DOMAIN`, `REACT_APP_PROJECT_ID`, `REACT_APP_STORAGE_BUCKET`, `REACT_APP_MESSAGING_SENDER`, `REACT_APP_APP_ID`, `REACT_APP_GOOGLE_CLIENT_ID`

## How to Run

```bash
cd server
npm start

cd ../client-front
npm start
```

## Example Usage

- Start the API and open the React app
- Navigate through the option, chat, and summary screens

## Project Structure

- `client-front/src/main/` - feature code, actions, and Firebase config
- `client-front/src/views/` - UI pages
- `server/routes/` - API route groups
- `server/controllers/` - business logic

## Current Status

Looks like a working portfolio demo, but the workspace snapshot does not include a root-level publication package.

## Limitations

- No root env example yet
- No tests were run here
- No explicit license at the repo root

## License

No explicit license file was found at the repository root.
