# DockerVolumesMapping
dockerVolumesMapping

Requirements: DOCKER VOLUMES MAPPING
A. On app svr1, pull ubuntu image (preferrably latest tag, but others should work too)
B. Create a new container with name ecommerce from the image pulled
C. Map the host volume /opt/data with container volume /tmp/. The sample.txt file present 
on same server under /tmp; copy that file to /opt/data.
