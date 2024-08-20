# atv2 sanna

QUESTÃO 01:
#include <iostream>  // Biblioteca para entrada e saída

int main() {
    std::cout << "Hello, World!" << std::endl;  // Exibe a mensagem
    return 0;  // Finaliza o programa
}


QUESTÃO 02:
#include <iostream>  // Biblioteca para entrada e saída

int main() {
    // Declaração de variáveis
    double num1, num2, soma;
    
    // Solicita ao usuário para inserir dois números
    std::cout << "Digite o primeiro número: ";
    std::cin >> num1;
    
    std::cout << "Digite o segundo número: ";
    std::cin >> num2;
    
    // Calcula a soma
    soma = num1 + num2;
    
    // Exibe a soma
    std::cout << "A soma de " << num1 << " e " << num2 << " é " << soma << "." << std::endl;
    
    return 0;  // Finaliza o programa
}


QUESTÃO 03:
#include <iostream>  // Biblioteca para entrada e saída

int main() {
    // Declaração da variável
    int numero;
    
    // Solicita ao usuário para inserir um número
    std::cout << "Digite um número: ";
    std::cin >> numero;
    
    // Verifica se o número é par ou ímpar
    if (numero % 2 == 0) {
        std::cout << "O número " << numero << " é par." << std::endl;
    } else {
        std::cout << "O número " << numero << " é ímpar." << std::endl;
    }
    
    return 0;  // Finaliza o programa
}


QUESTÃO 04:
#include <iostream>  // Biblioteca para entrada e saída

int main() {
    // Declaração das variáveis
    double num1, num2;
    
    // Solicita ao usuário para inserir dois números
    std::cout << "Digite o primeiro número: ";
    std::cin >> num1;
    
    std::cout << "Digite o segundo número: ";
    std::cin >> num2;
    
    // Verifica e exibe o maior dos dois números
    if (num1 > num2) {
        std::cout << "O maior número é " << num1 << "." << std::endl;
    } else if (num2 > num1) {
        std::cout << "O maior número é " << num2 << "." << std::endl;
    } else {
        std::cout << "Os dois números são iguais." << std::endl;
    }
    
    return 0;  // Finaliza o programa
}


QUESTÃO 05:
#include <iostream>  // Biblioteca para entrada e saída

int main() {
    // Declaração das variáveis
    double num1, num2, num3, media;
    
    // Solicita ao usuário para inserir três números
    std::cout << "Digite o primeiro número: ";
    std::cin >> num1;
    
    std::cout << "Digite o segundo número: ";
    std::cin >> num2;
    
    std::cout << "Digite o terceiro número: ";
    std::cin >> num3;
    
    // Calcula a média aritmética
    media = (num1 + num2 + num3) / 3;
    
    // Exibe a média
    std::cout << "A média aritmética dos números é " << media << "." << std::endl;
    
    return 0;  // Finaliza o programa
}


QUESTÃO 06:
#include <iostream>  // Biblioteca para entrada e saída
#include <cmath>     // Biblioteca para funções matemáticas

int main() {
    // Declaração da variável
    double raio, area;
    
    // Solicita ao usuário para inserir o raio do círculo
    std::cout << "Digite o raio do círculo: ";
    std::cin >> raio;
    
    // Calcula a área do círculo
    area = M_PI * raio * raio;
    
    // Exibe a área
    std::cout << "A área do círculo com raio " << raio << " é " << area << "." << std::endl;
    
    return 0;  // Finaliza o programa
}


QUESTÃO 07:
#include <iostream>  // Biblioteca para entrada e saída

int main() {
    // Declaração das variáveis
    double celsius, fahrenheit;
    
    // Solicita ao usuário para inserir a temperatura em Celsius
    std::cout << "Digite a temperatura em Celsius: ";
    std::cin >> celsius;
    
    // Converte a temperatura de Celsius para Fahrenheit
    fahrenheit = (celsius * 9.0 / 5.0) + 32;
    
    // Exibe a temperatura em Fahrenheit
    std::cout << "A temperatura em Fahrenheit é " << fahrenheit << "." << std::endl;
    
    return 0;  // Finaliza o programa
}


QUESTÃO 08:
#include <iostream>  // Biblioteca para entrada e saída

int main() {
    // Declaração da variável
    int numero;
    
    // Solicita ao usuário para inserir um número
    std::cout << "Digite um número para exibir a tabuada: ";
    std::cin >> numero;
    
    // Exibe a tabuada do número fornecido
    std::cout << "Tabuada do " << numero << ":" << std::endl;
    for (int i = 1; i <= 10; ++i) {
        std::cout << numero << " x " << i << " = " << (numero * i) << std::endl;
    }
    
    return 0;  // Finaliza o programa
}


QUESTÃO 09:
#include <iostream>  // Biblioteca para entrada e saída

int main() {
    // Declaração da variável
    int numero;
    unsigned long long fatorial = 1;  // Usa unsigned long long para suportar números grandes
    
    // Solicita ao usuário para inserir um número inteiro positivo
    std::cout << "Digite um número inteiro positivo: ";
    std::cin >> numero;
    
    // Verifica se o número é negativo
    if (numero < 0) {
        std::cout << "Número inválido. O número deve ser inteiro e positivo." << std::endl;
    } else {
        // Calcula o fatorial
        for (int i = 1; i <= numero; ++i) {
            fatorial *= i;
        }
        
        // Exibe o fatorial
        std::cout << "O fatorial de " << numero << " é " << fatorial << "." << std::endl;
    }
    
    return 0;  // Finaliza o programa
}


QUESTÃO 10:
#include <iostream>  // Biblioteca para entrada e saída

int main() {
    // Exibe a contagem regressiva de 10 a 1
    for (int i = 10; i >= 1; --i) {
        std::cout << i << std::endl;
    }
    
    std::cout << "Contagem regressiva completa!" << std::endl;
    
    return 0;  // Finaliza o programa
}
