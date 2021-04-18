<h1 align="center">
  <img src="frontend/src/assets/logo.svg"/>
<h1>

## About the project

Administrative dashboard to connect ONGs to people that are able to help. It's possible to create ONGs and cases related to the ONGs. Developed on Omnistack 11.0 guided by Rocketseat

## Tecnologies
- [NodeJS](https://nodejs.org/en/)
- [Yarn](https://yarnpkg.com/)

![lQd9PHvxPQ](https://user-images.githubusercontent.com/19476724/115164369-b94dac00-a082-11eb-8168-896ea4e97bb9.gif)


## Running the project

```bash
# clone the project
git clone https://github.com/GuilhermeFujita/BeTheHero-Semana_Omnistack-11.0.git

# Enter the project folder
cd BeTheHero-Semana_Omnistack-11.0

# In order to run the backend
cd backend

# Install dependencies
yarn install

# Run migrations from database
yarn knex migrate:latest

# Start the project
yarn start

## In order to run the frontend

# Enter the frontend folder
cd frontend

#Install dependencies
yarn install

#Start the project
yarn start

After that the frontend will be running on port 3000 and backend will be running on port 3333.
```