  Ejemplo 1: Imprimir los números del 1 al 10 utilizando un bucle for en C        
                                                                                  
    #include <stdio.h>                                                            
                                                                                  
    int main() {                                                                  
        for (int i = 1; i <= 10; i++) {                                           
            printf("%d\n", i);                                                    
        }                                                                         
        return 0;                                                                 
    }                                                                             
                                                                                  
  Ejemplo 2: Imprimir los números pares del 1 al 20 utilizando un bucle for en C++
                                                                                  
    #include <iostream>                                                           
                                                                                  
    int main() {                                                                  
        for (int i = 2; i <= 20; i += 2) {                                        
            std::cout << i << std::endl;                                          
        }                                                                         
        return 0;                                                                 
    }                                                                             
                                                                                  
  Ejemplo 3: Leer los números del 1 al 5 y sumarlos utilizando un bucle for en C  
                                                                                  
    #include <stdio.h>                                                            
                                                                                  
    int main() {                                                                  
        int suma = 0;                                                             
        for (int i = 1; i <= 5; i++) {                                            
            int numero;                                                           
            printf("Ingrese el número %d: ", i);                                  
            scanf("%d", &numero);                                                 
            suma += numero;                                                       
        }                                                                         
        printf("La suma es: %d\n", suma);                                         
        return 0;                                                                 
    }                                                                             
                                                                                  
  Ejemplo 4: Imprimir la tabla de multiplicar del 2 utilizando un bucle while en  
  C++                                                                             
                                                                                  
    #include <iostream>                                                           
                                                                                  
    int main() {                                                                  
        int i = 1;                                                                
        while (i <= 10) {                                                         
            std::cout << "2 x " << i << " = " << 2 * i << std::endl;              
            i++;                                                                  
        }                                                                         
        return 0;                                                                 
    }                                                                             
                                                                                  
  Ejemplo 5: Leer un número y calcular su factorial utilizando un bucle for en C  
                                                                                  
    #include <stdio.h>                                                            
                                                                                  
    int main() {                                                                  
        int numero;                                                               
        printf("Ingrese un número: ");                                            
        scanf("%d", &numero);                                                     
        int factorial = 1;                                                        
        for (int i = 1; i <= numero; i++) {                                       
            factorial *= i;                                                       
        }                                                                         
        printf("El factorial de %d es: %d\n", numero, factorial);                 
        return 0;                                                                 
    }                                                                             
                                                                                  
  Ejemplo 6: Imprimir la serie de Fibonacci hasta el número 10 utilizando un bucle
  while en C++                                                                    
                                                                                  
    #include <iostream>                                                           
                                                                                  
    int main() {                                                                  
        int a = 0, b = 1, i = 1;                                                  
        while (i <= 10) {                                                         
            std::cout << a << std::endl;                                          
            int temp = a;                                                         
            a = b;                                                                
            b = temp + b;                                                         
            i++;                                                                  
        }                                                                         
        return 0;                                                                 
    }                                                                             
                                                                                  
  Ejemplo 7: Leer un número y calcular su potencia utilizando un bucle for en C   
                                                                                  
    #include <stdio.h>                                                            
                                                                                  
    int main() {                                                                  
        int base, exponente;                                                      
        printf("Ingrese la base: ");                                              
        scanf("%d", &base);                                                       
        printf("Ingrese el exponente: ");                                         
        scanf("%d", &exponente);                                                  
        int resultado = 1;                                                        
        for (int i = 1; i <= exponente; i++) {                                    
            resultado *= base;                                                    
        }                                                                         
        printf("%d elevado a %d es: %d\n", base, exponente, resultado);           
        return 0;                                                                 
    }                                                                             
                                                                                  
  Ejemplo 8: Imprimir los números del 10 al 1 utilizando un bucle while en C++    
                                                                                  
    #include <iostream>                                                           
                                                                                  
    int main() {                                                                  
        int i = 10;                                                               
        while (i >= 1) {                                                          
            std::cout << i << std::endl;                                          
            i--;                                                                  
        }                                                                         
        return 0;                                                                 
    }                                                                             
                                                                                  
  Ejemplo 9: Leer un número y calcular su raíz cuadrada utilizando un bucle for en
  C                                                                               
                                                                                  
    #include <stdio.h>                                                            
    #include <math.h>                                                             
                                                                                  
    int main() {                                                                  
        int numero;                                                               
        printf("Ingrese un número: ");                                            
        scanf("%d", &numero);                                                     
        double raiz = sqrt(numero);                                               
        printf("La raíz cuadrada de %d es: %.2f\n", numero, raiz);                
        return 0;                                                                 
    }                                                                             
                                                                                  
  Ejemplo 10: Imprimir la tabla de multiplicar del 1 al 10 utilizando un bucle for
  anidado en C++                                                                  
                                                                                  
    #include <iostream>                                                           
                                                                                  
    int main() {                                                                  
        for (int i = 1; i <= 10; i++) {                                           
            for (int j = 1; j <= 10; j++) {                                       
                std::cout << i << " x " << j << " = " << i * j << std::endl;      
            }                                                                     
            std::cout << std::endl;                                               
        }                                                                         
        return 0;                                                                 
    }                                                                             
                                                                                  
  Espero que estos ejemplos te ayuden a entender mejor cómo funcionan las         
  estructuras repetitivas en C y C++.                                             


