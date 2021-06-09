# Deployment fun

## About
* install dependencies with `npm ci`
* run with `npm start`

## Task 1
* fork repo to your own github
* create yourself a Heroku account
* initiate deployment of the repo using pipelines into newly created free Heroku app
* initiate Heroku pipelines, enable Review Apps
* create a PR which will automatically set FUN environment variable

## Task 2
* initiate any kind of CI (GitHub Actions, CircleCI, ..), anything which can be connected to a GitHub
* initiate CI process - let it download dependencies, run dummy test, create deployment tarball
* utilize Ansible to initiate and deploy a machine - your local one (you can use vagrant with virtualbox, or use AWS free tier credits or any other kind of free cloud services)
* ideally, if using cloud, let the ansible deploy from the CI to the machine on e.g. `deploy` branch push
