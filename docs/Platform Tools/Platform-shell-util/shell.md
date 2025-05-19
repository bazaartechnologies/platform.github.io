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
3. Here you'll see multiple utils now as per the naming convention like</br>**util-finance-platform-fintech**
