# MVP
## Access To The Application
```sh
kubectl port-forward -n demo svc/ambassador 8088:80&
```
## Download image(example)
```sh
wget -O ~/Desktop/azure.png https://static-00.iconduck.com/assets.00/microsoft-azure-icon-512x396-6fn0yfat.png
```
## Convert image
```sh
curl -F 'image=@/~/Desktop/azure.png' localhost:8088/img/
```
# Demo
![Image](./app.gif)