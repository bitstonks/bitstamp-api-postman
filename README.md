# Bitstamp API Postman
Bitstamp Postman REST API Collection


[Postman](https://www.postman.com/) is a simple to use API testing tool which allows anyone to make requests to REST API Endpoints.


## Prerequisites
Create and activate API Key on your Bitstamp account: https://www.bitstamp.net/settings/access-control/api/

- Be careful when it comes to permissions. 
- Only enable permissions that you intend to use. 
- For maximum security use Whitelist address feature https://www.bitstamp.net/account/withdraw/whitelist/ for Crypto Withdrawals.
- You can also use REST API with the combination of a Sub Account, where withdrawals are not possible https://www.bitstamp.net/account/sub-accounts/
- Never share your API Credentials with anyone!


## Setup
- Download `bitstamp-api-postman` repository.
- Open Postman
- On the top left, click `import` button and select `bitstamp-collection.json` and `bitstamp-env.json` 
-  Import both JSON files


## Credentials Setup
- Once you have collection and environment files imported, click on `Environments` in the upper left side and Open Bitstamp Environment.
- Update Initial and Current Values for `apiKey` and `apiSecret` variables with your API credentials.
- Save the environment
- The result should look like:

| Variable  | Type    | Initial Value            | Current Value            |
|-----------|---------|--------------------------|--------------------------|
| baseUrl   | default | https://www.bitstamp.net | https://www.bitstamp.net |
| apiKey    | secret  | your-api-key             | your-api-key             |
| apiSecret | secret  | your-api-secret          | your-api-secret          |


## Usage
- Have your Bitstamp environment selected in the top left corner prior to making a request
- Select any desired request in the Collection
- Click Send 


## Bitstamp API
Documentation is available at https://www.bitstamp.net/api/


## Troubleshooting


## Structure
