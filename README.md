AWS-EC2-Custom-AMI-Creation

To create a Custom Amazon Machine Image (AMI) from an existing EC2 instance. 
AMIs are essential for capturing a "snapshot" of a configured server, allowing you to create backups
or launch multiple identical instances with the same software, settings, and data without manual reconfiguration.


 Architecture Components
**Source EC2 Instance: The virtual server used as the template for the image.

**Amazon Machine Image (AMI): The resulting snapshot containing the software configuration (operating system, 
                               application server, and applications).

**Snapshot: The underlying storage backup of the instance's EBS volumes
