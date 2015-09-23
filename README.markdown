## Nest Control sample app with jQuery

A simple thermostat control application that demonstrates how to access the Nest API from a web
application.

## Requirements
The development environment is a simple Node.js server managed by Yeoman. If you don't have them already
install these tools first:

* [Node](http://nodejs.org/download/)
* [Yeoman](http://yeoman.io/gettingstarted.html)

## Prerequisite
In order to run this example you must first create a client in the Nest Developer portal (https://developer.nest.com/clients).  The client should be created with the following required attributes:

OAuth Redirect URI:  http://localhost:8080/auth/nest/callback
Permissions:  Thermostat read/write

All other attributes values are not specific and can be determined by the developer.

## Running
To install required Bower components and Node modules, simply type:

    $ bower install
    $ npm install

Next you will need your client ID and client secret from developer.nest.com/clients set as environment variables:

    $ export NEST_ID=<CLIENT ID>
    $ export NEST_SECRET=<CLIENT SECRET>

And finally, use Grunt to start the server:

    $ grunt

Then open http://localhost:8080 in your browser and you will be walked through the authentication process.

## License

LCDBOLD
Copyright © 1999 by Samuel Reynolds. See /app/fonts/LCDBOLD/readme.txt

control-jquery
Copyright 2014 Nest Labs Inc. All Rights Reserved.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
