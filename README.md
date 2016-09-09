# rancher-md

contains a docker image which mimics the rancher-metadata API

```
docker build -t ranchermd .
docker run -it --rm -p80:80 ranchermd
```


# confd

```
confd -backend rancher -confdir ./ -onetime -prefix latest
```
