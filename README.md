# Let's learn docker! (A docker workshop)

Short url to this project:

     http://moourl.me/FJn 

## What is it?

* Docker is a technology for lightweight VMs. Well, that's not true, they're not VMs. But they feel like it.
  * [Why containers are lightweight but not VMs](https://www.upguard.com/articles/docker-vs.-vmware-how-do-they-stack-up). **<-- READ this one**
  * [Picture for Containers vs VMs](https://www.sdxcentral.com/wp-content/uploads/2016/01/containers-versus-virtual-machines-docker-inc-rightscale.jpg) [from this article](https://www.sdxcentral.com/cloud/containers/definitions/containers-vs-vms/) 
  * [Kernel technologies Docker is built with](https://upload.wikimedia.org/wikipedia/commons/thumb/0/09/Docker-linux-interfaces.svg/400px-Docker-linux-interfaces.svg.png) [from Wikimedia](https://commons.wikimedia.org/wiki/File:Docker-linux-interfaces.svg)
  * [VMs are houses, Docker containers are appartment buildings](https://blog.docker.com/2016/03/containers-are-not-vms/).
* You can do containers without Docker. Docker is just an implementation! Using Docker has been a bumpy ride, so it makes sense to consider alternatives. 
  * [rkt](https://coreos.com/rkt) by CoreOS. [rkt compared to other runtimes](https://coreos.com/rkt/docs/latest/rkt-vs-other-projects.html). [rkt vs Docker (2016)](https://bobcares.com/blog/docker-vs-rkt-rocket/)
  * There's a [standard for containers](https://www.opencontainers.org/)! Well, actually two, [one for the runtime](https://github.com/opencontainers/runtime-spec), [one for the images](https://github.com/opencontainers/image-spec). 

## Words & Terminology

Docker uses a bunch of concepts and has specific words for those. To be able to read documentation, and to talk to others, it's very important to understand what they mean.

In the following I'm trying to show a few analogue words from related domains, such as VMs or programming runtimes.

| Containers with Docker | VMs | AWS EC2 | Python | Node JS |
|--------|-----|---------|--------|---------|
| Docker | VMWare, VirtualBox | - | CPython, PyPy, Jython | ? |
| Image | VM Snapshot | [AMI](http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AMIs.html) | .py file | .js file |
| Container | Running VM | EC2 instance | A running Python process | A running Node process |
| Docker Hub | ? | AWS Marketplace for AMIs | [official pypi](https://pypi.python.org/) | the official [NPM registry](https://www.npmjs.com/) |
| Docker registry | ? | - | A pypi server | an npm server |

## Tutorials, Goals & Resources

### Docker for Beginners

### Docker-compose

### Docker swarm

