#This is a sample Image
FROM ubuntu

RUN apt-get update
RUN apt-get install -y nfs-common
ADD nfsmount.sh /root/script.sh
RUN chmod +x /root/script.sh
