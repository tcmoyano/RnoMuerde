# Curso R no muerde

## Introducción a R

R es un lenguaje de programación y un entorno de software libre, diseñado principalmente para el análisis estadístico y la visualización de datos. Es ampliamente utilizado por estadísticos, científicos de datos, bioinformáticos, y otros profesionales en campos que requieren análisis de datos complejos.

### **Características Principales de R:**

1. **Lenguaje de Programación:**
    - R es un lenguaje de programación interpretado, lo que significa que puedes ejecutar comandos de manera interactiva y ver los resultados de inmediato.
    - Es un lenguaje orientado a objetos, lo que permite organizar datos y funciones en objetos que pueden ser manipulados fácilmente.
2. **Análisis Estadístico:**
    - R ofrece una amplia variedad de técnicas estadísticas, incluyendo modelos lineales y no lineales, pruebas estadísticas, análisis de series temporales, clasificación, clustering, entre otros.
    - Permite realizar análisis desde los más simples hasta los más complejos, con la posibilidad de personalizar cada paso del análisis.
3. **Visualización de Datos:**
    - R es muy potente en la creación de gráficos y visualizaciones. Puedes generar desde gráficos simples como histogramas y gráficos de barras, hasta gráficos más complejos como mapas de calor, gráficos de dispersión tridimensionales y gráficos interactivos.
    - Paquetes como `ggplot2` son muy populares para crear visualizaciones sofisticadas y personalizadas.
4. **Entorno de Software:**
    - R no solo es un lenguaje, sino también un entorno de software en el que puedes escribir y ejecutar scripts, almacenar y manejar datos, y producir informes y gráficos.
    - R puede integrarse con otros lenguajes de programación como Python y C++, y es extensible a través de paquetes.
5. **Comunidad y Soporte:**
    - La funcionalidad de R se puede ampliar mediante paquetes, que son colecciones de funciones, datos y código que puedes instalar y utilizar. Actualmente, existen más de 15,000 paquetes disponibles en CRAN (Comprehensive R Archive Network), cubriendo una amplia gama de aplicaciones.
    - Para análisis de datos asociados a biología, está disponible la plataforma Bioconductor [https://www.bioconductor.org/](https://www.bioconductor.org/), la cual contiene más de 2300 paquetes disponibles para su uso.
    - R tiene una gran comunidad de usuarios que contribuyen con paquetes, tutoriales, y foros de discusión. La extensa documentación y los recursos en línea facilitan aprender y resolver problemas.

---

## **Tutorial de Instalación de R**

### **Paso 1: Descargar R**

### **1.1 Visitar el Sitio Web de CRAN**

- Abre tu navegador web.
- Dirígete al sitio oficial de CRAN (Comprehensive R Archive Network): [https://cran.r-project.org/](https://cran.r-project.org/).

### **1.2 Seleccionar el Sistema Operativo**

- En la página de CRAN, verás opciones para descargar R para diferentes sistemas operativos:
    - **Windows:** Haz clic en "Download R for Windows".
    - **macOS:** Haz clic en "Download R for (Mac) OS X".
    - **Linux:** Haz clic en "Download R for Linux".

### **Paso 2: Instalación de R en tu Sistema Operativo**

### **2.1 Instalación de R en Windows**

1. **Descargar el Instalador:**
    - Después de seleccionar "Download R for Windows", haz clic en "base" y luego en el enlace `Download R x.y.z for Windows` (donde x.y.z es la versión más reciente).
2. **Ejecutar el Instalador:**
    - Una vez descargado el archivo `.exe`, haz doble clic para ejecutar el instalador.
    - Acepta los términos y condiciones.
    - Elige la carpeta de instalación (la predeterminada suele ser adecuada).
    - Selecciona las opciones predeterminadas en las configuraciones adicionales y haz clic en "Next" hasta completar la instalación.
3. **Finalizar la Instalación:**
    - Una vez completada, puedes abrir R desde el menú de inicio.

### **2.2 Instalación de R en macOS**

1. **Descargar el Instalador:**
    - Después de seleccionar "Download R for (Mac) OS X", haz clic en el archivo `R-x.y.z.pkg` para descargar el instalador.
2. **Ejecutar el Instalador:**
    - Una vez que el archivo `.pkg` se haya descargado, ábrelo y sigue las instrucciones del instalador.
    - Acepta los términos y condiciones.
    - Selecciona el disco de instalación (generalmente tu disco principal).
3. **Finalizar la Instalación:**
    - Al terminar la instalación, R estará disponible en la carpeta de Aplicaciones.

### **2.3 Instalación de R en Linux (Ubuntu)**

1. **Abrir la Terminal:**
    - Presiona `Ctrl + Alt + T` para abrir la terminal.
2. **Actualizar los Repositorios:**
    - Ejecuta el siguiente comando para asegurarte de que tu lista de paquetes está actualizada:
        
        ```bash
        sudo apt update
        
        ```
        
3. **Instalar R:**
    - Instala R ejecutando el siguiente comando:
        
        ```bash
        sudo apt install r-base
        
        ```
        
4. **Verificar la Instalación:**
    - Una vez completada la instalación, puedes abrir R escribiendo `R` en la terminal y presionando `Enter`.

### **Paso 3: Verificación de la Instalación**

1. **Abrir R:**
    - **Windows:** Desde el menú de inicio, busca "R" y haz clic en el icono de R.
    - **macOS:** Ve a la carpeta de Aplicaciones y haz clic en el icono de R.
    - **Linux:** Escribe `R` en la terminal y presiona `Enter`.
2. **Ejecutar un Comando Simple:**
    - Una vez que R esté abierto, prueba ejecutando un comando simple:
        
        ```r
        print("¡R está instalado y funcionando!")
        
        ```
        
    - Si ves el mensaje "¡R está instalado y funcionando!" en la consola, entonces R se ha instalado correctamente.

### **Paso 4: Instalación de RStudio (Opcional pero Recomendado)**

RStudio es un entorno de desarrollo integrado (IDE) que facilita el uso de R. Puedes instalarlo siguiendo estos pasos:

1. **Descargar RStudio:**
    - Visita [https://posit.co/downloads/](https://posit.co/downloads/)
    - Selecciona la versión de RStudio adecuada para tu sistema operativo y descárgala.
2. **Instalar RStudio:**
    - **Windows y macOS:** Ejecuta el instalador descargado y sigue las instrucciones.
    - **Linux:** Si usas Ubuntu, puedes instalar RStudio con los siguientes comandos:
        
        ```bash
        sudo apt install gdebi-core
        sudo gdebi rstudio-x.y.z-amd64.deb  # Reemplaza x.y.z con la versión descargada
        
        ```
        
3. **Abrir RStudio:**
    - Una vez instalado, puedes abrir RStudio desde el menú de inicio (Windows), la carpeta de Aplicaciones (macOS), o escribiendo `rstudio` en la terminal (Linux).

---

## **Exploración de RStudio**

Una vez que hayas instalado RStudio, puedes explorarlo:

1. **Console:**
    - Es el área principal donde puedes escribir y ejecutar comandos de R.
2. **Environment/History:**
    - Aquí puedes ver y manejar todos los objetos que has creado en tu sesión de R.
3. **Files/Plots/Packages/Help/Viewer:**
    - Estas pestañas te permiten explorar archivos, visualizar gráficos, gestionar paquetes, acceder a la documentación y ver páginas web integradas.
4. **Script Editor:**
    - Puedes escribir y guardar scripts de R, que luego puedes ejecutar en la consola.

### **Ejemplo de una Sesión Simple en RStudio:**

1. Abre RStudio.
2. La consola mostrará este símbolo:
    
    ```
    >
    ```
    

Esto indica que está esperando una instrucción.

Recomendamos usar siempre un script de R, en el cual podemos escribir nuestros códigos, donde podemos luego editarlos y reutilizarlos.

Cuando queremos anotar alguna información no ejecutable en nuestro código podemos utilizar el signo “#”, todo lo que está  a la derecha de este signo, será leído como comentario, y no se ejecutará.

```
> # esto es un comentario
```

Podemos hacer operaciones matemáticas desde las más sencillas, por ejemplo:

```
> 1 + 1
```

Esta operación por supuesto entregará en pantalla el número “2”.

Esta información puede guardarse en objetos o variables. Existen muchos tipos de objetos, los cuales pueden ser cualquier texto, que comience con algún carácter que no sea un número. Ojalá no utilizar algunos caracteres utilizados en funciones como por ejemplo “F” de FALSE, o “T” de true.

 

```
> a = 1 + 1 # la variable "a" contendrá el número 2
```

Luego se puede hacer cualquier operación matemática utilizando variables y números, por ejemplo:

```
> c= a*2
```

Donde “c”, guardará el número 4.

# Tipos de objeto:

En R, hay varios tipos de objetos que puedes utilizar para almacenar y manipular datos. Cada tipo de objeto tiene características y usos específicos. A continuación, se describen los principales tipos de objetos en R:

### **1. Vectores**

- **Descripción:** Un vector es el tipo de objeto más básico en R. Es una colección de elementos del mismo tipo (numérico, carácter, lógico, etc.).
- **Ejemplo:**
    
    ```r
    # Vector numérico
    numeros <- c(1, 2, 3, 4, 5) # c(elemento1, elemanto2), es una función nativa de R para concatenar elementos.
    
    # Vector de caracteres
    caracteres <- c("a", "b", "c") # los caracteres siempre se escriben entre comillas
    
    # Puedes crear vectores de diferentes tipos mediante operaciones. Por ejemplo:
    
    vector.logico <- caracteres == "a" # esto pregunta si algún elemento del vector "caracteres" es igual a "a".
    
    # Con lo que creas el vector logico, que lo puedes visualizar de la siguiente forma:
    print(vector.logico)
    
    [1]  TRUE FALSE FALSE
    
    # o simplemente visuaizarlo escribiendo el nombre del vector:
    
    vector.logico
    
    [1]  TRUE FALSE FALSE
    
    ### hay diferentes formas de hacer lo mismo en R
    ```
    

### **2. Matrices**

- **Descripción:** Una matriz es una extensión de un vector en dos dimensiones (filas y columnas), y todos los elementos deben ser del mismo tipo.
- **Ejemplo:**
    
    ```r
    # Crear una matriz de 2x3
    matriz <- matrix(1:6, nrow = 2, ncol = 3)
    print(matriz)
    
    ```
    
    - **Resultado:**
        
        ```
          		[,1] [,2] [,3]
        [1,]    1    3    5
        [2,]    2    4    6
        
        ```
        

### **3. Data Frames**

- **Descripción:** Un data frame es una tabla en la que las columnas pueden contener diferentes tipos de datos (numéricos, caracteres, factores, etc.). Es uno de los objetos más utilizados en R para almacenar y manipular datos.
- **Ejemplo:**
    
    ```r
    df <- data.frame(
      Nombre = c("Juan", "María", "Pedro"),
      Edad = c(23, 22, 25),
      Ciudad = c("Talca", "Santiago", "Concepción")
    )
    print(df)
    
    ```
    

### **4. Listas**

- **Descripción:** Una lista es un objeto en R que puede contener diferentes tipos de elementos, incluyendo otros vectores, matrices, data frames, e incluso otras listas.
- **Ejemplo:**
    
    ```r
    mi_lista <- list(
      numeros = c(1, 2, 3),
      caracteres = c("a", "b", "c"),
      logicos = c(TRUE, FALSE, TRUE)
    )
    print(mi_lista)
    
    ```
    

### **5. Factores**

- **Descripción:** Un factor es un tipo especial de vector utilizado para representar datos categóricos. Los factores son útiles cuando tienes datos con un número limitado de valores únicos, como géneros o niveles de satisfacción.
- **Ejemplo:**
    
    ```r
    genero <- factor(c("Masculino", "Femenino", "Femenino", "Masculino"))
    print(genero)
    
    ```
    

### **6. Arrays**

- **Descripción:** Un array es similar a una matriz, pero puede tener más de dos dimensiones. Es útil para almacenar datos multidimensionales.
- **Ejemplo:**
    
    ```r
    # Crear un array de 3x3x2
    mi_array <- array(1:18, dim = c(3, 3, 2))
    print(mi_array)
    
    ```
    

### **7. Factores**

- **Descripción:** Los factores son utilizados para manejar datos categóricos. Son útiles para variables cualitativas que tienen un número limitado de valores únicos.
- **Ejemplo:**
    
    ```r
    colores <- factor(c("rojo", "azul", "verde", "rojo"))
    print(colores)
    
    ```
    

### **8. Funciones**

- **Descripción:** Las funciones son objetos en R que contienen una secuencia de comandos para realizar una tarea específica. Puedes crear tus propias funciones.
- **Ejemplo:**
    
    ```r
    mi_funcion <- function(x, y) {
      return(x + y)
    }
    resultado <- mi_funcion(3, 4)
    print(resultado)  # Resultado: 7
    
    ```
    

### **9. Listas**

- **Descripción:** Una lista en R es un tipo de objeto que puede contener una colección de diferentes tipos de elementos, como vectores, matrices, data frames, e incluso otras listas. Las listas son extremadamente flexibles y se utilizan ampliamente en R para almacenar conjuntos complejos de datos.
- **Ejemplo:**
    
    ```r
    mi_lista <- list(
      numeros = c(1, 2, 3),
      caracteres = c("a", "b", "c"),
      logicos = c(TRUE, FALSE, TRUE)
    )
    print(mi_lista)
    
    ```
    

### **10. Objetos S3, S4 y R6**

- **Descripción:** Estos son tipos de objetos más avanzados que se utilizan en la programación orientada a objetos en R. Permiten crear clases y métodos personalizados, lo que es útil para desarrollar paquetes y aplicaciones complejas.

Cada uno de estos tipos de objetos tiene su uso particular en R y es importante conocer cuándo y cómo utilizarlos según las necesidades del análisis o tarea que estés realizando.

# Como acceder a los elementos de un data frame

Acceder a los elementos de un `data frame` en R es una operación común y se puede hacer de varias maneras, dependiendo de lo que necesites. A continuación, te explico diferentes métodos para acceder a las filas, columnas y elementos específicos dentro de un `data frame`:

### **1. Acceder a una Columna por Nombre**

- **Método 1: Usando el símbolo `$`**
    - Puedes acceder a una columna de un `data frame` utilizando el símbolo `$` seguido del nombre de la columna.
    - **Ejemplo:**
        
        ```r
        df <- data.frame(
          Nombre = c("Juan", "María", "Pedro"),
          Edad = c(23, 22, 25),
          Ciudad = c("Talca", "Santiago", "Concepción")
        )
        
        # Acceder a la columna "Nombre"
        nombres <- df$Nombre
        print(nombres)
        
        ```
        
- **Método 2: Usando corchetes `[]` y el nombre de la columna**
    - También puedes acceder a una columna usando corchetes y especificando el nombre de la columna como una cadena de texto.
    - **Ejemplo:**
        
        ```r
        nombres <- df["Nombre"]
        print(nombres)
        
        ```
        
- **Método 3: Usando corchetes `[]` y el número de la columna**
    - Si conoces la posición de la columna, puedes acceder a ella utilizando su número.
    - **Ejemplo:**
        
        ```r
        nombres <- df[, 1]  # La primera columna
        print(nombres)
        
        ```
        

### **2. Acceder a una Fila por Número**

- **Usando corchetes `[]`:**
    - Puedes acceder a una fila específica usando corchetes y especificando el número de la fila.
    - **Ejemplo:**
        
        ```r
        primera_fila <- df[1, ]
        print(primera_fila)
        
        ```
        

### **3. Acceder a un Elemento Específico**

- **Usando corchetes `[]` y especificando fila y columna:**
    - Para acceder a un elemento específico dentro del `data frame`, usa corchetes con el número de la fila y el número de la columna.
    - **Ejemplo:**
        
        ```r
        elemento <- df[2, 3]  # Elemento en la segunda fila y tercera columna
        print(elemento)  # Resultado: "Santiago"
        
        ```
        
    - También puedes usar el nombre de la columna en lugar del número.
    - **Ejemplo:**
        
        ```r
        elemento <- df[2, "Ciudad"]  # Elemento en la segunda fila y columna "Ciudad"
        print(elemento)  # Resultado: "Santiago"
        
        ```
        

### **4. Acceder a Subconjuntos de un Data Frame**

- **Seleccionar múltiples filas y columnas:**
    - Puedes seleccionar un subconjunto de un `data frame` especificando rangos o vectores de números de filas y columnas.
    - **Ejemplo:**
        
        ```r
        subset <- df[1:2, c("Nombre", "Ciudad")]
        print(subset)
        
        ```
        
- **Filtrar datos usando condiciones:**
    - Puedes filtrar filas usando condiciones lógicas.
    - **Ejemplo:**
        
        ```r
        mayores_de_23 <- subset(df, Edad > 23)
        print(mayores_de_23)
        
        ```
        

###