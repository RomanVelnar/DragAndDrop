# DragAndDrop
## Purpose of this app
This app is meant to use the drag and drop mechanics where users can add their projects to the library. The whole projects is done in TS to make the inputs very strict.

## Structure of this project
At first whole code was written in one file. The next step was to distibute the code to multiple files so that is more readable. For this we have three options, all these options are performed in separate branches:

- 1st we could distribute the code to multiple files and use the export and import system. (This was done in the feature/restructure-ESModules branch)

- 2nd using Namespaces to group the code (This was done in the feature/restructure branch)

- 3rd File bundling using 3rd party pack, for this project we used the webpack, where per file or bundled compilation is possible and there are less imports to manage. (This was done in the feature/addingWebpack branch)

## Technologies used
- TypeScript 
- JS bundling
- Webpack
- HTML 
- CSS

## Future development
- added local storage 
- adding other functionalities to the app
- make the app mobile and used crossplatform
- spread the code to different files - done


## How to install the app

```
git clone https://github.com/RomanVelnar/DragAndDrop.git
```

run the npm install to install the dependencies
```
npm install
```

run the live server 
```
npm start
```
