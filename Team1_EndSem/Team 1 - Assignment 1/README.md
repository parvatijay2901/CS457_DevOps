# Setting up Complete CI/CD Jenkins Pipeline for Kubernetes
## Steps:
1. Setting up pre-configured Virtual Machines using Vagrant.
2. Updating /etc/hosts on all nodes & Adding ssh key from jenkinsserver to other nodes.
3. Cloning kubespray git repository and setting up kubespray.
4. Install kubectl on k8smaster.
5. Install and configure Jenkins on jenkinsserver.
6.  Install and configure Docker in jenkinsserver.
7.  Create a new Pipeline for our application in jenkins.
8.  Building and Testing Pipeline.
## References: 
1. https://jhooq.com/kubespray-12-steps-for-installing-a-production-ready-kubernetes-cluster/
2. https://jhooq.com/ci-cd-jenkins-kubernetes/
3. https://github.com/rahulwagh/springboot-with-docker
