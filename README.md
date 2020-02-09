# Config Preoday

## Description

This Micro Service is a Config Server that provide configuration of any Spring Boot Application. Created thinking on Weatherman API.
Is responsible to provide API-KEY, API-VER and API-FEED-TYPE to Weacherman API.

## Motivation

Principal motivation is to externalize configuration about NASA API on Weatherman API, that you can modify in this project and you can have efect on Weatherman API.
It was created thinking future propourses, also, like others Micro Services specific configurations

## How to make it work

* First, you need setup Java 8 Environment (JDK, JRE... )
* After, open this project in any IDE (i recommend Intellij)
* Now, you can run without problems :)

## Architecture

This Micro Service has communication with Eureka, that is registered to it
