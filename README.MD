# 🔬 Quiz de Ciencias — 4to Año MEP

Quiz interactivo sobre **El Cuerpo Humano** para estudiantes de 4to año de escuela (MEP - Costa Rica).

## 📚 Contenido del Quiz

El quiz contiene **30 preguntas** distribuidas en 5 secciones:

1. **La Célula** — Estructura, partes y formas
1. **Niveles de Organización** — Célula → Tejido → Órgano → Sistema → Organismo
1. **Sistema Respiratorio** — Órganos, proceso de respiración y enfermedades
1. **Sistema Circulatorio** — El corazón, venas, arterias y capilares
1. **La Sangre y la Inmunidad** — Glóbulos, plaquetas, plasma y tipos de inmunidad

## ✨ Características

- ✅ 30 preguntas mezcladas: opción múltiple, verdadero/falso y completar
- 📊 Barra de progreso en tiempo real
- 🎯 Resultados al final con puntuación y porcentaje
- 💡 Explicaciones detalladas para cada pregunta
- 🔄 Opción de reintentar el quiz
- 📱 Diseño responsive (funciona en celular, tablet y computadora)
- 🚀 Sin dependencias — solo HTML, CSS y JavaScript puro

## 🌐 Cómo publicar en GitHub Pages

1. Creá un nuevo repositorio en GitHub (por ejemplo: `quiz-ciencias-4to`)
1. Subí el archivo `index.html`
1. Andá a **Settings → Pages**
1. En **Source**, seleccioná la rama `main` y la carpeta `/root`
1. Guardá los cambios. En unos minutos, tu quiz estará disponible en:
   `https://tu-usuario.github.io/quiz-ciencias-4to/`

## 🎨 Personalización

El quiz está diseñado con variables CSS, por lo que es fácil cambiar colores. Buscá la sección `:root` en el archivo `index.html`:

```css
:root {
  --accent: #e63946;    /* Color principal (rojo) */
  --success: #2a9d8f;   /* Color de respuestas correctas */
  --warn: #f4a261;      /* Color secundario */
  /* ... */
}
```

## 📖 Para agregar más preguntas

Abrí `index.html` y buscá el array `questions`. Cada pregunta tiene esta estructura:

```javascript
{
  type: "multiple",           // "multiple", "truefalse" o "fill"
  question: "¿Tu pregunta?",
  options: ["A", "B", "C", "D"],  // solo para "multiple"
  correct: 1,                 // índice (multiple), true/false o array de respuestas (fill)
  explanation: "Explicación..."
}
```

## 📝 Licencia

Material educativo de libre uso para fines académicos.

-----

Hecho con 💛 para reforzar el aprendizaje de Ciencias Naturales.
