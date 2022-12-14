LAB - vCluster Usage
=====================

Sample workshop showing how to use vClusters to management cluster-scoped objects per workshop attendee.

If you already have the Learning Center operator installed and configured, to
deploy and view this sample workshop, run:

```
kubectl apply -f https://raw.githubusercontent.com/eduk8s/lab-markdown-sample/master/resources/workshop.yaml
kubectl apply -f https://raw.githubusercontent.com/eduk8s/lab-markdown-sample/master/resources/training-portal.yaml
```

This will deploy a training portal hosting just this workshop. To get the
URL for accessing the training portal run:

```
kubectl get trainingportal/lab-markdown-sample
```

The training portal is configured to allow anonymous access. For your own
workshop content you should consider removing anonymous access.
