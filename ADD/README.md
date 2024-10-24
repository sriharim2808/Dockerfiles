 # ADD
 ADD is same as COPY. It is useful to copy files from local to container. But it has 2 extra capabilities.

1. ADD can download the file directly from internet to the container.
2. ADD can untar/unzip the file directly into the container.
#  difference b/w ADD & COPY?
 1. COPY is only copy the files from local to docker image.
 2. ADD command also do the copy files apart from that 2 extra capabilities is there:
  --> ADD can download the file directly from internet to the container.
  --> ADD can untar/unzip the file directly into the container.

Remote URLs: ADD can download files directly from URLs, whereas COPY cannot. If you need to download something from the web during your Docker build, you must use ADD.