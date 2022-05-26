# docker-hello-world-app
Basic node.js application containarized in docker.

To build a docker image, run
``` docker build . -t <repository_name>```

To run the container
``` docker run -p <publicport>:<containerport> -d <imageName> ```

Navigate to ```http://localhost:<publicport>/``` to see it working

Or share this image with your colleagues as a tar file
``` docker save -o <generated tar file name> <imageNmae> ```
