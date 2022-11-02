# Technical Documentation for Developer
</br>

## Application
The website application is built with ReactJs, a Javascript framework. The reason for choosing Reactjs is that it is used for building interactive user interfaces and website applications quickly and efficiently. The amount of coding for Reactjs is also significantly reduced comparing to vanilla JS

## Development Workflow
</br>

### Dependencies
Run the following command to install all dependencies on your working environment.
```bash
npm install
```
If you encounter any error regarding to error dependency tree, please try the following command instead.
```bash
npm install --legacy-peer-deps
# or
npm install --force
```

### Run the development server
Run ``` npm start ``` to run the application under development mode
In order to run the application on local server, run the following commands in sequence
``` bash 
npm run build 
``` 
This command will build the application and create a build folder. Then in order to serve this build folder, run
``` bash
serve -s build
```
