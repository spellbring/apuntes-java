# JAVA BÁSICO

# Caracterícas de java

* Es un lenguaje de programación que apareció para los años 90

* es un lenguaje orientado a objeto

# Que significa que sea orientado a objetos?
Que el código se escribe dentro de clases, organizado en funciones(métodos),
que son invocados a través de objetos o instancias de clase. Se pueden aplicar
propiedades de orientación a objeto como herencia, sobrecarga y sobrescritura, polimorfismo y encapsulación

# Principales características

## Portabilidad
El programa java se compila una vez y se ejecuta en cualquier parte. El resultado de la compilación(bytecodes) es independiente de la plataforma.

## Encapsulación
Encapsulación, los datos dentro de una clase son protegidos con modificador
privado para que no sean accesibles directamente desde el exterior.

## Robusto
Gestión automática de memoria, no se permite acceso desde el código.

## Seguro
el código java se ejecuta en un entorno controlado por la Maquina
virtual de java, impide operaciones dañinas sobre el equipo.

## Compilación
Al compilar el código fuente, se genera uno o varios archivos .class,
conocidos como bytecodes, independientes de la plataforma.

Los bytecodes se ejecutan en cualquier sistema operativo que cuente
con la maquina virtual de java

# Java Virtual Machine
* Interpreta en tiempo de ejecución los bytecodes.

* Existen implementaciones de JVM para la mayoría de los Sistemas Operativos.

* Código de fuente -> Bytecodes (.class) -> JVM(windows, solaris, linux)

# Clase Java
* El código de una aplicación Java se estructura en clases.

* Las clases incluyen atributos o campos (variables) y métodos (Funciones).

* Se definen en archivos .java, al compilar se genera un archivo .class por
cada clase.


# Estructura de una clase
Un archivo .java puede contener varias clases, aunque solo una con 
modificador public, cuyo nombre debe coincidir con el archivo


Las clases contienen atributos, constructores y métodos, para poder
dar una instancia de una clase, se aplica el operador new. Por ejemplo:

```
Clase1 c = new Clase1();
c.metodo();
```

## Empaquetado de una clase

* Las clase se organizan en paquetes(directorios)

* Los paquetes se definen con la sentencia package. Una sentencia
package por archivo .java al principio del archivo.

* Al momento de compilarlo se genera un directorio con el nombre de ese
paquete con sus correspondientes .class

## Método main

Es el punto de entrada a un programa java. Debe estar en una clase
publica y tener exactamente el formato indicado:

opción 1
```

public class Clase{

	public static void main(String [] args){
	
	
	}
	
	

}
```
opción 2
```
public class Clase2{

	public static void main(String ... data){
	
	
	}
	
	

}
```
El método main es el punto de entrada de un programa java, este método
debe tener una clase pública

public: es un método accesible desde cualquier parte del código, para
este caso como es la via de entrada de un programa en java debe
tener esta palabra reservada, estos son llamados como modificadores
de acceso.

static: mas adelante entraremos en profundidad para esta palabra reservada.
Pero en resumidas cuentas este método puede ser accedido sin necesidad 
de instanciar esta clase.

void: Significa que esta función o método no devuelve ningún valor, pero 
cuando se declara o se llama, va hacer una acción sobre la maquina 
virtual de java.

main: es la firma del método, cada método debe tener tener definida
una acción, para este caso el método main es reconocido por java como
la vía de entrada para la ejecución de cualquier de cualquier programa
en java.

String [] args: es un arreglo de cadenas o "palabras" que puede
recibir este programa en java.
Para este caso aplican las siguientes formas:

```
String ... data

String [] args

String args[]W

```

puede que si se saca la palabra reservada "static" de la firma del 
método, este podría compilar de forma correcta pero no se podría ejecutar
el programa en java.


# Project Title

One Paragraph of project description goes here

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
Give examples
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc




