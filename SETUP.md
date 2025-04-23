# Setup

## Prerequisites

1. Make sure you have [Node.js](https://nodejs.org/en/) **LTS** (at least v20) installed:
   - Use `node --version` from your terminal to check the version
2. Install essential VS Code extensions:
   - Tailwind CSS IntelliSense
   - Prettier
   - ESLint
3. Set up the InvestTrack backend and database according to their instructions:
   - https://github.com/JBiong/startupvest-back
   
## Cloning & running the project

1. Clone this project:
   ```sh
   git clone git@github.com:mugnavo/startupsphere.git
   ```
   or via HTTPS:
   ```sh
   git clone https://github.com/mugnavo/startupsphere.git
   ```
2. Install dependencies:
   ```sh
   npm i
   ```
3. Create a `.env` file at the root directory of the project with the following variables:

   ```sh
   # https://account.mapbox.com/access-tokens
   NEXT_PUBLIC_MAPBOX_TOKEN=

   # Server URL for InvestTrack backend
   NEXT_PUBLIC_BACKEND_URL=
   ```

4. Run the project:
   ```sh
   npm run dev
   ```
   The development server should be running at `http://localhost:3001`.

5. The project shares the same backend and database with InvestTrack, so you can use the same credentials to log in.

## Deploying for production

1. Build the project:
   ```sh
   npm run build
   ```

2. Start the production server:
   ```sh
   npm start
   ```

