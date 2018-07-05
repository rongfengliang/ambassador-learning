
# ambassador grpc demo

> require you have install ambassador && qotm demo


## config service with grpc service

```code
kubectl apply -f demo-grpc.yaml
```

## test

```code
docker run -e ADDRESS=hostip:nodeport enm10k/grpc-hello-world greeter_client

```

