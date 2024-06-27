# Frontend Assignment: Implement a Charting Library in React.js

## Create a React.js application that displays a chart using a charting library. The chart should support timeframe breakdown, timeframe zooming, and interactive click events. The chart data will be provided in JSON format.

Assignment Requirements:

1. Setup React.js Project:
   - Initialize a new React.js project.
   - Ensure the project is set up with TypeScript (optional but recommended for better type safety).

2. Charting Library Integration:
   - Choose a charting library that supports timeframe breakdown, zooming, and click events. Recommended libraries include:
     - [Chart.js](https://www.chartjs.org/)
     - [Recharts](https://recharts.org/)
     - [ApexCharts](https://apexcharts.com/)
     - [Highcharts](https://www.highcharts.com/)

3. JSON Data Handling:
   - Create a JSON file or an endpoint to serve chart data. The JSON data should include timestamps and values to be plotted. Make sure the data has over 100 points. 
   - Example JSON data structure:
     ```json
     [
       { "timestamp": "2023-01-01T00:00:00Z", "value": 10 },
       { "timestamp": "2023-01-02T00:00:00Z", "value": 12 },
       { "timestamp": "2023-01-03T00:00:00Z", "value": 5 },
       ...
     ]
     ```

4. Chart Implementation:
   - Display the chart using the selected charting library.
   - Implement timeframe breakdown (e.g., daily, weekly, monthly views).
   - Enable timeframe zooming to allow users to zoom in/out on specific time periods.
   - Add click event handlers to display details of the clicked data point (e.g., show a tooltip or a modal with more information).

5. User Interface:
   - Create a simple UI with buttons or dropdowns to switch between different timeframe breakdowns (e.g., daily, weekly, monthly).
   - Ensure the UI is responsive and user-friendly.

6. Export the chart as png/jpg formats. 


Evaluation Criteria:

1. Functionality:
   - Correct integration of the charting library.
   - Smooth and accurate timeframe breakdown and zooming functionalities.
   - Correct handling and display of JSON data.
   - Proper implementation of click events.

2. Code Quality:
   - Clean and maintainable code.
   - Proper use of React hooks and React.js features.
   - TypeScript usage (if applicable) and type safety.

3. User Experience:
   - Intuitive and responsive UI.
   - Smooth interactions and transitions.

4. Deployment:
   - Successful deployment and accessibility of the application.


## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

