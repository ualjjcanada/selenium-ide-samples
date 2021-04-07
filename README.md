# selenium-ide-samples

Samples of [Selenium IDE](https://www.selenium.dev/selenium-ide/) tests.

## inputTextFieldValidation
Example projects for testing validation of input fields in HTML5.

Validation messages are checked in Spanish, harcoding the messages in asserts commands. So to pass the tests you should run these projects in Selenium IDE for *Firefox* configured *in Spanish*. 
You can allways search assert commands and update the harcoded messages to your language.


### Known issues
 
* `minlength` and `maxlength` attributes in input text fields are not properly managed by Selenium IDE [reported issue](https://github.com/SeleniumHQ/selenium-ide/issues/1222)