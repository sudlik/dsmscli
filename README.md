# DSmsCli
## About
CLI for SMSAPI REST API ([smsapi.pl/rest](http://smsapi.pl/rest)) written in D programming language ([dlang.org](http://dlang.org))
## Examples
```
// authenticate yourself as mail@example.com by p@5sw0rd password and send test ECO sms to 555012345 with content "Hello world!"
$ rdmd main sendsms test mail@example.com p@5sw0rd ECO 555012345 "Hello world!"
// authenticate yourself as mail@example.com by p@5sw0rd password and send test mms to 555012345 with subject "Hello world" and content from helloworld.smil
$ rdmd main sendmms real mail@example.com 1e010f40299bff32073402166e930c23 "Hello world" 555012345 helloworld.smil
```
## ToDo
 * add changing host
 * allow multiple receivers
 * add docs
 * add tests
 * add more examples
 * add named arguments