# kubernetes-devops-security

## Fork and Clone this Repo  sonar

## Clone to Desktop and VM

## NodeJS Microservice - Docker Image -
`docker run -p 8787:5000 siddharth67/node-service:v1`

`curl localhost:8787/plusone/99`
 
## NodeJS Microservice - Kubernetes Deployment - testing
`kubectl create deploy node-app --image siddharth67/node-service:v1`

`kubectl expose deploy node-app --name node-service --port 5000 --type ClusterIP`

`curl node-service-ip:5000/plusone/99`

##############################################################################################################################
1) Talisman for repository Scanning
_____________________________________________________________________________________________________________________________
![image](https://user-images.githubusercontent.com/95608758/225016011-e1f6dbd5-8ab4-4c5f-b287-ef1d7b1cf4f5.png)
![image](https://user-images.githubusercontent.com/95608758/225016080-9beb7bf1-7073-4741-888c-a948033a1634.png)


2) Mutation Testing on application code using  PIT
_____________________________________________________________________________________________________________________________
![image](https://user-images.githubusercontent.com/95608758/225016341-dc39b4c0-3cd0-41e8-b717-20de01cb0472.png)
![image](https://user-images.githubusercontent.com/95608758/225016376-214d27e5-e33a-4182-9891-00df352c3ca9.png)
![image](https://user-images.githubusercontent.com/95608758/225016416-befefaf6-afe8-4089-8669-0dc49f68a6f5.png)
![image](https://user-images.githubusercontent.com/95608758/225016466-100fd30d-eaae-4056-b75f-3ef2ce99fe34.png)
