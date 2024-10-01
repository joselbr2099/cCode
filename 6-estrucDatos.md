  Estructuras de Datos en C                                                       
                                                                                  
  1. Arreglos (Arrays):                                                           
                                                                                  
  • Definición: tipo nombre[tamaño];                                              
  • Ejemplo: int miArreglo[5];                                                    
  • Descripción: conjunto de elementos del mismo tipo almacenados en memoria      
  contigua.                                                                       
                                                                                  
  2. Estructuras (Structs):                                                       
                                                                                  
  • Definición: struct nombre { tipo elemento1; tipo elemento2; ... };            
  • Ejemplo: struct Persona { int edad; char nombre[20]; };                       
  • Descripción: conjunto de elementos de diferentes tipos almacenados en memoria 
  contigua.                                                                       
                                                                                  
  3. Uniones (Unions):                                                            
                                                                                  
  • Definición: union nombre { tipo elemento1; tipo elemento2; ... };             
  • Ejemplo: union valor { int entero; float flotante; };                         
  • Descripción: conjunto de elementos de diferentes tipos que comparten la misma 
  ubicación en memoria.                                                           
                                                                                  
  4. Punteros (Pointers):                                                         
                                                                                  
  • Definición: tipo* nombre;                                                     
  • Ejemplo: int* miPuntero;                                                      
  • Descripción: variable que almacena la dirección de memoria de un elemento.    
                                                                                  
  5. Listas Enlazadas (Linked Lists):                                             
                                                                                  
  • Definición: struct Nodo { tipo elemento; struct Nodo* siguiente; };           
  • Ejemplo: struct Nodo { int elemento; struct Nodo* siguiente; };               
  • Descripción: conjunto de elementos almacenados en memoria no contigua, donde  
  cada elemento apunta al siguiente.                                              
                                                                                  
  6. Pilas (Stacks):                                                              
                                                                                  
  • Definición: struct Pila { tipo* elementos; int tamaño; };                     
  • Ejemplo: struct Pila { int* elementos; int tamaño; };                         
  • Descripción: conjunto de elementos almacenados en memoria que siguen el orden 
  LIFO (Last In, First Out).                                                      
                                                                                  
  7. Colas (Queues):                                                              
                                                                                  
  • Definición: struct Cola { tipo* elementos; int tamaño; };                     
  • Ejemplo: struct Cola { int* elementos; int tamaño; };                         
  • Descripción: conjunto de elementos almacenados en memoria que siguen el orden 
  FIFO (First In, First Out).                                                     
                                                                                  
  8. Árboles (Trees):                                                             
                                                                                  
  • Definición: struct Nodo { tipo elemento; struct Nodo* hijoIzquierdo; struct   
  Nodo* hijoDerecho; };                                                           
  • Ejemplo: struct Nodo { int elemento; struct Nodo* hijoIzquierdo; struct Nodo* 
  hijoDerecho; };                                                                 
  • Descripción: conjunto de elementos almacenados en memoria no contigua, donde  
  cada elemento apunta a sus hijos izquierdo y derecho.                           
                                                                                  
  9. Gráficos (Graphs):                                                           
                                                                                  
  • Definición: struct Nodo { tipo elemento; struct Nodo** vecinos; int numVecinos;
  };                                                                              
  • Ejemplo: struct Nodo { int elemento; struct Nodo** vecinos; int numVecinos; };
  • Descripción: conjunto de elementos almacenados en memoria no contigua, donde  
  cada elemento apunta a sus vecinos.                                             
                                                                                  
  10. Matrices (Matrices):                                                        
                                                                                  
  • Definición: tipo nombre[numFilas][numColumnas];                               
  • Ejemplo: int miMatriz[3][4];                                                  
  • Descripción: conjunto de elementos del mismo tipo almacenados en una tabla    
  rectangular.                                                                    
                                                                                  
  11. Hash Tables (Tablas de Hash):                                               
                                                                                  
  • Definición: struct HashTable { tipo* elementos; int numElementos; int tamaño; 
  };                                                                              
  • Ejemplo: struct HashTable { int* elementos; int numElementos; int tamaño; };  
  • Descripción: conjunto de elementos almacenados en memoria que utilizan una    
  función de hash para acceder a los elementos.                                   
                                                                                  
  12. Set (Conjuntos):                                                            
                                                                                  
  • Definición: struct Set { tipo* elementos; int numElementos; };                
  • Ejemplo: struct Set { int* elementos; int numElementos; };                    
  • Descripción: conjunto de elementos almacenados en memoria que no contiene     
  valores duplicados.                                                             
                                                                                  
  Estructuras de Datos en C++                                                     
                                                                                  
  1. Arreglos (Arrays):                                                           
                                                                                  
  • Definición: tipo nombre[tamaño];                                              
  • Ejemplo: int miArreglo[5];                                                    
  • Descripción: conjunto de elementos del mismo tipo almacenados en memoria      
  contigua.                                                                       
                                                                                  
  2. Vectores (Vectors):                                                          
                                                                                  
  • Definición: std::vector<tipo> nombre;                                         
  • Ejemplo: std::vector<int> miVector;                                           
  • Descripción: conjunto de elementos del mismo tipo almacenados en memoria      
  dinámicamente.                                                                  
                                                                                  
  3. Estructuras (Structs):                                                       
                                                                                  
  • Definición: struct nombre { tipo elemento1; tipo elemento2; ... };            
  • Ejemplo: struct Persona { int edad; std::string nombre; };                    
  • Descripción: conjunto de elementos de diferentes tipos almacenados en memoria 
  contigua.                                                                       
                                                                                  
  4. Clases (Classes):                                                            
                                                                                  
  • Definición: class nombre { tipo elemento1; tipo elemento2; ... };             
  • Ejemplo: class Persona { public: int edad; std::string nombre; };             
  • Descripción: conjunto de elementos de diferentes tipos almacenados en memoria 
  contigua, con métodos y propiedades.                                            
                                                                                  
  5. Punteros (Pointers):                                                         
                                                                                  
  • Definición: tipo* nombre;                                                     
  • Ejemplo: int* miPuntero;                                                      
  • Descripción: variable que almacena la dirección de memoria de un elemento.    
                                                                                  
  6. Referencias (References):                                                    
                                                                                  
  • Definición: tipo& nombre;                                                     
  • Ejemplo: int& miReferencia;                                                   
  • Descripción: alias para una variable existente.                               
                                                                                  
  7. Listas Enlazadas (Linked Lists):                                             
                                                                                  
  • Definición: struct Nodo { tipo elemento; struct Nodo* siguiente; };           
  • Ejemplo: struct Nodo { int elemento; struct Nodo* siguiente; };               
  • Descripción: conjunto de elementos almacenados en memoria no contigua, donde  
  cada elemento apunta al siguiente.                                              
                                                                                  
  8. Pilas (Stacks):                                                              
                                                                                  
  • Definición: std::stack<tipo> nombre;                                          
  • Ejemplo: std::stack<int> miPila;                                              
  • Descripción: conjunto de elementos almacenados en memoria que siguen el orden 
  LIFO (Last In, First Out).                                                      
                                                                                  
  9. Colas (Queues):                                                              
                                                                                  
  • Definición: std::queue<tipo> nombre;                                          
  • Ejemplo: std::queue<int> miCola;                                              
  • Descripción: conjunto de elementos almacenados en memoria que siguen el orden 
  FIFO (First In, First Out).                                                     
                                                                                  
  10. Árboles (Trees):                                                            
                                                                                  
  • Definición: struct Nodo { tipo elemento; struct Nodo* hijoIzquierdo; struct   
  Nodo* hijoDerecho; };                                                           
  • Ejemplo: struct Nodo { int elemento; struct Nodo* hijoIzquierdo; struct Nodo* 
  hijoDerecho; };                                                                 
  • Descripción: conjunto de elementos almacenados en memoria no contigua, donde  
  cada elemento apunta a sus hijos izquierdo y derecho.                           
                                                                                  
  11. Gráficos (Graphs):                                                          
                                                                                  
  • Definición: struct Nodo { tipo elemento; struct Nodo** vecinos; int numVecinos;
  };                                                                              
  • Ejemplo: struct Nodo { int elemento; struct Nodo** vecinos; int numVecinos; };
  • Descripción: conjunto de elementos almacenados en memoria no contigua, donde  
  cada elemento apunta a sus vecinos.                                             
                                                                                  
  12. Matrices (Matrices):                                                        
                                                                                  
  • Definición: tipo nombre[numFilas][numColumnas];                               
  • Ejemplo: int miMatriz[3][4];                                                  
  • Descripción: conjunto de elementos del mismo tipo almacenados en una tabla    
  rectangular.                                                                    
                                                                                  
  13. Hash Tables (Tablas de Hash):                                               
                                                                                  
  • Definición: std::unordered_map<tipo1, tipo2> nombre;                          
  • Ejemplo: std::unordered_map<int, std::string> miTablaHash;                    
  • Descripción: conjunto de elementos almacenados en memoria que utilizan una    
  función de hash para acceder a los elementos.                                   
                                                                                  
  14. Set (Conjuntos):                                                            
                                                                                  
  • Definición: std::set<tipo> nombre;                                            
  • Ejemplo: std::set<int> miConjunto;                                            
  • Descripción: conjunto de elementos almacenados en memoria que no contiene     
  valores duplicados.                                                             
                                                                                  
  15. Mapas (Mapas):                                                              
                                                                                  
  • Definición: std::map<tipo1, tipo2> nombre;                                    
  • Ejemplo: std::map<int, std::string> miMapa;                                   
  • Descripción: conjunto de elementos almacenados en memoria que asocian cada    
  elemento con una clave única.                                                   
                                                                                  
  16. Mapas Multiconductor (Multimaps):                                           
                                                                                  
  • Definición: std::multimap<tipo1, tipo2> nombre;                               
  • Ejemplo: std::multimap<int, std::string> miMultimap;                          
  • Descripción: conjunto de elementos almacenados en memoria que asocian cada    
  elemento con una clave única, permitiendo valores duplicados.                   
                                                                                  
  17. Conjuntos Multiconductor (Multiconjuntos):                                  
                                                                                  
  • Definición: std::multiset<tipo> nombre;                                       
  • Ejemplo: std::multiset<int> miMulticonjunto;                                  
  • Descripción: conjunto de elementos almacenados en memoria que no contiene     
  valores duplicados, permitiendo ordenar los elementos.                          
                                                                                  
  Espero que esta lista te sea útil. ¡Si tienes alguna pregunta o necesitas más   
  ayuda, no dudes en preguntar! 
