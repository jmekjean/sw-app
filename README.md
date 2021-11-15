## To run this project:

### Generate npm credentials

Go to https://campuslabs.visualstudio.com/CollegiateLink/_packaging?_a=connect&feed=CampusLabsNPM
Click on npm
Click Windows or Other(for Mac) under Project setup
Follow setup instructions

### Running the backend

After your npm credentials are setup, make sure to run a `dotnet restore --interactive` from the src/App.CC.Home directory to restore all nuget packages
In VS Code: click debug, select .NET Core Launch(web), click run

### Starting the front end

make sure npm is installed, if not install in the root folder for all git files
In terminal cd into src/ClientApp
Run `yarn install`
Run `yarn start`
Open a new tab in the browser and make sure you are signed into devtestrp
Go to https://localhost:5000/actioncenter or https://localhost:5001/actioncenter
# sw-app
