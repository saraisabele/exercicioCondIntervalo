# exercicioCondIntervalo
# Resolvendo exercício condicional (if-else) sobre intervalos numericos
# Dessa vez montei o código fonte no editor de código Online GDB por ser mais rápido 
#  resolução do exercício 06 do curso Java Completo com Nelio alves: 
#     Você deve fazer um programa que leia um valor qualquer e apresente uma mensagem dizendo em qual dos
#     seguintes intervalos ([0,25], (25,50], (50,75], (75,100]) este valor se encontra. Obviamente se o valor não estiver em
#     nenhum destes intervalos, deverá ser impressa a mensagem “Fora de intervalo”.


      import java.util.Scanner;
      public class Main
      {
      	public static void main(String[] args) {
      	    Scanner sc = new Scanner(System.in);
      	    float qualquerValor;
        		System.out.printf("Digite qualquer valor de 0 a 100: ");
        		qualquerValor = sc.nextFloat();
        		
        		if(qualquerValor >= 0 && qualquerValor <= 25){
        		    System.out.printf("Intervalo (0, 25] ");
        		}else if(qualquerValor > 25 && qualquerValor <= 50){
        		    System.out.printf("Intervalo (25, 50]");
        		}else if(qualquerValor > 50 && qualquerValor <= 75){
        		    System.out.printf("Intervalo (50, 75]");
        		}else if(qualquerValor > 75 && qualquerValor <= 100){
        		    System.out.printf("Intervalo (75, 100]");
        		}else{
        		    System.out.printf("Fora de intervalo");
        		}
        	}
  }
