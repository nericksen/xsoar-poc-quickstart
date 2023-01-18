# XSOAR POC Quickstart Guide

The resources in this repository are intended to reduce the reptitive tasks involved with setting up a POC
for XSOAR and providing some example integration configurations and use cases.

As of now the repo contains the `xsoar_config.json` file needed to run the XSOAR CI/CD content pack which 
will auto install popular marketplace packs and configure some reccomended TIM feeds.

### Resources
* link to XSOAR CI/CD article
* link to XSOAR CI/CD marketplace pack


### Requirements
* XSOAR installation
* XSOAR CI/CD content pack
* Demisto API integration


## Instructions (Quick Start)
1. Start by deploying your XSOAR instance or logging into your hosted instance.
2. Generate an API key with admin privledges and add it to the "Demisto API" integration
3. Install the "XSOAR CI/CD" content pack from the marketplace.
4. Upload the POC quick start configuration playbook
5. Create a "Configuration Setup" incident type with the `xsoar_config.json` attached and no custom packs to install
6. Once the packs are installed run the Quickstart configuration playbook to setup and initialize the TIM feeds.


### Known Limitations
* Currently there is only content for auto deploying TIM feeds and use cases
* In the future this will configure incident use cases as well. 
