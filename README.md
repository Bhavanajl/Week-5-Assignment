# Week-5-Assignment


REQ: Develop the Spring Boot with RESTful API appliction for the Product Model and Test all the layers:


STEP1: Create the Product Entity.

STEP2: Create the Product Repository

STEP3: Create the Product Service by using the following methods:


         public Product saveProduct(Product product);
         public Product getProductById(int id);
         public List<Product> getAllProducts();
         public Product getProductByName(String productName);
         public Product updateProduct(Product product);//Update product price based on product id
         public boolean deleteProductById(int id);
         public boolean deleteProductByName(String pname);


Step4: Create the Product Controller by using the following handlers methods:

         public ResponseEntity<Product> saveProduct(...){
         		//1. save product
         		//2. return Product with HttpStatus as CREATED
         }

         public ResponseEntity<Product> getProductById(...){
               //1 Get Product By Id
               //2.Return Product with HttpStatus as OK
         }
         public ResponseEntity<List<Product>> getAllProducts(){
         		//1. Get All Products
         		//2. Return All products with HttpStatus is OK
         }
         public ResponseEntity<Product> getProductByName(....){
         		//1. Get Product ByName
         		//2. Return Product with HttpStatus is OK
         }
         public ResponseEntity<Product> updateProduct(....){
                //1. Update Product
                //2. Return Product with HttpStatus is OK
         }
         public ResponseEntity<String> deleteProductById(...){
                 //1. Delete Product By Id
                 //2. Return HttpStatus Message is Success Delete with Status Code Ok
         }
         public ResponseEntity<String> deleteProductByName(.....){
          		  //1. Delete Product By Name
                 //2. Return HttpStatus Message is Success Delete with Status Code Ok
         }



Step5: Create the following TestSuit for the corresponding Layers:

        - ProductRepositoryTest.java
        
        - ProductServiceTest.java
        
        - ProductControllerTest.java
        
 
 Note: Test all the layers.
--------------------------------------------
