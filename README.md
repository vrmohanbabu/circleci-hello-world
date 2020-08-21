## Overview

Learning about the basic concepts used in CircleCI.

---

## Setup the Enviroment

* Fork this repository.
* AWS account with IAM role created with cloudformation and ec2 policy.

## Setup the CircleCI:

* Go to [https://circleci.com/](https://circleci.com/) and login with your GitHub account.
* Click "Add Projects".
* Click "Setup Up Project" on the selected repo.
* Click on the "Use Existing Config" to run the pipeline and click "Start Building".

## Create an env variable in CircleCI:

* In the [CircleCI](https://app.circleci.com/) application, go to your project’s settings by clicking the gear icon on the Pipelines page, or the three dots on other pages in the application.
* Click on Environment Variables.
* Add new variables by clicking the Add Variable button and enter a name as "name" and value.
* Add AWS IAM user access and secret Keys in CircleCI environment.
  * AWS_ACCESS_KEY_ID
  * AWS_SECRET_ACCESS_KEY
  * AWS_DEFAULT_REGION

### tags:

* Check out the tags to see different basic in CircleCI.
