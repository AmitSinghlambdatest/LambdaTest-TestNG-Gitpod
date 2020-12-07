# Welcome to Lambdatest - Java TestNG Selenium 

## Step 1: Configure your settings and required capabilites for your test

For running a test we will need your `username` and `access key` to map with our cloud infrastrure. 

You can find the required credentials here : <https://www.lambdatest.com/capabilities-generator>

### Change the properties 

Add your Lambdatest `username` and `access key` in testcase.java
```
String username = <YOUR LT_USERNAME> #Replace with your username
String accessKey = <YOUR LT_ACCESS_KEY> #Replace with your access key
```

## Step 2: Running Tests

We have preinstalled all the required environment for running the tests. You can now execute the tests in the console by the following commands: 

#### To run single test
```
$ mvn test -P single
```

#### To run parallel/multiple test
```
$ mvn test -P parallel
```


## Step 3: Test Results

Once you have completed running the tests you can find the results at : <https://automation.lambdatest.com> with the build name `TestNG` as a prefix. 

For any other quires please connect with us at <support.lambdatest.com>

### Happy testing! :computer:
