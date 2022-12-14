# How to build and run
## Prerequisites
- Create a .env file matching the .env.example 
(Normally you would not share keys or commit this information even in a .env.example, but since this is an assessment and they 
are not really secrets it is ok.)
- Install node
- Have docker installed (for running with Docker only)

## Run with Docker
`docker-compose up -d`

## Run with npm
`npm start`

# Solution description
This solution uses Material UI to be able to quickly setup and style react components. A component library was created to easily 
reuse components. If you are running with npm, the port is configurable by changing the port in the .env file to your desired port. If you are running with Docker, the port is configurable in the docker-compose.yml. For this project the port is set to 3000. A button on the page will use the countapi and has the key stored in the .env file.

# Enhancements
- Addition of a theme to store the styling for the app. This is cleaner than the inline styling of components.
- Using rem instead of px for sizing to allow easier control in the application as well as improve accessibility.
- Styling breaks could be added for the addition of a responsive design.
- Jest testing could be added to ensure requirements are met.