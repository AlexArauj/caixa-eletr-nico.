# caixa-eletr-nico.
package CaixaEletronico;

import java.util.Scanner;

public class CaixaEletronico {

	public static void main(String[] args) {
		
		Scanner sc=new Scanner(System.in);
		
		System.out.println("Caixa Eletrônico");
	    System.out.println("");
	    System.out.println("");
	    System.out.println("1- Abastecimento");
	    System.out.println("");
	    System.out.println("2- Operações Financeiras");
	    System.out.println("");
	    System.out.println("Escolha a opção: ");
	    
	    
	    int opcao=sc.nextInt();
	    
	    switch(opcao) {// a principal função do switch e verifica igualdade
	    case 1:
	    	System.out.println("Você escolheu a opção Abastecimento");
	    	break;// esta função é usada para quebra um loop
	    case 2:
	    	System.out.println("Você escolheu a opção Operações Financeira");
	    	break;
	    default:
	    	System.out.println("A opção escolhida é inexistente. Selecione apenas 1 ou 2");
	        break;
	    	
	    }
	    sc.close();
	}

}
