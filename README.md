	    //variaveis
	    double nota1, nota2, media = 0.0;
	    Scanner tec = new Scanner(System.in);
	    
	    //entradas
	    System.out.println(" :: CALCULADORA DE MÉDIA ESCOLAR ::..");
	    System.out.print("Digite a nota1: ");
	    nota1 = tec.nextDouble();
	    System.out.print("Digite a nota2: ");
	    nota2 = tec.nextDouble();
	    
	    
	    //processamento
	    media = (nota1 + nota2) / 2;
	    
	    //saidas
	    if (media >= 6.0) {
	        System.out.println("Média " +  media + " - APROVADO!!");
	} else {
	        System.out.println("Média " + media + "- REPROVADO. ");
	   } 
	    
	}

    
}
    public class Main
    {
	public static void main(String[] args) {
	    //variaveis   
	    double peso = 0.00;
	    
	    //entradas
	    peso = 450.00;
	    
	    //processamento
	    if (peso > 500.00) {
	    
	    //saída
	    System.out.println("ALERTA :: PESO MAXIMO ATINGIDO!! ::");
	    } 
	}           
}
public class Main
{
	public static void main(String[] args) {
	   double nota1, nota2, media = 0.00;
	    
	    //variaveis   
        nota1 = 8.00;
        nota2 = 7.00;
	    
	    media = (nota1 + nota2) / 2;
	    
	   if (media <= 4.99) {
	       System.out.println("Media - " + media + " - REPROVADO!!");
	    }
	    else    
	    {
	        if (media >= 6.01) {
	            System.out.println("Média - " + media + " - APROVADO!!");
	           
	        }
	        else {
	            System.out.println("Média - " + media + " - RECURPERAÇÃO!!");
	        }    
	    }
	}
}
