# Física 1 — Entrenador IA

Entrenador interactivo de Física 1 para estudiantes universitarios. Podés usarlo **con IA** (necesitás tu propia API Key) o **sin IA** para consultar los resumenes de las fórmulas sin conexión, si es que se tiene descargado el index.html.

Listo para usar online en:
https://fisica-1.vercel.app/

---

## ¿Qué es esto?

Una herramienta de estudio de una sola página (HTML) que cubre temas de Física 1:

Cinemática · Dinámica · Trabajo y Energía · Potencia · Cantidad de Movimiento e Impulso · Choques · Centro de Masa · Rotación de Cuerpos Rígidos · Torque · Trabajo y Potencia en la Rotación · Rodamiento sin deslizamiento · Cantidad de Movimiento Angular · Hidrostática · Hidrodinámica · Movimiento Armónico · Óptica

---

## Modos de uso

### Sin IA (Solo Formulas)
No necesitás cuenta ni API Key. Accedés directamente a los resumenes de las fórmulas de cada tema: fórmulas detalladas, descripción de variables y consejos clave. Funciona sin conexión una vez que cargó la página.

### Con IA (Entrenador interactivo)
Necesitás una API Key de alguno de los proveedores soportados. La IA actúa como un entrenador que te explica, te da ejercicios y te hace preguntas para testear si entendiste.

Tres modos por tema:
- **EXPLICAR** — teoría clara con fórmulas y ejemplos
- **EJERCICIO** — ejercicio numérico resuelto paso a paso
- **QUIZ** — la IA te pregunta y corrige tu respuesta

Cuando dominás un tema, la IA lo marca como completado y suma a tu racha.

Para modificar el prompt que le da la instrucción al LLM, buscar la función: ```function sysPrompt()``` 

---

## Proveedores de IA soportados

| Proveedor | Modelo | Costo |
|---|---|---|
| 🟠 Anthropic | claude-sonnet-4 | Pago (créditos gratis al registrarse) |
| ⚪ OpenAI | gpt-4o-mini | Pago |
| 🔵 Google Gemini | gemini-2.0-flash | **Gratis** |
| 🟣 Meta / Groq | llama-3.3-70b | **Gratis** |
| ⚫ xAI Grok | grok-3-mini | Requiere X Premium |

**Recomendación:** Gemini o Groq son gratuitos.

Dónde conseguir cada key:
- Anthropic: [console.anthropic.com/keys](https://console.anthropic.com/keys)
- OpenAI: [platform.openai.com/api-keys](https://platform.openai.com/api-keys)
- Gemini: [aistudio.google.com/apikey](https://aistudio.google.com/apikey)
- Groq: [console.groq.com/keys](https://console.groq.com/keys)
- xAI: [console.x.ai](https://console.x.ai)

---

## Privacidad

- Tu API Key se guarda **solo en tu navegador** (localStorage). Nunca se envía a ningún servidor de esta app.
- El historial de conversaciones también es local — solo vos lo ves.
- Las llamadas a la IA van directo desde tu navegador al proveedor que elegiste.
- Podés borrar el historial en cualquier momento desde el botón dentro de la app.

---

## Créditos

- En este proyecto se ha utilizado IA (Claude de Anthropic). Se generó el código, los resumenes de fórmulas y el diseño de la interfaz.
- Intervine para agregar algunas formulas y modificar algunos detalles del diseño.
- Construido con HTML, CSS y JS puro — sin frameworks ni dependencias externas. 

