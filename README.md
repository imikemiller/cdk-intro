# Setup

In both directories (cdk and cdk demo) run 

`npm install`

This will install all the packages from the node repository.

If you want to run the react web application on your local machine go into the `cdk-demo` directory and run

`npm run start`

# Deploy

Setup your AWS keys and then go into the `cdk-demo` directory and run

`npm run build`

This will create the `build` directory ready to be deployed. Once this is completed run

`cdk bootstrap aws://<your account ID>/<Region from ~/aws/config>`

then

`cdk deploy`
