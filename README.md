# admin-mongo

This is a ready-to-deploy online MongoDB admin tool for the WISE-PaaS users who did not subscribe to the dedicated MongoDB service and could not remotely access the database.

## Deploying to Your Namespace

### Step 1

```shell
$ git clone git@github.com:WISE-PaaS/admin-mongo.git
$ cd admin-mongo/
$ code .
```

### Step 2

_ingress.yaml_

``host``: {appName}.{namespace}.{clusterName}**.en.internal**

### Step3

```shell
$ kubectl apply -f k8s/
```