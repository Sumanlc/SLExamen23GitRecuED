## Examen Entornos de Desarrollo. IES Marcos Zaragoza
### Recuperación Git. 14/05/24


Nombre y apellidos: ____Suman Lamichhane____			

 

LINK DEL REPOSITORIO:_____https://github.com/Sumanlc/SLExamen23GitRecuED.git____
> Vamos a trabajar sobre Strings.  
> Debajo de cada ejercicio deberán aparecer las capturas de pantalla pertinentes que justifiquen su realización. Intentad hacer todo lo posible desde la consola si no se indica lo contrario. 
> Se valorará negativamente las malas prácticas de GIT 

 

**1.- (0,5) Crea un repositorio privado en github “AAAExamen23GitRecuED“ e invítame a colaborar: "TomBort8" . AAA serán las primeras letras de tu nombre, 1er apellido y 2º apellido respectivamente.** 

<a href="https://ibb.co/R6w5rVh"><img src="https://i.ibb.co/gWKnqBv/Captura-de-pantalla-2024-05-14-122027.png" alt="Captura-de-pantalla-2024-05-14-122027" border="0"></a>

**2.- (0,5) Inicializa el repostiorio en local y vincúlalo al repostiroio de github** 
<a href="https://ibb.co/hKyspys"><img src="https://i.ibb.co/SKPNqPN/Captura-de-pantalla-2024-05-14-122541.png" alt="Captura-de-pantalla-2024-05-14-122541" border="0"></a>


**3.- Crea un main que pida una cadena por teclado .** 

```
import java.util.Scanner;

public class ProcesamientoTexto {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Por favor, ingresa un texto:");
        String texto = scanner.nextLine();
        scanner.close();
    }
}
```
> Sube los cambios al repositorio. 

<a href="https://ibb.co/0J7WfWX"><img src="https://i.ibb.co/w6kbKbL/Captura-de-pantalla-2024-05-14-123137.png" alt="Captura-de-pantalla-2024-05-14-123137" border="0"></a>


<a href="https://ibb.co/4Z018kj"><img src="https://i.ibb.co/wN2cStK/Captura-de-pantalla-2024-05-14-123237.png" alt="Captura-de-pantalla-2024-05-14-123237" border="0"></a>


<a href="https://imgbb.com/"><img src="https://i.ibb.co/kgW0P4q/Captura-de-pantalla-2024-05-14-125004.png" alt="Captura-de-pantalla-2024-05-14-125004" border="0"></a>


<a href="https://ibb.co/qr9tqsT"><img src="https://i.ibb.co/jrGc0Mn/Captura-de-pantalla-2024-05-14-125042.png" alt="Captura-de-pantalla-2024-05-14-125042" border="0"></a>



**4.- (0,2) Crea  un fichero Leeme.txt : “Vamos a trabajar sobre Strings con una clase propia, crearemos Ramas para que cada miembro trabajae su parte y luego las uniremos todas”.** 
<a href="https://ibb.co/frXhNHH"><img src="https://i.ibb.co/HGKWPqq/Captura-de-pantalla-2024-05-14-125635.png" alt="Captura-de-pantalla-2024-05-14-125635" border="0"></a>
*  **4.1  (0,3)Crea también un fichero de texto que no debes subir a github pero debe estar dentro de la carpeta NoSubir.txt: (Este archivo debes añadirlo y quitarlo, como si te hubieras confundido). “Este archivo debe estar en la carpeta pero no subido a git”.** 

<a href="https://ibb.co/p4fnRbD"><img src="https://i.ibb.co/qmNxW7G/Captura-de-pantalla-2024-05-14-125846.png" alt="Captura-de-pantalla-2024-05-14-125846" border="0"></a>

> Muestra por comandos que no lo has subido 

<a href="https://imgbb.com/"><img src="https://i.ibb.co/YRDFs2T/Captura-de-pantalla-2024-05-14-130530.png" alt="Captura-de-pantalla-2024-05-14-130530" border="0"></a>

> Sube los cambios al repositorio. 

**5.- (0,5) Muestra la diferencia entre los 2 últimos commits.** 

<a href="https://imgbb.com/"><img src="https://i.ibb.co/M5wXwwN/Captura-de-pantalla-2024-05-14-130718.png" alt="Captura-de-pantalla-2024-05-14-130718" border="0"></a>

**6.- (0,5) Crea 2 ramas Alicia y Bob** 

<a href="https://imgbb.com/"><img src="https://i.ibb.co/XyR19Gt/Captura-de-pantalla-2024-05-14-130839.png" alt="Captura-de-pantalla-2024-05-14-130839" border="0"></a>

**7.- Sitúate en Alicia y añade al main las siguientes funcionalidades:**
```
    public static String convertirAMayusculas(String texto) {
        return texto.toUpperCase();
    }
    
    public static String recortarEspacios(String texto) {
        return texto.trim();
    }

```

> Sube los cambios al repositorio (rama Alice).

<a href="https://ibb.co/nz5hTVf"><img src="https://i.ibb.co/m6MQmYt/Captura-de-pantalla-2024-05-14-131638.png" alt="Captura-de-pantalla-2024-05-14-131638" border="0"></a>

**8.- Sitúate en Bob y añade al main lo siguiente:**
```
    public static String convertirAMinusculas(String texto) {
        return texto.toLowerCase();
    }
    
    public static String invertirTexto(String texto) {
        return new StringBuilder(texto).reverse().toString();
    }
    
```

> Sube los cambios al repositorio (rama Bob). 

<a href="https://imgbb.com/"><img src="https://i.ibb.co/YWk0N0B/Captura-de-pantalla-2024-05-14-132006.png" alt="Captura-de-pantalla-2024-05-14-132006" border="0"></a>

**9.- (1) Muestra la diferencia entre las ramas Alicie y Bob y guárdalo en un fichero llamado DIFERENCIA _RAMAS (desde consola). Este ficehro debe subirse al repositorio.** 

 <a href="https://imgbb.com/"><img src="https://i.ibb.co/RCjmVK9/Captura-de-pantalla-2024-05-14-132135.png" alt="Captura-de-pantalla-2024-05-14-132135" border="0"></a>
 
 <a href="https://imgbb.com/"><img src="https://i.ibb.co/TrrZ8w5/Captura-de-pantalla-2024-05-14-132851.png" alt="Captura-de-pantalla-2024-05-14-132851" border="0"></a>

**10.- (1,5) Fusiónalo en main (consola) y resuelve el conflicto (en gitHUB).** 

> Sube los cambios al repositorio. 

<a href="https://imgbb.com/"><img src="https://i.ibb.co/HgftHj1/Captura-de-pantalla-2024-05-14-133454.png" alt="Captura-de-pantalla-2024-05-14-133454" border="0"></a>

<a href="https://imgbb.com/"><img src="https://i.ibb.co/NLbGyfP/Captura-de-pantalla-2024-05-14-133717.png" alt="Captura-de-pantalla-2024-05-14-133717" border="0"></a>


<a href="https://ibb.co/TRLvWWG"><img src="https://i.ibb.co/wCs0ccq/Captura-de-pantalla-2024-05-14-133816.png" alt="Captura-de-pantalla-2024-05-14-133816" border="0"></a>


<a href="https://ibb.co/5Lvc2ZZ"><img src="https://i.ibb.co/WfFKsCC/Captura-de-pantalla-2024-05-14-134541.png" alt="Captura-de-pantalla-2024-05-14-134541" border="0"></a>

 

**11.-(0,5) Borra las ramas Alice Y Bob.**

 <a href="https://imgbb.com/"><img src="https://i.ibb.co/vs8j5Nk/Captura-de-pantalla-2024-05-14-134658.png" alt="Captura-de-pantalla-2024-05-14-134658" border="0"></a>

**12.- (0,5) Entra a SOURCETREE y haz una captura del eje temporal del repositorio. Haz una breve explicación de lo que observas.** 

 <a href="https://ibb.co/sRqY58h"><img src="https://i.ibb.co/dMDYb8S/Captura-de-pantalla-2024-05-14-134834.png" alt="Captura-de-pantalla-2024-05-14-134834" border="0"></a>

**13.- (0,75) ¿ Cuál es la diferencia entre “git pull” y “git clone” ?** 

**git clone:** lo utilizamos para empezar a trabajar ya que agrega el repositorio remoto a tu area de trabajo.
**git pull:** descarga una actualización del estado del repositorio remoto al repositorio local y a los archivos (osea combina un fetch y un merge).




**14.- (1,25) Abre el main y déjalo inservible poniendo el tipo de dato a StringBuilder. Sube los cambios. A continuación deshaz el último commit.**
 

**15.- (1,25) Vuelve al estado en el que estaba el proyecto al acabar el ejercicio 3 en local.**
 
 
 **16.-(0,75) Añade este documento al repoitorio, con todas las imágenes para que se pueda ver desde git.**


**17.-  Por último, ejecutad el siguiente comando:** 

> *history > historial.txt* 

**sube el resultado a aules junto al PDF de este documento.** 