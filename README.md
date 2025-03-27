# Inventory Management Application

This is a React-based inventory management application built with Vite. It uses `json-server` to simulate a backend API and `axios` for making HTTP requests. The application displays a list of inventory items fetched from a local JSON database.

## Features

- Fetch and display inventory items from a mock server.
- Show loading and error states during data fetching.
- Responsive UI styled with Tailwind CSS.

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository:

   ```sh
   git clone <repository-url>
   cd inventory
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

### Running the Application

1. Start the mock server using `json-server`:

   ```sh
   npx json-server --watch db.json --port 3001
   ```

2. Start the development server:

   ```sh
   npm run dev
   ```

3. Open the application in your browser at:
   ```
   http://localhost:5173
   ```

### Additional Commands

- Build the application for production:

  ```sh
  npm run build
  ```

- Preview the production build:
  ```sh
  npm run preview
  ```

### Notes

- Ensure that `db.json` is present in the root directory for `json-server` to work correctly.
- The mock server runs on `http://localhost:3001` by default.
