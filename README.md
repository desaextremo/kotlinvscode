# Instalación y configuración del compilador Kotlin, en Visual Studio Code

### Pre requisitos

* <strong><em><a href="https://code.visualstudio.com/Download" target="_blank">Visual Studio Code</a></em></strong> instalado

* Plugins de <strong><em><a href="https://marketplace.visualstudio.com/items?itemName=mathiasfrohlich.Kotlin" target="_blank">Kotlin</a></em></strong> y <strong><em><a href="https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner" target="_blank">Code Runner</a></em></strong> instalados

<p align="center">
	<a href="https://marketplace.visualstudio.com/items?itemName=mathiasfrohlich.Kotlin" target="_blank">
	<img src="images/kt5.png">
	</a>
</p>

<p align="center">
<a href="https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner" target="_blank">
	<img src="images/kt6.png">
	</a>
</p>


### Descargar y descomprimir el compilador de kotlin para tu Sistema Operativo
https://github.com/desaextremo/kotlin

<p align="center">
	<img src="images/kt1.png">
	<strong><em>Compilador de kotlin para Windows</em></strong>
</p>
  
<p align="center">
	<img src="images/kt2.png">
	<strong><em>Descomprime el compilador kotlin en un directorio</em></strong>
</p>

### Configurar variables de entorno

* Ingresar a variables de entorno a través del cuadro de busqueda de <strong><em>Window.</em></strong>


<p align="center">
	<img src="images/kt7.png">
	<strong><em>Editar variables de entorno</em></strong>
</p>

* Hacer clic en el botón <strong><em>Variables de entorno</em></strong>, ubicar la sección <strong><em>Variables de sistema</em></strong>, hacer clic sobre la variable <strong><em>path</em></strong> y luego clic en el botón <strong><em>Editar.</em></strong>

<p align="center">
	<img src="images/kt3.png">
	<strong><em>Configurar variables de entorno</em></strong>
</p>

* Modificar la variable <strong><em>path</em></strong>
<p align="center">
	<img src="images/kt4.png">
	<strong><em>Modificar la variable path</em></strong>
</p>

	1 Hacer clic en el botón <strong><em>Nuevo</em></strong>

	2 Ingresar la ruta al directorio en donde se encuentra el compilador de <strong><em>Kotlin:</em></strong> 
	<strong><em><directorio instalacion de kotlin/ bin></em></strong>
 
 **Ejemplo:**
	```
	C:\software\kotlin-compiler-1.3.72\kotlinc\bin
	```

	3 Hacer clic sobre el botón <strong><em>Aceptar</em></strong>, y dos veces más sobre el botón <strong><em>Aceptar</em></strong> de los cuadros de dialogo previamente abiertos.

* Iniciar <strong><em><a href="https://code.visualstudio.com/Download" target="_blank">Visual Studio Code</a></em></strong>, escribir programa básico:

``` kotlin
fun main(args: Array<String>) {
	println("hola mundo");
}
```
* Hacer clic en el botón <strong><em>Run code</em></strong>, o pulsar la combinación de teclas <strong><em>(Ctrl + Alt +N)</em></strong>
  
<p align="center">
	<img src="images/kt8.png">
	<strong><em>Resultado en consola</em></strong>
</p>
