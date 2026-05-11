Lab Manual 1: Introduction to Docker Containerization

Lab Questions

What role does the Dockerfile play in containerization?

The Dockerfile acts as the blueprint or set of instructions for building a Docker image. It contains all the commands (like choosing a base image, setting a working directory, and copying files) required to create a reproducible environment for an application.

Why are Docker containers lighter than virtual machines?

Docker containers are lighter because they share the host machine's OS kernel rather than requiring a full guest operating system for every instance. This eliminates the overhead of running multiple OS kernels, leading to faster startup times and lower resource usage.

What happens when the container finishes execution?

When the main process inside a container (defined by the CMD or ENTRYPOINT) finishes execution, the container transitions to an "Exited" state. The container's filesystem and metadata remain on the disk until it is explicitly removed, but it no longer consumes active CPU or memory resources.


<img width="1106" height="370" alt="{BB534900-BE66-466A-A37B-08F8CAA81D86}" src="https://github.com/user-attachments/assets/cc8ae2e8-a087-4e05-973b-ff5f95c4c299" />
