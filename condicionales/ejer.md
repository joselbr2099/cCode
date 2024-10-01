  Ejemplo 1: Verificar si un número es mayor que 10 en C                          
                                                                                  
    #include <stdio.h>                                                            
                                                                                  
    int main() {                                                                  
        int numero;                                                               
        printf("Ingrese un número: ");                                            
        scanf("%d", &numero);                                                     
        if (numero > 10) {                                                        
            printf("El número es mayor que 10\n");                                
        } else {                                                                  
            printf("El número es menor o igual que 10\n");                        
        }                                                                         
        return 0;                                                                 
    }                                                                             
                                                                                  
  Ejemplo 2: Verificar si un número es par o impar en C++                         
                                                                                  
    #include <iostream>                                                           
                                                                                  
    int main() {                                                                  
        int numero;                                                               
        std::cout << "Ingrese un número: ";                                       
        std::cin >> numero;                                                       
        if (numero % 2 == 0) {                                                    
            std::cout << "El número es par\n";                                    
        } else {                                                                  
            std::cout << "El número es impar\n";                                  
        }                                                                         
        return 0;                                                                 
    }                                                                             
                                                                                  
  Ejemplo 3: Verificar si un número es positivo, negativo o cero en C             
                                                                                  
    #include <stdio.h>                                                            
                                                                                  
    int main() {                                                                  
        int numero;                                                               
        printf("Ingrese un número: ");                                            
        scanf("%d", &numero);                                                     
        if (numero > 0) {                                                         
            printf("El número es positivo\n");                                    
        } else if (numero < 0) {                                                  
            printf("El número es negativo\n");                                    
        } else {                                                                  
            printf("El número es cero\n");                                        
        }                                                                         
        return 0;                                                                 
    }                                                                             
                                                                                  
  Ejemplo 4: Verificar si un número es múltiplo de 3 o 5 en C++                   
                                                                                  
    #include <iostream>                                                           
                                                                                  
    int main() {                                                                  
        int numero;                                                               
        std::cout << "Ingrese un número: ";                                       
        std::cin >> numero;                                                       
        if (numero % 3 == 0 && numero % 5 == 0) {                                 
            std::cout << "El número es múltiplo de 3 y 5\n";                      
        } else if (numero % 3 == 0) {                                             
            std::cout << "El número es múltiplo de 3\n";                          
        } else if (numero % 5 == 0) {                                             
            std::cout << "El número es múltiplo de 5\n";                          
        } else {                                                                  
            std::cout << "El número no es múltiplo de 3 ni 5\n";                  
        }                                                                         
        return 0;                                                                 
    }                                                                             
                                                                                  
  Ejemplo 5: Verificar si un número es primo en C                                 
                                                                                  
    #include <stdio.h>                                                            
                                                                                  
    int main() {                                                                  
        int numero;                                                               
        printf("Ingrese un número: ");                                            
        scanf("%d", &numero);                                                     
        int es_primo = 1;                                                         
        for (int i = 2; i <= numero / 2; i++) {                                   
            if (numero % i == 0) {                                                
                es_primo = 0;                                                     
                break;                                                            
            }                                                                     
        }                                                                         
        if (es_primo) {                                                           
            printf("El número es primo\n");                                       
        } else {                                                                  
            printf("El número no es primo\n");                                    
        }                                                                         
        return 0;                                                                 
    }                                                                             
                                                                                  
  Ejemplo 6: Verificar si un número es mayor que la suma de dos números en C++    
                                                                                  
    #include <iostream>                                                           
                                                                                  
    int main() {                                                                  
        int numero1, numero2, numero3;                                            
        std::cout << "Ingrese tres números: ";                                    
        std::cin >> numero1 >> numero2 >> numero3;                                
        if (numero1 > (numero2 + numero3)) {                                      
            std::cout << "El primer número es mayor que la suma de los otros      
  dos\n";                                                                         
        } else {                                                                  
            std::cout << "El primer número no es mayor que la suma de los otros   
  dos\n";                                                                         
        }                                                                         
        return 0;                                                                 
    }                                                                             
                                                                                  
  Ejemplo 7: Verificar si un número es palindrómico en C                          
                                                                                  
    #include <stdio.h>                                                            
                                                                                  
    int main() {                                                                  
        int numero;                                                               
        printf("Ingrese un número: ");                                            
        scanf("%d", &numero);                                                     
        int invertido = 0;                                                        
        int original = numero;                                                    
        while (numero != 0) {                                                     
            invertido = invertido * 10 + numero % 10;                             
            numero /= 10;                                                         
        }                                                                         
        if (invertido == original) {                                              
            printf("El número es palindrómico\n");                                
        } else {                                                                  
            printf("El número no es palindrómico\n");                             
        }                                                                         
        return 0;                                                                 
    }                                                                             
                                                                                  
  Ejemplo 8: Verificar si un número es primo y mayor que 100 en C++               
                                                                                  
    #include <iostream>                                                           
                                                                                  
    int main() {                                                                  
        int numero;                                                               
        std::cout << "Ingrese un número: ";                                       
        std::cin >> numero;                                                       
        int es_primo = 1;                                                         
        for (int i = 2; i <= numero / 2; i++) {                                   
            if (numero % i == 0) {                                                
                es_primo = 0;                                                     
                break;                                                            
            }                                                                     
        }                                                                         
        if (es_primo && numero > 100) {                                           
            std::cout << "El número es primo y mayor que 100\n";                  
        } else {                                                                  
            std::cout << "El número no es primo o no es mayor que 100\n";         
        }                                                                         
        return 0;                                                                 
    }                                                                             
                                                                                  
  Ejemplo 9: Verificar si un número es múltiplo de 4 o 9 en C                     
                                                                                  
    #include <stdio.h>                                                            
                                                                                  
    int main() {                                                                  
        int numero;                                                               
        printf("Ingrese un número: ");                                            
        scanf("%d", &numero);                                                     
        if (numero % 4 == 0 || numero % 9 == 0) {                                 
            printf("El número es múltiplo de 4 o 9\n");                           
        } else {                                                                  
            printf("El número no es múltiplo de 4 ni 9\n");                       
        }                                                                         
        return 0;                                                                 
    }                                                                             
                                                                                  
  Ejemplo 10: Verificar si un número es positivo y mayor que 10 en C++            
                                                                                  
    #include <iostream>                                                           
                                                                                  
    int main() {                                                                  
        int numero;                                                               
        std::cout << "Ingrese un número: ";                                       
        std::cin >> numero;                                                       
        if (numero > 0 && numero > 10) {                                          
            std::cout << "El número es positivo y mayor que 10\n";                
        } else {                                                                  
            std::cout << "El número no es positivo o no es mayor que 10\n";       
        }                                                                         
        return 0;                                                                 
    }                                                                             
                                                                                  
  Espero que estos ejemplos te ayuden a entender mejor cómo funcionan las         
  estructuras condicionales en C y C++.                           
