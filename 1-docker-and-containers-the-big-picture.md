# Docker and Containers: The Big Picture by Nigel Poulton (Pluralsight)

## What are containers?
* Containers removes the need for a hypervisor and cuts the overhead by installing only one operating system that all the containers operate on. Removing the operating system from each VM reduces resource consumption on the server.
* Docker Images are essentailly powered off virtual machines that can be started and stopped at will.
* Container ecosystem is still relatively young compared to hypervisors (15+ years).

## What is Docker?
* Docker is open source (Apache License 2.0). About making tools that enables to build/manage/deploy containers.
* Heavily developed and backed by giants in tech, as well as individual contributors.
* Docker Inc is separate from Docker Project (on Github).
* Open Container Initiative is the lightweight governance guiding the open standards.

## Preparing to Thrive in a Container World
* Containers are coming, accept this reality. "Don't do a Larry" (Ellison) - refused to accept Cloud computing was the future. Docker (container) adoption is up and continuously growing.
* Identify infrastructure in the business that could be ran in a container.
* Containers for different purposes - logging, monitoring, management, etc.

## What kind of work will containers do?
* Stateless: App that doesn't keep any changes or data.
* Stateful: App that keeps changes and data.
* Docker and containers can handle both stateful and stateless, but they excel in stateless apps.
* While legacy apps can be dropped into a container and run, that is kind of missing the point. Containers encourage one to rework and redesign their apps (modern, scalable, self-healing, portable).
* Docker containers are persistant (stopping a container does not wipe it's data).

## Docker Hub and other container registries
* Container registries are a place to store and retrieve container images.
* Docker Hub is the official Docker registry, but there are many 3rd party registries (quay.io).
* Within a registry, you can customize images and save them as public/private repositories.
* Enterprise solution using Docker Trusted Registry and Docker Content Trust.

## Are Docker and Containers ready for production and the enterprise?
* Three channels for Docker Engine: Experimental (nightly builds), Stable (release every 2 months), Commercially Supported (release every 6 months, focused on stability).
* Docker Swarm (Native Docker clustering) has reached version 1.0 and is considered production ready.
* Tutum can be used to deploy to the cloud.
* The container ecosystem is growing rapidly with lots of startups specializing in container technology, as well as established players.

## What is container orchestration all about?
* Apps comprised of multiple parts (Load balancer, DB, Logs, HTTP server, etc).
* Can define, provision, deploy and scale apps in a single click.
* Docker Machine - provision docker hosts/engines
* Docker Compose - compose multi-container apps
* Docker Swarm - Schedule container over multiple Docker engines
* Kubernetes developed by Google but has become open-source. 