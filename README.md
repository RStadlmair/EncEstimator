# EncEstimator

Encryption Estimator for SEPPmail users

## Use case

SEPPmail offers a REST-API "the Legacy API" to query statistical information about
its status. One of this features allows to estimate what kind of encryption the APpliance will use for a specific E-Mail address. 
The code in this repository should finally be a C#/.NETCore/WPF Application that allows the user to enter an E-Mail address to find out what kind of encryption is going to be used.

## APP Description

The Application has a simple user interface with a usage and one config page.
In the config page you have to specify 3 values.

* Base link to the  SEPPmail API
* Username (in e-mail address format)
* Password

The main page has a single field to enter an e-mail address and a "Go" button to query the SEPPmail legacy app.

After the query is complete, one of the five options for encryption are shown in the program

## Current status

As of today (17. Feb .2020) the app is not even in alpha state. Currently, the mechanism to query the REST-API is implemented and delivers a raw JSON file and is listed in a different namespace. This has to be moved into the main app.
All "todo´s" are listed in "issues", and i am going to work on those from now on.
