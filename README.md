# apigee-mock-api-cicd
- Maven deploy instructions 
```
cd ./pallab-mock-api
export apigee_email={apigee username}
export apigee_password={apigee password}
export apigee_org=roykpallab-eval
mvn install -Ptest -Dusername=$apigee_email -Dpassword=$apigee_password -Dorg=$apigee_org

```
