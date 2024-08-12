# ecommerce-angular-springbootjava
Full stack E-commerce Application using Angular and Java SpringBoot



# Project Setup and Configuration:

### Backend:
* In the starter: we visit ```https://start.spring.io/``` 
* Choose Maven and then version that it supported installed on PC 
* Dependencies Added:  Lombok, MySQL Driver, Rest Repositories, Spring Data JPA
* Import the project in Intellij IDEA
* Go to ```http://localhost:8080/api``` and check the api on browser
* Same go to ```http://localhost:8080/api/product-category``` and check the api
* Same go to ```http://localhost:8080/api/product-category/1/products``` and check then api


### Frontend:

* Run ```ng new angular-ecmmerce``` to create apps
* Run ```ng generate component components/product-list``` to create component
* Run ```ng serve --open``` and see ```http://localhost:4200/``` on browser
* Run ```ng generate class common/product``` to create component class
* Run ```ng generate service services/product``` to create service

##### Frontend : I tegrating Online shop template:

* Run ```npm install bootstrap@5.2.0``` and configure bootstrap on the project.
* ```npm install @fortawesome/fontawesome-free``` and configure font awesome on the project.
