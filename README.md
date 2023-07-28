# scaler-devops-challenge

1. You are creating a Kubernetes ConfigMap using a YAML file to store key-value pairs for your application's configurations. However, when you apply the YAML, you encounter an error. Can you identify what might be wrong with the following YAML snippet?"


```
apiVersion: v1
kind: ConfigMap
metadata:
  name: my-app-config
data:
  config.properties:
    app.name: MyApp
    app.version: "1.0"
    db.url: jdbc:mysql://db-server:3306/mydb
    db.username: myuser
    db.password: mypassword
```

2. ou have a Kubernetes cluster running multiple pods, and suddenly, some of the pods in a specific deployment are failing to start, showing CrashLoopBackOff status. You check the pod logs, but they don't provide any clear error message. What steps would you take to troubleshoot and resolve the issue?
