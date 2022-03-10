# case-study-5th-week

case Study:
===========
PizzaHouse Store Management Application (JPA):
===============================================

Use LayerdArchiteture Format:
============================
1.create a package with com.pizzamanagement.model
   1.1 create a model class (Pizza)
   
    properties of Pizza Class:
	========================
	private int pizzaNo;
	private String pizzaType;
	private int pizzaPrice;
	private String DeliveryAdd;
	
	1.1.1=> Add one default constructor 
	1.1.2=> Add one Parameterized constructor with given properties
	1.1.3=> Add toString() method with class Properties


2.create a package with com.pizzamanagement.service 

   2.1=>create a Interface PizzaService
         
		 Add Services pizzaHouseStore
		 ============================
		 *addPizza
		 *updatePizaa
		 *deletePizza
		 *findPizzaByNo
		 
	2.2=> create a class PizzaServiceImpl
	     
		   *provide implemntation of services added in PizzaSevice Interface
		             *create Dao "OBJECT" TO Accsess the data 
					 * create a default serviceimpl constructor 
					         initialize the dao object in above constructor 
					 
          		 
3. create a package with com.pizzamanagement.Dao
    
	3.1=>create a Interface PizzaDao
	      
		  Accsess pizza Data from Service pizza
		 =======================================
		*getPizzaByNo
		*addPizza
		 *updatePizaa
		 *deletePizza
		 
	 3.2=> create a class PizzaDaoImpl
	     
		   *provide implemntation of services added in PizzaDao Interface 
	                *create EntityManager "OBJECT" TO Accsess the data from database
					 * create a default serviceDao constructor 
					         initialize the entity object in above constructor	   
  	
4. create a package with com.pizzamanagement.Ui

     4.1=> create a Test class with main method 
      4.2==> create object of PizzaService 
      4.3==>Do all crud operations to call the services 

5. META-INF
      *Create a xml file name is persistence.xml 
           *add the database properties 
           *add the hibernate properties 		   

 
 
