# Lecture outline

1. [Overview](lecture-overview.md)
2. [Containers](containers.md)
   1. What is a container?
   2. Difference between containers and VMs
   3. Why are we only talking about Docker?
3. [Docker overview](docker-overview.md)
   1. The Docker platform
   2. Docker Engine
   3. What can I use Docker for?
   4. Docker architecture
4. [Develop with Docker](develop-with-docker.md)
   1. Prepare Docker environment
      1. Install Docker
      2. Verify version
      3. Verify installation
   2. Build an image from a Dockerfile
      1. What is a Dockerfile?
      2. Start with basic Dockerfile
      3. Build the app
      4. Run the app
   3. Publish the image
      1. Publish image to Docker
         1. Log into Docker \(hub.docker.com\)
         2. Tag image
         3. Publish the image
         4. Pull and run the image from the remote repo
      2. Publish the image to OCI registry
         1. Overview of the OCI registry and user credentials
         2. Log in with Docker to OCI registry
         3. Tag image
         4. Publish the image
         5. Pull and run the image from the remote repo
   4. Interact with a container
      1. Exec into a container
      2. Test out container connectivity with the outside world
5. [Use multi-stage builds](use-multi-stage-builds.md)
   1. Why use multi-stage builds?
   2. Use multi-stage builds
   3. Cleanup: Name build stages
   4. Stop at a specific build stage
   5. Use an external image as a stage
6. [Manage application data](manage-application-data.md)
   1. Storage options \(volumes, bind mounts, tmpfs\)
   2. Volumes
      1. Description of volumes, what are they useful for?
      2. Instances where volumes should be used
      3. Create a volume and attach to the container
   3. Bind mounts
      1. Description for bind mounds, what are they useful for?
      2. Instances where volumes should be used
      3. Create a volume and attach to the container
   4. Tmpfs
      1. Description for tmpfs mounts, what is it useful for?
      2. Instances where tmpfs mounts should be used
      3. Use a tmpfs mount in a container

#### 

