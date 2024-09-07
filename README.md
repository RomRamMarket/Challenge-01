# Reto 01: Creando una casa simple

<p> Una de las ventajas de esta actividad es que, aunque es relativamente simple, te brinda la oportunidad de equivocarte y es un buen reto para comenzar a coordinar la comunicación entre todos los miembros del equipo. Nos permite poder implementar una estructura de trabajo en equipo que nosotros mismos decidimos y ajustamos. Poder tener esa estructura del orden en que se deben hacer las cosas sirve para facilitar el resultado final y también que cada miembro del grupo pueda tener un rol importante en la creación del proyecto. Además, nos pareció interesante ver cómo se pueden crear estructuras complejas utilizando figuras más simples. Nos da la curiosidad de ver si pudiésemos crear un videojuego entero utilizando solamente cubos (de hecho, ¡ya se ha logrado!). El construir algún concepto con cubos es una buena manera de explorar la creatividad y conocer las herramientas que nos da Unity. Tuvimos muchas complicaciones con Unity Version Control, pues creamos el proyecto para trabajar todos en equipo, pero por alguna razón aunque el proyecto estaba conectado a Unity Version Control y todos teniamos los permisos dentro de la organización, sucedía que el proyecto nunca se podía acceder a través de Unity Hub, haciendo imposible la colaboración desde distintos lugares.</p>

<h2>Evidencia de proyectos en la organización</h2>

<image
  src="org.png"
  width = 90%
  height = 90%>


  <h2>Evidencia de que en Unity Hub no aparecen los proyectos creados</h2>

<image
  src="UVC.png"
  width = 90%
  height = 90%>





<h2> Construcción de paredes
  </h2>

<p>Utilizamos objetos cúbicos en Unity y le aplicamos traslaciones, escalamientos y rotaciones.</p>
<p>Para la <strong>parte frontal izquierda</strong>, creamos un objeto <code>Cube</code> (que se encuentra bajo <code>GameObject</code> --> <code>3D Object</code>) y escalamos sus tres componentes para que obtuviera la forma de un prisma rectangular. Luego, se realizó una traslación (utilizando los botones visuales o "flechas" que nos proporciona el motor de videojuegos).</p>
<image
  src="LeftFront.png"
  width = 90%
  height = 90%>

<p>La <strong>parte frontal derecha</strong> fue una simple copia del pedazo que ya se había creado. Se duplicó y realizamos una traslación. Para duplicarlo seleccionamos el objeto que queremos duplicar, presionamos click derecho y seleccionamos la opción de <code>Duplicate</code>. </p>
<image
  src="RightFront.png"
  width = 90%
height = 90%>

<p>Para la <strong>parte frontal con marco</strong> para la puerta de entrada, copiamos (de la manera antes explicada) el pedazo frontal izquierdo y escalamos su componente en Y para que tuviese menos altura. Luego, se trasladó verticalmente para estar alineado con los otros dos muros.</p>
<image
  src="FrameFront.png"
  width = 90%
  height = 90%>

  
<h3> Pared de la izquierda </h3>
<p>Para las <strong> paredes laterales</strong>  igualmente utilizamos objetos <code>Cube</code> y le aplicamos traslaciones, escalamientos y rotaciones. Tuvimos que alinearlas justo con la parte frontal para que no hubiera ningún espacio de separación y se formara la figura deseada. Este alineamiento se hizo utilizando las herramientas que aparecen en la parte superior derecha en donde Unity nos permite, una vez seleccionado el objeto en cuestión, ajustar sus coordenadas.</p>

<image
  src="LeftWall.png"
  width = 90%
height = 90%>


<h3> Pared de la derecha</h3>
<p>Para el caso de la <Strong> segunda pared lateral (derecha) </Strong> se tomó la iniciativa de duplicar la pared lateral previamente hecha y trasladarla a justo el lado que hacía falta. Para trasladarla, se usó la misma idea de ajustar sus coordenadas.</p>


  <image
  src="RightWall.png"
  width = 90%
height = 90%>

<h3> Alargamiento de paredes y construcción de la pared de fondo</h3>

<p> <strong>El alargamiento de paredes y construcción de la pared de fondo </strong> funcionó en su mayoría de la misma manera, pues utilizando las opciones de <code>Scale</code>, que están justo debajo de la herramienta de traslación, entonces se ajustó el tamaño de cada pared para que la casa no fuera plenamente cuadrada, sino que en el interior hubiera un espacio rectangular.</p>

  <image
  src="Walls.png"
  width = 90%
height = 90%>


<h3> Creación inicial del techo</h3>

<p>Primero creamos un <code>Cube</code> para nuestra primera parte del techo.</p>

  <image
  src="CreateRoof.png"
  width = 90%
  height = 90%>


<h3> Ajustar tamaño del techo</h3>

  <p> Luego, seleccionando nuestro cubo antes creado, fuimos "tanteando" con la función <code>Scale</code> situada a la derecha de nuestra pantalla hasta que el cubo tenía una forma adecuada para ser el techo de una casa como esperábamos construirla.</p>

  <image
  src="RoofScale.png"
  width = 90%
  height = 90%>


<h3> Manipular su inclinación</h3>

<p> Luego, seleccionamos el <code>Transformation Tool</code> en el centro de la escena para poder manipular la rotación de nuestro techo y hacer que se parezca aún más a un techo en cuestión de su inclinación.</p>


   <image
  src="RotationRoof.png"
  width = 90%
  height = 90%>


<h3>Duplicar el trabajo</h3>

 <p>Una vez satisfechos con el tamaño y la inclinación de nuestro techo, vamos a crear la otra parte del techo haciendo clic con el botón derecho del ratón sobre nuestro cubo creado y pulsando Duplicar o <code>Duplicate</code>. Esto hace que nuestros parámetros se copien inmediatamente a este siguiente cubo.</p>

  <image
  src="duplicate.png"
  width = 90%
  height = 90%>

<h3>Ubicando el duplicado en la parte necesaria</h3>

<p> Ajustando los parámetros de posición y rotación encontrados en la parte superior derecha, podemos llegar a que ambas partes del techo se conecten a la perfección como se muestra en la siguiente imagen. Una vez ambas partes estén alineadas, el trabajo está terminado.</p>

  <image
  src="FinalRoof.png"
  width = 90%
  height = 90%>


<h3>Trabajo final</h3>

  <image
  src="FinalHome.png"
  width = 90%
  height = 90%>
  

  

  
