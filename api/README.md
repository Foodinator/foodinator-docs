# Foodinator API

## Purpose of this component
- Act as a gateway to the services that we provide
- Provide the AI component with the right information

## Tech Stack choice
- For productivity reasons, We choose to go with nodejs. Framework: Express
- For The flexibility in the db side, we choose Mongodb. Framework: Mongoose

## Architecture
- It doesn't matter at this point. Something standard and easy to use is and understand by others is the priority now.
- Might change in the future.

## Branches
- master: We leave this for the production system. Our production server code will be here. This branch will have a job that makes it possible for continious integration with each push. The only branch that can merge into this one is the developement branch. 
- Developement: This is the developemnt branch, the one that we dont push to directly. And the one where we make our new features and see if they work well, by writing tests of course. 
- other branches: If you want to implement a feature, you make a branch with the name of tha feature and then, you have to write tests for it and then make a pull request. 
