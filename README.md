# installation-service-landing-page

# Getting started

- Clone the repository

```
git clone  <git lab template url> <project_name>
```

- Install dependencies
  Make sure that your device has Nodejs installed, then execute the following command to install the dependencies.

```
cd frontend
yarn
```

- Build and run the project

```
yarn build
yarn start
```

Navigate to `http://localhost:3000`

## Project Structure

The folder structure of this app is devived into 2 parts:
For frontend
| Name | Description |
| ------------------------ | --------------------------------------------------------------------------------------------- |
| **node_modules** | Contains all dependencies |
| **src** | Contains source code that will be compiled to the dist dir |
| **src/app/components** | Directory is typically used to organize Next components in a structured way within a project |
| **src/app/pages** | Directory is typically used to organize layout of the page such as Header and Footer |
| **src/app/model** | Directory is typically used to define the data of the declared or passed-in data |
| **src/app/layout** | Directory is typically used to organize the main pages of your application |
| **src/app/dataAPI_fnc** | Directory is typically used to call API from Backend to Frontend |  
| **src/app/page.tsx** | The Homepage of this application |  
| **src/app/assets** | Directory is typically used to storge image |  
| package.json | Contains dependencies as well as [build scripts](#what-if-a-library-isnt-on-definitelytyped) |
