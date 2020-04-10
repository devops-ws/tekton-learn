You can use the below command to create a secret against the docker hub registry:

```
export USERNAME=
export PASSWORD=
export EMAIL=

kubectl create secret docker-registry docker-hub \
    --docker-server=docker.io \
    --docker-username=$USERNAME \
    --docker-password=$PASSWORD \
    --docker-email=$EMAIL
```