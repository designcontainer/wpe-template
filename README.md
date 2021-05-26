# Setup guide

## Setup WP Engine install
## Create a WP Engine install
No need to use any template here. Just create a blank install with your desired install name.

## Setup repository
### Create a repository using this template
After you have recieved confirmation from WP Engine that your install has finished setting up, create a new repo using this template. 

![New repository screenshot](https://i.gyazo.com/923ab502b818ec4855e7dec160cd24f7.png)

### ⚠️ Setting repository name
It is important that your repository name matches your WP Engine install name, as it will be used for directly establishing a connection with the install using the wp-engine workflow.

## After initializing repository
### Set topics
To keep our Github repositories clean and consistent please asign the following topics as you see fit:
- `global-ci` The global action handler will automatically update all repositories tagged with this topic.
- `production`, `staging`, `development` The environment type.
- `site` The repo type.
- `wpengine` Where the site is located.

### Readme
Rename the `README-template.md` file to `README.md` and fill out the blank spaces.