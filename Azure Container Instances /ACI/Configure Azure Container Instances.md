## Configure Azure Container Instances

In this demonstration we create, configure, and deploy a container by using Azure Container Instances (ACI) from the Azure Portal. The ACI application displays a static HTML page with the public Microsoft Hello World image. 

1. Use the Azure portal.

1. Search for and select **Container instances**.

1. **Create** a new container instance. 

1. Fill in the **Resource group** and **Container name**. 

1. Discuss the **Image source** options. Use **Quickstart images**.

1. For **Container image** use **mcr.microsoft.com/azuredocs/aci-helloworld:latest (Linux)**. This sample Linux image packages a small web app written in Node.js that serves a static HTML page.

1. On the **Networking** page, specify a **DNS name label** for your container. 

1. Leave all other settings as their defaults, then select **Review + create**.

1. Wait for the resource to deploy.

1. On the **Overview** page for the resource, ensure the **Status** is **Running**.

1. Navigate to the **FQDN** for the container instance and ensure the welcome page displays. 

**Note**: To avoid additional costs, delete the resource. 
