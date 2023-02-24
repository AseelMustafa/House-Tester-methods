# House-Tester-methods.

*Problem Statement:
*Create a class named House that holds: a house number,
*number of bedrooms, number of baths, and price.
*Create a constructor that accepts values for each data field. 
*Also create a get method for each field. 
*Write an application that creates three House objects.
*Then display data for all the House objects. Save the files as House.java and TestHouses.java.
*/

I will start with House class ,the file House.java
here is my codes


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
