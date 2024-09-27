CI/CD Workflow Documentation

Purpose of the Workflows

The workflows in this project automatically build, test, and deploy the application. Every time I push changes to the main branch, the CI (Continuous Integration) workflow checks that everything works, and then Heroku automatically deploys the updated version of the app.

Steps Involved

1. Checkout Code: The workflow pulls the latest code from the repository.
2. Set Up Java 11: Java 11 is installed to build and run the project.
3. Build with Maven: The project is built using Maven to make sure everything compiles.
4. Run Tests: Tests are automatically run to catch any issues before deployment.
5. Heroku Deployment: After a successful build and test, Heroku automatically deploys the application.

Configuration and Dependencies

- Java Version: 11
- Maven: Used to build the project and run tests.
- Heroku: Used to deploy the app.
