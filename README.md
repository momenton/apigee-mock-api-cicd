# apigee-mock-api-cicd
- Maven deploy instructions on ec2 instance 
```
cd ./mock-api-proxy
export apigee_email={apigee username}
export apigee_password={apigee password}
export apigee_org=roykpallab-eval
mvn install -Ptest -Dusername=$apigee_email -Dpassword=$apigee_password -Dorg=$apigee_org

```
