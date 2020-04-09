# Nirmata Circle CI Orb

## Getting Started
This orb is avaible on CircleCI Orb Registry.  The usage and examples are the definative guide to using this orb.
https://circleci.com/orbs/registry/orb/nirmata/nirmata

## Modifying the Orb
The orb.yaml file contains everything you need to customize the orb for your own use.  See orb docs for syntax details.  Email support with questions using nctl or the Nirmata API.

## Requirements
- Internet access to download nctl from S3
- Access to the orb

## Using on sites with restricted internet
- Create container with nctl binary
- Customize orb
  - Remove the download, and chmod sections
  - Fix the path to nctl
  
## Compatiblity with prior releases
 This orb was tested on Nirmata PE 2.9.3, and nirmata.io (~10.x).  Versions prior to 2.8.0 should use the older curl based 1.1.2 version.  The code for the 1.1.12 release is the head of this repo.

## Support 
  If you have issues with this orb or need help customizing the orb please email support@nirmata.com.
