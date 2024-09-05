# Reto 01: Creando una casa simple

<p> Una de las ventajas de esta actividad es que, aunque es relativamente simple, te brinda la oportunidad de equivocarte y es un buen reto para comenzar a coordinar la comunicación entre todos los miembros del equipo ?????.
Poder tener esa estructura en el orden en que se deben hacer las cosas para facilitar el resultado final y también que cada miembro del grupo pueda tener un rol importante en la creación del proyecto. Además, es interesante ver cómo se pueden crear estructuras complejas utilizando figuras más simples. Nos da la curiosidad de ver si pudiésemos crear un videojuego entero utilizando solamente cubos (de hecho, ¡ya se ha logrado!)</p>

<h2> Construcción de paredes
  </h2>

<p>Utilizamos <code>Cube 3D Objects</code> y le aplicamos traslaciones, escalamientos y rotaciones.</p>
<p>Para la <strong>parte frontal izquierda</strong>, creamos un cubo y escalamos sus tres componentes para que obtuviera la forma de un prisma rectangular. Luego, se realizó una traslación.</p>
<image
  src="LeftFront.png"
  width = 90%;
  height = 550px>

<p>La <strong>parte frontal derecha</strong> fue una simple copia del pedazo que ya se había creado. Se duplicó y realizamos una traslación.</p>
<image
  src="RightFront.png"
  width = 90%;
  height = 550px>

<p>Para la <strong>parte frontal con marco</strong> para la puerta de entrada, copiamos el pedazo frontal izquierdo y escalamos su componente en Y para que tuviese menos altura. Luego, se trasladó verticalmente para estar alineado con los otros dos muros.</p>
<image
  src="FrameFront.png"
  width = 90%;
  height = 550px>

  
<h3> Pared de la izquierda </h3>
<p>Para las <strong> paredes laterales</strong>  igualmente utilizamos  <code>Cube 3D Objects</code> y le aplicamos traslaciones, escalamientos y rotaciones. Tuvimos que alinearlas justo con la parte frontal para que no hubiera ningún espacio de separación y se forme la figura deseada. Este alineamiento se hizo utilizando las herramientas que aparecen en la parte superior derecha en donde Unity nos permite una vez seleccionado el objeto en cuestión ajustar sus coordenadas.</p>

<image
  src="LeftWall.png"
  width = 90%;
  height = 550px>


<h3> Pared de la derecha</h3>
<p>Para el caso de la <Strong> segunda pared lateral (derecha) </Strong> se tomó la iniciativa de copiar y pegar la pared lateral previamente hecha y trasladarla a justo el lado que hacía falta. Para trasladarla se usó la misma idea de ajustar sus coordenadas</p>


  <image
  src="RightWall.png"
  width = 90%;
  height = 550px>

<h3> Alargamiento de paredes y construcción de la pared de fondo</h3>
<p> <Strong>El Alargamiento de paredes y construcción de la pared de fondo </Strong> funcionó en su mayoría de la misma manera pues utilizando las opciones de <code>Scale</code>, que está justo debajo de la herramienta de traslación, entonces se ajustó el tamaño de cada pared para que la casa no fuera plenamente cuadrada sino que en el interior hubiera un espacio rectangula</p>



  <image
  src="Walls.png"
  width = 90%;
  height = 550px>


  


  
