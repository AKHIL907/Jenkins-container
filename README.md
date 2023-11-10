# Jenkins-container
In this project creating a docker file for jenkins and build the docker image the run it as container


# Step1
Create a Dockerfile

![Screenshot from 2023-11-09 07-55-38](https://github.com/AKHIL907/Jenkins-container/assets/137915095/3a2e0edd-cae3-49e6-9939-d83e1df57fe7)

# Step2
Build the Dockerfile, and then the Docker image will be created. Using the below command, we can build the image where the '.' represents the Dockerfile in the present directory.

``` docker build -t jenkins . ```

![Screenshot from 2023-11-09 07-55-05](https://github.com/AKHIL907/Jenkins-container/assets/137915095/a76174b6-530a-4fc6-b80d-51b15a3164ad)

To list the Docker images use above command

``` docker images ```

![Screenshot from 2023-11-09 08-40-35](https://github.com/AKHIL907/Jenkins-container/assets/137915095/e5efccda-d1bd-4564-86d8-18339233320f)

# Step3
Run the docker container  with the imagename and tag using the below command expose on port 8080.
``` docker run -dp 8080 jenkins:1 ```

![Screenshot from 2023-11-10 20-14-09](https://github.com/AKHIL907/Jenkins-container/assets/137915095/01acf98d-431b-4ee4-960c-be4d577b837d)
