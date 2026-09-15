## Inicio del repositorio de la Unidad-4                    
# Estructura de datos                   

# Lectura 1 de Objetos, Variables y Etiquetas                 

"Creamos un objeto (en este caso, un número)"                    
altitud = 10000  # metros                      

"'altitud' es una etiqueta que apunta al objeto entero 10000"                           
"Podemos crear otra etiqueta que apunte al mismo objeto"                      
elevacion = altitud                      

"Si modificamos el valor al que apunta 'elevacion'"                        
elevacion = 9500                        

"'altitud' sigue apuntando al valor original"                    
print(altitud)  imprimira 10000                    
print(elevacion)  imprimira 9500        

<img width="714" height="536" alt="image" src="https://github.com/user-attachments/assets/632d2c38-43ad-4f34-a457-bec6c76f0529" />   

### Lectura 2 ID de objetos                                       
velocidad = 800  # km/h            
print(id(velocidad))  # Muestra el identificador único del objeto                       

otra_velocidad = 800                                  
print(id(otra_velocidad))  # Para números pequeños, Python reutiliza objetos                       

lista1 = [1, 3, 67]                  
print(id(lista1))                  

<img width="989" height="188" alt="image" src="https://github.com/user-attachments/assets/db111da7-3960-413b-9086-85f2bf4cfb98" />          

### Lectura 3: Mutabilidad vs Inmutabilidad            

La mutabilidad se refiere a si un objeto puede ser modificado después de su creación.                   

##Objetos Inmutables**: No pueden ser modificados después de su creación. Si parece que los estamos modificando, en realidad estamos creando nuevos objetos.                     

#- Ejemplos: números (int, float), strings, tuplas, frozensets                         

##Objetos Mutables**: Pueden ser modificados después de su creación.                                 

#- Ejemplos: listas, diccionarios, sets                

<img width="734" height="568" alt="image" src="https://github.com/user-attachments/assets/e92c0e05-c4b5-49b1-a2de-eba3d3409f18" />                     

**Implicaciones en el paso de argumentos**                      

La mutabilidad afecta cómo se comportan los objetos cuando se pasan como argumentos a funciones.                     

> Realiza el siguiente ejercicio y explica (en tu bitácora) tu respuesta a la pregunta:                                    
>                         

❓¿Cómo afecta la mutabilidad a los objetos que se usan como argumentos de una función?     
def agregar_combustible(tanques, litros):                            
    tanques.append(litros)             
    print(f"Combustible actualizado: {tanques}")             

combustible_actual = [1000, 1200, 800]  # Lista (objeto mutable)              
agregar_combustible(combustible_actual, 500)                 
print(combustible_actual)  # [1000, 1200, 800, 500] - La lista original fue modificada                   

hace que la lista inicial que habíamos definido al inicio desaparezca por completo y solo imprime la última lista                         

# Listas                         
#Ejemplo de listas modificando y agregando cosas en una sola con for                            
<img width="1370" height="894" alt="image" src="https://github.com/user-attachments/assets/19d6327c-51eb-4e53-a226-a471f27fde91" />                                          

cómo se cuenta la cantidad de lo que hay en la lista                                                          
num = len(canciones)                                                            
print(num)                                                        
                                      
<img width="919" height="767" alt="image" src="https://github.com/user-attachments/assets/dda7f8cc-d2b0-4135-a3fe-5ca6226ed447" />                                   
# como se accede a los elementos de la lista                              
print(canciones[0])                          
# Si se pone cero se pone la pimera canción pero si se pones un -1 se inicia desde la última canción en este caso iria de 0 hasta 4 y de -1 a -5 una sola vuelta                                       

<img width="1032" height="894" alt="image" src="https://github.com/user-attachments/assets/70f99bd4-2f00-4199-8515-3689e627d913" />                                  

<img width="923" height="914" alt="image" src="https://github.com/user-attachments/assets/706f4c22-5bcb-4677-8b5b-fd6085066bc2" />                                                   
                
# Listas 2                                      
while y cambiarlo al for                                
<img width="722" height="299" alt="image" src="https://github.com/user-attachments/assets/386c8bb3-dac5-4492-9169-aae0a28a7941" />                            

# Ejemplo 1

<img width="573" height="389" alt="image" src="https://github.com/user-attachments/assets/a300e45a-fdee-4865-8ed4-6ac73678a0df" />






        

