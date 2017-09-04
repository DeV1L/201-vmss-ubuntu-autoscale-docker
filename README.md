### Autoscale demo app on Ubuntu 16.04 ###

VM Scale Set which instaLls Docker and run container from Azure Container Registry. The VM Scale Set scales up when average CPU across all VMs > 70%, scales down when avg CPU < 30%.

- Login and password for ACR provides during deployment
- Deploy the scale set with an instance count of 1 
