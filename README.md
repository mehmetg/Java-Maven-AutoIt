##Java-Maven-AutoIt Example

Uploads hello.exe and runs it as part of the test run. It should display a "Hello World!" message box with an OK button.
You may need to minimize the browser to see it, if you take over the control of the session.

>This code is presented as an example only, since your tests and testing environments may require specialized scripting. This information should be taken only as an
>illustration of how one would set up tests with Sauce Labs, and any modifications will not be supported. For questions regarding Sauce Labs integration, please see 
>our documentation at https://wiki.saucelabs.com/.

###Environment Setup:

``` export SAUCE_USERNAME=<username>```<br>
``` export SAUCE_ACCESS_KEY=<key>```<br>
``` export AUTOIT_FILE=<full path to file>```<br> 
You should point it to the included hello.exe file

###Test Run:

```mvn test```
