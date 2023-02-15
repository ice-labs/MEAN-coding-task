# Angular coding task
Welcome to learnmall.in Tech Angular coding task.

## The task
Create a simple Rick and Morty app that displays a list of characters from the show and allows users to view details about each character.

Sample character card

![image](https://user-images.githubusercontent.com/124139608/216905974-54456783-f951-4e1c-8b08-d13d9b4ce57f.png)

* use https://rickandmortyapi.com/api to fetch characters and their details
* for api documentation visit https://rickandmortyapi.com/documentation/#rest



You can find specific acceptance criteria below.

### Acceptance Criteria
1. A component for displaying the list of characters is created and it makes a GET request to the Rick and Morty API to retrieve a list of characters.
2. The list of characters is displayed in the template using *ngFor, showing each character's name, image, and species as shown in above sample character card.
3. A detail component is created for viewing more information about a character, which is accessible by clicking on a character in the list.
4. The detail component makes a GET request to the Rick and Morty API for the specific character based on its id, passed in as a route parameter.
5. The detail component displays the character's name, image, species, status, origin, and location.
6. Navigation is added to the app so that users can move between the character list and character detail pages.
7. The code should be submitted as a GitHub repository with clear documentation on how to run the application locally should be added in README.md.
8. (Optional) The application can be deployed to a test server and the link to the deployed application can be provided.

## Ground rules
1. The solution should be coded in TypeScript. Styling should be done in CSS or SCSS. Your choice.
2. Put the code on your GitHub account in a public repo.
3. You don't need to add any extra features or improvements not listed in the Acceptance Criteria. There are no bonus points for it.
4. You can use other external libraries to speed up your work.
5. You can use a styling framework (Material UI, Bootstrap, or other) for quick and consistent styling.
6. If you're not able to implement all parts of the task, partial submissions are welcome.
7. Provide the GitHub repository link via email within 48 hours of receiving the task.
8. The code should be properly organized and follow best practices for maintainability and scalability.

## Tips
1. Simplicity is highly valued in this exercise.
