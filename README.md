# 23.02.2026_Flujos-de-Entrada-Salida-Ficheros

1. Diseña un programa Java que cree un archivo en el que se guarde una cadena cualquiera
carácter a carácter.

2. Diseña un programa Java que genere un archivo en el que se guarden las cadenas existentes
en un arrayList de tipo String.

3. Diseña un programa Java que solicite palabras (sin espacios) al usuario (método next() de
Scanner) y las guarde en un archivo. El proceso de petición finaliza cuando el usuario teclee
“fin”, que no debe escribirse en el archivo.

4. Diseña un programa que lea el archivo de código fuente que está implementando
(Principal.java), que no deja de ser un archivo de texto, y lo muestre por consola carácter a
carácter.
a) Implementa este programa haciendo uso de la clase FileReader.
b) Implementa este programa haciendo uso de las clases FileReader + BufferedReader.
5. Implementa un programa que guarde en un fichero de texto
En un lugar de la Mancha,
de cuyo nombre no quiero acordarme.
La primera línea debe guardarse carácter a carácter, y la segunda, en una sola sentencia.

6. Escribir un programa que duplique el contenido de un fichero cuyo nombre se pide al usuario.
El fichero copia tendrá el mismo nombre con el prefijo “copia_de_”.

7. Crea un fichero de texto NumerosRealex.txt y escribe en él varios números decimales
separados por espacios simples. Implementa un programa que acceda a dicho fichero, lea los
números y calcule la suma de ellos y la media aritmética, mostrando los resultados por
pantalla.

8. Crea un fichero de texto llamado Enteros.txt que incluya varios números enteros separados
por distintas secuencias de espacio y tabulaciones, incluso en distintas líneas. Implementa un
programa que lea dicho fichero, lea los números y calcule la suma de ellos y la media
aritmética, mostrando los resultados por pantalla.

9. Escribe un programa que lea un archivo carta.txt y cuente los caracteres, las palabras y las
líneas que contiene el fichero. Para simplificar, supondremos que cada palabra está separada
de la otra por un espacio simple o por un cambio de línea (\n).

10. Diseña un programa Java que tenga una clase ManejadorDeFicheros que tenga 3 métodos que
permitan (implementa también una clase Principal que pruebe la clase anterior):
a) Leer líneas de un archivo de texto cualquiera y guardarlas en un arrayList.
b) Ordenar el arrayList
c) Volver a escribir las palabras en el archivo.
ManejadorDeFicheros
+ palabras : List<String>
+ ManejadorDeFicheros()
+ leeArchivoTXT(String ruta) : void
+ ordenaPalabras() : void
+ imprimirPalabras() : void

11. A partir del siguiente archivo: https://drive.google.com/file/d/1jPMZxpvRY-hXSzZz-MbYlDNkx6YSWjRR/view
Diseña una aplicación que busque cadenas de texto en el mismo. La salida debe ser como la de
la imagen:

12. Crea un fichero Jugadores.txt con información del siguiente tipo (nombre edad estatura):
Implementa un programa Java que lea los datos del fichero, muestre los nombres y calcula la
edad media y la estatura media, mostrándolas por pantalla
