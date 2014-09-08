CSCE_156_Projects
=================

import java.util.Scanner;

public class HalfLife {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		int atomicNumber;			//atomic number of the element
		int years = 0;					//the number of years elapsed
		String elementName;			//the name of the element
		String elementSymbol;		//the element symbol
		double initialMass = 10;	//initial mass of the element
		double finalMass = 0;
		double h;				//the calculated half-life of the element
		double r = 0;				//rate of decay 
		double c;					//part of the rate of decay equation
		double d = -0.693;
		int count = 0;
		
	
		
		Scanner scanner = new Scanner(System.in);
		
		System.out.print("Enter the atomic number of the element: ");
		atomicNumber = scanner.nextInt();
		
		System.out.print("Enter the element name: ");
		elementName = scanner.next();
		
		System.out.print("Enter element symbol: ");
		elementSymbol = scanner.next();
		
		System.out.print("Enter element half life: ");
		h = scanner.nextDouble();
		
		System.out.print("Enter the elements inital mass, in grams: ");
		initialMass = scanner.nextDouble();
		
		//below, the formula for C
		
		c = Math.pow(Math.E,d);
		
		r = initialMass * Math.pow(c,years);
		
		while (count < initialMass/2) {
			finalMass = initialMass - r;
			count ++;
		}
		System.out.print("The element " + elementName + "" + "(" + atomicNumber + "-" + elementSymbol + ")" + "will reach it's half-life in " + count + " years, with a mass of " + finalMass + "grams.");
	}
	
	
}
