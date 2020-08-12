# Simple Spring Boot Demo ready to Deploy on Kubernetes


#### Build Docker Image

```
mvn clean package spring-boot:build-image
```

#### Deploy on Kubernetes

```
kubectl apply -f target/classes/META-INF/dekorate/kubernetes.yml
```

