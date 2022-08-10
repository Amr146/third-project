# Pipeline process
1. We make a change in the project
1. Then we commit and push the change to the github repository
1. then CircleCI starts working and running scripts according to the config.yml to build the api and frontend
1. CircleCI waits for approval 
1. CircleCI starts to deploy both the api and the frontend
1. the updates reaches AWS and is applied 
1. the updates is live and available for users