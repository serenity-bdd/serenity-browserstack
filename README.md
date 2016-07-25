# serenity-browserstack

[Serenity](http://www.thucydides.info/docs/serenity/) Integration with BrowserStack.

![BrowserStack Logo](https://d98b8t1nnulk5.cloudfront.net/production/images/layout/logo-header.png?1469004780)

<img src="http://www.thucydides.info/docs/serenity/images/serenity-logo.png" height = "100">

## Setup
* Clone the repo
* Install dependencies `mvn install`
* Update `serenity.properties` file with your [BrowserStack Username and Access Key](https://www.browserstack.com/accounts/settings)

## Running your tests
- To run a single test, run `mvn verify -P single`
- To run parallel tests, run `mvn verify -P parallel`
- To run local tests, run `mvn verify -P local`

## Notes
* You can view your test results on the [BrowserStack automate dashboard](https://www.browserstack.com/automate)
* To test on a different set of browsers, check out our [platform configurator](https://www.browserstack.com/automate/java#setting-os-and-browser)
* You can export the environment variables for the Username and Access Key of your BrowserStack account
  
  ```
  export BROWSERSTACK_USERNAME=<browserstack-username> &&
  export BROWSERSTACK_ACCESS_KEY=<browserstack-access-key>
  ```
  
## Additional Resources
* [Documentation for writing automate test scripts in Java](https://www.browserstack.com/automate/java)
* [Customizing your tests on BrowserStack](https://www.browserstack.com/automate/capabilities)
* [Browsers & mobile devices for selenium testing on BrowserStack](Browsers & Mobile Devices for Selenium Testing)
* [Using REST API to access information about your tests via the command-line interface](https://www.browserstack.com/automate/rest-api)
