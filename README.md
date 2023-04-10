# Duplicate Character Remover App

This is a web application built using ReactJS that allows the user to remove duplicate characters from a string. The app has two screens, where the first screen takes input from the user and the second screen shows the resultant string after removing the duplicate characters.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository onto your local machine.
2. Navigate to the project directory in your terminal.
3. Install the dependencies by running `npm install`.
4. Run the development server by running `npm start`.
5. Open your web browser and navigate to http://localhost:3000 to view the app.

## Usage

On the first screen of the app, the user is presented with an input field and a "Submit" button. The user can enter any value into the input field and click the "Submit" button to proceed to the second screen.

If the input field is empty or contains only space characters, the user will be shown an alert asking them to provide a non-empty value. In this scenario, the user will not be redirected to the second screen.

On the second screen, each character of the input string is rendered as a card on the UI. Each card has the character and a delete icon on top. Clicking on the delete icon deletes all duplicate instances of the chosen character in the string. Only the clicked instance of the character remains on the screen.
- Let's say if the original string is `aabcaccda`. Clicking on the first `a` should leave the string as `abcccd`.
Let's say the original string is `baebdeb`. Clicking on the character b at index 3 (0 index), should result in `aebde`.

Cards for the same characters have the same background color. If there are no more characters with greater than 1 appearance in the string, a success header is displayed. The original string and the new resultant string are also shown. The user can go back to the first screen by clicking the back button.

## Technologies Used

This project was built using the following technologies:

- ReactJS
- JavaScript
- CSS
- A react package named - color-hash

## Contributing

Contributions to this project are welcome! If you would like to contribute, please follow these steps:

1. Fork this repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them to your branch.
4. Push your changes to your forked repository.
5. Submit a pull request to this repository with a description of your changes.

n.b : I used an npm package named color-hash to generate same colour background for every same string charecter, though in the display.js file you will see three function: getRandomColor(), uniqueChars(), elementColors() these combined were supposed to do the task that color-hash in doing.. you guys work around that :)
## Project Idea
https://github.com/HousewareHQ/frontend-engineering-octernship

