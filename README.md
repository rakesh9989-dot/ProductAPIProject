ProductAPI project:
	
1. The project is about building a springboot application which performs CRUD operations on product Management.
2. I used RESTful API for managing products using Spring Boot and MongoDB.
3.The Product.java will create the products collection in the mongoDB. The code will recognize the document 
by annotation @Document(collection="products").
4. In ProductRepository.java , it is used to connect the product.java to MongoDB.@Repository is used to identify it is a repository.
5. In ProductService.java implemented CRUD operations.@Service is used to define it is a service class.
6. In ProductController.java the main implementation is done. Created api's for every CRUD operation.
7. So I used postman api to test api keys working or not. To add data in mongoDB , we need to set the post method and insert the data 
in JSON format. We need to append api key for post method to the link.
8. @RestController is used to control the all api's which are created. @RequestMapping("/api/products") is the main api or root api.
9. For post method we have annotation as  @PostMapping, for get method we have @GetMapping("yout_api"), for put we have @PutMapping("/{id}"),
for delete we have  @DeleteMapping("/{id}"). These annotations will help to identify which method should use.



## Spring Boot
This is a simple Spring Boot project. This application serves as a basic template for a Spring Boot based application.
This project is bootstrapped with [Spring Initializr](https://start.spring.io/).

## How to run

1. Run the application by running the following command in the terminal:
   ```sh
   mvn spring-boot:run
   ```   

2. Refresh the URL in a simple browser to see the output. You can also click the run button above the Main program to run the application instead the above command.


![](https://static.onecompiler.com/images/posts/3zzkbysj7/run-spring-boot.png)

> If you do not see the Run button, Please wait for a minute for the project to load and open as a Java Project.

<!-- 1. Before running the application, make sure all dependencies are installed. To install dependencies, run following command in terminal:
   ```sh
   ./gradlew build -x test
   ```

2. To run the application, run following command in terminal:
   ```sh
   ./gradlew bootRun
   ```   
3. Refresh the URL in simple browser to see the output.    -->
