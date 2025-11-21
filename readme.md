# continuous Integration with github actions 

Continuoius Integration include lint, test, build

1. create a ci.yaml inside .github/worklows/ci.yaml 
   - ``` touch .github/worklows/ci.yaml ```

for lint
   - here eslint is used
for test 
   - jest is used
for build 
   - "build": "tsc && cp -R views dist/views"


# continuous delivery and deployment 

1. create a remote server (prefer not t2.micro)

2. ssh -> create a directory(prefer at home)-> clone the git repository (cd pipeline require to pull latest `compose.yml` file from github)

3. add server secrets inside github -> repo > settings > secrets & variable > actions

