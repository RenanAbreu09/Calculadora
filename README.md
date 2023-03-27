#include <stdio.h>

int main(void)
{
	char escolha;	
	float a, b, c, d;
	
	printf("Voce quer somar(+), diminuir(-), multiplicar(*) ou dividir(/)?\n\n");
	scanf("%c", &escolha);
	
	
	if(escolha == '+'){
		printf("Coloque o primeiro numero que voce queira somar\n\n");
		scanf("%f", &a);
		printf("Coloque o segundo numero que voce queira somar\n\n");
		scanf("%f", &b);
		
		c=a+b;
		printf("A soma de %.1f + %.1f eh %.1f\n\n",a , b, c);
	
	}else if(escolha == '-'){
		printf("Coloque o primeiro numero que voce queira diminuir\n\n");
		scanf("%f", &a);
		printf("Coloque o segundo numero que voce queira diminuir\n\n");
		scanf("%f", &b);
		
		c=a-b;
		printf("A subitracao de %.1f - %.1f eh %.1f\n\n",a ,b ,c);		
		
	}else if(escolha == '*'){	
		printf("Coloque o primeiro numero que voce queira multiplicar\n\n");
		scanf("%f", &a);
		printf("Coloque o segundo numero que voce queira multiplicar\n\n");
		scanf("%f", &b);
		
		c=a*b;
		printf("A multiplicacao de %.1f * %.1f eh %.1f\n\n",a ,b ,c);	
	
	}else if(escolha == '/'){	
		printf("Coloque o primeiro numero que voce queira dividir\n\n");
		scanf("%f", &a);
		printf("Coloque o segundo numero que voce queira dividir\n\n");
		scanf("%f", &b);
		
		c=a/b;
		printf("A divisao de %.1f / %.1f eh %.1f\n\n",a ,b ,c ,d);	
	

	}
	}	

