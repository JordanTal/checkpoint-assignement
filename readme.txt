FYI - The ci configuration depends on the public DNS of the ec2 machine ehich is dynamic at the moment ( so drone ci is not initialized by main.tf run) , need to modify accordingly or set a static DNS / IP then run it on the instance. "

when can set a static IP / DNS - 
Please JUST include the drone configuration in the main.tf terraform file 
for that just need to add the content of 'drone_configuration.txt' to 'file.sh'


----
**dockerized service in docker hub :

https://hub.docker.com/repository/docker/jordant23/python-docker
docker push jordant23/python-docker:tagname
----