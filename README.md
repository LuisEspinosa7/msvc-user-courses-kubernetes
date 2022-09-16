# Courses Users - EXAMPLE MICROSERVICES WITH KUBERNETES (BACKEND)

Courses Users are microservices for creating courses and add user to them. It's quite useful to play around with different architectures and technologies. They comunicate to each other by using feign client and are over kubernetes pods in this specific approach (repository), you may find different deployment options on the other repositories in my github. This WEB APP's backend was developed by Luis Espinosa Llanos using a microservice approach and the following technologies and tools were used: 

<table style="width:100%">
  <tr>
    <td>
  	Core	
    </td>
    <td>
  	Java 11, Spring Boot 2, Data JPA, Hibernate, Loombok, Jackson Databinding, Feign client.
    </td>
  </tr>
  <tr>
    <td>
  	Databases
    </td>
    <td>
  	PostgreSQL 14, MySQL.
    </td>
  </tr>
  <tr>
    <td>
  	Service discovery	
    </td>
    <td>
  	Kubernetes Services with Spring Kubernetes library.
    </td>
  </tr>
  <tr>
    <td>
  	Virtualization
    </td>
    <td>
  	Docker.
    </td>
  </tr>
  <tr>
    <td>
  	Server	
    </td>
    <td>
  	Apache Tomcat Embebido (Spring Boot)
    </td>
  </tr>
  <tr>
    <td>
  	IDE	
    </td>
    <td>
  	Intellij IDE
    </td>
  </tr>
  <tr>
    <td>
  	Executable	
    </td>
    <td>
  	Jar
    </td>
  </tr>
  <tr>
    <td>
  	Deployment	
    </td>
    <td>
  	Kubernetes - Minikube (Local)
    </td>
  </tr>
</table>

It was written using the best practices for instance, a controller, service and repository layer approach, code reusing, 
dependecy injection, inversion of control, abstractions, design patterns and more... 

## Video
A video exposing the functionality of the proyect in local environment.

1. https://youtu.be/6ELtLr9F4PM


## EKS (Elastic Kubernetes Service) implementation on AWS
You will find the EKS deployment implementation on the branch: 
- <b> eks-courses-users </b>

## Development Resources
I provide the following resources:

<table style="width:100%">
  <tr>
    <td>
  	Resources
    </td>
    <td>
	They are in the documentation folder 
    </td>
  </tr>
</table>





## Pictures
Some pictures of the project:

<table style="width:100%">
  <tr>
    <td>
  		<img width="450" alt="Image" src="https://user-images.githubusercontent.com/56041525/190690269-0d39cb03-c296-46d7-b8ed-300bc31dba53.PNG">
	  </td>
    <td>
  	<img width="450" alt="Image" src="https://user-images.githubusercontent.com/56041525/190690309-fcaf8c91-c023-4087-ab6b-9c0952be721a.PNG">
    </td>
  </tr>
</table>


<table style="width:100%">
  <tr>
    <td>
  		<img width="450" alt="Image" src="https://user-images.githubusercontent.com/56041525/190690350-38a7793e-c8fb-4098-be20-1d199e25d966.PNG">
	  </td>
    <td>
	<img width="450" alt="Image" src="https://user-images.githubusercontent.com/56041525/190690371-63075270-9c08-448e-ac59-33c5ef7e35e7.PNG">
    </td>
  </tr>
</table>


<table style="width:100%">
  <tr>
    <td>
  		<img width="450" alt="Image" src="https://user-images.githubusercontent.com/56041525/190690392-51f51ded-e0d0-4052-8b8d-3049f7f5917d.PNG">
	  </td>
    <td>
	<img width="450" alt="Image" src="https://user-images.githubusercontent.com/56041525/190690472-49358c98-1816-4b95-b328-1575245473fd.PNG">
    </td>
  </tr>
</table>


<table style="width:100%">
  <tr>
    <td>
  		<img width="450" alt="Image" src="https://user-images.githubusercontent.com/56041525/190690548-fcf67e3e-58b0-49cf-92dd-9de2c9842366.PNG">
	  </td>
    <td>
	<img width="450" alt="Image" src="https://user-images.githubusercontent.com/56041525/190690576-fe77949d-247c-41a9-8ab8-e6f0001d5472.PNG">
    </td>
  </tr>
</table>


<table style="width:100%">
  <tr>
    <td>
  		<img width="450" alt="Image" src="https://user-images.githubusercontent.com/56041525/190690640-bdb1b8d6-0da6-4c24-a3a3-511fb8c0e03f.PNG">
	  </td>
  </tr>
</table>



## Installation

This proyect should be installed using the following command on the base project's folder:
```bash
kubectl apply -f [each-file in the order mentioned on the video]
```

## Usage
The recommendation by now is to import it in your favority IDE. And run the project the way I did.


## Contributing
This proyect is quite simple, and is part of my personal portfolio, so it is not intended to receive contributions.
