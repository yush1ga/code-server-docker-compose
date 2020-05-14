code-server docker-compose
--

## Run

```
git clone https://github.com/yush1ga/code-server-docker-compose
mkdir -p $HOME/Projects
mkdir -p $HOME/.local/share/code-server
cd code-server-docker-compose
UID=${UID} GID=${GID} docker-compose up
```

Access http://$HOSTNAME:18080/
