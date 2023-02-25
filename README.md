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
        
       

        ## Also,in the problem statments: < Write an application that creates three House objects.>
        
#Creating the TestHouse Class      
I started with the package ,created the class(TestHouses),and then used the main method.The main method needs a <public> modifier,and we still dont have any objects created in the class  we used <static>.<void> is the return type.
        
        package Houses;
        public class TestHouses {
        //The main method in java: 
        public static void main(String[]args){
        }
        
![main](https://user-images.githubusercontent.com/126033476/221374513-f59faf59-f0d4-4ec6-85f7-2d6dfcb6a52d.jpg)

Created three house objects:house1,house2,house3,and I passed the inforamtion.

        Everything in Java is associated with classes and objects, along with its attributes and methods. 
        A Class is like an object constructor, or a "blueprint" for creating objects.

        //Create three houses objects
        House house1=new House(2, 150, 2, 190000);
        House house2=new House(4, 302, 3, 3660000);
        House house3=new House(3, 783, 2, 200000);

The the last thing is displaying the data :
I used System.out.println() to print the data.

![system](https://user-images.githubusercontent.com/126033476/221377249-5ad890d2-d0ed-408b-8c95-87821bb6530c.png)


        
    System.out.println("Bedrooms:"+ house1.getBedroom());
    System.out.println("House Number:"+house1.getHousenum());
    System.out.println("Bathroom:"+house1.getBathroom());
    System.out.println("Price"+house1.getPrice());
    System.out.println("Bedrooms:"+house2.getBedroom());
    System.out.println("House Number:"+house2.getHousenum());
    System.out.println("Bathroom:"+house2.getBathroom());
    System.out.println("Price"+house2.getPrice());
    System.out.println("Bedrooms:"+house3.getBedroom());
    System.out.println("House Number:"+house3.getHousenum());
    System.out.println("Bathroom:"+house3.getBathroom());
    System.out.println("Price"+house3.getPrice());
    
        }
        }
        
        
Here is the code of TestHouses class/file: TestHouse.java.

![Screenshot (138)](https://user-images.githubusercontent.com/126033476/221377035-3f7b8f4d-c37e-4d2e-8e30-389d85a25ea4.png)

        #Output:
![Screenshot (139)](https://user-images.githubusercontent.com/126033476/221377425-38f01308-1520-4c2a-b1dd-aa386e0bfa9b.=


But i figured an easier way to display the data by using a display method






