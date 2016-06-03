# crucial-terminal-commands
Crucial terminal commands
 
### Unfreeze mouse
  ``` bash
  	 sudo rmmod psmouse && sudo modprobe psmouse
  ```

### Copy SSH key via xclip 
 ``` bash
    xclip -sel clip < key.pem
 ```