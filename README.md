# Presentation
# (slide 1)
Hello! I'm Anya and I will tell you what Docker is and how it works.
# (slide 2)
Do yo know the famous phrase: "It works on my machine?"
# (slide 3)
What is Docker?
Docker is a popular tool to make it easier to build, deploy and run applications using containers.
# (slide 4)
And now you can ask me what are containers?
# (slide 5)
Containers allow us to package all the things that our application needs like such as libraries and other dependencies and ship it all as a single package. In this way, our application can be run on any machine and have the same behavior. On the slide you can see a visualization of the virtual environment of containers
# (slide 6)
Docker was first released in 2013, only five years ago, but it is already used by a lot of companyes.
# (slide 7)
It should be remembered that Docker is non a virtual machine.
A docker container unlike a VM does non require or include a separate operating system. Instead, it relies on the kernel's functionality and uses  resource isolation for CPU and memory, and separate namespaces to isolate the application's view of the operating systems.

And an image on the slide shows a comparison between VM and Docker containers. As we can see Docker containers are simpler than VMs.
# (slide 8)
Docker is composed of the follow four components: 
+ Docker client and Daemon
+ Images
+ Docker registries
+ Containers

And now more about each of them

# (slide 9)
Docker has a client-server architecture. Docker Daemon or server is responsible for all the actions that are related to containers. The daemon recieves the commands from Docker client through CLI or Rest APIs. Docker client can be on the same host as daemon or it can be present on any other host.

Images are the basic building blocks of Docker. Containers are build from images. Images can be configured with applications and used as a template for creating containers. It is organized in a layered fashion. Every change in an image is added as a layer on top of it.

Docker registry is a repository for Docker images. Using Docker registry you can build and share images with your team. A registry  can be public or private. Docker Inc provides a hosted registry service called Docker Hub. It allows you to upload or download images from a central location. If your repository is public all your images can be accessed by other Docker Hub users. Uoy can also create a private registry in Docker Hub. Docker Hub acts like git, where you can build your images locally on your laptop, commit it and then can be pushed to the Docker Hub

Container is the execution environment for Docker. Containers are created from images. It is a writable layer of the image. as I said earlier you can package your application in a containers, commit it and make it a golden image to build more containers from it. Two or more containers can be linked together to form tiered application architecture. Containers can be started, stopped, commited and terminated. If you terminate a container without commiting it, all the changes will be lost.

# (slide 10)
Let's go to the last question - what can be Docker used for?
+ Fast, consistent delivery of your applications.

Docker enables and also streamlines the development lifecycle into a desciplined environment where developers are allowed to work in these standartized environments with the use of local containers that provide the applications and.

+ Responsive deployment and scaling.

Docker makes it very easy and also allows highly portable workloads. Docker containers have flexiblity running on a developer's laptop, a physical machine, a virtual machine, a virtual machine in a data center, on cloud providers or premise providers. Dynamically managing the workloads is very easy with the Docker's portability and light weighted nature.

It also makes it very easy to scale up or to teaar down applications and services, as and how the buisiness dictates it to.

+ Running more workloads on the same hardware.

As I said earlier, Docker is lightweight. It provides viable cost-effective alternative to its counterparts as like the hipervisor-based virtual machines. This enables than you can consume more on these resources and at the same time achieve the business goals as well. It is very much recommended for high-density environments and also for the small or medium deployments.

# (slide 11)
Today we have introduced the concepts of Docker and where this application finds its usage. Docker provides containerization of services into secluded individual virtual machine without really worrying about the OS and networking resources . We have also understood the usage, architecture and the design of Docker.

It is all I have for you today.

Thanks for attention!
