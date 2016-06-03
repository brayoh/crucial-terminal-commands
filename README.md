# Crucial terminal commands

### Unfreeze mouse
  ``` bash
  	 sudo rmmod psmouse && sudo modprobe psmouse
  ```

### Copy SSH key via xclip 
 ``` bash
    xclip -sel clip < key.pem
 ```
### generate ssl cert using letsencrypt
 ``` bash
 	letsencrypt --text --email=<email-id> --domains <domain.com> --agree-tos --renew-by-default --manual certonly --config-dir ~/.letsencrypt/etc --work-dir ~/.letsencrypt/var-lib/ --logs-dir ~/.letsencrypt/var-log/
 ```