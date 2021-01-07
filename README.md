# kubernetes

An Awesome kubernetes aka K8s learning Repo

## Installation

Installing Kubernet using VirtalBox and **Windows** as base OS

1. Install virtalbox



2. Install miniqube
		Program for installing k8s server on virtual box 
	
		Download https://storage.googleapis.com/minikube/releases/latest/minikube-installer.exe 
		and install it.
	
		Change location to same directory and run following command
		
		miniqube status  | run command to check proper installation
	
		miniqube.exe start --driver=virtualbox --kubernets-version=v1.20.2 
	


3. Install kubectl 

		Program to manage k8s server
	
		Change location to same directory where miniqube program is installed and run following command
		
		curl -LO https://storage.googleapis.com/kubernetes-release/release/v1.20.0/bin/windows/amd64/kubectl.exe
		
		
		
## Usage

* Basic commands for managing Pods

		kubectl.exe get pods
