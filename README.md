Udacity Neighborhood Map Project (P8)

This is a single page application, made with React, npm packages, Google Maps API, and Foursqare API.

*How to install?*

You need npm to be installed on you computer. You can download from the npm site if you don't have installed yet.

Then in the command prompt, npm install then npm start, and your browser will open the project.

*How to use?*

You can click on the markers, so the app will fetch basic informations from the Foursqare database.

On the top left corner you will find the menu, with the list of locations, but you can filter them with the search box, if needed.

*What about the dependecies?*
node modules: node components to run the app, not recommeded to modify them.
public: favicon
        index.html
        manifest.json

src:
    components:
        app.js - this the application file, control the page, and manage the eventlisteners, maps markers, app behaviour.
        filter.js - responsible for the filter function, and for the sidebar
        map.js - map function
    data:
        auth.js - developer API keys
        locations.js - location database array
        mapStyle.js - map styling, modify to chane the mapp appearence
    images:
        icons, and map markers
    app.css: app styling and appearance
    App.test.js - testing solution
    index.css
    registerServiceWorker.js: service worker -- 
    Production mode: - To create a production build use `npm run build`
- Navigate to the build directory and start the server with `npm run deploy`
- This mode includes a Service Worker.
    
