Bootstrap: docker
From: ubuntu:latest

%runscript

exec echo "The runscript is the containers default runtime command!"


%files
/home/vanessa/Desktop/hello-kitty.txt /data/hello-kitty.txt
/home/vanessa/Desktop/party_dinosaur.gif /tmp/the-party-dino.gif


%environment
VARIABLE=MEATBALLVALUE
export VARIABLE

%labels
AUTHOR vsochat@stanford.edu

%post

apt-get update && apt-get -y install python3 git wget
mkdir /data
echo "The post section is where you can install, and configure your container."
