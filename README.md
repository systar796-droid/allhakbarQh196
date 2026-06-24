# Haikus for Codespaces

Improved and cleaned-up Node.js sample that serves a small collection of haikus.

This repository is a lightweight demo Node.js app (Express + EJS) originally based on an Azure sample. I've added basic repository housekeeping files: CI workflow, Dependabot config, contributing guidelines, and issue templates.

## Features
- Small Express app that renders haikus from haikus.json using EJS templates.
- Simple start and dev scripts in package.json.

## Requirements
- Node.js 16+ (or compatible LTS)

## Run locally
1. Install dependencies:

   npm install

2. Start the app:

   npm start

3. Open your browser at http://localhost:3000 (or PORT defined in env).

For development with auto-reload:

   npm run dev

## Project layout
- index.js - main Express server
- haikus.json - sample content
- views/ - EJS templates (rendered by the app)
- public/ - static assets (images, css)

## Contributing
See CONTRIBUTING.md for contribution guidelines.

## License
This project includes an MIT license file. See LICENSE for details.
