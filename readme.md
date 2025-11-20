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


