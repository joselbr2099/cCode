  Estructuras Condicionales en C                                                  
                                                                                  
  1. If (Si): if (condición) { instrucción; }                                     
                                                                                  
  • Ejemplo: if (x > 5) { printf("x es mayor que 5\n"); }                         
                                                                                  
  2. If-Else (Si-No): if (condición) { instrucción1; } else { instrucción2; }     
                                                                                  
  • Ejemplo: if (x > 5) { printf("x es mayor que 5\n"); } else { printf("x es     
  menor o igual que 5\n"); }                                                      
                                                                                  
  3. If-Else If (Si-No Si): if (condición1) { instrucción1; } else if (condición2)
  { instrucción2; }                                                               
                                                                                  
  • Ejemplo: if (x > 5) { printf("x es mayor que 5\n"); } else if (x == 5) {      
  printf("x es igual que 5\n"); }                                                 
                                                                                  
  4. Switch (Selector): switch (expresión) { caso1: instrucción1; break; caso2:   
  instrucción2; break; ... }                                                      
                                                                                  
  • Ejemplo: switch (x) { case 1: printf("x es 1\n"); break; case 2: printf("x es 
  2\n"); break; default: printf("x no es 1 ni 2\n"); break; }                     
                                                                                  
  5. Operador Condicional (?:): expresión ? valor si verdadero : valor si falso   
                                                                                  
  • Ejemplo: x > 5 ? printf("x es mayor que 5\n") : printf("x es menor o igual que
  5\n")                                                                           
                                                                                  
  Estructuras Condicionales en C++                                                
                                                                                  
  1. If (Si): if (condición) { instrucción; }                                     
                                                                                  
  • Ejemplo: if (x > 5) { std::cout << "x es mayor que 5\n"; }                    
                                                                                  
  2. If-Else (Si-No): if (condición) { instrucción1; } else { instrucción2; }     
                                                                                  
  • Ejemplo: if (x > 5) { std::cout << "x es mayor que 5\n"; } else { std::cout <<
  "x es menor o igual que 5\n"; }                                                 
                                                                                  
  3. If-Else If (Si-No Si): if (condición1) { instrucción1; } else if (condición2)
  { instrucción2; }                                                               
                                                                                  
  • Ejemplo: if (x > 5) { std::cout << "x es mayor que 5\n"; } else if (x == 5) { 
  std::cout << "x es igual que 5\n"; }                                            
                                                                                  
  4. Switch (Selector): switch (expresión) { caso1: instrucción1; break; caso2:   
  instrucción2; break; ... }                                                      
                                                                                  
  • Ejemplo: switch (x) { case 1: std::cout << "x es 1\n"; break; case 2:         
  std::cout << "x es 2\n"; break; default: std::cout << "x no es 1 ni 2\n"; break;
  }                                                                               
                                                                                  
  5. Operador Condicional (?:): expresión ? valor si verdadero : valor si falso   
                                                                                  
  • Ejemplo: x > 5 ? std::cout << "x es mayor que 5\n" : std::cout << "x es menor 
  o igual que 5\n"                                                                
                                                                                  
  6. Assert: assert(condición)                                                    
                                                                                  
  • Ejemplo: assert(x > 5)                                                        
 
