# WSO2-Identity server docker-compose with Postgres-SQL

### Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [Usage](#usage)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)
<!-- * [License](#license) -->

## General Information

This is a docker-compose project for WSO2 identity server with PostgreSQL database support enabled

Database scripts are located at 

`\conf\identity-server\repository\scripts`

two databases will be created 

``WSO2_SHARED_DB `` and `` WSO2_IDENTITY_DB ``

Configuration file located at

`conf\identity-server\repository\conf\deployment.toml`

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used

- PostgreSQL - 14.3
- WSO2 Identity Server - 5.11.0

## Usage

Colone the project and run docker-compose up command

`docker-compose up`

for run only the identity server

`docker-compose -f docker-compose-only-wso-is.yaml up`

## Acknowledgements

Give credit here.

- https://github.com/wso2/product-is

## Contact

Created by [@chathunbandara](https://www.chathunz.com/) - feel free to contact me!
