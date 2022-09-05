# Getting Started





# Deploy Backend 
To deploy an application run the following commands:
            cd backend

            npm install

            npm install --save-dev serverless-iam-roles-per-function@next 

            serverless

            serverless deploy --verbose

# Deploy Frontend

       To run a client application first edit the client/src/config.ts file to set correct parameters. And then run the following commands:
             cd client
            npm install
            npm run start
            
       This should start a development server with the React application that will interact with the serverless TODO application.

