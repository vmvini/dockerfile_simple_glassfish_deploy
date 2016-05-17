# dockerfile_simple_glassfish_deploy

The file project.war it's a simple java servlet project.
You can replace this file by your own .war project.

On your console, go to the folder where Dockerfile and project.war are.

Tipe the following command to build the container image with name 'my_glassfish_proj_deploy_img':
"sudo docker build -t my_glassfish_proj_deploy_img ." 

Run the container with the command below:
"sudo docker run -dit -p 48:4848 -p 80:8080 -p 81:8181 my_glassfish_proj_deploy_img"




