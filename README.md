# Kubernetes

To run application :

```sh
kubectl create -f .
```

A configmap will be created from the `configmap.blog.yaml` file, containing environment variables.  
The app and db deployments will use these environment variables.

The web service is exposed on port `31023`. To see the app working, you can run :

```sh
curl -L <YOUR_NODE_IP>:31023
```