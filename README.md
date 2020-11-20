# Salesforce Marketing Cloud - Transactional Send Journey & Event Notification Service - Postman Collection

## Introduction

This is a [Postman](https://postman.com) collection containing the necessary requests to interact with *Transactonal Send Journeys* and set up the *Event Notification Service* in Salesforce Marketing Cloud.

## Setup

Create a set of environment variables and define the following ones:

 - clientId (the client id from the installed package in Marketing Cloud)
 - clientSecret (the client id from the installed package in Marketing Cloud)
 - accountId (the MID of your Marketing Cloud business unit or account)
 - authEndpoint (the authentication endpoint from the installed package in Marketing Cloud)
 - hostEndpoint (the REST endpoint from the installed package in Marketing Cloud)
 - access_token (no need to set a value here)

## Usage

Import the collection into [Postman](https://postman.com), select the environment you set up earlier and modify the requests to suit your needs. This includes setting the desired keys, adding the subscriber information you need to use, and switching the IDs with the ones you get back from some other requests.

The first request you need to send is the one called *Request SFMC Token v2* in order to authenticate your API requests.

## API documentation

The API endpoints that are part of the collection are documented by Salesforce here:

 - [Transactional Messaging API](https://developer.salesforce.com/docs/atlas.en-us.noversion.mc-apis.meta/mc-apis/transactional-messaging-api.htm)
 - [Event Notification Service](https://developer.salesforce.com/docs/atlas.en-us.mc-apis.meta/mc-apis/ens.htm)

## Contributors

|Major Contributors | |
|:----|----:|
|Markus Slabina |[![mslabina on Twitter](https://raw.githubusercontent.com/ExactTarget/fuelux/gh-pages/invertobird-sm.png)](https://twitter.com/mslabina) [![mslabina on Github](https://raw.githubusercontent.com/ExactTarget/fuelux/gh-pages/invertocat-sm.png)](https://github.com/mslabina) |

## License (MIT)

__Copyright © 2020 [Markus Slabina](https://github.com/mslabina)__

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
