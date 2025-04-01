# threejs-3d-models

Este proyecto utiliza Three.js para renderizar y animar modelos FBX en un entorno 3D. Se han implementado controles de cámara, carga dinámica de modelos y animaciones, así como una interfaz de usuario para modificar parámetros en tiempo real.


El código establece un entorno de visualización 3D con una escena iluminada, una cuadrícula y un plano que simula el suelo. Se permite cargar diferentes modelos FBX, que pueden incluir animaciones y transformaciones morph. Algunas de las principales 
características son:

- Utiliza la biblioteca Three.js para crear una escena 3D, que incluye iluminación, cámaras y objetos interactivos.
  
- Implementación de OrbitControls, que permite al usuario mover la cámara y explorar la escena desde diferentes ángulos.

- Los modelos FBX se cargan dinámicamente usando `FBXLoader`, permitiendo incluir diferentes animaciones y transformaciones.

- Se gestionan las animaciones de los modelos cargados mediante `AnimationMixer`, lo que facilita la reproducción y control de animaciones.

- A través de una interfaz gráfica (GUI), los usuarios pueden ajustar los "morph targets" de los modelos, permitiendo la personalización de sus formas.

- Se utiliza `Stats.js` para mostrar el rendimiento en tiempo real del renderizado y las animaciones, como el número de cuadros por segundo (FPS).
