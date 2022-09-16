# Courses Users - EXAMPLE MICROSERVICES (BACKEND)

Courses Users are microservices for creating courses and add user to them. It's quite useful to play around with different architectures and technologies. They comunicate to each other by using feign client and are over EC2 instances in this specific approach (repository), you may find different deployment options on the other repositories in my github. This WEB APP's backend was developed by Luis Espinosa Llanos using a microservice approach and the following technologies and tools were used: 

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
  	Just DNS or docker name
    </td>
  </tr>
  <tr>
    <td>
  	Virtualization
    </td>
    <td>
  	Docker, docker-compose
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
  	Cloud Provider	
    </td>
    <td>
  	Amazon Web Services (EC2)
    </td>
  </tr>
</table>

It was written using the best practices for instance, a controller, service and repository layer approach, code reusing, 
dependecy injection, inversion of control, abstractions, design patterns and more... 

## Video
A video exposing the functionality of the proyect in local environment as well as on AWS on a Desktop screen.

1. https://youtu.be/RLi9VIkEJ24


## Elastic Container Service implementation on AWS
You will find the ECS deployment implementation on the branch: 
- <b> ecs-courses-users </b>

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
  		<img width="450" alt="Image" src="https://user-images.githubusercontent.com/56041525/189465670-aa7201c1-ccf2-40d6-9d0a-e3ab739c406a.PNG">
	  </td>
    <td>
  	<img width="450" alt="Image" src="https://user-images.githubusercontent.com/56041525/189465676-5cd67160-8350-4502-b0f1-08adee6af650.PNG">
    </td>
  </tr>
</table>


<table style="width:100%">
  <tr>
    <td>
  		<img width="450" alt="Image" src="https://user-images.githubusercontent.com/56041525/189465681-eeb4e169-1a4f-4e7f-9174-c437abb7354f.PNG">
	  </td>
    <td>
	<img width="450" alt="Image" src="https://user-images.githubusercontent.com/56041525/189465695-4fa8f68b-fe5d-46fc-82de-da577d5d8ab8.PNG">
    </td>
  </tr>
</table>



## Installation

This proyect should be installed using the following command on the base project's folder:
```bash
docker-compose up -d
```

## Usage
The recommendation by now is to import it in your favority IDE. And run the project the way I did.


## Contributing
This proyect is quite simple, and is part of my personal portfolio, so it is not intended to receive contributions.
