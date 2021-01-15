---
page_type: sample
languages:
- java
products:
- azure
extensions:
- services: Trafficmanager
- platforms: java
---

# Getting Started with Trafficmanager - Manage Simple Traffic Manager - in Java #


  Simple Azure traffic manager sample.
   - Create 4 VMs spread across 2 regions
   - Create a traffic manager in front of the VMs
   - Change/configure traffic manager routing method
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/traffic-manager-java-manage-simple-profiles.git

    cd traffic-manager-java-manage-simple-profiles

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.