  Estructuras básicas de C                                                        
                                                                                  
  1. Variables:                                                                   
                                                                                  
  • Declaración: tipo variable;                                                   
  • Ejemplo: int x;                                                               
  • Tipos: int, char, float, double, etc.                                         
                                                                                  
  2. Constantes:                                                                  
                                                                                  
  • Declaración: const tipo variable = valor;                                     
  • Ejemplo: const int PI = 3.14;                                                 
  • Tipos: int, char, float, double, etc.                                         
                                                                                  
  3. Arreglos:                                                                    
                                                                                  
  • Declaración: tipo arreglo[tamaño];                                            
  • Ejemplo: int x[5];                                                            
  • Acceso: arreglo[indice]                                                       
                                                                                  
  4. Estructuras:                                                                 
                                                                                  
  • Declaración: struct nombre { tipo variable; };                                
  • Ejemplo: struct persona { int edad; char nombre[20]; };                       
  • Acceso: estructura.variable                                                   
                                                                                  
  5. Funciones:                                                                   
                                                                                  
  • Declaración: tipo función (parámetros) { cuerpo };                            
  • Ejemplo: int suma (int x, int y) { return x + y; }                            
  • Llamada: función(parámetros);                                                 
                                                                                  
  Estructuras básicas de C++                                                      
                                                                                  
  1. Variables:                                                                   
                                                                                  
  • Declaración: tipo variable;                                                   
  • Ejemplo: int x;                                                               
  • Tipos: int, char, float, double, etc.                                         
  • Adicionalmente, se puede utilizar auto para inferir el tipo.                  
                                                                                  
  2. Constantes:                                                                  
                                                                                  
  • Declaración: const tipo variable = valor;                                     
  • Ejemplo: const int PI = 3.14;                                                 
  • Tipos: int, char, float, double, etc.                                         
  • Adicionalmente, se puede utilizar constexpr para constantes evaluadas en      
  tiempo de compilación.                                                          
                                                                                  
  3. Arreglos:                                                                    
                                                                                  
  • Declaración: tipo arreglo[tamaño];                                            
  • Ejemplo: int x[5];                                                            
  • Acceso: arreglo[indice]                                                       
  • Adicionalmente, se puede utilizar std::array para arreglos de tamaño fijo.    
                                                                                  
  4. Estructuras:                                                                 
                                                                                  
  • Declaración: struct nombre { tipo variable; };                                
  • Ejemplo: struct persona { int edad; char nombre[20]; };                       
  • Acceso: estructura.variable                                                   
  • Adicionalmente, se puede utilizar class para definir clases.                  
                                                                                  
  5. Funciones:                                                                   
                                                                                  
  • Declaración: tipo función (parámetros) { cuerpo };                            
  • Ejemplo: int suma (int x, int y) { return x + y; }                            
  • Llamada: función(parámetros);                                                 
  • Adicionalmente, se pueden utilizar virtual y override para definir funciones  
  virtuales.                                                                      
                                                                                  
  6. Clases:                                                                      
                                                                                  
  • Declaración: class nombre { public: tipo variable; };                         
  • Ejemplo: class persona { public: int edad; char nombre[20]; };                
  • Acceso: clase.variable                                                        
  • Adicionalmente, se pueden utilizar private y protected para definir membres   
  privados y protegidos.                                                          
                                                                                  
  7. Punteros inteligentes:                                                       
                                                                                  
  • Declaración: std::unique_ptr<T> ptr; o std::shared_ptr<T> ptr;                
  • Ejemplo: std::unique_ptr<int> ptr = std::make_unique<int>(10);                
  • Acceso: ptr->variable o *ptr                                                  
                                                                                  
  8. Referencias:                                                                 
                                                                                  
  • Declaración: tipo & referencia;                                               
  • Ejemplo: int x = 10; int &ref = x;                                            
  • Acceso: referencia                                                            
                                                                                  
  9. Enumeraciones:                                                               
                                                                                  
  • Declaración: enum nombre { valor1, valor2, ... };                             
  • Ejemplo: enum color { rojo, verde, azul };                                    
  • Acceso: nombre::valor o nombre.valor (en C++11)                               


