# Code 401: Advanced Software Development in Full-Stack Javascript:

## Lab 16: AWS Cloud Server

## [Github Pull Request](https://github.com/nickibaldwin/basic-express-server-aws/pull/1)

## GUI Deployment:
Working: http://servertestbab-env.eba-ebd232db.us-west-2.elasticbeanstalk.com/

1. Choose NodeJS as your platform

1. Create and upload a server.zip file with your application source code

1. Did not include node_modules or package-lock.json

## CLI Deployment: 
Broken: http://aws-server-test.eba-ebd232db.us-west-2.elasticbeanstalk.com/

1. `eb init` - Initializes your folder as an Elastic Beanstalk application

1. Choose your region (us-west-2)

1. Choose [Create new Application]

    Note: If you already have an application, you could also choose that to connect

1. Answer the other questions as appropriate
    Choose Node.js at the correct version

1. `eb create my-environment-name` - Create an "environment" for your app to reside in

1. `eb deploy` to deploy your new application to your new environment
You'll also use this whenever you make code changes