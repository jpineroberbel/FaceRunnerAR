# 📱 Proyecto Final – Face Runner (Unity + AR Foundation)

## 🎯 Objetivo del proyecto
Desarrollar un **juego de tipo Endless Runner** en **Realidad Aumentada** utilizando **Unity y AR Foundation**, en el que el jugador controle al personaje **mediante los movimientos de su cara**, haciendo uso de **face tracking** con la cámara frontal del dispositivo.

El objetivo del juego es **avanzar el mayor tiempo posible**, evitando enemigos y obstáculos, y recogiendo objetos que otorguen puntos.

---

## 🕹️ Descripción general del juego

*Face Runner* es un juego en tercera persona donde:

- El personaje avanza automáticamente hacia delante.
- El jugador **no utiliza botones ni joystick**, sino que controla al personaje con su **cara**.
- El escenario se desplaza o se genera de forma continua (estilo endless runner).
- Aparecen enemigos y objetos coleccionables a lo largo del recorrido.

---

## 😃 Sistema de control (Face Tracking)

El control del personaje se realiza exclusivamente mediante **movimientos faciales**, detectados mediante **AR Face Tracking**.

### Controles obligatorios
- 👈 **Mover a la izquierda**: inclinación de la cabeza hacia la izquierda.
- 👉 **Mover a la derecha**: inclinación de la cabeza hacia la derecha.
- ⬆️ **Saltar**: gesto facial (a elegir por el alumno):
  - Abrir la boca  
  - Levantar las cejas  
  - Parpadear ambos ojos  

> 🔧 El gesto seleccionado para el salto debe justificarse y funcionar correctamente.

---

## 🧍 Player (Jugador)

El personaje debe contar con:

- Movimiento automático hacia delante.
- Movimiento lateral limitado (izquierda / derecha).
- Capacidad de salto.
- Sistema de colisiones activo.

### Requisitos técnicos
- Uso de `Rigidbody` y/o `CharacterController`.
- Animaciones básicas (opcional pero recomendable).
- Respuesta fluida a los gestos faciales.

---

## 👾 Enemigos y obstáculos

Durante la partida aparecerán:

- **Enemigos u obstáculos** que el jugador debe evitar.
- Si el jugador colisiona con un enemigo:
  - El juego termina (*Game Over*), **o**
  - Se resta una vida (opcional).

### Requisitos
- Al menos **un tipo de enemigo u obstáculo**.
- Aparición o movimiento automático.
- Colisiones correctamente configuradas.

---

## ⭐ Objetos coleccionables

A lo largo del recorrido aparecerán objetos que:

- Se recojan al colisionar con el jugador.
- Incrementen la **puntuación**.

### Opcional (mejora de nota)
- Diferentes tipos de objetos con distintos valores.
- Efectos visuales y/o sonoros al recogerlos.

---

## 🧮 Sistema de puntuación

El juego debe incluir:

- Un **contador de puntos** visible en pantalla.
- Aumento de puntuación al recoger objetos.

### Opcional
- Puntos por tiempo de supervivencia.
- Sistema de récords (*High Score*).

---

## 🖥️ Interfaz de usuario (UI)

La interfaz debe incluir como mínimo:

- Visualización de la puntuación.
- Pantalla de **Game Over**.
- Botón de **Reiniciar** o **Volver a jugar**.

### Opcional
- Pantalla de inicio.
- Instrucciones breves sobre los gestos faciales.

---

## 🧑‍💻 Requisitos técnicos obligatorios

- Proyecto desarrollado en **Unity**.
- Uso de **AR Foundation**.
- Uso de **AR Face Manager**.
- Control del personaje mediante **datos de face tracking** (rotación de cabeza y/o *blend shapes*).
- Proyecto funcional en un **dispositivo móvil compatible** (Android o iOS).
- Código organizado y comentado.

---

## 📦 Entregables

El alumnado deberá entregar:

1. Proyecto completo de Unity.
2. APK / build del juego (si es posible).
3. Documento breve (PDF o TXT) explicando:
   - Gestos faciales utilizados.
   - Sistema de control del jugador.
   - Funcionalidades extra implementadas.

---

## 🚀 Resultado esperado

Al finalizar el proyecto, el alumno habrá desarrollado un **juego completo en Realidad Aumentada**, aplicando **face tracking**, integrando lógica de juego, interacción natural y diseño de experiencia de usuario.
