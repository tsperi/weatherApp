# Weather Forecast App

Built by [tsperi](https://www.github.com/tsperi/weatherApp)

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

This is based from the "Weather App" React guide as seen [here](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md).

# Table of Contents

- [What this app is about](#what-this-app-is-about)
- [Why am I building this app?](#why-am-i-building-this-app)
- [Development Flow](#development-flow)


#### What This App Is About

- Built to display current weather and a 5-Day forecast for a particular zip code
- Testing sandbox for React, ES6, and Bootstrap
- Experimenting with API Calls from [Open Weather Map](http://openweathermap.org)

#### Why Am I Building This App?

I've been exposed to React/Redux off and on for about 2 years now. I've used it in
a few projects but never really grasped the concepts.

I recently took a workshop with TalkRise on React/Redux and they used a simple React app
tutorial [as seen here](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md).
After building it a few times, I realized that the API calls available through Open Weather Maps 
could be extended to output other data ... such as a 5-day forecast. Hence the conception of this app.

<i>My goal is to create a weather app using React that would include a 5-day
future Forecast and output all this to an interactive front-end built using
JQuery and Bootstrap.</i>

#### Development Work Flow

- Two branches within my [WeatherApp repo](https://github.com/tsperi/weatherApp): Master and Develop.
- All work done locally gets committed and pushed to Develop
- Create Pull Request to Master
- Check all code and ensure that there will be no conflicts
- Merge Pull Request into Master
- I use [Netlify](http://www.netlify.com) to quickly deploy the Master branch
live to the Internet.

You can see the most recent version of the Weather Forecast App 
[here](http://comedian-bonnie-81560.netlify.com/).