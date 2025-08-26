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
import java.util.Scanner;

public class MediaAluno {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        
        System.out.print("Digite a primeira nota: ");
        double nota1 = scanner.nextDouble();

        System.out.print("Digite a segunda nota: ");
        double nota2 = scanner.nextDouble();

        System.out.print("Digite a terceira nota: ");
        double nota3 = scanner.nextDouble();

        System.out.print("Digite a quarta nota: ");
        double nota4 = scanner.nextDouble();

       
        double media = (nota1 + nota2 + nota3 + nota4) / 4;

        
        if (media >= 5) {
            System.out.println("Aprovado");
        } else {
            System.out.println("Reprovado");
        }

        
        System.out.print("Digite o custo mensal de material escolar (em R$): ");
        double custoMaterial = scanner.nextDouble();

        System.out.printf("Custo mensal de material: R$ %.2f\n", custoMaterial);

        scanner.close();
		public class Main
{
	public static void main(String[] args) {
        import java.util.Scanner;

    public class EquacaoSegundoGrau {
        Scanner scanner = new Scanner(System.in);

        
        System.out.print("Digite o valor de a: ");
        double a = scanner.nextDouble();

        System.out.print("Digite o valor de b: ");
        double b = scanner.nextDouble();

        System.out.print("Digite o valor de c: ");
        double c = scanner.nextDouble();

        
        if (a != 0 && b != 0 && c != 0) {
            
            double delta = (b * b) - (4 * a * c);
            System.out.println("Delta = " + delta);

            if (delta < 0) {
                System.out.println("Sem raízes reais.");
            } else if (delta == 0) {
                double x = -b / (2 * a);
                System.out.println("Existe uma raiz real : x = " + x);
            } else {
                double raizDelta = Math.sqrt(delta); 
                double x1 = (-b + raizDelta) / (2 * a);
                double x2 = (-b - raizDelta) / (2 * a);
                System.out.println("Existem duas raízes reais:");
                System.out.println("x1 = " + x1);
                System.out.println("x2 = " + x2);
            }

            
            System.out.print("Digite o valor base para cálculo dos descontos (R$): ");
            double valorBase = scanner.nextDouble();

            double ip = valorBase * 0.11;       
            double inss = valorBase * 0.09;     
            double planoSaude = valorBase * 0.08; 

            double totalDescontos = ip + inss + planoSaude;
            double valorLiquido = valorBase - totalDescontos;

            System.out.printf("Desconto IP: R$ %.2f\n", ip);
            System.out.printf("Desconto INSS: R$ %.2f\n", inss);
            System.out.printf("Desconto Plano de Saúde (8%%): R$ %.2f\n", planoSaude);
            System.out.printf("Valor líquido após descontos: R$ %.2f\n", valorLiquido);

        } else {
            System.out.println("Equação incompleta: os coeficientes a, b e c devem ser diferentes de zero.");
        }

        scanner.close();
    }
}

	}
import java.util.Scanner;

public class Main
{
    public static void main(String[] args) {
       
        //variaveis
        int ra;
        String nome, email, telefone;
        double cpf, peso, altura, mensalidade;
        byte idade, numirmaos;
        char sexo;
        Scanner leitura = new Scanner(System.in);   
       
        //entradas
        ra = leitura.nextInt();
        nome = leitura.next();
        cpf = leitura.nextDouble();
        idade = leitura.nextByte();
        sexo = leitura.next().charAt(0);
        peso = leitura.nextDouble();
        altura = leitura.nextDouble();
        mensalidade = leitura.nextDouble();
        //numirmaos = leitura.nextByte();
        //email = leitura.nextLine();
        //telefone = leitura.nextLine();
       
       
       //processamentos

       //saídas 
       System.out.println("Ra:" + ra);
        System.out.println("Nome: " + nome);
        System.out.println("Cpf: " + cpf);
        System.out.println("Idade:" + idade);
        System.out.println("Sexo:" + sexo);
        System.out.println("Peso:" + peso);
        System.out.println("Altura:" + altura);
        System.out.println("Mensalidade:" + mensalidade);

    }
}	 
	
	
