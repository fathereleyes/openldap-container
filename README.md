

1- OpenLDAP + phpldapadmin 
https://github.com/Ramhm/openldap

2- Documentation:
https://github.com/Ramhm/openldap

3- Reference:
https://github.com/osixia/docker-open...


after all this resouces reading and modification i created docker-compose file and 
uploded it in my github repositorey u can get it using this command and pull it , it is public .

git clone https://github.com/fathereleyes/openldap-container.git

1-after you clone my project , you shall to make sure from the status of your docker engine 
using this command 

#docker info or sudo systemctl status docker
2-make sure from the status of docker compose engine using this commands . 

#systemctl status docker

docker-compose down
#docker-compose --version


3-now you can build your project by go to the directorey after installing git 
and execute the following command 
docker-compose up -d

4-to check the running of your ldap container you can do this commands 

#docker ps 
#watch docker ps
#docker-compose ps
#docker-compose logs
5-to stop your docker compose file you can execute this command 
docker-compose down
6-you can login to your ui console using this user name and password which i modified in docker compose file
you can login by typing in the webconsole the user name and password as follow 
Login DN: cn=admin,dc=quicklocal,dc=com
Password: admin

7-for any requset or inquire feel free to contact me 
