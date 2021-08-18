**DOCKER**

Docker is a set of platform as a service (PaaS) products that use OS-level virtualization to deliver software in packages called containers. Containers are isolated from one another and bundle their own software, libraries and configuration files; they can communicate with each other through well-defined channels. Because all of the containers share the services of a single operating system kernel, they use fewer resources than virtual machines.

The service has both free and premium tiers. The software that hosts the containers is called *Docker Engine*.

In simple terms, Docker is a platform/tool that allows to “build, ship, and run any app, anywhere.” Docker applications run in containers that can be used on any system: a developer’s laptop, systems on premises, or in the cloud. 

**CONTAINERS**

A container is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another. A Docker container image is a lightweight, standalone, executable package of software that includes everything needed to run an application: code, runtime, system tools, system libraries and settings.

Container images become containers at runtime and in the case of Docker containers - images become containers when they run on Docker Engine.

Containers are an abstraction at the app layer that packages code and dependencies together. Multiple containers can run on the same machine and share the OS kernel with other containers, each running as isolated processes in user space. Containers take up less space than VMs (container images are typically tens of MBs in size), can handle more applications and require fewer VMs and Operating systems.

*MICROSERVICES WITH DOCKER*

Docker is the world's leading software containerization platform. It encapsulates your microservice into what we call as  Docker container which can then be independently maintained and deployed. Each of these containers will be responsible for one specific business functionality. 

**Docker Components** 

Docker Client : Docker client is a CLI of Docker tool which is used to communicate with the Docker Daemon.  

Daemon : Docker Daemon is a service installed in Docker Host. It runs and manages the Docker containers and other resources it acts based on commands from Docker Client.  

Docker registries : It is a repository which stores images. User can interact with Registry with push pull commands with mediation of Daemon. 

Images :  A Docker Image is a file, comprised of multiple layers, that is used to execute code in a Docker container. 

Containers : It is a environment, it consists of libraries and other dependencies required for application and used to ship application and dependencies as one package. In other words, Docker Container is the run time instance of images. 

Docker Engine : Docker Engine is a containerizing technology that builds and  runs containers using Docker components and services.  

**DOCKER INSTALLATION AND REFERENCE**

*Reference* : https://docs.docker.com/

*Installation* : https://docs.docker.com/get-docker/ (You will have an option to download in different OS).
