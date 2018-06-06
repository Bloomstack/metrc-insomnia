# Insomnia Export file for METRC

![image](https://user-images.githubusercontent.com/6697133/41035043-1ea8330e-69a9-11e8-99c1-21947c9462ba.png)

When going through METRC's Evaluation we realized that it would be better if we organized our requests, to be able to quickly test and iterate. 

## What does this include?
* All the API Endpoints that are required to pass the evaluation and a bit more
* REST Entities separated as folders
* Separate sub-environments for each "Facility" for the Sandbox
* Every POST request has a JSON Body that can be used with some minor changes (Usually tags)

## Setup

* Import METRC.json into your [Insomnia REST Client](https://insomnia.rest/)
* Open "Manage Environments" and set the API Keys as variables in the "Base Environment"
* Change the URL if required (by default it points at the California Sandbox)
* Select the Sub-Environment (Facility) you want to use or make your own
* That's it!

## TODO 

* Add the rest of the endpoints
* Add comments for confusing endpoints
* REST

## Links 
* [METRC API Documentation](https://sandbox-api-ca.metrc.com/Documentation#)