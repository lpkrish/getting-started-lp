# Download and Run a Simple Application in a Docker Container
I did the following steps successfully: 
1. Downloaded the docker on Windows.
2. Downloaded the sample application from <https://github.com/docker/getting-started/tree/master/app>. I created a Dockerfile and added it to the folder that contains the file package.json.
3. Created an image in the docker container, tested and deployed it.

The table below describes the tasks I performed and the issues I noticed while creating the docker container image.  

| | Task | Description | Issues noticed | Comments |
|-|------|--------------|---------------| --------|
|1|Install Docker Desktop on Windows | I followed the instructions at <https://docs.docker.com/docker-for-windows/install/>. | The Prerequisites section is not added. | Sound knowledge of Linux is required. It should be listed in the section **Prerequisites**. |
|2|Get Familiar with Docker Desktop |I followed the instructions at <https://docs.docker.com/get-started/>.| No information is provided about installing Git on WSL2. | Installed Git using the command `sudo apt install git`. |
|3|Download and Run a Simple Application in a Docker Container. |  I followed the instructions at <https://docs.docker.com/get-started/02_our_app/>,| Step 1 in the section **Build the app’s container image** is incorrect. | The correct folder to build the image is the parent folder of the folder in which the Dockerfile is added. |

The snapshot below is of the image I created in the docker container.
![docker](https://user-images.githubusercontent.com/99960154/154833572-d8c8284d-f236-45c1-be34-8a209cb94fc6.png)

The snapshot below is of the container running.
![Image Run](https://user-images.githubusercontent.com/99960154/154833585-221a8bb6-b60c-4cef-8f88-937d9149a0e4.png)

The snapshot below is of running application in the Web browser.
![Outcome](https://user-images.githubusercontent.com/99960154/154833596-f7731f5a-eb31-405d-ab62-facd574a88cb.png)

