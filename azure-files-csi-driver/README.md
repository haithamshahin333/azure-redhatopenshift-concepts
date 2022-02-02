# Install Azure File CSI Driver

1. [Azure File CSI Driver Docs](https://github.com/kubernetes-sigs/azurefile-csi-driver)
2. [ARO-Related Issue](https://github.com/kubernetes-sigs/azurefile-csi-driver/issues/714)
3. [NFS Details](https://github.com/kubernetes-sigs/azurefile-csi-driver/tree/master/deploy/example/nfs)

# Steps
1. Run through `script.sh` step by step
2. Deploy `example-sc.yaml` and `example-pvc.yaml`
3. You should see the NFS File share dynamically deployed and a Service Endpoint created where the NFS File Share is access from the ARO worker subnet
> Note: You can also customize to use private endpoints as well - [example](https://github.com/kubernetes-sigs/azurefile-csi-driver/issues/718)

# Troubleshooting
1. Validate the `deploy/cloud.conf` json looks accurate
