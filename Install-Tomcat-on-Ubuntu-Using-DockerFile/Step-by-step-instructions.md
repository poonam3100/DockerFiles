#Move to Directory
cd Install-Tomcat-on-Ubuntu-Using-DockerFile

#build Docker Image
docker build -t <your-image-name> .

#list images
docker images

#Run container using build-image
docker run -d --name <your-conatiner-name> -p 8083:8080 <your-image-name>

#List the Running conatiners
docker ps 

#Check tomcat is running on 8083
If you are using AWS or other cloud then => Go to your Browser & try <your-VM-IP>:8083
If you using local docker environment then => localhost:8083