# demo-spring-boot-app

**Step 1:** Build the Docker image using below command.

``` docker build -t demo-spring-boot-app . ```

**Step 2:** Tag  docker image.

```docker tag demo-spring-boot-app dhiraj2020/demo-spring-boot-app:latest```

**Step 3:** Push image.

```docker push dhiraj2020/demo-spring-boot-app:latest```

**Step 4:** Apply kubernetes deployment file

```kubectl apply -f kube-files/deployment.yaml```

**Step 5:** Apply kubernetes service file

```Kubectl apply -f kube-files/service.yaml```
