# 🤖 Colección de AI Skills & System Prompts

Bienvenido a mi repositorio de **System Prompts** (o *Skills*). Aquí recopilo y comparto instrucciones estructuradas y avanzadas para exprimir al máximo modelos de Inteligencia Artificial como Claude, ChatGPT y otros LLMs.

El objetivo de estas *skills* es darle a la IA una "personalidad" definida, un área de conocimiento experta y reglas estrictas de comportamiento. Así pasamos de respuestas genéricas y complacientes a asistentes realmente útiles, rigurosos y profesionales.

---

## 📚 Skills Disponibles

Aquí tienes el índice de los prompts que he diseñado hasta ahora. Haz clic en el archivo para ver el código completo.

| Skill | Descripción | Archivo |
| :--- | :--- | :--- |
| **👨‍🏫 Profesor Experto en DAM** | Transforma a la IA en un docente veterano del grado superior de Desarrollo de Aplicaciones Multiplataforma. Exige *Clean Code*, usa el método socrático para enseñar y domina desde Sistemas Informáticos hasta Android y Spring Boot. | [`profesor-dam.md`](./profesor-dam.md) |
| *(Próximamente...)* | ... | ... |

---

## 🚀 Cómo utilizar estas Skills

Dependiendo de la herramienta que utilices, hay varias formas de "inyectar" estos prompts a tu IA:

### 1. Claude Pro (Projects) - *Recomendado*
Es la forma más potente de usarlos. 
1. Crea un nuevo *Project* en Claude.
2. Ve a la sección **Custom Instructions**.
3. Pega el contenido completo del archivo `.md` correspondiente. 
4. Todo el chat dentro de ese proyecto asumirá ese rol por defecto.

### 2. Chat normal (Claude Gratis / ChatGPT)
La forma más rápida si no tienes versiones de pago.
1. Abre el archivo `.md` de la skill que quieras.
2. Copia todo el texto.
3. Pégalo en tu **primer mensaje** del chat y añade al final: *"Por favor, adopta este rol e instrucciones a partir de ahora para toda la conversación."*

### 3. ChatGPT Plus (Custom GPTs)
Si prefieres el ecosistema de OpenAI.
1. Ve a **Explore** > **Create a GPT**.
2. Ve a la pestaña **Configure**.
3. Pega todo el contenido del archivo `.md` en la caja de **Instructions**.

### 4. Entornos de Desarrollo o API
Si programas tus propias integraciones (con Python, Node.js, Cursor, etc.).
1. Descarga el archivo `.md` a tu entorno local.
2. Haz que tu código lea el archivo y pase el texto completo dentro del parámetro `system` en tu llamada a la API de Anthropic o OpenAI.

---
💡 *Si estos prompts te resultan útiles para tus estudios o trabajo, ¡no dudes en darle una ⭐ a este repositorio!*
