Art M&A DevOps interview:

Goal:
	Our goal is to evaluate the candidate's ability to configure and troubleshoot a standard Art environment.  In this exercise we will go over a few things:

Prerequisit:
	Please make sure to setup a kubernetes environment (Minikube is recommended).  On a mac, HomeBrew is a good way to deploy minikube.
	Also it's recommended you have local docker daemon running unless you have a docker-hub account.  Use the following command to point to local docker repo: "eval $(minikube docker-env)"

Exercise:
1.	Build a docker image with the provided nginx.conf
2.	Deploy the image with the provided "deployment.yaml" file.
3.	Identify the issues preventing the container from starting.
