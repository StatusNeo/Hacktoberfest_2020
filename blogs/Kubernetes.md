<h1>Kubernetes</h1>

<p>Kubenetes is an open source system originally developed by google to aid developers in the automation of deploying and managing applications inside containers across multiple machines.
</p>
<p align="center">
<img src="https://octoperf.com/img/blog/kraken-kubernetes-ingress-nginx-frontend/kubernetes.png" width="400">
</p>
<h2>
Introducing containers
</h2>

<p>Container systems (such as Docker) have popularised the strategy for developers to deploy applications inside ‘containers’ with all the content it needs, essentially virtualising a perfect environment to run the application with all included assets and libraries, removing the need for clients to run a virtual machine which is quite intensive in comparison.
</p>
<p>So while docker manages a container, Kubernetes has the ability to manage multiple containers across multiple machines and be able to scale the containers as needed as well as having logging tools that allow you to monitor and manage your clusters of containers, easing the burden of your workload.  
</p>

<h2>Terminology</h2>
<p>Introducing the most common terminology within the Kubernetes framework:</p>
<b>Node</b>
<p>A node is a virtual machine on your cluster, contains everything needed to run your applications within containers</p>
<b>Pod</b>
<p>A pod is a singular or small group of containers running within the same virtualised space called a pod</p>
<b>Cluster</b>
<p>Cluster is a group of nodes or virtualised environments running your application.</p>
<b>Kubernetes secret</b>
<p>An object within Kubernetes that has built in security, only accessible when absolutely nessesary but protected from exposing it and creating security risks.</p>
<b>kubectl</b>
<p>The CLI for managing your clusters of containers within Kubernetes</p>
