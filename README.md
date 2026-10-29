# 📺 ¡Super Geometría TV! 📐 — Clasificación de Triángulos y Cuadriláteros (Edición Smart TV LG)

Aplicación web interactiva contenida en **un único archivo HTML (`index.html`)**, lista para publicar en **GitHub Pages** y diseñada específicamente para verse en el navegador de una **Smart TV LG (webOS)** para un niño de **9 años (4.º de Educación Primaria)**.

Incluye íntegramente todos los términos, definiciones y ejercicios prácticos de las **dos fichas escolares de clase** (Clasificación de Triángulos y Clasificación de Cuadriláteros).

---

## ✨ ¿Qué puede hacer este programa?

### 1. Juego Alterno en cada Ronda (Nombre ↔ Figura + Tabla Práctica)
El juego alterna automáticamente la dinámica pregunta tras pregunta para que el niño nunca se aburra y domine tanto el vocabulario como el reconocimiento visual:
- **Rondas Impares — "¿Cómo se llama esta figura?" (Ves el Dibujo ➔ Eliges el Nombre)**:
  - Muestra en una pizarra gigante el polígono con sus marcas geométricas (rayitas en lados iguales, cuadradito verde de `90º` en ángulos rectos, arcos de ángulos y flechas `>>` en lados paralelos).
  - El niño elige el **nombre correcto** entre 4 botones grandes.
- **Rondas Pares — "¡Busca el Dibujo!" (Ves el Nombre ➔ Eliges la Figura)**:
  - El enunciado superior pide encontrar una figura por su nombre (por ejemplo: *"¿Cuál de estas figuras es un ROMBOIDE?"* o *"Encuentra el TRAPECIO RECTÁNGULO"*).
  - Se muestran **4 pizarras con dibujos diferentes** en una cuadrícula `2x2` para elegir el dibujo correcto con el puntero del mando de la tele.
- **Rondas Especiales — "⭐ Practico de la Ficha (Doble Clasificación de Triángulos)"**:
  - Reproduce el cuadro inferior `"PRACTICO: Clasifica los siguientes triángulos según sus lados y ángulos"` de la primera ficha escolar, donde el niño clasifica un mismo triángulo eligiendo su tipo por **LADOS** (*Equilátero, Isósceles o Escaleno*) y por **ÁNGULOS** (*Acutángulo, Rectángulo u Obtusángulo*).

---

### 2. Temario Completo de las 2 Hojas del Colegio
Desde el menú principal se puede elegir practicar **Todo Mezclado** o por separado:

#### 🔺 Hoja 1: Clasificación de Triángulos
1. **Según la longitud de sus lados**:
   - **Equilátero**: Tres lados miden lo mismo.
   - **Isósceles**: Dos lados miden lo mismo.
   - **Escaleno**: Ningún lado mide lo mismo.
2. **Según la amplitud de sus ángulos**:
   - **Rectángulo**: Un ángulo recto (`90º`).
   - **Acutángulo**: Tres ángulos agudos (`< 90º`).
   - **Obtusángulo**: Un ángulo obtuso (`> 90º`).

#### 🔷 Hoja 2: Clasificación de Cuadriláteros
1. **Paralelogramos** (*los lados son paralelos dos a dos*):
   - **Cuadrado**: 4 lados iguales y 4 ángulos rectos.
   - **Rectángulo**: Lados iguales dos a dos y 4 ángulos rectos.
   - **Rombo**: 4 lados iguales y ángulos iguales dos a dos.
   - **Romboide**: Lados y ángulos iguales dos a dos.
2. **Trapecios** (*sólo tienen dos lados paralelos*):
   - **Trapecio rectángulo**: Un lado no paralelo perpendicular a los lados paralelos (con ángulos rectos).
   - **Trapecio isósceles**: Lados no paralelos iguales.
   - **Trapecio escaleno**: Lados no paralelos desiguales y no perpendiculares.
3. **Trapezoides** (*los lados no son paralelos / ningún lado paralelo*).

---

### 3. Sistema de Vidas (❤️), Puntuación (⭐), Rachas (🔥) y Sonidos (🔊)
- **Vidas configurables**: Permite elegir entre **3 vidas**, **5 vidas** o **Vidas Infinitas** para practicar sin presión.
- **Puntuación y Combos**: Cada acierto suma `+100 puntos` más una bonificación creciente por **racha de aciertos seguidos (`🔥 x2, x3, x4...`)**.
- **Comodín `💡 Pista del Profe`**: Muestra pistas visuales adicionales sobre los lados y ángulos en la pizarra sin perder vidas.
- **Sonidos Musicales Web Audio API**:
  - No necesita archivos MP3 externos: genera en tiempo real fanfarrias de acierto, sonido de pérdida de vida y una **melodía única para cada figura** (ej. 3 notas iguales para el Equilátero, 2 iguales y 1 distinta para el Isósceles, esquina cuadrada para el ángulo de `90º`, etc.).
- **Modo 1 o 2 Jugadores**: Permite jugar en solitario o por turnos en el salón eligiendo avatares de animales (`🦊`, `🐼`, `🦁`, `🐸`, `🦄`, `🦖`...).
- **📖 Chuleta Interactiva de la Ficha**: Un modo de estudio visual donde el niño puede ver todas las figuras de las dos hojas y pulsar sobre ellas para escuchar sus sonidos antes de jugar.

---

### 4. Optimización Especial para Navegador de Televisión LG (webOS)
- **Diseño `16:9` a pantalla completa (`100vw x 100vh`)** sin barras de desplazamiento (`overflow: hidden`).
- **Control con LG Magic Remote o Botones Numéricos**: Se puede jugar apuntando con el puntero del mando o pulsando los botones `1`, `2`, `3`, `4` y `OK / Enter` del mando a distancia.
- **Sin campos `<input>` de texto**: Evita que se abra el teclado virtual en pantalla del televisor LG.

---

## 🚀 Cómo subirlo a GitHub Pages

1. Sube el archivo [`index.html`](file:///c:/Users/elcas/Desktop/APP_Antigravity/Juego_Triangulos_Cuadrilateros_TV/index.html) (y este [`README.md`](file:///c:/Users/elcas/Desktop/APP_Antigravity/Juego_Triangulos_Cuadrilateros_TV/README.md)) a un repositorio de GitHub.
2. Entra en **Settings ➔ Pages**, selecciona la rama `main` y pulsa **Save**.
3. Abre la dirección web generada desde el navegador de tu televisión LG.
