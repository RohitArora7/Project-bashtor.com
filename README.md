# Bashtor




**Tags :**________________________________________________________________

```<c>``` : Check prev command is successfully run or not. 

```<k:all``` : Check all pods are running or not.

```<k:p:pod_name``` : Check a particular pod is created and is in running phase.

```&&``` : This must be used at end of commands where ```<c>``` fails 

Example:
sudo apt install vim -y && \
```<c>```




**Note :**________________________________________________________________

1. Before using **<k:all , <k:p:pod_name** kube-config file must be present in local system .kube directory i.e. 
2. Kubectl must be installed in remote machine so that it can give update when pods not ready.  
3. ```<c>```  tag must also be included before ```<k:all , <k:p:pd_name```.
4. Install Curl before running bastor.
5. Program is tested on ubuntu 22.04 or highter.





**Shortcuts :**___________________________________________________________

> EDITOR SHORTCUT

Ctrl + b : Resize Editor to 20 %\
Ctrl + n : Resize Editor to 50 %\
Ctrl + m : Resize Editor to 70 %

> BUTTON SHORTCUT

Send cmd : Ctrl + j : Auto select the single command and send it to terminal.\
Select cmd : Ctrl + g : Send selected command to terminal.\
Start Script : Ctrl + w : Start script include ```<c>, <k:all, <k:p:pod_name```.\
Stop Script : Ctrl + e : Stop the script from executing.\
Open file : Ctrl + o : open the file.\
Save file : Ctrl + s : save the file.\
Select cmd and run in background : Ctrl + l : Incase you wanna run command in local machine rather than in VM

> TERMINAL SHORTCUT

Ctrl + L : Clear the terminal.\
Ctrl + Insert : Copy from terminal.\
Shift + Insert : Paste into terminal.
