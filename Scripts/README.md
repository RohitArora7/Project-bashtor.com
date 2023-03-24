**Tags :**________________________________________________________________

```<c>``` : Check prev command is successfully run or not. 

```<k:all``` : Check all pods are running or not.

```<k:p:pod_name``` : Check a particular pod is created and is in running phase.

```&&``` : This must be used at end of commands where ```<c>``` fails 

Example:\
sudo apt install vim -y ```&&``` \
```<c>```