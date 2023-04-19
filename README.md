/** 1. Criar um programa que leia a temperatura em Celsius e converta para Fahrenheit.*/

fundamentos do pacote;
java de importação. util. Scanner;

Exercicio de classe pública1 {
	
	public static void main(String[] args) {
		
		Scanner scanner = novo Scanner(Sistema. em);
		
		Sistema. fora. println("Digite a temperatura em Celsius: ");
		duplo celsius = scanner. próximoDuplo();
		
		conversão duplo  = celsius * 1,8 + 32;
		
		Sistema. fora. print("Valor em Farenheit: " + conversao);
		
		scanner. fechar();
	}

}
