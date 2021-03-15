## DOCKER-COMPOSE GITEA

**NOTE:** Before running, either create a file called ***.env*** with the line `DB_PW=<password>`, or replace both occurrences of `"${DB_PW}"` in ***docker-compose.yml*** with an actual password. Do the same thing with the values "UID" and "GID". 

> You can get your UID on Unix/Linux systems with `id -u` and your GID with `id -g`.

Example **.env** file:

```
DB_PW=badpasswd
UID=1000
GID=1000
```
This repository was originally part of a larger repository - I copied it from *SYS265/docker01/* in my [CNCS Journal Repository](https://github.com/eliminmax/cncs_journal/tree/master/SYS265/docker01)

