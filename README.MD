# App Description

Node JS Flights API that loads flight information and returns it for our Interimaginary departures app

Testing the app locally outside of docker from the project directory run
`yarn install`
`yarn start`

Use this URL to view the api locally:
<http://127.0.0.1:8080>

## Running in your local docker

`docker build -t interimaginary:api .`
`docker run -p 8080:8080 interimaginary:api`

## Deploying to heroku (deploys the static app not the container)

`heroku login`
`git remote add heroku https://git.heroku.com/still-fjord-81783.git`
`git push heroku main`
`heroku open`

Viewing the API in the heroku container:
<https://still-fjord-81783.herokuapp.com/>
