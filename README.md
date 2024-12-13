# Instructions to Run the Server

This project only has you editing code in the front end (browser side) of the application, but an important part of being a front-end developer is interacting with the back end, the server. So you'll need to get the existing server up and running in order to have a place to fetch data from.

---

## Overview

First you'll need to make sure your device's version of the project has all the dependencies the project needs to be able to actually run (Steps 1-2 below). If you'd like, you can view the dependencies in Backend/package.json.

Then you'll need to start up the development server (Step 3). This is necessary because this server is where you will be fetching the project data from throughout your work on the project.

Finally, it will be helpful to know the exact locations on the server from which you'll get data or which you'll post data to. This is where steps 4-5 will be helpful.

---

## Steps to Get Started

1. Navigate into the Backend directory. Do this with the `cd` command in your terminal, followed by the file path to wherever your project is on your device.

> Example: `cd Desktop/Sophie-Bluel-website-en-master/Backend`

2. Once you have navigated to the Backend directory of this project, type `npm install` in your terminal and hit enter. This tells npm to examine all the dependencies in the package.json file and install them.

3. Now that you have all of the dependencies necessary to start the back end server, run `npm run start` in your terminal. This will fire up the development server you will use for the project.

4. Open your preferred browser and navigate to [http://localhost:5678](http://localhost:5678). If the browser displays a white page with "Cannot GET /" then that is actually a sign you've gotten the server running _correctly_. If you get a different page that says the browser was unable to connect, something has gone wrong. Make sure you are navigated to the correct folder for all of this: **Sophie-Bluel-website-en-master/Backend**.

5. In your browser URL bar, navigate to [http://localhost:5678/api-docs](http://localhost:5678/api-docs). This page is a master list of all of the data endpoints from which you will be posting and getting data from throughout this project.

When you are ready to shut down the development server, you can use "ctrl + C" or "cmd + C" in your terminal. When you want to continue working, you'll need to run `npm run start` again from the Backend directory.

For this project, _you will not be editing or adding code in the Backend directory_. You needed to complete the steps above to start the server that will be used to post and get data, but the code you will be working with for this project will _only_ be in the FrontEnd directory.

Happy Hacking!
