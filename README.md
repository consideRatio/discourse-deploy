# A deployment of Discourse

This README is for the information about the deployment of a discourse for OpenHack and how to maintain it.

# About how to install

1: Go to https://console.cloud.google.com
   - Visit [Compute engine -> VM Instances](https://console.cloud.google.com/compute/instances?project=ds-platform).
   - Create a VM instance of n1-standard-1
   - Create it in finland for quite low climate impact compared to other regions.
- HTTP + HTTPS
- ALlow full access to cloud APIs   - 



# About the setup

Discourse software: https://github.com/discourse/discourse_docker 

Where is it deployed?
- Google


Domain config:
- Orderland
- forum.openhack.io, an A record points to Google VM's external IP

Email config:
- https://www.oderland.se/support/artikel/hur-skickar-jag-mail-med-smtp-i-wordpress/

https://github.com/discourse/discourse/blob/master/docs/INSTALL-cloud.md#start-discourse

How was the authentication setup?
- 

# About maintenance

## To upgrade
We do it by ...

## To add a plugin
We do it by ....

