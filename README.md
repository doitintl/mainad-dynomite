# mainad-dynomite

## Deploy

to deploy simply run :  

```bash
sh ./create-cluster-bidder-settings.sh

```

## Details

This will create instnaces in multiple regions with docker (you can see the startup script in the create-cluster-bidder-settings.sh)
The startup script will :
  1. change the configuration-file-template.yaml according to the region and zone
  2. deploy docker containers with dynomite running startup script startup.sh


