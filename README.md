# Dashboards

This application allows you to build personalized dashboards using drag &amp; drop. Dashboards consists out of widgets
that are placed on the board. Widgets are simple to implement, so everyone can make widgets they need.

### Technology Stack 

Front-end:
* CxJS
* React
* Babel
* webpack

Back-end:
* Firebase

### Experimental Browser Features

This app uses experimental browser features such as:

* `display: grid` 
* `IntersectionObserver` 

These features are not yet fully supported in all browsers.

### Getting Started

Clone the repo and install packages using `yarn install` or `npm install`.

Start the application on your machine:

```
npm start
```

To build the application for deployment, run:

```
npm run build
```

### Contributing

We would be very happy to accepts PRs, especially for new widgets. Widgets are defined inside the `app/widgets` folder 
and that is probably the best place to start experimenting with the app.  

### Deployment

The `master` branch is continuously deployed to [dashboards.cxjs.io](https://dashboards.cxjs.io) 
using [Netlify](https://www.netlify.com/). 

### License

This project is licensed under MIT License, however, please note that [CxJS](https://cxjs.io) is free 
for non-commercial projects only. 