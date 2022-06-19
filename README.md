# Docker & Database Tutorial
### Prepared by: Group 3
Name| Matric Number
------------ | -------------
Muhammad Naim Imran bin Mohd Nizar | 1917173
Ahmad Sanoh |  1921973
Ahmad Aiman Syammi Bin Ali | 2012381
Nasr Khalil Ahmed Hasan |  1916417

Lecturer: Dr Rizal, Section 1

## Docker Introduction
Docker is a set of platform as a service products that use OS-level virtualization to deliver software in packages called containers. The service has both free and premium tiers. The software that hosts the containers is called Docker Engine.

## Docker Installation
1.If you want to download the app just go to [Docker](https://docs.docker.com/desktop/windows/install/) and click on "Docker Desktop for Windows".

![docker](https://user-images.githubusercontent.com/76858112/174468652-24116d06-72e5-43c8-9dbe-4127086a4c38.png)

2. Tick the term checkbox and accept the Service Agreement

![dockerterms](https://user-images.githubusercontent.com/76858112/174468667-c809befa-c51e-42f2-95cb-c2e8a0a09122.png)


## WSL 2 Linux Kernel Installation 
Here is the WSL installation, for your computer to use docker you will have to download Linux Kernel. A link is already shown on the image below that sends you straight to the page in order to download the Linux Kernel. Just press the link and proceed downloading.

![linux kernel](https://user-images.githubusercontent.com/76858112/174470589-88490dcb-5abb-4fe7-8321-bac8654eadbd.png)

Once on the page go to “Step 4” and click the link under “Download the latest package” and it will automatically start downloading.

![linux kernel1](https://user-images.githubusercontent.com/76858112/174470657-4fbc3968-24d5-4df2-8180-684eee00d6cc.png)

After downloading, click on the file and when it opens press “Next”  and wait for the setup to finish installing and then click the finish button.

![linux kernel2](https://user-images.githubusercontent.com/76858112/174470690-37eca532-636e-4896-9e19-8eb4d13c6367.png)

## Starting Docker
Press the “Start” button to get started with Docker.

![docker start](https://user-images.githubusercontent.com/76858112/174470864-0fe3ae66-bdd7-4b55-8d67-044b444f8dcb.png)

Complete the tutorials, after pressing the “Next Step” button you will see an instruction to push your image to your Docker Hub.

![docker start1](https://user-images.githubusercontent.com/76858112/174470963-f23f5d83-4b0f-467e-8ad9-0efffaf51bbd.png)

![docker start2](https://user-images.githubusercontent.com/76858112/174470976-2d536229-c44f-4576-a202-93db19bec326.png)

When you completed Docker Tutorial or skipped the tutorials, the "Home Page" section will be like this and there are several container options to download.
We chose the MongoDB as our database.

![docker start3](https://user-images.githubusercontent.com/76858112/174471016-80520633-47f1-47c3-9bf8-19408c7977fb.png)


## Installing MongoDB Container
 Try opening your Windows PowerShell and type "docker --version" to ensure MongoDB is compatible. Type docker pull mongo and it will pull mongo image to your docker storage.
To see the images with its versions with the related details just type “docker image”.

When you type "docker run --name mongo_example -d mongo".
It will create a Docker Container with these meaning below
docker run: this command Docker to run a container
(double dash)name : this will give name to the container
mongo_example: name of the container
-d: detach, this means if we close the powershell/terminal the container will run on background
mongo: the image name we want to use.
Brief, it is all stated in the pictures.

![container1](https://user-images.githubusercontent.com/76858112/174485270-c5c77f93-4d8b-4fee-97c9-f5db444d5187.png)

![container2](https://user-images.githubusercontent.com/76858112/174485283-98a60091-c400-472c-a650-bcfa98cc640c.png)

![container3](https://user-images.githubusercontent.com/76858112/174485304-4b59e009-43aa-4b02-8993-1cb760eb1a08.png)

![container4](https://user-images.githubusercontent.com/76858112/174485312-4911fdee-f755-44a2-ae75-dc536979f278.png)

This is the sample run in the containers, make sure the container is running and this option is available

![container5](https://user-images.githubusercontent.com/76858112/174485336-4c0139be-38a8-4104-9880-b48ff4317f76.png)


## Creating Database in MongoDB using CLI

![cli1](https://user-images.githubusercontent.com/76858112/174485416-ba055e92-502e-46f3-8b1e-4ef7647fda61.png)

![cli2](https://user-images.githubusercontent.com/76858112/174485424-98674acf-106d-4b31-ad0b-68e86b15fa6d.png)

![cli3](https://user-images.githubusercontent.com/76858112/174485431-4128fb1f-3fa7-450c-97aa-824383c23d37.png)

![cli4](https://user-images.githubusercontent.com/76858112/174485436-c817de36-2b31-4c32-b8f6-87c2ad63777a.png)

![cli5](https://user-images.githubusercontent.com/76858112/174485440-a29dceaa-e61f-498b-9d77-157dd1524366.png)

## MongoDB Compass Installation

![compass1](https://user-images.githubusercontent.com/76858112/174485523-b72cf459-6881-4fcf-972f-a27b21bfee6d.png)

![compass2](https://user-images.githubusercontent.com/76858112/174485526-7ee81a79-b271-4d4e-8bc9-c10d30e178fb.png)

![compass3](https://user-images.githubusercontent.com/76858112/174485533-8a070226-1120-469f-86aa-bcdc600646bc.png)

![compass4](https://user-images.githubusercontent.com/76858112/174485538-a33b2414-a51d-42aa-b91f-44c136540692.png)

![compass5](https://user-images.githubusercontent.com/76858112/174485539-b1c918d0-7dd8-430d-b481-69817958b460.png)

![compass6](https://user-images.githubusercontent.com/76858112/174485540-8912b870-902c-4c67-820c-46255b960abb.png)











