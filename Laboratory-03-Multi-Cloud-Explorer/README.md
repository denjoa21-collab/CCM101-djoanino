## Checkpoint 7: Linux Investigation Results

### System Information

| Information | Result |
|-------------|--------|
| **Operating System** | Ubuntu 24.04 LTS |
| **CPU** | Architecture:                x86_64
            CPU op-mode(s):            32-bit, 64-bit |
| **Memory** | Mem:           1.9Gi       427Mi       855Mi       1.1Mi       789Mi       1.4Gi|
| **Disk Space** | /dev/vda1        19G  5.4G   13G  30% /|


### Cloud Migration Options

If this Linux server were migrated to the cloud, the following services could host it:

**AWS:**
- **Amazon EC2** - Direct migration of the Ubuntu VM
- **AWS Lightsail** - Simpler, cost-effective alternative
- **AWS Elastic Beanstalk** - For PaaS-style deployment of applications

**Azure:**
- **Azure Virtual Machines** - Migrate the Ubuntu server using Azure Migrate
- **Azure App Service** - For web applications running on Ubuntu
- **Azure Container Instances** - Containerize the workload

**GCP:**
- **Compute Engine** - Direct VM migration with Ubuntu images
- **Cloud Run** - For containerized applications
- **App Engine Flexible** - PaaS option for web applications

### Migration Considerations

The choice of cloud service depends on:
- The workload type (web application, database, API server, etc.)
- Migration strategy: 
  - **Lift-and-Shift** - Move the VM as-is (EC2, Azure VMs, Compute Engine)
  - **Re-platform** - Make minimal changes for optimization
  - **Refactor** - Rebuild as a cloud-native application
- Cost considerations and required performance
- Integration requirements with other cloud services
- Security and compliance requirements

### Commands Used
