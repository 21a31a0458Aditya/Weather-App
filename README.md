<!--<h1 align="center">  
  Weather-Dashboard
</h1>

<h3 align="center">Weather info fetching app. Built using <a href="https://angular.dev" target="_blank">Angular</a>.</h3><br/>

<h3>
<p align="center">
  <a href="#live-version">Live Version</a> •
  <a href="#about">About</a> •
  <a href="#installation">Installation</a> •
  <a href="#architectue">Architectue</a> •
  <a href="#credits">Credits</a>
</p>
</h3>

## Live-version

[Weather-Dashboard App](https://weather-dashboard-87yg.onrender.com/)

## About

This is a weather dashboard app. The app uses [weatherapi](https://www.weatherapi.com/docs/) to fetch weather forecast and displays weather information of a location that user can search.

## Installation

```bash
# Clone this repository
$ git clone https://github.com/durlavkalita/weather-dashboard

# Go into the repository
$ cd weather-dashboard

# Install dependencies
$ npm install

# Generate application key
$ npm run start

```

The application should start on [localhost:4200](http://127.0.0.1:4200/)

## Architecture

The app uses some of the most well known angular functionalities. For weather search based on location and forecast display a `weather` component was created using `ng generate component weather`. Similarly to handle api calls to [weatherapi](https://www.weatherapi.com/docs/) a service was created using `ng generate service weather`. For icons [angular material](https://material.angular.io/) and for styling [tailwindcss](https://tailwindcss.com) has been used. The site is fully responsive and displays a weather forecast of Guwahati city on 2024-06-22 21:21 by default.

## Credits

- [WeatherAPi](https://www.weatherapi.com/docs/)
- [Angular](https://angular.dev/)
- [Angular Material](https://material.angular.io/)
- [Tailwindcss](https://tailwindcss.com)
