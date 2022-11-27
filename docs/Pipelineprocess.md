# udagram


## Pipeline

```
- npm run frontend:install - to install frontend dependencies
- npm run api:install - to install backend dependencies
- npm run frontend:lint - to lint the frontend code for style erros
- npm run frontend:build - to build the frontend code
- npm run api:build - to build the backend code
- npm run api:env - to export the ENV to the build folder
- npm run api:zip - to zip the www folder to then deploy
- npm run api:ebenv - to set the ENV in the EB service
- npm run api:deploy - to deploy the backend to the EB service
- npm run frontend:deploy - to deploy the frontend to the S3 service
```
![Screenshot](https://github.com/Ibrahimzn/finalproject/blob/master/docs/digrams/pipelinedigram.png?raw=true)