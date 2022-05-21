---
title: Linux
---

# Linux command

| command    | Description   |
|----------------|----------|
| pstree | Display tree of processes |
| hostname | Show or set the system's host name |
| hostname -I | Show all network addresses of the host |
| nmap -p \<port\> \<address\> | Ping specific port |
| ab -n \<number\> http://localhost:80/ | Perform \<number\> requests on specific url (apt install apache2-utils) |

# Linux tutorials



https://linuxize.com/post/how-to-set-up-ssh-keys-on-ubuntu-1804/

and 
# grep Password /etc/ssh/sshd_config 
PermitEmptyPasswords no
PasswordAuthentication no


https://www.digitalocean.com/community/tutorials/how-to-partition-and-format-storage-devices-in-linux



https://www.youtube.com/watch?v=pJF83mSllWE


https://medium.com/swlh/postgresql-replication-with-docker-c6a904becf77


[How to open ports in linux](https://creodias.eu/-/how-to-open-ports-in-linux- "https://creodias.eu/-/how-to-open-ports-in-linux-")

SELECT pg_reload_conf(); - reload pg_hba.conf

psql -h <ip_add> -p <port> -d <db_name> -U <user> - pripojenie sa na vzdialenu databazu
  
https://github1s.com/

https://confluence.jaytaala.com/display/TKB/Create+a+persistent+SSH+tunnel+between+servers+with+systemd

https://devconnected.com/how-to-ping-specific-port-number/


https://www.brandonchecketts.com/archives/creating-a-permanent-ssh-tunnel-between-linux-servers

https://vsupalov.com/docker-shared-permissions/
  
  

RESIZE disk on VM
  https://www.networkshinobi.com/proxmox-linux-vm-template/
  
  https://forum.proxmox.com/threads/resize-disk-of-ubuntu-19-10-vm-on-proxmox.70352/
  
  sudo parted /dev/sda
  
  resizepart 2
  
  
