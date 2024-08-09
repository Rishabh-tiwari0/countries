# Country Info App

This project is a React-based application that displays information about countries. You can search for countries, filter them by region, and view detailed information about each country by clicking on the country card.

## Features

- Display a list of countries with basic information (flag, name, population, region, and capital).
- Search countries by name.
- Filter countries by region.
- View detailed information about a selected country.

## Technologies Used

- React
- Tailwind CSS
- React Icons
- JSON data for country information

## Installation and Setup

Follow the instructions below to set up and run the project on your local machine.

### Prerequisites

Make sure you have the following installed on your system:

- [Node.js](https://nodejs.org/) (v14 or later)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Clone the Repository

Clone this repository to your local machine using the following command:

```bash
git clone https://github.com/your-username/country-info-app.git
Install Dependencies
Navigate to the project directory and install the required dependencies:

bash
Copy code
cd country-info-app
npm install
# or if you are using yarn
yarn install
Running the Application
To run the application, use the following command:

bash
Copy code
npm start
# or if you are using yarn
yarn start
This will start the development server and open the application in your default browser. If it doesn't open automatically, you can access it by navigating to http://localhost:3000 in your browser.

Project Structure
Here's a brief overview of the project's structure:

bash
Copy code
/country-info-app
│
├── /public            # Public assets
├── /src               # Source code
│   ├── /components    # React components
│   ├── /data          # Country data (JSON)
│   ├── App.js         # Main App component
│   ├── index.js       # Entry point
│   └── index.css      # Global styles
│
├── package.json       # Project metadata and dependencies
└── README.md          # Project overview and instructions
Usage
Searching for Countries
Use the search bar at the top of the page to search for countries by name.
The list of countries will automatically filter based on the input.
Filtering by Region
Click the "Filter by Region" button to select a region from the dropdown menu.
The list of countries will update to show only those within the selected region.
Viewing Country Details
Click on any country card to view detailed information about that country.
Click the "Back" button to return to the list of countries.
```
