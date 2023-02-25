# House-Tester-method
This article will provide a java program I've created in the CS232 course, including the process to create the program, and how java Methods can improve the program.

*Problem Statement:
*Create a class named House that holds: a house number,
*number of bedrooms, number of baths, and price.
*Create a constructor that accepts values for each data field. 
*Also create a "et"method for each field. 
*Write an application that creates three House objects.
*Then display data for all the House objects. Save the files as House.java and TestHouses.java.
*/

I started my program by creating the package. The package in the java program is a group of related classes. Our classes in this project were (House) Class and (TestHouses) Class.
From the classes, we created two java files:House.java and TestHouse.java.I will start with the House Class processes: First, create a House class, then declare the variables using the private modifier-"The private access modifier is accessible only within the class"- and use int and double data type. (int-"stores whole numbers", a house number, number of bedrooms, number of baths).(Double 

I will start with House class/the file House.java.
        //House Class
        package Houses; 
        public class House {

        //Declare variables
        private int no_bedrooms;        
        private int housenum;
        private int no_bathroom;
        private double price;
    
        //Constructor
        public House(int no_bedrooms,int housenum,int no_bathroom,double price){
            this.no_bathroom=no_bathroom;
            this.no_bedrooms=no_bedrooms;
            this.housenum=housenum;
            this.price=price;
        }
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

    
        }
