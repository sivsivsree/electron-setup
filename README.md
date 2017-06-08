# electron-setup

To get started, install Node if you don't have it in your system already. Our application should be structured as follows:

project-structure

There are two package.json files in this project.

For development


Learn Angular
Related Course
The package.json directly inside the project root contains the configurations, dependiencies for your development environment and build scripts. These dependencies and package.json file will not be included inside the production build.

For your application

The package.json inside app folder is the manifest file for your application. So whenever you need to install npm dependencies to be used in your application directly, you should install it against this package.json

The format of package.json is exactly same as that of Node's module. Your application’s startup script should be specified in main property inside your app/package.json.
