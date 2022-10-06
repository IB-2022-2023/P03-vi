# Práctica 03. Edición de ficheros de texto con vi

# Factor de ponderación: 4

### Objetivos
Los objetivos de esta práctica son que el alumnado:
* Aprenda a utilizar el editor [vim](https://www.vim.org/)
  conociendo al menos los comandos básicos de edición
* Sepa editar ficheros remotos en la VM de la asignatura usando vi
* Sepa ejecutar comandos básicos de Linux

### Rúbrica de evaluacion de esta práctica
Se señalan a continuación los aspectos más relevantes (la lista no es exhaustiva) que se tendrán en cuenta a la hora de evaluar esta práctica:
* Ha de acreditar que es capaz de editar ficheros remotos en la VM de la asignautra usando vi
* Ha de acreditarse que se es capaz de conectarse a la máquina virtual de la asignatura y ejecutar comandos básicos de Linux 

### Introducción
Todo usuario de Linux que se precie debiera saber utilizar el editor vi.  
Son varias las áreas en las que necesitará usar un editor de texto: la programación o la edición de ficheros de configuración del sistema son dos de las más relevantes.
Hay varios editores de texto notables disponibles para sistemas operativos basados en Linux.
Los usuarios de terminal gráfica utilizarán el editor por defecto de su distribución, pero si se accede al fichero desde la terminal, 
o a través de `ssh` en otro servidor, con frecuencia tendrá que editar el texto utilizando uno de los conocidos editores en terminal.
Existen otros editores más sencillos de utilizar, pero puede que Ud. acceda a una máquina que no disponga de ellos y que no le permita 
instalar su propio editor, de modo que conocer vi podrá sacarle de más de un apuro.

Vi fue el primer editor de texto orientado al terminal creado para Unix. 
Fue diseñado para ser simple pero potente en cuanto a la manipulación de texto.
Vim (Vi IMproved), como su nombre indica, es un clon de Vi y ofrece aún más funciones que éste. 
Es gratuito y de código abierto, y está diseñado para ser utilizado tanto desde una interfaz de línea de comandos 
como en forma de aplicación independiente en una interfaz gráfica de usuario (GUI).
Es altamente configurable y dispone de características notables como resaltado de sintaxis, soporte para ratón, versiones gráficas, modo visual, 
muchos comandos de edición nuevos y una gran cantidad de extensiones.
A modo de resumen, se indican a continuación algunas de las características por las que utilizaremos vi en
*Informática Básica*:

1. Es gratuito y de código abierto
2. Está disponible en la mayoría, si no en todas las distribuciones de Linux existentes.
3. Está bien documentado. Es muy fácil hallar información sobre cualquier duda sobre su uso.
5. Es muy personalizable y extensible
6. Tiene configuraciones portátiles
7. Utiliza menos recursos del sistema
8. Es compatible con todos los lenguajes de programación y formatos de archivo
9. Es muy popular en el mundo de Linux

### Tutoriales
En la Práctica 1 de la asignatura ya se indicaron algunas referencias para un primer contacto con vi.
[Este tutorial](https://blog.desdelinux.net/usando-vim-tutorial-basico/) 
permite aprender lo básico sobre cómo editar y modificar un fichero usando vi.
El [tutorial interactivo on-line](https://www.openvim.com/) 
enseña el uso del editor de forma interactiva.
[Este otro tutorial](https://github.com/Izaird/Vim-primeros-pasos) explica lo básico del editor a través de ejemplos concretos con ficheros de texto.
Igualmente tanto
[el tutorial](https://web.stanford.edu/class/cs107/resources/vim.html) 
de una asignatura de Stanford como el de la lección
[The Missing Semester of Your CS Education](https://missing.csail.mit.edu/2020/editors/) 
del MIT también son dos buenos tutoriales de iniciación.

Por último la 
[Vim Quick Reference Card](http://www.cheat-sheets.org/saved-copy/vimqrc.pdf)
que tiene también disponible a través del aula virtual de la asignatura es una hoja que merece la pena
imprimir y tener disponible en sus primeras sesiones de edición.
Recuerde imprimirla y llevarla consigo a la evaluación de esta práctica.

Elija de los anteriores el tutorial que prefiera, y no se conforme con estudiar solo uno de ellos.

### Funciones
Asegúrese de saber cómo realizar en vim cada una de las tareas que se exponen a continuación.
Si no obtiene la información necesaria en alguno de los tutoriales, también es un buen recurso
consultar
[Stackoverflow](https://stackoverflow.com/questions/tagged/vim)
donde podrá hallar multitud de preguntas/respuestas sobre el editor.

Estas son algunas de las tareas que debe ser capaz de realizar en vim.
Subraye o marque de algún modo cada una de ellas en su copia de la 
[Vim Quick Reference Card](http://www.cheat-sheets.org/saved-copy/vimqrc.pdf)

* Comenzar la edición de un fichero de texto en vi usando la ruta (path) absoluta del fichero
* Desplazarse dentro del fichero en todas las direcciones (líneas arriba/abajo y derecha/izquierda dentro de
  cada línea
* Desplazarse al final/principio (primera/última línea) del fichero
* Desplazarse en una línea de texto a la izquierda/derecha avanzando de palabra en palabra
* Abandonar la edición del fichero de diferentes modos: habiendo grabado (escrito) la sesión o sin grabar

