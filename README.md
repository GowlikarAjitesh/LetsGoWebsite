# Welcome to LetsGo 👋

![LetsGo_Home](https://github.com/GowlikarAjitesh/LetsGoWebsite/assets/117850813/5a26a227-62b4-41a2-86ff-59fc89599665)


A ReactJS Trip Advisor Web App made with RapidAPI's TravelAdvisor API and Google Maps API

<p>
  <img alt="Version" src="https://img.shields.io/badge/version-0.0.0-blue.svg?cacheSeconds=2592000" />
  <a href="https://www.linkedin.com/in/ajitesh-gowlikar/" target="_blank"  >Linkedin
  </a>
</p>

### ✨ [Live Preview](https://lets-go-ajitesh-gowlikar.netlify.app/)

## Install
Run the Command to Install all dependencies.
```sh
npm install
```

## Usage

Create API Credentials/Keys from the following Providers

* [Google Maps](https://console.cloud.google.com/) "Enabling the Specific Services: Maps Javascript API & Places API"
* [Travel Advisor (Rapid API)](https://rapidapi.com/apidojo/api/travel-advisor/)

Create a `.env` file in your root directory, create the variables as seen below filling in your API Keys appropriately
```sh
VITE_TRAVEL_API_KEY=TRAVEL-ADVISOR-APIKEY-HERE
VITE_GOOGLE_MAP_API_KEY=GOOGLE-MAP-APIKEY-HERE
```
Locate and Append the Google Map API Key onto the Script Tag in the `index.html` file as seen below
```sh
<script src="https://maps.googleapis.com/maps/api/js?v=3.exp&libraries=geometry,drawing,places&key=GOOGLE-MAP-APIKEY-HERE"></script>
```
Now run the command to start the development server.
```sh
npm run dev
```
Your project should start running on `http://localhost:3000`

## Author

👤 **Ajitesh Gowlikar**

* gmail: [@babblebey](ajiteshgowlikar@gmail.com)
* LinkedIn: [@babblebey](https://www.linkedin.com/in/ajitesh-gowlikar/)
* Instagram: [@babblebey](https://instagram.com/the_gowlikar)

