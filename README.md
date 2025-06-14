# 🧠 Mini Reto JS - Rick and Morty Card Gallery

Este proyecto es una actividad práctica de 20 minutos diseñada para reforzar los siguientes conceptos de JavaScript:

- Consumo de API con `fetch`
- Uso de `async` / `await`
- Manipulación del DOM
- Manejo de eventos
- Event bubbling

---

## 🎯 Objetivo

Consumir la API pública de **Rick and Morty** y mostrar en pantalla todas las tarjetas de personajes que cumplan con las siguientes condiciones:

- `species` debe ser `"Human"`
- `status` debe ser `"Alive"`
- Solo se debe mostrar la **primera página** de resultados

---

## 💻 ¿Qué tienes que hacer?

1. Al dar clic en el botón “Cargar Humanos Vivos”, se deben obtener los personajes desde la API.
2. Insertar dinámicamente una tarjeta por personaje dentro del contenedor principal.
3. Cada tarjeta debe mostrar:
   - Nombre
   - Género
   - Origen
   - Ubicación
   - Imagen
4. Se debe escuchar clics sobre las tarjetas usando **event bubbling**, y al hacer clic en una, se mostrará su nombre en la consola.

---

## 🗂 Estructura del proyecto

```bash
.
├── reto.html       # Estructura base con el botón y contenedor para tarjetas
├── style.css       # Estilos listos para usar, incluye diseño de tarjeta
├── script.js       # Tu lógica en JavaScript (archivo que vas a modificar)
├── Actividad.html  # Archivo para trabajar en clase
└── README.md       # Instrucciones del reto
