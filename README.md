# AzureVMMetadata

The Azure Instance Metadata Service (IMDS) provides information about currently running virtual machine instances. We can use it to manage and configure your virtual machines. This information includes the SKU, storage, network configurations.

IMDS is a REST API that's available at a well-known, non-routable IP address (169.254.169.254). We can only access it from within the VM. Communication between the VM and IMDS never leaves the host.
