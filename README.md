# Azure-Platform-Maintenance-Notification
Azure Platform Maintenance Notification using In-VM Metadata Service

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fwasimbloch%2FAzure-Platform-Maintenance-Notification%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

This template creates the virtual machine with In-VM metadata service is installed using the windows task scheduler. Task scheduler is configured to use in-VM metadata service using the PowerShell script and creates the event viewer entry for upcoming virtual macine reboot event. User can configure OMS and can view maintenance notification for the upcoming virtual machine Reboot event.
