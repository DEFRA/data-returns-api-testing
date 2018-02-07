# Data returns PI API tests

The Data Returns (PI) service will be a new [digital service](https://www.gov.uk/service-manual/digital-by-default) for submitting environmental monitoring data to the [Environment Agency](https://www.gov.uk/government/organisations/environment-agency).  It is being developed in a phased approach, and the first type of data you will be able to submit is the landfill emissions monitoring data that is required by many environmental permits.

The first Phase is designed to allow Permit Holders to submit there annual PI returns using an online service


## About this project

This project contains the automated API test for the Data Returns PI and LF services. We use Postman, (https://www.getpostman.com/) as the means to test the service, and this project contains the collections required to test Landfill. Master and PI APIs

## Pre-requisites
* Download Postman API client for Chrome- https://www.getpostman.com/
* Clone Master Data API to local machine - git clone https://github.com/DEFRA/data-returns-data-exchange.git


## Execution

### Postman API client
Once postman has been installed, collections from the git repo can be imported and run with the Postman API Client.

* Open Postman API client
* Import Postman Collection files from git repo into postman (Import button top left hand side)
* Click on Collection tab top left, and the imported Collections should appear.
* Collections should be now ready to execute:

https://www.getpostman.com/docs/postman/sending_api_requests/requests


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
