# Flutter fetch data API 

### A simple Flutter app that fetches data from API and then display it. 

## Table of contents
* [General info](#general-info)
* [Screenshots](#screenshots)
* [Learnings](#learnings)
* [Installation](#installation)
* [Dependencies](#dependencies)
* [API](#api) 
* [Usage](#usage)

## General info
This is a simple Flutter application implementing a Flutter API call basics by doing this playlist ![Flutter REST API]([https://www.youtube.com/playlist?list=PLXbYsh3rUPSzuLcZsIkpDmftSQbFmUq9x]) by ![Nitish Kumar Singh](https://www.youtube.com/@NitishKumarSingh).

## Screenshots
<img src="https://github.com/AGreynoon/flutter_fetch_data_api/blob/main/screenshots/Screenshot_1.png" width="300" height="600"/> <img src="https://github.com/AGreynoon/flutter_fetch_data_api/blob/main/screenshots/Screenshot_2.png" width="300" height="600"/> <video width="300" height="600" controls="controls"><source src="https://github.com/AGreynoon/flutter_fetch_data_api/blob/main/screenshots/screenshot_3.mp4" type="video/mp4" /></video>

## Learnings
During this project, I focused on practicing the following Flutter concepts:
* **Folder Structure:** I learned how to structure project folders depending on project scale and the technologies, for this project I used `Folders By Type Pattern`.
* **Widgets:** I implemented advanced widget layouts like `SafeArea`, `ExpansionTile`, `TextField`, `searchTextField`, `Visibility`, and more.
* **Navigating Screens:** How to move from one screen to another via `Navigator.push`.
* **State Management**: Used `StatefulWidget` to manage loading and success states effectively.  
* **API Integration**: Fetched and displayed data from an external API using the `http` package.  
- **JSON Parsing**: Parsed API responses into Dart objects using model classes.  
- **Asynchronous Programming**: Applied `async/await` for seamless asynchronous operations.  
* **Reusability**: Created reusable components to simplify the app's architecture. 
* **UI:** How to style the UI in general.

## Installation:
1. Clone this repository.
2. Ensure you have Flutter installed (https://docs.flutter.dev/get-started/install).
3. Run `flutter pub get` to install dependencies.


## Dependencies:
This project uses the `http` package for persistent storage of tasks.


## API:
This project interacts with the ![randomuser](https://randomuser.me) API. Please refer to the API documentation (https://randomuser.me/documentation) for details on authentication and usage guidelines.

## Usage:
* Run `flutter run` to launch the app on your device or simulator.