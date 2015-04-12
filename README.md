To build the application, clone the repository and build the app.

```
mvn clean install
```

Login to bluemix using the cloudfoundry api, push the application.

```
cf api https://console.ng.bluemix.net/
cf login
cf push
```

```
cf logs springboot-bluemix-example
cf events springboot-bluemix-example
newrelic
```


