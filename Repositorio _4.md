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


        

