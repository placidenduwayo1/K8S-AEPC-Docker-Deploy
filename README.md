# containerization microservices-base application

this git is containing a **docker-compose** template file for deploying appliccation microservices:

* utility docker containers related to services:
	 * a configuration container: ***k8s-aepc-ms-config-server***
	 * a container of registration of microservices: ***k8s-aepc-ms-registry-service***
 
* containers related to business microservices:

	* a container microservice of managing addresses: ***k8s-aepc-bs-ms-address***
	* a container microservice of managing employees: ***k8s-aepc-bs-ms-employee***
	* a container microservice of managing projects: ***k8s-aepc-bs-ms-project***
	* a container microservice of managing companies: ***k8s-aepc-bs-ms-company***

the backend(a spring boot microservices-base application) is located [back]()

## microservices configuration server
- all services (utility services and business services) configiration files for config server are located here: [ms-config](https://github.com/placidenduwayo1/K8s-AEPC-ms-config-centralisation.git)

