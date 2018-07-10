# invoice_management
NodeJS microservices with Kubernetes and ambassador as a API Gateway

![ambassador](/img/ambassador.png)

# Overview

This is an simple application made with nodeJS called invoice_management, to use with ambassador (API Gateway) and Kubernetes (minikube) for scaling our services. The following steps show each services including ambassador (API Gateway Native https://www.getambassador.io/)

 - An API gateway to route traffic into our system
 - An authentication service to limit access
 - A front end invoices service to return information about invoices
 - A back end expected date service that’ll tell us when an invoice is likely to be paid

 ![ms_diagram](/img/ms_diagram.png)


# requirements
Virtual Box with Minikube (for more details please read this documentation https://kubernetes.io/docs/tasks/tools/install-minikube/)

