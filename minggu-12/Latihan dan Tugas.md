# Kubernetes Intro

## Step 1 : [Minikube Installation & Configuration](https://minikube.sigs.k8s.io/docs/start/)
1. Download Minikube Installer and run the installer for the latest release in link [minikube start](https://minikube.sigs.k8s.io/docs/start/).<br>
![image](https://github.com/Afifa9/tekn-cloud-computing/assets/114986359/214fbb89-aa97-4308-862d-560468a05884)


![image](https://github.com/Afifa9/tekn-cloud-computing/assets/114986359/842e006e-6e01-4420-a07c-0708a7d100fd)


2. Start Cluster by run a command prompt with administrator access and then type the following command ```minikube start```:<br>

![image](https://github.com/Afifa9/tekn-cloud-computing/assets/114986359/f4c4a29e-4d50-4787-9851-8dcb712daafa)


3. Try Interact With The Cluster and then type the following command ```kubectl get po -A``` in the command prompt.<br>

![image](https://github.com/Afifa9/tekn-cloud-computing/assets/114986359/fa5d2599-5ae3-4490-805d-cb940ccaa393)


4. Open a new terminal and type the following command ```minikube dashboard``` in the command prompt and then access in [this link](http://127.0.0.1:51134/api/v1/namespaces/kubernetes-dashboard/services/http:kubernetes-dashboard:/proxy/#/workloads?namespace=default).<br>

![image](https://github.com/Afifa9/tekn-cloud-computing/assets/114986359/9ff6e93f-71e9-4bbc-b154-bba42202f007)

Direct ke web browser

![image](https://github.com/Afifa9/tekn-cloud-computing/assets/114986359/8fe0c03f-6de3-4c57-9aac-4cfea4d8229d)


## Step 2 : [Create a Deployment](https://kubernetes.io/docs/tutorials/hello-minikube/#create-a-deployment)

1. Type the following command ```kubectl create``` to create a Deployment that manages a Pod in the command prompt. The Pod runs a Container based on the provided Docker image.<br>

![image](https://github.com/Afifa9/tekn-cloud-computing/assets/114986359/b8328059-6a55-4c8f-b9cb-ee55707f8538)


2. See the Deployment that was created earlier, with following this command ```kubectl get deployments``` in the command prompt.<br>

![image](https://github.com/Afifa9/tekn-cloud-computing/assets/114986359/19592ca3-30eb-41dc-8767-53a26bc8d8bf)


3. See the Pod with following this command ```kubectl get pods``` in the command prompt.<br>

![image](https://github.com/Afifa9/tekn-cloud-computing/assets/114986359/6884aae6-f60f-46c9-9ada-bc28ad49767f)

4. See the cluster events with following this command ```kubectl get events``` in the command prompt.<br>

![image](https://github.com/Afifa9/tekn-cloud-computing/assets/114986359/a0c95517-2030-46cb-bc25-8cf93781c8fc)


5. See the kubectl configuration with following this command ```kubectl config view``` in the command prompt.<br>

![image](https://github.com/Afifa9/tekn-cloud-computing/assets/114986359/6aa52859-66dd-4c3c-b123-402e1ce81755)

## Step 3 : [Create a Service](https://kubernetes.io/docs/tutorials/hello-minikube/#create-a-service)

1. Expose the Pod to the public internet using the ```kubectl expose``` command:<br>

![image](https://github.com/Afifa9/tekn-cloud-computing/assets/114986359/ffe8fe9b-61ee-42fc-9281-2ba09e5a2213)


The --type=LoadBalancer flag indicates that you want to expose your Service outside of the cluster.<br>
The application code inside the test image only listens on TCP port 8080. If you used kubectl expose to expose a different port, clients could not connect to that other port.

2. See the Service that was created earlier, with following this command ```kubectl get services``` in the command prompt.<br>

![image](https://github.com/Afifa9/tekn-cloud-computing/assets/114986359/22426b0c-0038-4e3b-9440-f1a924d20818)

3. Run the following command ```minikube service hello-node``` in the command prompt, and opens up a browser window that serves your app and shows the app's response.<br>

![image](https://github.com/Afifa9/tekn-cloud-computing/assets/114986359/29510ef6-1fbb-4955-9958-daa9c4c35c2e)


![image](https://github.com/Afifa9/tekn-cloud-computing/assets/114986359/249582ff-c169-4b2f-b15a-d1d2acbfb5e8)


## Step 4 : [Enable add-ons](https://kubernetes.io/docs/tutorials/hello-minikube/#enable-addons)

1. View list the currently supported addons with following this command ```minikube addons list```:<br>

![image](https://github.com/Afifa9/tekn-cloud-computing/assets/114986359/4b321e9f-6dc7-4762-b0c8-9ed2da189233)

2. Enable an addons metrics server, with following this command ```minikube addons enable metrics-server```:<br>

![image](https://github.com/Afifa9/tekn-cloud-computing/assets/114986359/38ff1fb1-e4c2-4a1e-90e3-a3e63ddd1a50)


3. View the Pod and Service you created by installing that addon with following this command ```kubectl get pod,svc -n kube-system```:<br>

![image](https://github.com/Afifa9/tekn-cloud-computing/assets/114986359/16f89d6e-e8b1-41ee-a8de-ffd203df7cd2)


4. Disable metrics server with following this command ```minikube addons disable metrics-server```:<br>

![image](https://github.com/Afifa9/tekn-cloud-computing/assets/114986359/a23d9092-29a9-44be-b9f4-f100b34a9cb9)


## Step 5 : [Clean Up](https://kubernetes.io/docs/tutorials/hello-minikube/#clean-up)

1. Try to clean up the resources you created in your cluster, with following this command ```kubectl delete service hello-node & kubectl delete deployment hello-node```:<br>

![image](https://github.com/Afifa9/tekn-cloud-computing/assets/114986359/c7aa6ba9-d472-445a-948e-f7894367f210)


![image](https://github.com/Afifa9/tekn-cloud-computing/assets/114986359/690ac07b-dd7f-4923-91a1-8dd4c19e0dbc)

2. Stop the Minikube cluster with following this command ```minikube stop```.<br>

![image](https://github.com/Afifa9/tekn-cloud-computing/assets/114986359/88a4e99c-e150-4242-b7a6-59026cfcca21)

<p>Perintah diatas dijalankan untuk menghentingkan proses minikube, dari hasil tersebut terdapat 1 node yang dihentikan</p>

3. Optionally, delete the Minikube Virtual Machine with following this command ```minikube delete```:<br>

![image](https://github.com/Afifa9/tekn-cloud-computing/assets/114986359/412d2b99-5ebd-43c4-b79c-57e8fbc724f9)

<p> Selanjutnya perintah yang terakhir digunakan untuk menghapus minikube yag ada didalam virtual machine</p>
