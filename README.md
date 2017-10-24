# Step Functions Example
This is an example of creating, deploying and invoking AWS Step Functions created with the Serverless Framework.


## Prerequisites

* You have made you AWS access and secret key available through a provided method, like storing them in the ~/.aws/credentials file or export them into environment variables
* You need to install Node.js  with a minimum version of 6.5.0 
* Then you need to install the serverless CLI with `sudo npm install -g serverless`
* `npm install`


## Deploy

* `serverless deploy -v`


## Test

Now you could invoke the Step Function with `serverless invoke stepf -n hellostepfunc1` if everything went fine. We should see the output: `ciao world!`


## Undeploy

* `serverless remove`