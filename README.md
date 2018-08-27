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
////////////////////////////////////////////////////////////

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
		lado1=sc.nextFloat();
		System.out.print ("lado 2:");
		lado2=sc.nextFloat();
		
		System.out.println("area trapezio:" +areaTrapezio(bMaior,bMaior,altura));
		System.out.println("area trapezio:" +perimetroTrapezio(bMaior,bMenor,lado1,lado2));
		
	}
		public static float areaTrapezio(float baseMaior,float baseMenor,float altura){
		return ((baseMaior+baseMenor)*altura)/2;
		}
		
		public static float perimetroTrapezio(float baseMaior,float baseMenor,float lado1,float lado2){
			return (baseMaior+baseMenor+lado1+lado2);
		}
			
        
        
	}
