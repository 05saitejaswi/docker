Docker is a tool designed to make it easier to create, deploy, and run applications by using containers. Containers allow a developer to package up an application with all of the parts it needs, such as libraries and other dependencies, and ship it all out as one package. By doing so, thanks to the container, the developer can rest assured that the application will run on any other Linux machine regardless of any customized settings that machine might have that could differ from the machine used for writing and testing the code.

More on containers

What are containers?
Containers cheat sheet
10 things to avoid in containers
Red Hat Container Development Kit
In a way, Docker is a bit like a virtual machine. But unlike a virtual machine, rather than creating a whole virtual operating system, Docker allows applications to use the same Linux kernel as the system that they're running on and only requires applications be shipped with things not already running on the host computer. This gives a significant performance boost and reduces the size of the application.

And importantly, Docker is open source. This means that anyone can contribute to Docker and extend it to meet their own needs if they need additional features that aren't available out of the box.

Who is Docker for?
Docker is a tool that is designed to benefit both developers and system administrators, making it a part of many DevOps (developers + operations) toolchains. For developers, it means that they can focus on writing code without worrying about the system that it will ultimately be running on. It also allows them to get a head start by using one of thousands of programs already designed to run in a Docker container as a part of their application. For operations staff, Docker gives flexibility and potentially reduces the number of systems needed because of its small footprint and lower overhead.

Getting started
Here are some resources that will help you get started using Docker in your workflow. Docker provides a web-based tutorial with a command-line simulator that you can try out basic Docker commands with and begin to understand how it works. There is also a beginners guide to Docker that introduces you to some basic commands and container terminology. Or watch the video below for a more in-depth look:



Docker and security
Docker brings security to applications running in a shared environment, but containers by themselves are not an alternative to taking proper security measures.

Dan Walsh, a computer security leader best known for his work on SELinux, gives his perspective on the importance of making sure Docker containers are secure. He also provides a detailed breakdown of security features currently within Docker, and how they function.

More to read
Why is Docker the new craze in virtualization and cloud computing?
Do I need OpenStack if I use Docker?
How to grant rights to users to use Docker in Fedora
What does Docker provide if not virtualization?
Who's using Docker?
ClusterHQ brings databases to Docker with Flocker
What Docker 1.0 means for OpenStack
More Docker articles from Opensource.com
Want to master microservices? Learn how to run OpenShift Container Platform in a self-paced, hands-on lab environment.

