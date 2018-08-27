package aula20;

import java.util.Scanner;

public class exercicio2 {

	public static void main(String[] args) {
		
		float bMaior,bMenor,altura,area,perimetro,lado1,lado2;
		Scanner sc = new Scanner(System.in);
		System.out.print ("base maior:");
		bMaior=sc.nextFloat();
		System.out.print ("base menor:");
		bMenor=sc.nextFloat();
		System.out.print ("altura:");
		altura=sc.nextFloat();
		System.out.print ("lado 1:");
		lado2=sc.nextFloat();
		System.out.print ("lado 2:");
		lado1=sc.nextFloat();
		area=((bMaior+bMenor)*altura)/2;
		perimetro=bMaior+bMenor+lado1+lado2;
		System.out.println("area trapezio:" +area);
		System.out.println("area trapezio:" +perimetro);
		sc.close();		
        System.exit(0);
        
	}

}
