# ArgoCD Sample

This sample is part of a blog article, demonstrating an usage of DataImportCron (DIC) deployed by
ArgoCD in a specific OpenShift cluster(s).

DataImportCron (DIC) deploys a new DataVolume (DV), PresistentVolumeClaim (PVC) and a DataSource (DS)
that will import an exported containerDisk from the container registry and display it as a
golden image to create a Virtual Machine (VM) from InstanceType. 
