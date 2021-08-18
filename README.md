**DOCKER**

Docker is a set of platform as a service (PaaS) products that use OS-level virtualization to deliver software in packages called containers. Containers are isolated from one another and bundle their own software, libraries and configuration files; they can communicate with each other through well-defined channels. Because all of the containers share the services of a single operating system kernel, they use fewer resources than virtual machines.

The service has both free and premium tiers. The software that hosts the containers is called *Docker Engine*.

In simple terms, Docker is a platform/tool that allows to “build, ship, and run any app, anywhere.” Docker applications run in containers that can be used on any system: a developer’s laptop, systems on premises, or in the cloud. 

**CONTAINERS**

Containerization is a technology that’s been around for a long time, but it’s seen new life with Docker. It packages applications as images that contain everything needed to run them: code, runtime environment, libraries, and configuration. Images run in containers, which are discrete processes that take up only as many resources as any other executable.

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
