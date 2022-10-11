# ResumenGithub
## Creación de repositorio en GitHub

1. Selecccionar el icono de la esquina derehca superior. 

![alt text](https://github.com/juliasuarz/resumenGithub/blob/main/Captura%20de%20pantalla%202022-09-20%20a%20las%2020.44.10.png?raw=true)



2. Selecccionar en la pestaña abierta nuevo repositorio
    
![captura](https://github.com/juliasuarz/resumenGithub/blob/main/Captura%20de%20pantalla%202022-09-20%20a%20las%2020.44.24.png?raw=true)

        
        
3. Creamos uno nuevo
   
![captura3](https://github.com/juliasuarz/resumenGithub/blob/main/Captura%20de%20pantalla%202022-09-20%20a%20las%2020.44.34.png?raw=true)
     
     
4. Introducimos el nombre del repositorio que estamos creando (sin espacios), añadimos una pequeña descripción y seleccionamos la casilla “Add a README       file”

![captura4](https://github.com/juliasuarz/resumenGithub/blob/main/Captura%20de%20pantalla%202022-09-20%20a%20las%2020.44.44.png?raw=true)
    
    
    
5. Creamos el repositorio
    
![Captura5](https://github.com/juliasuarz/resumenGithub/blob/main/Captura%20de%20pantalla%202022-09-20%20a%20las%2020.45.03.png?raw=true)
    
    
6. Ya tenemos un repositorio nuevo creado, para editarle seleccionamos el icono en forma de lapiz de la derecha.

![captura6](https://github.com/juliasuarz/resumenGithub/blob/main/Captura%20de%20pantalla%202022-09-20%20a%20las%2020.46.31.png?raw=true)
    
    
    
## Markdown
-**Encabezados**
 ```
    # Encabezado 1
    ## Encabezado 2
    ### Encabezado 3
    #### Encabezado 4
    ##### Encabezado 5
    ###### Encabezado 6
```

   # Encabezado1
   ## Encabezado 2
   ### Encabezado 3
   #### Encabezado 4
   ##### Encabezado 5
   ###### Encabezado 6
     
       
  
-**Párrafos y saltos de línea**
  
   Para realizar un salto de línea y empezar una frase en una línea siguiente dentro del mismo párrafo, tendrás que pulsar dos veces la barra espaciadora       antes de pulsar una vez intro.
  
   Otra manera de generar encabezados es con el símbolo ` = ` (para el encabezado 1), o con guiones ` - ` para el encabezado 2.
     
   ```
   Esto sería un encabezado 1
===
Esto sería un encabezado 2
—-
````
   
     
       
-**Citas**

   Utilizando el carácter mayor que ` > ` al comienzo del bloque de texto.
     
   > Un país, una civilización se puede juzgar por la forma en que trata a sus animales.  — Mahatma Gandhi

   Incluso puedes concatenar varios ` >> ` para crear citas anidadas.
   > Esto sería una cita como la que acabas de ver.
> 
> > Dentro de ella puedes anidar otra cita.

  
  
-**Listas**

   Para crear listas desordenadas utiliza ` * ` asteriscos, ` - ` guiones, o ` + ` símbolo de suma.
   
````
- Elemento de lista 1
- Elemento de lista 2
* Elemento de lista 3
* Elemento de lista 4
+ Elemento de lista 5
+ Elemento de lista 6
````
- Elemento de lista 1
- Elemento de lista 2
* Elemento de lista 3
* Elemento de lista 4
+ Elemento de lista 5
+ Elemento de lista 6

  
    Para generar listas anidadas dentro de otras, simplemente tendrás que tabular:
  
````
- Elemento de lista 1
- Elemento de lista 2
    - Elemento de lista 3
    - Elemento de lista 4
 ````

- Elemento de lista 1
- Elemento de lista 2
    - Elemento de lista 3
    - Elemento de lista 4

  
-**Listas ordenadas**
      
Para crear listas ordenadas debes utilizar la sintaxis de tipo: «número.» ` 1 ` . Al igual que ocurre con las listas desordenadas, también podrás anidarlas o combinarlas.

`````
1. Elemento de lista 1
2.  Elemento de lista 2
    - Elemento de lista 3
    - Elemento de lista 4
        
`````
1. Elemento de lista 1
2.  Elemento de lista 2
    - Elemento de lista 3
    - Elemento de lista 4
    
        

-**Reglas horizontales**
      
   Se utilizan para separar secciones de una manera visual
`````
***
---
___
`````
***
---
___

    
        
-**Elementos de línea**
         
| Markdown      | Resultado     |       
| ------------- |-------------  | 
| `*cursiva*`   | *cursiva*     | 
| `_cursiva_`   | _cursiva_     |   
| `**negrita**`	| **negrita**   |
| `__negrita__`	| __negrita__   |

   Tambien se pueden combinar
| Markdown      | Resultado     |       
| ------------- |-------------  | 
| `***cursiva y negrita***`   | ***cursiva y negrita***    | 
| `___cursiva y negrita___`   | ___cursiva y negrita___     |   

        
            

-**Links o enlaces**
  
   Se crean escribiendo la palabra o texto enlazada entre `[]` corchetes, y el link en cuestión entre `()` paréntesis.
   
   | Markdown      | Resultado     |       
| ------------- |-------------  | 
| `[enlace en línea](http://www.limni.net)	`   | [enlace en línea](http://www.limni.net)	    | 


        
-**Código**
    
    La forma más sencilla de escribir código en Markdown es envolver el texto entre dos comillas sencillas.
    
   ![captura8](https://github.com/juliasuarz/resumenGithub/blob/main/Captura%20de%20pantalla%202022-10-11%20a%20las%209.05.47.png?raw=true)
    
   `Esto es una línea de código`
   
    
        

-**Imágenes**
     
   Solo que en este caso, deberás añadir un símbolo de `!` exclamación al principio y el enlace no será otro que la ubicación de la imagen.

    `![Texto alternativo](/ruta/a/la/imagen.jpg)`


    
-**Links automáticos**
     
   Para generar links automáticos tan solo tendrás que rodearlos con los símbolos `< >`
    `<http://www.limni.net>`
    <http://www.limni.net>

        
        
-**Tablas**
     
     
`| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
`
    | Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |








    




        



   

   
    
    
