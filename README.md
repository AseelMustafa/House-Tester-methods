# House-Tester-method

        <introduction>
        
This article will provide a java program I've created in  CS232 course.It includes: processes of how we created the program,and how we used the java variables,functions and objects.Also,it will include how i can improve the program by using Java methods. ***we will go through the varibleds and create the get methods and another methods
        
        
        /*Problem Statement:
         *Create a class named House that holds: a house number,
         *number of bedrooms, number of baths, and price.
         *Create a constructor that accepts values for each data field. 
         *Also create a "et"method for each field. 
         *Write an application that creates three House objects.
         *Then display data for all the House objects. Save the files as House.java and TestHouses.java.
         */

    
I started the program by creating java package.The package in java program is used to group related classes. Our classes in this project were (House) Class and (TestHouses) Class.   

        //House Class
        package Houses; 
        public class House {

 #Creating House Class       
From the classes, we created two java files:House.java and TestHouse.java.I will start with the House Class processes: First, create a House class, then declare the variables using the private modifier-"The private access modifier is accessible only within the class"- and use int and double data type. (int-"stores whole numbers", a house number, number of bedrooms, number of baths).(Double-"Stores fractional numbers. Sufficient for storing 15 decimal digits",the price of the house).

        //Declare variables
        private int no_bedrooms;
        private int housenum;
        private int no_bathroom;
        private double price;


The next step is the Constructor-"A constructor in Java is a special method that is used to initialize objects."-I called the consurctour method when I created an object of a class.

        //Constructor
        public House(int no_bedrooms,int housenum,int no_bathroom,double price){
            this.no_bathroom=no_bathroom;
            this.no_bedrooms=no_bedrooms;
            this.housenum=housenum;
            this.price=price;
        }

In the problem statment they asked to create "get method",and we used the get method to returns the variable value.
        here is how we can call a method in java program
![methods get-in-java2](https://user-images.githubusercontent.com/126033476/221368432-5d0dfcda-788a-405d-b1a3-3e0850dbf41e.png)

<Here is what I did>
To create the method I started with get ,followed with the variable name,and the first letter in upper case:

         //public int getBedroom(){
The get method(getBedroom()) will return the value of the variable,which is the number of the bedroom(no_bedroom).
Then I did the same thing for the the House number ,the number of bathroom ,and the price of the house.    
        
        
        //Getters methods
        public int getBedroom(){
            return this.no_bedrooms;
        }
        public int getHousenum(){
            return this.housenum;
        }
        public int getBathroom(){
            return this.no_bathroom;
        }
        public double getPrice(){
            return this.price;
        }
        }


Here is the code of House class/file: House.java.

![Screenshot (136)](https://user-images.githubusercontent.com/126033476/221367055-7b9f2dbb-c545-4d45-96c0-1e1f3cbd47bb.png)

![Screenshot (137)](https://user-images.githubusercontent.com/126033476/221367063-9babf361-70fc-4d44-9fe3-c7616aac7dc4.png)
       
       
#Creating the TestHouse Class        
        
        
        


    


    
        }
