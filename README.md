# Data returns PI API tests

The Data Returns (PI) service will be a new [digital service](https://www.gov.uk/service-manual/digital-by-default) for submitting environmental monitoring data to the [Environment Agency](https://www.gov.uk/government/organisations/environment-agency).  It is being developed in a phased approach, and the first type of data you will be able to submit is the landfill emissions monitoring data that is required by many environmental permits.

The first Phase is designed to allow Permit Holders to submit there annual PI returns using an online service


## About this project

This project contains the automated API test for the Data Returns PI and LF services. We use Postman, (https://www.getpostman.com/) as the means to test the service, and this project contains the collections required to test Landfill. Master and PI APIs

## Pre-requisites
* Donwload Postman API client for Chrome- https://www.getpostman.com/
* Close Master Date API to local machine - git clone https://github.com/DEFRA/data-returns-data-exchange.git


## Installation

Installing the Postman app

Postman is available as a native app for Mac, Windows, and Linux operating systems. To install Postman, go to the apps page and click Download for Mac / Windows / Linux depending on your platform.

* macOS installation
Once you’ve downloaded app, you can drag the file to the “Applications” folder. Double click on Postman to open the application.

* Windows installation
Download the setup file
Run the installer

* Linux installation
Installation on Linux can vary between distributions. Check out this guide for installing the Postman app on Ubuntu 16.04.

* Postman Pro

Postman Pro has the facilty to back and synchronise Postman collections on github, but the full version is required. 

Note: Cost involved with this version.

Details below:

https://www.getpostman.com/docs/pro/integrations/github



## Execution

###Postman API client
Once postman has been installed, collections from the git repo can be imported and run with the Postman API Client.

* Open Post man API client
* Import Postman Collection files from git repo into postman (Import but top left habd side)
* Click on Collection tab top left, and the imported Collections should appear.
* Collections should be now ready to execute:

https://www.getpostman.com/docs/postman/sending_api_requests/requests

### Command line exectution
Post collection JSON files can also be run from the command line using Newman

https://www.getpostman.com/docs/postman/collection_runs/command_line_integration_with_newman

### Jenkins integration
* Install and run through jenkins 

https://www.getpostman.com/docs/postman/collection_runs/integration_with_jenkins



## Contributing to this project

If you have an idea you'd like to contribute please log an issue.

All contributions should be submitted via a pull request.



## License

THIS INFORMATION IS LICENSED UNDER THE CONDITIONS OF THE OPEN GOVERNMENT LICENCE found at:

http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3

The following attribution statement MUST be cited in your products and applications when using this information.

> Contains public sector information licensed under the Open Government license v3

### About the license

The Open Government Licence (OGL) was developed by the Controller of Her Majesty's Stationery Office (HMSO) to enable information providers in the public sector to license the use and re-use of their information under a common open licence.

It is designed to encourage use and re-use of information freely and flexibly, with only a few conditions.
