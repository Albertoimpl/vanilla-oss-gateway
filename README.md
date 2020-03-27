
# Publishing the image
```bash
./gradlew jib --image=albertoimpl/vanilla-oss-gateway:0.0.1
```

# Local development
```bash
skaffold dev
```
```bash
curl localhost:3000/actuator/health
```

# Testing helm chart
```bash
helm install --dry-run --debug my-gateway ./chart/spring-cloud-gateway
```
# Installing the helm chart

```bash
helm install my-gateway ./chart/spring-cloud-gateway
```
