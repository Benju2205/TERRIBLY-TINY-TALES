# TERRIBLY-TINY-TALES
This is a repository for the Assignment of Terribly Tiny Tales.

## React App for Word Frequency Histogram

This is a simple React app that fetches the content of a text file from a URL and analyzes the frequency of occurrence of each word in the text. The app displays a histogram of the 20 most frequently occurring words and provides an option to download the histogram data as a CSV file.

## Libraries and Plugins Used

The app uses the following libraries and plugins:

- React (https://reactjs.org/)
- Recharts (https://recharts.org/)
- react-csv (https://www.npmjs.com/package/react-csv)
- Bootstrap (https://getbootstrap.com/)

## Components of the Code

The code consists of a single component, 'App'. The component defines the following states:

'text': to store the text content of the fetched file
'wordCount': to store the word count data
The component defines the following functions:

'handleSubmit': to fetch the text file and analyze the word count data
'getWordCount': to extract and count the words in the text content
The component renders a button to initiate the file fetch and display the histogram. If the word count data is available, the component also renders a histogram using the 'BarChart', 'Bar', 'XAxis', 'YAxis', 'CartesianGrid', and 'Tooltip' components from Recharts. The component also renders a 'CSVLink' component from 'react-csv' to enable the user to download the histogram data as a CSV file.

## Installation and Usage

To use this app, you need to have Node.js installed on your machine. You can follow these steps to install and run the app:

1. Clone this repository to your local machine.
2. Open a terminal window in the project directory and run the command 'npm install' to install the dependencies.
3. After the installation is complete, run the command 'npm start' to start the app.
4. Open a web browser and go to http://localhost:3000/ to view the app.
5. Click the "Submit" button to fetch and analyze the text data.
6. The histogram of the 20 most frequently occurring words will be generated and displayed.
7. Click the "Export" button to download a CSV file of the histogram data.

## Code Structure

- `App.js`: The main component that fetches the text data, generates the histogram data, and renders the UI.
- `index.js`: The entry point of the application.
- `index.css`: The CSS file for the application styling.
- `README.md`: The documentation file for the application.
