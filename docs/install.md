# CodeSpace Installation

To install Codespace on your linux machine all you have to do is installing Docker. This can be done via the command below.

```
bash <(wget -qO- https://raw.githubusercontent.com/RunesRepoHub/Codespace/docker-install-script.sh)
```

When Docker has been installed then you can run this command to get the docker container up and running.

```
docker run -p 8080:80 rune004/codespace:latest
```