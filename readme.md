# Goals of this project
- Utilise unused hardware - 2 x Raspberry pi 3B+ and 1 x Raspberry pi 2B. Don't we all have raspberries just sitting around ?
- Learn more about networking - networking is a very broad field and some extra knowledge won't hurt.
- Learn about k8s and specifically microk8s - kubernetes is something I've wanted to play for a long time, but now I have the chance and time mess around, microk8s were the first thing that came when I was looking for a raspberry pi cluster, so I went with that
- Start my home lab - a goal that I had for a long time and didn't have the time to commit to it. Ideally I would like to expand my lab and do more things
- And just have fun in the process


---

# The setup

I'll be following this guide to get started [How to build a Raspberry Pi Kubernetes cluster using MicroK8s](https://ubuntu.com/tutorials/how-to-kubernetes-cluster-on-raspberry-pi#1-overview) which looks pretty straightfoward - building and setting up the cluster. In my case my cluster physical apperance will be less impressive. 

![cluster_setup](img/)


I'm going with Ubuntu server and sadly I see this error: ![warning](img/warning.png)
Which means that the Pi 2B will not be part of the cluster, since It can't support 64-bit systems.

