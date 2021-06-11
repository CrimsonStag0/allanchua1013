# API Gateway + Vue JS + Express + PostgreSQL 

This repository showcases an API gateway fronting an app that uses Vue JS, Express and PostgreSQL. Each piece of architecture is running isolated on their own container.

## How it looks like in local

TODO: Add diagram for local development

## How it will look like in AWS

![Stack Diagram](https://github.com/allanchua101/api-gateway-vue-express-pg/blob/master/Stack%20Diagram.png "Stack Diagram")

## Pre-requisites

The following items should be installed on your machine:

- Docker          (Containerization)
- Docker Compose  (Service Orchestration Locally)
- NodeJS          (API and GUI Development)
- .NET Core       (API Gateway Development)

## Technology Stack

- .NET Core
- Node JS
- VueJS
- Express JS
- Ocelot
- PostgreSQL

## Running Application

Run the following on the project root directory:

```sh
docker-compose up
```

## Access GUI

To access GUI, navigate to [http://localhost:52793](http://localhost:52793)  

To hit an API, navigate to [http://localhost:52793/v1/api/users/list](http://localhost:52793/v1/api/users/list)

### TLDR;
I'm writing about API gateways in my blog @ [https://www.pogsdotnet.com](https://www.pogsdotnet.com)
  
### Buy me a [beer](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&token=ic5ciSp5Z94TumpnfONJmROb0xippis50yfGler3P855dm7ULl_Yq1AuAucXDmVob9IRLW) so I can code more? :beer:

![QR Code](https://github.com/allanchua101/api-gateway-vue-express-pg/blob/master/QR%20Code.png "QR Code")
