# Shell utility for calling internal APIs 🧠

## 🧘 Why there was a need for it? 

- We need to make the API endpoints public on gateway that were meant to be called internally by the devs only, so didn't made sense to make them public hence to call the APIs from within the network we used ArgoCD.

## 🚀 How ArgoCD solved the problem? 
- ArgoCD offers web-based-terminal through which we can take shell into a pods right from ArgoCD UI and make a curl request from there to call the internal API.

https://argo-cd.readthedocs.io/en/latest/operator-manual/web_based_terminal/

## 💡 How to use it?
1. Login to ArgoCD
2. Search in apps 'util'</br>
![image.png](assets/util-0.png)</br>
3. Here you'll see multiple utils now as per the naming convention like</br>**util-fintech-platform-fintech**</br>
**fintech-platform** is the domain
**fintech** is the cluster
4. Click on the util in which your service lies according to the domain and cluster
5. Just click on the sync button
![image.png](assets/util-1.png)</br>
**After syncing you'll see the blue progressing icon that means session has started for 5 mins**
![image.png](assets/util-2.png)</br>
6. Click on the pod you'll switch to terminal tab
![image.png](assets/util-3.png)</br>
7. I ran this curl command but you will run the actual endpoint which you wish to call but make sure the service you are calling is in the domain fintech-platform and running in EKS cluster fintech account for rest services we have more utils w.r.t that
```curl bazaar-lending-service-base.lending-platform.svc.cluster.local/actuator/health```
![image.png](assets/util-4.png)</br>