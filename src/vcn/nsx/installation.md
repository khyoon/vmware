# Installation

NSX-T Installation: Deploy Additional NSX-T Manager Nodes from UI

login into the MSX manager UI https://nsxmanagerip

Click System -> Overview -> Add Nodes:

![](https://i0.wp.com/virtual-llew.com/wp-content/uploads/2020/02/image-56.png?fit=640%2C474&ssl=1)

2Select the Compute Manager from the drop-down menu, enable SSH (if required), enter the cli and root password, DNS, NTP and select the form factor:

**_Note:_** _Select the same form factor as of the first NSX-T manager deployment in_ [https://virtual-llew.com/nsx-t-deployment-deploy-nsx-t-manager/](https://virtual-llew.com/nsx-t-deployment-deploy-nsx-t-manager/)

![](https://i1.wp.com/virtual-llew.com/wp-content/uploads/2020/02/image-57.png?fit=640%2C511&ssl=1)

Specify the name, vSphere cluster, datastore and network details:

![](https://i2.wp.com/virtual-llew.com/wp-content/uploads/2020/02/image-58.png?fit=640%2C510&ssl=1)

The status could now be monitored from the same screen, screenshot below showing _deployment in progress_:

![](https://i1.wp.com/virtual-llew.com/wp-content/uploads/2020/02/image-59.png?fit=640%2C362&ssl=1)

A successful deployment will show the “Management Cluster” as _Stable_, “Cluster Connectivity” as _Up_ and “Repository Status” as _Sync Complete_, as shown in the screenshot below:

![](https://i1.wp.com/virtual-llew.com/wp-content/uploads/2020/02/image-60.png?fit=640%2C362&ssl=1)