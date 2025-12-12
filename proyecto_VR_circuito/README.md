# Simulador de Coches VR

## Descripción del Proyecto
Este proyecto es un simulador de coches en **realidad virtual** desarrollado en HTML y A-Frame. Permite al usuario explorar un **circuito en 360°**, interactuar con un **box de mecánicos**, cambiar coches, escuchar sonidos de motor y ver trofeos y decoración del entorno.

El proyecto está dividido en cuatro escenas principales:

1. **Pantalla de inicio (`index.html`)**: Página principal con presentación del proyecto y botón de acceso al simulador.
2. **Circuito 360° (`escena-1-circuito.html`)**: Escena inmersiva que permite al usuario visualizar un circuito de carreras en 360 grados con sonido ambiental y un portal hacia el box.
3. **Box de mecánicos (`escena-2-box.html`)**: Escena interactiva donde el usuario puede cambiar de coche, escuchar el motor, ver trofeos, pedestales y otros elementos decorativos del box.
4. **Simulador de carrera**: Esta escena donde se ve el coche en movimiento con un velocimetro en tiempo real

---

## Tecnologías Utilizadas

- **HTML5 / CSS3**: Estructura y estilos de las páginas.
- **A-Frame (VR)**: Creación de escenas en 3D y VR.
- **JavaScript**: Componentes interactivos para:
  - Cambiar el modelo de coche.
  - Reproducir sonidos (motor y música).
  - Mostrar información de trofeos.
  - Portal para cambiar de escena.
- **Assets 3D**: Modelos `.gltf` de coches, trofeos, pedestales, mesas, ruedas y decoración.
- **Assets multimedia**: Imágenes, texturas, sonidos de ambiente y motor.

---

## Estructura del Proyecto
proyecto_VR_circuito/
│
├── index.html # Página principal / menú del simulador
├── escena-1-circuito.html # Escena 1: Circuito 360° con imagen esférica y sonidos ambientales
├── escena-2-box.html # Escena 2: Box de mecánicos, coches y trofeos interactivos
├── escena-3-circuito.html # Escena 3: Circuito, ambiente de gradas y coche en movimiento
│
├── assets/ # Carpeta con todos los recursos del proyecto
│ ├── 360/ # Imágenes 360° para la escena del circuito
│ ├── images/ # Logos, fondos, cuadros, etc.
│ ├── models/ # Modelos 3D (coches, mesas, trofeos, pedestales, etc.)
│ ├── sounds/ # Sonidos (motor, música, ambiente, aceleración)
│ └── textures/ # Texturas para suelos, paredes y techo
│
└── README.md # Documentación del proyecto (este archivo)

---

## Funcionalidades

### `index.html`
- Presenta el proyecto y autoría.
- Botón de acceso al simulador VR.

### `escena-1-circuito.html`
- Imagen 360° del circuito con sonido ambiental.
- Sonido de aceleración periódica.
- Portal interactivo para ir a la escena del box.
- Texto flotante animado indicando la acción.

### `escena-2-box.html`
- **Coches interactivos**: Puedes elegir entre varios modelos usando botones.
- **Sonido del motor**: Pulsando un botón reproduce un motor.
- **Trofeos interactivos**: Al pulsar muestran información en un panel.
- **Decoración**: Pedestal, mesa de trofeos, cuadro, descanso, imagen de marcas, coches de exposición.
- **Interactividad adicional**: Reproducir música, paneles que miran a la cámara automáticamente.

### `escena-3-circuito.html` 
- Coche simulado en movimiento por la pista.  
- Panel de velocidad en tiempo real.  
- Gradas y entorno 3D para mayor realismo.  

---

## Cómo ejecutar

1. Clonar o descargar el repositorio.
2. Abrir `index.html` en un navegador compatible con A-Frame.
3. Navegar usando mouse o VR para interactuar con el circuito y el box.
4. Explorar las distintas escenas y probar la interactividad.

---

## Autores

- **David Garrido** - 1ºDAM  
- **Mario Lopez** - 1ºDAM  
