# Download and Run a Simple Application in a Docker Container
I did the following steps successfully: 
1. Downloaded the docker on Windows.
2. Downloaded the sample application from https://github.com/docker/getting-started/tree/master/app and added a docker file to it.
3. Created an image in the docker container, tested, and deployed it.

The table below describes the tasks I performed and the issues i noticed while creating the docker container image.  

| Task | Description | Issues noticed | Comments |
|------|--------------|---------------| --------|
| 1. Install Docker Desktop on Windows | I followed the instructions at https://docs.docker.com/docker-for-windows/install/. | The Prerequisites section is not added. | Sound knowledge of Linux is required. It should be listed in the section "Prerequisites". |
| 2. Get Familiar with Docker Desktop |I followed the instructions at https://docs.docker.com/get-started/.| No information is provided about installing Git on WSL2. | Installed using the command `sudo apt install git`. |


