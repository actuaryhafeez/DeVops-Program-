# access index.html from container 
    
    docker container ls
    docker container run -it ubuntu /bin/bash
    apt-get install apache2
    apt-get update
    apt-get upgrade
    cd /var/www/html
    echo "Welcome to Docker Container" > index.html
    ifconfig 
    curl ip
# port mapping
    docker container run -it -p 3600:80 ubuntu /bin/bash
    apt-get install apache2
    apt-get update
    apt-get upgrade
    cd /var/www/html
    echo "Welcome to Docker Container" > index.html
    ifconfig 
    Ip:3600
    contrl + p # exit without closing container 
