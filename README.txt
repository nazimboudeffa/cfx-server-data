Install, apache2, libapache2-mod-php, php, mysql-server, mysql-client, phpmyadmin

https://docs.fivem.net/server-manual/setting-up-a-server/
Just replace the step 4 in Linux installation by this repo

Then here is the phpmyadmin dumps of the server (so it will be the same clone)
https://www.dropbox.com/sh/bnkx62zeufinyre/AACGmmN6_nYkfRUgxetprUZ1a?dl=0

To run the server
#nohup /home/unicorn/fxserver/server/run.sh +exec server.cfg  > m y.log 2>&1 &

if you want see it runnning tape 
#ps -ef 

to stop it if the process number is 1234
#kill -9 1234

for more info on our server please refere to github.com/dennisbooker
