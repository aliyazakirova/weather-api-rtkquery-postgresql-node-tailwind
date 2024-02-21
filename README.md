## Weather API Project

This project utilizes Redux RTK Query to fetch weather data from three countries: Turkey, Russia, and the United Kingdom. The retrieved data is displayed on a page named "City Information."

### Features

- Fetch weather data from the API using Redux RTK Query.
- Display weather information in a tabular format.
- Save the retrieved data to a PostgreSQL database collection named "history-query."
- Retain the entire history of queries.

### Steps to Run the Project

1. **Clone the Repository:**
   ```bash
   git clone <repository_url>
   ```

2. **Install Dependencies:**
   ```bash
   cd weather-api-project
   npm install
   ```

3. **Set Up PostgreSQL Database:**
   - Ensure PostgreSQL is installed and running on your system.
   - Create a database named `weather_db`.
   - Set up the necessary credentials and configurations in the `.env` file.

4. **Start the Backend Server:**
   ```bash
   npm run start:server
   ```

5. **Start the Frontend React App:**
   ```bash
   npm start
   ```

6. **Access the Application:**
   Open your browser and navigate to `http://localhost:3000` to view the application.

### Usage

1. **City Information Page:**
   - Enter the name of a city in the provided input field.
   - Upon retrieving data, the weather information will be displayed below in a tabular format.
   - The data will also be saved to the PostgreSQL database collection "history-query."

2. **Viewing Query History:**
   - Access the database to view the entire history of queries made.

### Technologies Used

- React.js
- Redux RTK Query
- Node.js
- PostgreSQL
- Tailwind CSS

### Contributors

- Aliya https://github.com/aliyazakirova 

Feel free to reach out for any questions or contributions!
