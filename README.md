# Hub and Spoke ARO Example Deployment

The goal with this repo is to show an example of how to deploy a private, secure ARO and force-tunnel traffic through Azure Firewall in the Hub VNET. You can fork this repo and add/customize as needed.

Under the `hub-spoke-deployment` directory you will find the guide to deploying the architecture.

### References
- [Hub and Spoke Architecture](https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/hybrid-networking/hub-spoke?tabs=cli)
- [Hub and Spoke Original Bicep Templates](https://github.com/mspnp/samples/tree/master/solutions/azure-hub-spoke)
- [Azure Red Hat OpenShift](https://docs.microsoft.com/en-us/azure/openshift/)

### Architecture
![](./images/aro-hub-spoke-diagram.png)