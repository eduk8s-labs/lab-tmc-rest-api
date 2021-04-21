LAB - TMC REST API
==================

Workshop exploring the TMC REST API.

If you already have the Educates operator installed and configured, to
deploy and view this sample workshop, run:

```
kubectl apply -f https://raw.githubusercontent.com/eduk8s-labs/lab-tmc-rest-api/master/resources/workshop.yaml
kubectl apply -f https://raw.githubusercontent.com/eduk8s-labs/lab-tmc-rest-api/master/resources/training-portal.yaml
```

This will deploy a training portal hosting just this workshop. To get the
URL for accessing the training portal run:

```
kubectl get trainingportal/lab-tmc-rest-api
```

The training portal is configured to require an access code, use "tanzu".
