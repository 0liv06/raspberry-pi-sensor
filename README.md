# raspberry-pi-sensor

## Synopsis
This application uses the Adafruit to use the DHT-11 sensor to monitor the temperature and humidity of the place it is currently located.

## Architecture
### Server.py
Is the Python script to be ran in the RaspberryPI that handles connections and returns the temperature and humidity information using JSON Format.

### WeatherAPI
Is the Java microservice to be ran using java -jar command used to talk to the RaspberryPI and expose Webservice method to access the temperature and humidity information coming from the PI.

### WeatherWeb
Is the User Interface (UI) enabling users to visualise the current temperature information.

## Setup
### Setup Python Server

### Setup WeatherAPI

### Setup WeatherUI

## Keywords
Raspberrypi3, python, Spring boot, Spring Web, Angular, Webservices

## Useful links