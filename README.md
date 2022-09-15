# containerproject
# Project architecture
  ![arch](https://user-images.githubusercontent.com/96655654/190453949-8024c9f8-47c2-45cd-8561-0d0099adb8b6.png)
Build the dockerimages using following commands


     docker build -t vprofiledb:V1 db
     docker build -t vprofileapp:V1 app
     docker build -t vprofileweb:V1 web
     
     
     
validate the compose file that you have created the image name as above or you can change it as per your needs while building .Make sure to mention the same image name in the docker-compose.yml file.



# Run
  docker-compose up to run in frontend
  
  docker-compose up -d to run in detached mode
