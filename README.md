# Azure Service Database

This repo contains an example of the Azure Service Components for Clams (last update 15.05.2021).
All data was gathered from the (Microsoft Pricing Calculator)[https://azure.microsoft.com/en-us/pricing/calculator/]. We gathered 18.000+ service configurations, call components, and arranged most of them into pattern refeinment trees in combination with (Cloud Computing Patterns)[http://www.cloudcomputingpatterns.org].


This data is meant to be used with the component-registry-server. So please install the it first from 
https://github.com/openclams/component-registry-server.


The `azure_cloud_service_database.sql` file contains the tables with the components. Load them with your favorite mysql client into the database used by the component-registry-server. 

Additionally, you need to copy the icons to the component-register-server.
Unzip `components.zip` to `components/`, and move the components folder to  the  `storage/app/public` of the component-register-server.

# License:

## Microsoft Azure Icons

Source: https://docs.microsoft.com/en-us/azure/architecture/icons/

Terms: Microsoft permits the use of these icons in architectural diagrams, training materials, or documentation. You may copy, distribute, and display the icons only for the permitted use unless granted explicit permission by Microsoft. Microsoft reserves all other rights.

Read also the full Terms of Use: components/azure/Microsoft_Terms_of_Use.pdf

## Cloud Computing Pattern

These icons are released unter the Creative Commons Attribution 4.0 International License.
Please include the following in your PNG file and text to give appropriate credit:

CC-BY.png http://www.cloudcomputingpatterns.org

License: http://creativecommons.org/licenses/by/4.0/
