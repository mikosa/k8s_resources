## Installation
need to have python 3 and pip 3 installed
```
pip3 install  kubernetes  prettytable
```
you can add it to your linux path if u need to

## Run the script
The script uses your active kubeconfig on your machine. so if you have several kubernetes cluster, you will need to switch to the correct kubernetes cluster context before

then run 
```
./resources
```

+-----------------+---------------+------------------+
|    Namespace    | Requested CPU | Requested Memory |
+-----------------+---------------+------------------+
|     default     |       0       |        0         |
| kube-node-lease |       0       |        0         |
|   kube-public   |       0       |        0         |
|   kube-system   |      200      |       140        |
+-----------------+---------------+------------------+