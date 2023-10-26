# microservices-config
Git repo for all configurations of Bank microservice

## Table of Contents

- [Project Overview](#project-overview)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Running the Config Server](#running-the-config-server)
- [Configuration Management](#configuration-management)
  - [Git Repository](#git-repository)
  - [Configuration Files](#configuration-files)
- [Client Services](#client-services)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

In microservices architecture, it's essential to manage configuration properties efficiently across services. The Spring Cloud Config Server simplifies this by providing a centralized location for storing and distributing configuration properties. This project demonstrates how to set up a Spring Boot Configuration Server and how client services can retrieve their configuration from it.

## Getting Started

### Prerequisites

To run this project, you need the following tools installed:

- [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-downloads.html)
- [Maven](https://maven.apache.org/download.cgi)

### Running the Config Server

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/samah222/microservices-config.git

2. Navigate to the project directory:
   ```bash
   cd spring-boot-config-server
   
 The Config Server will start on port 8085, see the application.properties file.
