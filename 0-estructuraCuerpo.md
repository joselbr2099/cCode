  Estructura básica de un programa en C                                           
                                                                                  
    #include <stdio.h>  // Inclusión de bibliotecas estándar                      
                                                                                  
    // Declaración de variables globales                                          
    int variableGlobal = 10;                                                      
                                                                                  
    // Prototipo de funciones                                                     
    void miFuncion(void);                                                         
                                                                                  
    int main(void) {                                                              
      // Declaración de variables locales                                         
      int variableLocal = 20;                                                     
                                                                                  
      // Instrucciones del programa principal                                     
      printf("Hola, mundo!\n");                                                   
      miFuncion();                                                                
                                                                                  
      return 0;                                                                   
    }                                                                             
                                                                                  
    // Definición de la función miFuncion                                         
    void miFuncion(void) {                                                        
      printf("Estoy dentro de miFuncion\n");                                      
    }                                                                             
                                                                                  
  Estructura básica de un programa en C++                                         
                                                                                  
    #include <iostream>  // Inclusión de bibliotecas estándar                     
                                                                                  
    // Declaración de variables globales                                          
    int variableGlobal = 10;                                                      
                                                                                  
    // Prototipo de funciones                                                     
    void miFuncion(void);                                                         
                                                                                  
    int main() {                                                                  
      // Declaración de variables locales                                         
      int variableLocal = 20;                                                     
                                                                                  
      // Instrucciones del programa principal                                     
      std::cout << "Hola, mundo!" << std::endl;                                   
      miFuncion();                                                                
                                                                                  
      return 0;                                                                   
    }                                                                             
                                                                                  
    // Definición de la función miFuncion                                         
    void miFuncion() {                                                            
      std::cout << "Estoy dentro de miFuncion" << std::endl;                      
    }                                                                             
                                                                                  
  Estructura común a C y C++                                                      
                                                                                  
  • La primera línea incluye una biblioteca estándar que proporciona funciones    
  para realizar operaciones comunes como la entrada y salida de datos.            
  • La siguiente línea declara una variable global que está disponible en todo el 
  programa.                                                                       
  • Luego, se declara un prototipo de función que indica la existencia de una     
  función llamada miFuncion que se definirá más adelante.                         
  • La función main es la función principal del programa y es donde se inicia la  
  ejecución del programa. Dentro de main, se declaran variables locales y se      
  escriben las instrucciones del programa principal.                              
  • Finalmente, se define la función miFuncion que se llamó desde main. Esta      
  función realiza alguna acción y luego regresa a main.                           
                                                                                  
  Diferencias entre C y C++                                                       
                                                                                  
  • La inclusión de bibliotecas: En C, se incluye <stdio.h>, mientras que en C++, 
  se incluye <iostream>.                                                          
  • La salida de datos: En C, se utiliza printf, mientras que en C++, se utiliza  
  std::cout.                                                                      
  • La sintaxis de la función main: En C, se declara con int main(void), mientras 
  que en C++, se declara con int main().                                          
  • La sintaxis de las funciones: En C++, se utiliza std:: para acceder a las     
  funciones y objetos de la biblioteca estándar.                                  


