# Cronjob-Controller by KubeBuilder 2.0

This is sample controller for Cronjob Resource.
The Controller handles Cronjob Resource.  
If you want to know the detail of Cronjob, See [Sample YAML](./config/samples/batch_v1_cronjob.yaml).

This is made along [The Kubebuilder Book](https://book.kubebuilder.io/cronjob-tutorial.html).  

# Usage

Run localy

```
$ make install
$ make run
$ kubectl apply -f config/samples/batch_v1_cronjob.yaml
```

Run container as Deployment

```
$ make deploy
$ kubectl apply -f config/samples/batch_v1_cronjob.yaml
```
