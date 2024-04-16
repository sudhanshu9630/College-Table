# College-Table

## Deployement link - [[sudhanshu-college-table.netlify.app](https://sudhanshu-college-table.netlify.app/)]

This project showcases an implementation of an infinite scroll table layout designed for displaying college data. It incorporates sorting functionality based on Collegedunia rating, fees, and user review rating in both ascending and descending orders. Furthermore, it offers a search feature to facilitate filtering colleges by name.


## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
- [Dummy JSON](#dummy-json)
- [Implementation Details](#implementation-details)
- [Dependencies](#dependencies)
- 
## Overview

This project creates a table layout to display college data. Initially, it loads 10 rows, and as the user scrolls down, more rows are dynamically loaded into the table, providing an infinite scroll experience. Each row displays information about a college, including its name, featured flag, ratings, fees, and user review rating. Users can sort the table based on collegedunia rating, fees, and user review rating in both ascending and descending orders. Additionally, a search functionality allows users to filter colleges by name.

## Features

- Infinite scroll: Load additional rows dynamically as the user scrolls down.
- Sorting: Sort the table based on collegedunia(CDRating) rating, fees, and user review rating in both ascending and descending orders.
- Search: Filter colleges by name.
- Featured flag: Display a featured flag for colleges with a truthy featured value.

## Setup

To run this project locally, follow these steps:

1. Navigate to the project directory:

   ```bash
   cd college-list
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

## Usage

Once the development server is running, open your web browser and navigate to `http://localhost:5173` to view the infinite scroll table. You can scroll down to load more college data dynamically. Use the sorting buttons to sort the table based on different criteria, and use the search bar to filter colleges by name.

## Dummy JSON

The project uses a dummy JSON file containing data for different colleges. This data is loaded into the table to demonstrate the functionality. You can replace this dummy data with your own college data as needed.

## Implementation Details

The project is built using React.js and leverages javascript concepts for infinite scrolling, sorting, and filtering functionality. The table layout is designed to optimize performance by only rendering the visible rows, and additional rows are loaded dynamically as the user scrolls down.

## Dependencies

- React.js
- Vite
- Other dependencies as specified in the `package.json` file.
