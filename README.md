# nodeRAIN

## Create a nodeJS server has become simple!

* NGINX as http proxy
* Nodejs as http server
* Supervisor as nodejs proc runner
* Git for deploy
* and finally bash command to easy manage server!
(on Ubuntu 12.10 X64 Server)

(thanks to http://cuppster.com/2011/05/12/diy-node-js-server-on-amazon-ec2/ who inspire me)

--NOTE: the script not complete need more work!

(more info are coming on http://noderain.it)

## Getting Started

To setup the server

1. get bash setup
  
  `mkdir /home/tmp`
  
  `cd /home/tmp`
  
  `wget https://github.com/nodeRAIN/bash/archive/master.zip .`

  `unzip master.zip`

  `chmod 775 /home/tmp/bash-master/noderain-setup.sh`

2. login as root

  `su root`

3. launch the script and follow the instructions
  
  `/home/tmp/bash-master/noderain-setup.sh`

4. Wait a few minutes!

Script work on Ubuntu 12.10 X64 Server
