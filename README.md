<h1>Uber-like App</h1>

<p>
This app is a demonstration of React Native, Tailwind, and Google APIs. It mimics Uber's ability to select locations, calculate distance and time, and estimate costs for a ride.
</p>
<h2>Features</h2>
<p>
Users can select their pickup and dropoff locations on a map.
The app calculates the distance and time for the ride using the Google Distance Matrix API.
The estimated cost of the ride is displayed to the user.
The user can confirm the ride and proceed to a payment screen.
</p>
<h2>Technologies Used</h2>
React Native: A cross-platform framework for building mobile apps using JavaScript.
Tailwind CSS: A utility-first CSS framework for rapidly building custom user interfaces.
Google Maps Platform: A suite of APIs that enable developers to integrate maps, routes, and places into their applications.
<h2>Installation</h2>
To run this app locally, you will need to have the following dependencies installed:
<ul>
<li>Node.js</li>
<li>Expo CLI</li>
</ul>

<h2>Then, follow these steps:</h2>
Clone the repository: git clone https://github.com/your-username/uber-app.git
Navigate to the project directory: cd uber-app
Install dependencies: npm install
Start the app: expo start
Configuration
To use the Google Distance Matrix API in this app, you will need to obtain an API key from the Google Cloud Console. Then, create a .env file in the root directory of the project and add your API key as follows:

GOOGLE_MAPS_API_KEY=your-api-key-goes-here
