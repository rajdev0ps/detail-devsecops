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

###################################################################################################
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

3) SAST Statics Application Scanning Test using SONARCLOUD
_____________________________________________________________________________________________________________________________
![image](https://user-images.githubusercontent.com/95608758/225016905-d51e565a-93df-4652-a68a-d00af76790d7.png)
![image](https://user-images.githubusercontent.com/95608758/225016959-24f4d85a-26a2-45e9-ab43-07099d28c5b4.png)

4) Vulnerablity Scanning using Dependency Check Plugin 
_____________________________________________________________________________________________________________________________
![image](https://user-images.githubusercontent.com/95608758/225017318-7a15c775-0ef7-44a5-b55f-97949fb0ea46.png)
![image](https://user-images.githubusercontent.com/95608758/225017342-8c9a6788-b05b-46a5-a551-4ef2c99859ba.png)

5) Vulnerablity Scanning for Containers and Artifacts using TRIVY
_____________________________________________________________________________________________________________________________
![image](https://user-images.githubusercontent.com/95608758/225017672-9aa5b8e3-dab0-45a4-ba8c-f3bb8930980e.png)
![image](https://user-images.githubusercontent.com/95608758/225017698-544d336e-058d-4486-a88d-30db319ab71a.png)
![image](https://user-images.githubusercontent.com/95608758/225017722-3e3707d1-72f9-470b-ba19-7dd8c5c6ec67.png)
![image](https://user-images.githubusercontent.com/95608758/225017750-f4bdf784-57b6-4bf3-8104-a4ffb5b634ea.png)
![image](https://user-images.githubusercontent.com/95608758/225017766-05edddef-f24c-4002-bc2a-e9a34e0497a8.png)

6) OPA (Open Policy Agent) for Hardening Docker/Terraform/kubernetes configurations
_____________________________________________________________________________________________________________________________
![image](https://user-images.githubusercontent.com/95608758/225018285-1490798f-d2a4-469b-8c80-12ae50e36862.png)
![image](https://user-images.githubusercontent.com/95608758/225018324-30cc0edb-f5f6-42ff-b461-033ee9d41358.png)
![image](https://user-images.githubusercontent.com/95608758/225018414-29236625-98e2-431d-8f95-40f489d8cdae.png)
![image](https://user-images.githubusercontent.com/95608758/225018502-424190e3-bc4c-4a0b-b61d-3d6f75264925.png)

7) Scanning Kubernetes cluster for exploits using kubescan 
_____________________________________________________________________________________________________________________________
![image](https://user-images.githubusercontent.com/95608758/225018877-931158a2-f919-4922-bdee-7463a839bda3.png)
![image](https://user-images.githubusercontent.com/95608758/225018917-1b77da73-767f-478e-ae9e-10ca863a421c.png)
![image](https://user-images.githubusercontent.com/95608758/225018986-e0cc36b4-0093-4909-8353-38665917d836.png)
![image](https://user-images.githubusercontent.com/95608758/225019020-4bfba3e6-0e23-4f48-b50e-9305a4074778.png)



############################################ END #######################################################

