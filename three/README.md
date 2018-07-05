
# ambassador Rate Limiting

> require you have install ambassador && qotm demo

## insatll Rate Limiting service

```code
kubectl apply -f example-rate-limit.yaml
```

## config service with Rate Limiting

```code
kubectl apply -f service-config.yaml
```

## test

```code
curl -v -H "x-ambassador-test-allow: probably" $AMBASSADORURL/qotm/quote/1
```