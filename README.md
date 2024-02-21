## Weather API Project

This project utilizes Redux RTK Query, Node.js, and PostgreSQL to fetch weather data from three countries: Turkey, Russia, and the United Kingdom. The retrieved data is displayed on a page named "City Information."

### Features

- Fetch weather data from the API using Redux RTK Query.
- ![image](https://github.com/aliyazakirova/weather-api-rtkquery-postgresql-node-tailwind/assets/93845260/0c4024c5-16b2-493e-bbb1-d829613c5cec)

- Display weather information in a tabular format.
- ![image (1)](https://github.com/aliyazakirova/weather-api-rtkquery-postgresql-node-tailwind/assets/93845260/617acfd4-3eb3-4aec-b566-69350cebe8b2)
![image (5)](https://github.com/aliyazakirova/weather-api-rtkquery-postgresql-node-tailwind/assets/93845260/ac82b10b-e85d-41cb-a218-d043d86fd436)

- Save the retrieved data to a PostgreSQL database collection named "history-query."
- ![image (2)](https://github.com/aliyazakirova/weather-api-rtkquery-postgresql-node-tailwind/assets/93845260/18d75650-2ee6-45f9-ba21-c8814c0059f1)
![image (4)](https://github.com/aliyazakirova/weather-api-rtkquery-postgresql-node-tailwind/assets/93845260/0b57474b-645b-40de-a5b4-df0c590efc99)

- Retain the entire history of queries.
![image (3)](https://github.com/aliyazakirova/weather-api-rtkquery-postgresql-node-tailwind/assets/93845260/f5c2b78f-ebff-4986-afb1-32e8e6256a60)

### Steps to Run the Project

1. **Clone the Repository:**
   ```bash
   git clone <repository_url>
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Set Up PostgreSQL Database:**
   - Ensure PostgreSQL is installed and running on your system.
   - Create a database named `weather_db`.
   - Set up the necessary credentials and configurations in the `.yml` file.

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
   - Choose the name of a city in the provided dropdown field.
   - Upon retrieving data, the weather information will be displayed below in a tabular format.
   - The data will also be saved to the PostgreSQL database collection "history-query."

2. **Viewing Query History:**
   - Access the database to view the entire history of queries made with the country, city, temperature and 'feels like' information along with the current date.

### Technologies Used

- React.js
- Redux RTK Query
- Node.js
- PostgreSQL
- Tailwind CSS

### Contributors

- Aliya https://github.com/aliyazakirova 

Feel free to reach out for any questions or contributions!
