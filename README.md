# Citi-RedHatOpenShift

Day-1 Commads: 

   2 docker build -t citi-web-image .
   3 docker images
   4 docker run -td --name web-app -p 81:80 citi-web-image
   5 docker logout
   6 docker login
   7 docker tag citi-web-image muralisocial123/citi-web-image
   8 docker push muralisocial123/citi-web-image
   9 docker pull muralisocial123/citi-web-image:latest
