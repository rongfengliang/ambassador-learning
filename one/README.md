
# ambassador basic demo

* insatll

```code
kubectl apply -f ambassador-no-rbac.yaml
kubectl apply -f ambassador-service.yaml

```

* deploy demo service

```code
kubectl apply -f qotm.yaml

```

* Access

```code
get ambassador service nodeport 

and the  http://hostip:nodeport/qotm/
```