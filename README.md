# CloudFoundry Example based on a Simple Servlet

There are many ways how to build services with java on cloud foundry. One option is to use just a plain servlet and build a service within that. 

## Prepare and Deploy

Go into the manifest and replace the org name d043918trial with your org name
Then build the java war package with Maven
```
mvn clean install
```
Then push to Cloud Foundry
```
cf push
```




