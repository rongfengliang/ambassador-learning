# multi ambassador running

## How to run

```code
kubectl create namespace test
kubectl create namespace test-svc
```

## Run multi ambassador

* deploy

```code
kubectl apply -f ambassador-no-rbac.yaml -f ambassador-no-rbac-test.yaml
```

* service

```code
kubectl apply -f ambassador-service.yaml -f ambassador-service-test.yaml
```

## delpoy demo service

```code
kubectl apply -f demo-1.yaml -f demo-2.yaml

```