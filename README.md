# Courses Users - EXAMPLE MICROSERVICES WITH AWS EKS (BACKEND)

Courses Users are microservices for creating courses and add user to them. It's quite useful to play around with different architectures and technologies. They comunicate to each other by using feign client and are over AWS EKS kubernetes in this specific approach (repository), you may find different deployment options on the other repositories in my github. This WEB APP's backend was developed by Luis Espinosa Llanos using a microservice approach and the following technologies and tools were used: 

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
  	Kubernetes - AWS EKS
    </td>
  </tr>
</table>

It was written using the best practices for instance, a controller, service and repository layer approach, code reusing, 
dependecy injection, inversion of control, abstractions, design patterns and more... 

## Video
A video exposing the functionality of the proyect in AWS EKS

1. https://youtu.be/6ELtLr9F4PM


## MINIKUBE (KUBERNETES LOLCA) implementation:
You will find the MINIKUBE implementation on the branch: 
- <b> master </b>

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
  		<img width="450" alt="Image" src="https://user-images.githubusercontent.com/56041525/190865791-9555c28a-0a69-489f-b1d9-10030700549f.PNG">
	  </td>
    <td>
  	<img width="450" alt="Image" src="https://user-images.githubusercontent.com/56041525/190865798-becc144d-25ab-4761-be42-c5db55d63673.PNG">
    </td>
  </tr>
</table>



<table style="width:100%">
  <tr>
    <td>
  		<img width="450" alt="Image" src="https://user-images.githubusercontent.com/56041525/190865806-a4cec0e7-84c1-482d-8e08-42ce253fc363.PNG">
	  </td>
    <td>
	<img width="450" alt="Image" src="https://user-images.githubusercontent.com/56041525/190865817-fb24d9e8-985c-4303-bd68-f68e4d439b1b.PNG">
    </td>
  </tr>
</table>


<table style="width:100%">
  <tr>
    <td>
  		<img width="450" alt="Image" src="https://user-images.githubusercontent.com/56041525/190865827-7383f8b0-386d-48d9-8c92-63b58ee76e03.PNG">
	  </td>
    <td>
	<img width="450" alt="Image" src="https://user-images.githubusercontent.com/56041525/190865831-cd8539fb-76f7-4778-84fd-95ab63593e7b.PNG">
    </td>
  </tr>
</table>


<table style="width:100%">
  <tr>
    <td>
  		<img width="450" alt="Image" src="https://user-images.githubusercontent.com/56041525/190865854-78806b8b-5890-413d-91d2-d4d53b97570e.PNG">
	  </td>
    <td>
	<img width="450" alt="Image" src="https://user-images.githubusercontent.com/56041525/190865863-e3e8f8d5-6253-4068-8192-c151e86e1417.PNG">
    </td>
  </tr>
</table>



<table style="width:100%">
  <tr>
    <td>
  		<img width="450" alt="Image" src="https://user-images.githubusercontent.com/56041525/190865876-b5a52c6a-738d-4358-be0d-4a1732e0c576.PN">
	  </td>
    <td>
	<img width="450" alt="Image" src="https://user-images.githubusercontent.com/56041525/190865886-c2596471-2126-4d2e-bb43-5c447d4c3a95.PNG">
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
