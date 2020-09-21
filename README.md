First install docker and docker-compose
pull pihole/pihole:latest from docker
need to do some networking stuff here... check a guide or something involves etting network-manager.conf (NetworkManager.conf in /etc/)
clone docker-compose file
touch pihole.log file
mkdir pihole in cloned directory
docker-compose it up
point router DNS to current device ip
