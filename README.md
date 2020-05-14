# React Park Client

#### By: Michelle Morin, Jamison Cozart, Brandan Sayarath, Drake Wilcox
#### May 11-13, 2020

## Description
_This React frontend application interacts with a custom .NET [Parks Lookup](https://github.com/michelle-morin/ParkAPI) web api._

## Component Tree
![component tree](component-tree.png)

## UI
![user interface](captured.gif)

## Specification User Stories
* As a user, I want to be able to view a list of all parks.
* As a user, I want to be able to search for a park by name, state, and/or campsite availability.
* As a user, I want to be able to view details of a specific park.
* As a user, I want to be able to add a new park via API call.
* As a user, I want to be able to edit details for a park.

## Setup/Installation Requirements

#### Node install

###### For macOS:
_If Homebrew is not installed on your computer already, then install Homebrew by entering the following two commands in Terminal:_
* ``/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)``
* ``echo 'export PATH=/usr/local/bin:$PATH' >> ~/.bash_profile``

_Install Git by entering the following command in Terminal:_
* ``brew install git``

_Next, install Node.js by entering the following command in Terminal:_
* ``brew install node``

###### For Windows:
_Please visit the [Node.js website](https://nodejs.org/en/download/) for installation instructions._

#### Install the ParksLookup WebAPI

_Clone the ParkAPI repository by entering the following commands in Terminal (macOS) or PowerShell (Windows):_
* ``cd desktop``
* ``git clone https://github.com/michelle-morin/ParkAPI``
* ``cd ParkAPI/ParksLookup``
* ``dotnet restore``
* ``dotnet ef database update``
* ``dotnet watch run``

#### Install this application

_In a separate Terminal or PowerShell, navigate to the directory where you would like to clone this application (e.g., the destop) and clone this repository by entering the following commands:_
* ``git clone https://github.com/jamisoncozart/react-park-client``
* ``cd park-client``
_Confirm that you have navigated to the park-client project directory (e.g., by entering ``pwd``)._

_Next, install npm at the project's root directory by entering the following commands in Terminal (macOS) or PowerShell (Windows):_
* ``npm install``
* ``npm start``

_Open the contents of this application in a text editor or IDE of your choice (e.g., to open the contents of the directory in Visual Studio Code on macOS, enter the command ``code .`` in Terminal)._

## Technologies Used

* Git
* JavaScript
* npm
* Webpack
* React
* Redux
* React-Redux
* React Thunk Middleware
* Fetch library
* Custom-built .NET Web API (https://github.com/michelle-morin/ParkAPI)
* React Bootstrap component library
* React-Spring animations
* React-Helmet for SEO

### License

[MIT](https://choosealicense.com/licenses/mit/)

Copyright &copy; 2020 **_Michelle Morin, Jamison Cozart, Brandan Sayarath, Drake Wilcox_**
