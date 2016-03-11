# Create a SoftNAS Cloud Virtual Machine with NFS/CIFS Enabled

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fjimyjohny%2Fazure-quickstart-templates%2Fmaster%2Fsoftnas-cloud%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fjimyjohny%2Fazure-quickstart-templates%2Fmaster%2Fsoftnas-cloud%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

This template allows you to create a SoftNAS Cloud Virtual Machine from a specified image. It also attaches one empty data disk and share it using NFS/CIFS. This template also deploys a Storage Account, Virtual Network, Public IP addresses and a Network Interface.

NOTE: Before you can use a marketplace image from an API, you must enable the image for programmatic use. In the Azure portal, find the marketplace image (Softnas BYOL ) that you want to use and then click Want to deploy programmatically, Get Started ->. Enter any required information and then click Save.
