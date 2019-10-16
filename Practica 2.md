---


---

<h2 id="práctica-2">PRÁCTICA 2</h2>
<ol>
<li>Definir constantes</li>
<li>Definir numero de páginas para todos los registros</li>
<li>Encontrar el tamaño de la fila</li>
<li>Encontrar el tamaño de página</li>
<li>Encontrar el tamaño de la B.D</li>
</ol>
<pre><code>#include &lt;iostream&gt; 
using namespace std; 
int main (){ 
int tamanoFila;
int tamanoPagina;
int totalBase; 
//Base da datos de una biblioteca 
//Estudiantes 
int NoCuenta = 8;//String PK 
int Nombre = 8; //String 
int ApellidoPaterno = 8;
int ApellidoMaterno =8; 
int Edad = 4; 
//Carrera 
int idCarrera=8; //String PK 
int NombreCarrera = 8; 
//Campus
int idCampus=8;//String PK 
int NombreCampus = 8; 
//Ciudad
int idCiudad = 8; 
int NombreCiudad=8; 
int telefono = 8; 
//Prestamo 
int FechaPrestamo= 3;//Date 
int FechaEntrega = 3;//Date
//Libro
int idLibro=8; 
int Titulo = 8; 
int Ano=4; 
//Autor
int NombreAutor = 8; 
int ApellidoPaterno_A=8; 
int ApellidoMaterno_A=8; 
tamanoFila = (2*4)+(17*8)+(2*3); 
printf("\n Tamaño fila en bytes: %i\n",tamanoFila);
tamanoPagina = (tamanoFila*100); 
printf("\n Tamaño pagina en bytes: %i\n",tamanoPagina); totalBase = (tamanoPagina*20000); 
printf("\n Tamaño base de datos en bytes: %i\n",totalBase); return 0; 
 }```
https://drive.google.com/file/d/19bCUJALqRbH1NqdC_o-f0HB_Roods3PA/view?usp=sharing 

&gt; Written with [StackEdit](https://stackedit.io/).
</code></pre>

