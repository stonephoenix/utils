In MacOs, docker ps does not work, you could use 
  colima start

To start colima now and restart at login:
``` shell
  brew services start colima
```
Or, if you don't want/need a background service you can just run:
``` shell
  /usr/local/opt/colima/bin/colima start -f
```
