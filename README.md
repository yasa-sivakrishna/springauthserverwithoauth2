

# SpringAuthServer

A Spring Boot application that functions as an OAuth2 Authorization Server, providing secure authentication and authorization services for client applications.

## Overview

This project implements an OAuth2 Authorization Server using Spring Boot and Spring Security. It supports various OAuth2 grant types and is designed to be easily integrated with client applications requiring secure authentication mechanisms.

## Features

* OAuth2 Authorization Server implementation
* Support for multiple grant types (e.g., Authorization Code, Client Credentials)
* Token issuance and validation
* Secure client registration and management
* Integration with Spring Security for robust security configurations

## Prerequisites

* Java 11 or higher
* Maven 3.6.0 or higher

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/yasa-sivakrishna/springauthserverwithoauth2.git
cd springauthserverwithoauth2/SpringAuthServer
```



### Build the Project

```bash
mvn clean install
```



### Run the Application

```bash
mvn spring-boot:run
```



The application will start on `http://localhost:9005`.

## Configuration

The application can be configured using the `application.properties` or `application.yml` file located in the `src/main/resources` directory. Key configurations include:

* Server port
* OAuth2 client details
* Token validity durations
* Security credentials

Ensure to update these configurations as per your requirements.

## Usage

Once the server is running, client applications can interact with it to obtain access tokens and authenticate users. Typical OAuth2 flows supported include:

* Authorization Code Grant
* Client Credentials Grant
* Password Grant (if enabled)
* Refresh Token Grant

Refer to the OAuth2 specifications and Spring Security documentation for detailed information on implementing these flows in your client applications.



---
