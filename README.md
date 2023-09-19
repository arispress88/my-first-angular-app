# My First Angular App
Creating the Angular Homes app by following along with the tutorial found on [angular.io](angular.io).


### Installation

Before you can use this project, you'll need to install Angular. Follow these steps:

1. **Install Node.js and npm:**
   If you don't have Node.js and npm (Node Package Manager) installed, download and install them from [nodejs.org](https://nodejs.org/).

2. **Install Angular CLI:**
   Open your terminal or command prompt and run the following command to install Angular CLI globally:
   ```
   npm install -g @angular/cli
   ```

3. **Clone this repository:**
   ```
   git clone https://github.com/arispress88/my-first-angular-app.git
   cd angular-practice
   ```

4. **Install project dependencies:**
   ```
   npm install
   ```

5. **Start the development server:**
   ```
   ng serve
   ```

6. Open your web browser and navigate to `http://localhost:4200/` to see the application running.
7. In order to run the JSON server, be sure to run the following command from the root of the project:
```
json-server --watch db.json
```

## Instructions
1. The app is fairly simple in terms of usage, the home page is a list of homes with photos, name of the homes, and the locations.
2. All of the homes have an option to click "Learn More" to get more details about a certain home.
3. On the details page for a home, there is a form at the bottom where you can enter a first name, last name, and email address.
4. Open the Dev Tools by right-clicking on the page and selecting "Inspect".
5. Navigate to the Console tab of the Dev Tools.
6. After opening the Console, enter a first name, last name, and email address into the form and click "Apply Now" at the bottom of the form.
7. The first name, last name, and email address should appear in the console, letting you know that the app has received the data.
8. You can also filter your searches by city.
9. Typing in the name of one of the cities listed on the page will filter the results to just that city.
10. Try typing `Chicago` into the search bar at the top of the page and click the search button.

