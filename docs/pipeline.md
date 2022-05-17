CI/CD
-----

The git repository for this project is connected to circleCi, When developers commit and push any code modification to the repo circleCi will be triggered then in circleCi will carry out all the steps mentioned in the yml file (which available in .circleCi/config.yml from repo main branch) in order to build and deploy frontend to s3 bucket and backend to elastic beanstalk.

Note:

- CircleCi build and deploy ethier frontend or backend through running build and deploy scripts mentioned in package.json.
- All environment variables added to circleCi.
