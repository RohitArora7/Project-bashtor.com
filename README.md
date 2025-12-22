# Bashtor




**Tags :**________________________________________________________________

```<c>``` : Check prev command is successfully run or not. 

```<r>``` : re-Check prev command untill successfully run. 

```<k:all``` : Check all pods are running or not.

```<k:p:pod_name``` : Check a particular pod is created and is in running phase.


**Shortcuts :**___________________________________________________________

> EDITOR SHORTCUT

Ctrl + b : Resize Editor to 20 %\
Ctrl + n : Resize Editor to 50 %\
Ctrl + m : Resize Editor to 70 %

> BUTTON SHORTCUT

-RUN \
Ctrl + j : Auto select the single command and send it to terminal.\
Ctrl + g : Send selected command to terminal.\
Ctrl + l : Incase you wanna run command in local machine run in background rather than in VM.

-SCRIPT \
Ctrl + w : Start script include ```<c>, <k:all, <k:p:pod_name```.\
Ctrl + e : Stop the script from executing.

-FILE \
Ctrl + o : open the file.\
Ctrl + s : save the file.

-TAGS \
Ctrl + q : Add ```<c>``` at end of all commands.\
Ctrl + r : Remove all ```<c>```.

> TERMINAL SHORTCUT

Ctrl + L : Clear the terminal.\
Ctrl + Insert : Copy from terminal.\
Shift + Insert : Paste into terminal.


**Note :**________________________________________________________________

1. Before using **<k:all , <k:p:pod_name** kube-config file must be present in local system .kube directory i.e. 
2. Kubectl must be installed in remote machine so that it can give update when pods not ready.  
3. ```<c>```  tag must also be included before ```<k:all , <k:p:pd_name```.
4. Install Curl before running bastor.
5. Program is tested on ubuntu 22.04 or highter.



**How it's work :**________________________________

https://www.youtube.com/watch?v=cPrxVsA1Iak
