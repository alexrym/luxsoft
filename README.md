In this repository two tasks

1. a) Parameterize the address of the git repository from which the code will be loaded.
   b) Place the downloaded code in the /tmp/code folder on the host machine.
   c) Configure a docker-compose file to do steps 2 and 3.

2. a) Create simple bash script print "Hello world".
   b) Using Centos7 crete service which started the script.
   c) Using maven create rpm with rpm-maven-plugin installed service and started script.
   d) Check everything with command systemctl start %servicename% && systemctl status
