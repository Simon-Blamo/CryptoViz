# CryptoViz

## About The Project
The Crypto Portfolio project is a dynamic web application that allows users to track their cryptocurrency holdings. Built using the Django framework, the application integrates with CoinGecko’s API to fetch real-time cryptocurrency data, providing users an intuitive, interactive platform to manage their investments.

Key features of the project:

- Real-time cryptocurrency data fetched from the CoinGecko API.
- User-friendly interface with interactive card elements for each cryptocurrency.
- Detailed information for each cryptocurrency, including market cap, volume, and price history.
- Integration of form inputs to add cryptocurrency holdings to the portfolio.
- Styled using custom CSS for a sleek, dark-themed design.
- 
## Getting Started

1. **Clone the repo:**

   ```shell
   git clone https://github.com/Simon-Blamo/CryptoViz.git
   ```

2. **`cd` to repo:**

3. **Create the `pipenv` environment:**

   ```shell
   pipenv install
   ```

   Once you install the pipenv environment, you can activate it by doing:
   
   ```shell
   pipenv shell
   ```
4. **Navigate to the project directory:**
      ```shell
       cd CryptoViz
       ```
5. **Configure the database:**
      ```shell
       python manage.py migrate
       ```
6. **Run the development server:**
      ```shell
       python manage.py runserver
       ```

## Disclaimer
This project aims to simplify the process of tracking and managing cryptocurrency investments by providing real-time data and a responsive, interactive UI.
