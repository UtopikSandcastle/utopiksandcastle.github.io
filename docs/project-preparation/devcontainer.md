---
layout: default
title: Developing inside a Container
parent: Project Preparation
nav_order: 2
---

# Developing inside a Container

## References
- [Learn more about Development Containers](https://containers.dev/)

## Connect to Docker server
There are multiple way to connect Visual Studio Code to Docker. Check this documentation to find the must appropriate way for you: [Developing inside a Container](https://code.visualstudio.com/docs/devcontainers/containers)

This project has been created using a remote connection SSH to a Docker server and using Dev Container on that remote server. But it should not matter which way you chose. Dev Container are even so strongly recommended.

## Clone your repository
Clone your repository where you whish. The folder going to be mounted inside the container.

[Learn more about Cloning a repository](https://code.visualstudio.com/docs/sourcecontrol/overview#_cloning-a-repository)

## Add a container file
If you not already did, open your repository in Visual Studio Code. Open the Command Pallette (`F1`) and search for **Dev Containers: Add Dev Container Configuration Files...**.

Select a Docker image. 
- Frontend use **Node.js & TypeScript**
- Backend API use **C# (.NET)**

Select the **default** version.

Select additional features as needed or just click **OK**.

Click **Reopen in Container** on the popup or click on the **Remote Menu** (bottom left blue button) and select **Reopen in Container**

If everything goes well, you should be now inside your container in a fresh environment.

[Learn more about Automate dev container creation](https://code.visualstudio.com/docs/devcontainers/create-dev-container#_automate-dev-container-creation)