# jmeter-examples
This is a collection of examples of usage of JMeter for different purposes.
In order to run each test case, just install on your system the latest JMeter, open it and open the file of the test case you would like to run.
Please note that in some test cases extra requirements may be needed (e.g. installing on local a target server like HttpOrg.bin, that sometimes does not work on the web anyway it can be deployed locally with Docker).

List of test cases:
- TestBasicAuth.jmx -> Test the HTTP Basic Authentication against httpbin.org (on the website or on the site deployed on local via Docker)
- LogicControllers.jmx -> Example of usage of some logic controllers
- BrowserRecording.jmx -> Example of a test case registered from a browser
- ExtractModifyReuseVar.jmx -> Example of usage of variable extractor from a response (JSON Extractor), modification (via JSR223 PostProcessor) and reusage in a subsequent request
