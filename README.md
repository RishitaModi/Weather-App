
# Weather-App

WeatherApp is a sleek and intuitive weather application designed to provide users with accurate and up-to-date weather information. 
Built with a user-friendly interface, WeatherApp offers a seamless experience for accessing real-time weather data, forecasts, and weather-related insights.

Creating a weather app using HTML, CSS, and JavaScript involves several steps, including setting up your project, designing the interface, fetching data from the OpenWeatherMap API, and displaying that data. 
Below is a step-by-step guide to creating a weather app:

1: Setting Up the Project
Create a Project Folder: Start by creating a new folder for your project. Inside this folder, create the following files:

index.html
style.css

2.Get OpenWeatherMap API Key

(i) Sign Up for an Account
Visit the OpenWeatherMap website: Go to [OpenWeatherMap](https://openweathermap.org/api)
Sign up for an account: Click on "Sign Up" at the top right corner of the homepage. Fill in the necessary details (name, email, password) and complete the registration process.

(ii)Log In to Your Account
Log in: Once you have registered, log in to your OpenWeatherMap account by clicking on "Sign In" and entering your credentials.

(iii) Access the API Keys Section
Navigate to the API keys page: After logging in, go to your account dashboard. 
You can find this by clicking on your username at the top right corner and selecting "My API keys" from the dropdown menu, or directly navigate to API keys.

(iv) Create a New API Key
Create an API key: On the API keys page, you will see an option to "Generate" or "Create" a new API key. Click on this button.
Name your API key: Enter a name for your API key to help you identify its purpose (e.g., "Weather App Key").
Generate the key: Click on the "Generate" button to create the key.

(v)Copy Your API Key
Copy the API key: Once generated, you will see your new API key listed on the page. Copy this key as you will need it to authenticate your API requests.

Example: How Your API Key Looks
Your API key will look something like this: '1234567890abcdef1234567890abcdef'

For reference watch https://youtu.be/MIYQR-Ybrn4?feature=shared 

3: Structure the HTML
In the index.html file, create the basic structure of your app.

4: Style the App
In the style.css file, add some basic styling.

5.Add JavaScript Functionality
In the HTML file,using <script> tag add the code to fetch weather data and update the UI.

Explanation of JavaScript Code: 

Event Listener: An event listener is added to the "Get Weather" button to trigger the function when clicked.

Fetch API: The fetch function is used to make a GET request to the OpenWeatherMap API with the city name and API key.

Handling Response: The response from the API is converted to JSON and then processed.

Updating the UI: If the city is found (status code 200), the weather information is displayed. If not, an alert is shown.

6. Testing: Open the index.html file in a web browser and test your app by entering different city names and clicking the "Search" button.

Display the Weather App

![Screenshot (28)](https://github.com/RishitaModi/Weather-App/assets/149221459/09b6ff47-f29e-4e84-80fb-c3c987e75b09)

Add City Name and click on "Search" Button.

![Screenshot (29)](https://github.com/RishitaModi/Weather-App/assets/149221459/6c9d54ff-3d64-4881-82aa-5e5b17a427bd)

Display's Current Weather Condition which includes Temperture (°c),Humidity (%) and Wind Speed(km/h).

![Screenshot (30)](https://github.com/RishitaModi/Weather-App/assets/149221459/3cbd9028-e35b-4614-ac97-cdc731d67392)

![Screenshot (31)](https://github.com/RishitaModi/Weather-App/assets/149221459/159d8ef5-f9fb-4d6e-a832-bf26e77494be)

![Screenshot (32)](https://github.com/RishitaModi/Weather-App/assets/149221459/3739204b-1e08-4f85-8125-38b2d04cbc0d)






