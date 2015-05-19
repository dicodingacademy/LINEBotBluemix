[![Build Status](https://travis-ci.org/garethjevans/springboot-bluemix-example.svg?branch=master)](https://travis-ci.org/garethjevans/springboot-bluemix-example)

To build the application, clone the repository and build the app.

```
mvn clean install
```

Login to bluemix using the cloudfoundry api, push the application.

```
cf api https://api.ng.bluemix.net/
cf login
cf push
```

To debug the appliction use the following commands.

```
cf logs springboot-bluemix-example
cf events springboot-bluemix-example
```

newrelic

