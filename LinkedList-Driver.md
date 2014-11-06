CSCE_156_Projects
=================

Projects for CSCE 156


package unl.cse.trucks;

import unl.cse.utils.RandomStringUtils;

public class Driver {

	
    public static void main (String[] args){

    	//TODO: Test cases should be made here
    
    	
    	
    	
    	TruckList tl = new TruckList();
    	//Truck t = new Truck.Builder().licensePlate("ABC 123").build();
    	Truck truck1 = new Truck.Builder().licensePlate(RandomStringUtils.randomAlphabetic(3) + " " + RandomStringUtils.randomNumeric(3)).build();
    	Truck truck2 = new Truck.Builder().licensePlate(RandomStringUtils.randomAlphabetic(3) + " " + RandomStringUtils.randomNumeric(3)).build();
    	Truck truck3 = new Truck.Builder().licensePlate(RandomStringUtils.randomAlphabetic(3) + " " + RandomStringUtils.randomNumeric(3)).build();
    	Truck truck4 = new Truck.Builder().licensePlate(RandomStringUtils.randomAlphabetic(3) + " " + RandomStringUtils.randomNumeric(3)).build();
    	Truck truck5 = new Truck.Builder().licensePlate(RandomStringUtils.randomAlphabetic(3) + " " + RandomStringUtils.randomNumeric(3)).build();
    	Truck truck6 = new Truck.Builder().licensePlate(RandomStringUtils.randomAlphabetic(3) + " " + RandomStringUtils.randomNumeric(3)).build();
    	Truck truck7 = new Truck.Builder().licensePlate(RandomStringUtils.randomAlphabetic(3) + " " + RandomStringUtils.randomNumeric(3)).build();
    	Truck truck8 = new Truck.Builder().licensePlate(RandomStringUtils.randomAlphabetic(3) + " " + RandomStringUtils.randomNumeric(3)).build();
    	Truck truck9 = new Truck.Builder().licensePlate(RandomStringUtils.randomAlphabetic(3) + " " + RandomStringUtils.randomNumeric(3)).build();
    	Truck truck10 = new Truck.Builder().licensePlate(RandomStringUtils.randomAlphabetic(3) + " " + RandomStringUtils.randomNumeric(3)).build();
    	
    	
    	tl.addToEnd(truck1);
    	tl.addToEnd(truck2);
    	tl.addToEnd(truck3);
    	tl.addToEnd(truck4);
    	tl.addToEnd(truck5);
    	tl.addToEnd(truck6);
    	tl.addToEnd(truck7);
    	tl.addToEnd(truck8);
    	tl.addToEnd(truck9);
    	tl.addToEnd(truck10);    	
    	tl.print();
    	
    	
    	
	
	}
}
