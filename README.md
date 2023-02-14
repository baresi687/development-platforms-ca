---
title: Docker Case Study
keywords: Development platforms, Docker, Containerization, Platform as a service

---

# Docker Case Study

## Introduction

Docker is an open source software platform that simplifies building, running and managing applications.<br>
By packaging software into standardized executable [containers](https://en.wikipedia.org/wiki/Containerization_(computing)), Docker applications are independent of the host Operating system and can run in any environment.


## Brief History

Docker Inc. was founded in 2010 during the Summer [Y Combinator](https://en.wikipedia.org/wiki/Y_Combinator) startup incubator group and launched in 2011.<br>
In 2013 Docker had its public debut in Santa Clara at [PyCon](https://en.wikipedia.org/wiki/Python_Conference), and was released as open source in March 2013.

#### Major Milestones

- **September 19, 2013:**<br> Red Hat and Docker announce a collaboration around Red Hat's linux distributions and Red Hat's own containerization product [OpenShift](https://en.wikipedia.org/wiki/OpenShift).
-  **October 15, 2014:**<br> Microsoft announces support for integration of the Docker engine into Windows Server, and native support for Docker client in Windows.
-  **December 2015:**<br> Oracle Cloud adds support for Docker containers.
-  **May 2016:**<br> Docker project analysis showed the following organizations as main contributors to Docker: The Docker team, Cisco, Google, Huawei, IBM, Microsoft, and Red Hat.
- **January 2017:**<br> An analysis of LinkedIn profile mentions showed a rapid adoption rate with 160% growth in 2016.
- **August 2020:**<br> Microsoft announces support for Docker on Windows 10 versions 1903 and 1909 running WSL.<br>
By now Docker is supported on all major Windows versions including Home.

## Features

Docker software consists of three components:

- **Software:** The Docker daemon, or service. A persistent process that manages Docker containers. And Docker client that provides [CLI](https://en.wikipedia.org/wiki/Command-line_interface) to interact with Docker daemon.
- **Objects:** Used to assemble an application in Docker. Like images, containers and services.
- **Registries:** Repositories for images. Images are read-only templates for building containers. Docker client connects to the registry to download images for use, or upload built images.

#### Fast and easy configuration and deployment
Docker containers allow a developer to package an application with all the parts it needs to run independently from the host Operating system, and deploy anywhere.

#### Application isolation
Docker containers run applications in an isolated environment where each container is independent and can execute any kind of application.

#### Docker Hub repository
Docker Hub is the world's largest public repository for container images. Including community developers and open source projects.


## Strengths

#### Cloud Platform support
All major cloud computing providers have individual support for Docker. This includes Amazon Web Services and Google Compute Platform. 

#### Return on investment and cost savings
Because of reduced infrastructure resources required to run Docker applications, companies and organizations can save on server costs and the number of developers needed to maintain them, allowing teams to be smaller and more effective.

#### Continuous integration efficiency
The same container image can be used in every step of the deployment process, speeding up the time it takes to go from build to production.


## Weaknesses

#### Applications with Graphical interfaces (GUI)
Docker is designed in general for hosting applications that run on the command line.
Although there are ways to run a graphical interface inside a Docker container, performance may become cumbersome.

#### Container performance
Docker containers use less resources than [Virtual machines](https://en.wikipedia.org/wiki/Virtual_machine), but performance will not equal [bare-metal](https://en.wikipedia.org/wiki/Bare-metal_server).

#### Data storage
On container shutdown, all the data stored inside will be lost.<br>
There are tools like Docker Data Volumes to keep data safe, but they are awkward to use and need improvements.


## Comparison

#### Docker vs. Kubernetes
There is some confusion regarding Docker vs. [Kubernetes](https://en.wikipedia.org/wiki/Kubernetes)<br>
Docker is a container runtime, while Kubernetes is platform for running and managing multiple container runtimes, typically called container orchestration platform.<br>
Docker has its own container orchestration platform called Docker Swarm.
<br><br>
**Docker Swarm** is easy to install and lightweight. As it is native to Docker, it works well with the Docker CLI and other existing Docker tools like compose.<br>
It is however tied to the Docker platform and has limits in its functionality compared to Kubernetes.
<br><br>
**Kubernetes** is feature rich and can sustain and manage large and complex workloads with broad open source community support.<br>
The learning curve however is steep compared to Docker Swarm, and the installation process is complex.


## Summary

Docker can significantly speed up the development process of applications with its containerization technology and widespread industry support.
One example of applications well suited for Docker is microservices.<br><br>
As Docker containers are separated from the outside, they will allow your app to work in a consistent and predictable way in every environment.<br><br>
If your software product is a web application running on a server, and not a Desktop app with GUI, then Docker might be the right choice.


### Credits

- Hreinn Gylfason (baresi687)

#### References

General

- https://en.wikipedia.org/wiki/Docker_(software)
- https://aws.amazon.com/docker/
- https://www.freecodecamp.org/news/docker-simplified-96639a35ff36/
- https://www.knowledgehut.com/blog/devops/docker-features
- https://www.docker.com/products/docker-hub/
- https://apiumhub.com/tech-blog-barcelona/top-benefits-using-docker/
- https://www.channelfutures.com/open-source/docker-downsides-container-cons-to-consider-before-adopting-docker
- https://www.freecodecamp.org/news/7-cases-when-not-to-use-docker/
- https://www.freecodecamp.org/news/kubernetes-vs-docker-swarm-what-is-the-difference/

Major Milestones

- https://techcrunch.com/2013/09/19/dotcloud-pivots-and-wins-big-with-docker-the-cloud-service-now-part-of-red-hat-openshift/
- https://www.zdnet.com/article/docker-container-support-coming-to-microsofts-next-windows-server-release/
- https://www.crn.com/news/cloud/300079216/oracle-acquires-docker-container-startup-stackengine-plans-austin-based-cloud-computing-center.htm
- https://gist.github.com/icecrime/18d72202f4569a0cab1ee60f7583425f
- https://www.linkedin.com/pulse/docker-momentum-2016-analysis-michael-mullany/
- https://devblogs.microsoft.com/commandline/wsl-2-support-is-coming-to-windows-10-versions-1903-and-1909/

