# Reto: Paint 3D
## Descripción
En equipos, implementar una App Gráfica 3D interactiva de un Paint de modelos 3D, con las siguientes características:

1. La posibilidad de seleccionar hasta 10 modelosdiferentes **20 pts** 
2. Los modelos 3D no pueden ser primitivas de THREEJS, sino que deben ser geometrías propietarias: una pirámide, una caja, una casita,etc. **20 pts** [x]
3. La funcionalidad del Paint3D es básica:
    1. El usuario usa la interfaz gráfica para seleccionar un modelo y ubicarlo en la escena (posición y orientación) **10 pts**
    2. El usuario puede ubicar en la escena más de un mismo tipo de modelo **10 pts**
    3. El usuario debe poder aplicar la siguiente funcionalidad a toda la escena:
        * Visualizar todos los modelos de la escena 3D como wireframe o sólido **5 pts**  [x]
        * Cambiar el color del fondo (el color de borrado del framebuffer) **5pts** [x]
        * Visualizar/ocultar el piso en z = 0 (se puede usar THREE.PlaneGeometry) **5 pts** [x]
        * Visualizar/ocultar el panel de estadísticasde desempeño (fps, tiempo y memoria)  **5 pts** [x]
    4. El usuario debe poder aplicar la siguiente funcionalidad a cada objeto de la escena:
        * Su ubicación (posición y orientación) **5 pts**
        * Su visualización como wireframe o sólido **5 pts**
        * Su color de dibujo **5 pts**
        * Su transparencia **5 pts**

Subir a Canvas archivo index.html