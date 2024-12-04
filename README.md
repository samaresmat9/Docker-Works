docker container run -detach --publish 80:80 --name n1 nginx

docker container stop n1

docker container start n1

docker exec -it n1 bash

# After the bach of nginx oppening and the root and it's special container-id  appeared , if you want to know the nginx version you can write this command :
  service nginx -V
  
#if you want to know the stutus of nginx you can write that after the root and it's special container-id :
    service nginx status
