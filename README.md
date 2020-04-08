# apigee-mock-api-cicd
- Maven deploy instructions 
```
cd ./pallab-mock-api
export apigee_email=roykpallab@gmail.com
export apigee_password=Pall@1985
export apigee_org=roykpallab-eval
mvn install -Ptest -Dusername=$apigee_email -Dpassword=$apigee_password -Dorg=$apigee_org

```
