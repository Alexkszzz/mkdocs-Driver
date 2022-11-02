# Frontend Technical Documentation
The web application can be mainly be divided into two sides: frontend or also known as client-side application, an application that runs inside the browser of the user, backend or also known as server-side application, an application that is connected with a database and provides apis for frontend in order to retrieve data or post data to. This documentation only contains information for frontend as this is made by frontend developer.

## Frontend Pages
This web application has 2 versions. Desktop version will be serving admin for their daily task of managing and assigning consigments to driver, while the mobile version will be serving drivers, in order for them to manage their own consignments, upload evidence and information in real time. 

All pages components will be found under ```src/Components``` folder

## State
All states of the application, such as consignments, userId, etc. will be stored and retrieved with [react-redux](https://react-redux.js.org/)

## Styling
Styling and components are done with [mui-v5](https://mui.com/material-ui/getting-started/overview/)