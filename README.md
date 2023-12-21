## RASTAD Milena M1_EXAM

## Command I did to deploy the app via docker and k8s

docker build -t my-counterjs-app .

docker run -p 8080:8080 my-counterjs-app

docker login

docker tag my-counterjs-app mimi83web/my-counterjs-app:1.0.0

docker push mimi83web/my-counterjs-app:1.0.0

![image](https://github.com/Mimi83-Web/Exam_Microservice/assets/80813713/3d977fe7-543f-4ed5-91c7-f529fb0408f4)


kubectl apply -f fichier_deployment.yaml

kubectl expose deployment counterjs-deployment --type=NodePort --name=counterjs-service --port=8080

![image](https://github.com/Mimi83-Web/Exam_Microservice/assets/80813713/0e2d3108-961a-466a-b81e-b474d4b19489)

![image](https://github.com/Mimi83-Web/Exam_Microservice/assets/80813713/8b259102-b98c-4c0a-9077-c27ca7adc2d1)

![image](https://github.com/Mimi83-Web/Exam_Microservice/assets/80813713/f37150b1-e611-4479-a363-3d884d561e44)

![image](https://github.com/Mimi83-Web/Exam_Microservice/assets/80813713/00014e28-2de9-45ed-b0a0-e4ad13979feb)

