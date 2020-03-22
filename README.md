# ocp4-vmware
## prepare-iso.yaml
Create the ISOs for RHCOS with static IP configuration. Tweak using the inventory.yaml and the group_vars/all.yaml

## upload-iso.yaml
Upload the ISOs to vsphere datastore. Tweak using the inventory.yaml and the group_vars/all.yaml

## create-installer.yaml
Create the ignition files and setup a apache webserver to serve them. Tweak using the inventory.yaml and the group_vars/all.yaml
