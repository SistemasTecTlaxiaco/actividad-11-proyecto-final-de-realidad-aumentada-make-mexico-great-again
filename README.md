# 🤖 Proyecto de Realidad Aumentada: Robot Motivacional

Este proyecto es una experiencia interactiva en Realidad Aumentada (AR) desarrollada con **Three.js** que muestra un robot 3D capaz de emitir **frases motivacionales** de manera dinámica. El entorno se proyecta utilizando la **cámara trasera del dispositivo**, creando una interacción inmersiva directamente en el navegador web.

## 🌟 Características

- 🎥 Fondo de video en tiempo real usando la cámara trasera del dispositivo.
- 🤖 Carga e integración de modelo 3D `.gltf` con animación básica.
- 💬 Frases motivacionales que cambian automáticamente cada 5 segundos.
- 📦 Posicionamiento del texto dinámico en relación con la boca del modelo 3D.
- 🌐 Todo el contenido corre directamente en el navegador sin instalaciones.

## 🛠️ Requisitos

- Navegador moderno compatible con WebGL y acceso a la cámara (Chrome recomendado).
- Permisos de cámara activados.
- Servidor local (opcional pero recomendado): puedes usar [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) en VS Code o correr con:

  ```bash
  npx serve .
🚀 Cómo usar
Clona este repositorio:

bash
Copiar
Editar
git clone https://github.com/tuusuario/robot-motivacional-ar.git
cd robot-motivacional-ar
Coloca el archivo del modelo scene.gltf en la raíz del proyecto.

Abre el archivo index.html en un navegador moderno.

Es recomendable abrirlo desde un servidor local para evitar problemas de permisos con la cámara. Puedes usar:

bash
Copiar
Editar
npx serve .
o el plugin Live Server en VS Code.

Permite el acceso a la cámara cuando el navegador lo solicite.

¡Listo! Verás el robot con frases motivacionales en tiempo real sobre el entorno capturado por tu cámara.

💬 Frases motivacionales incluidas
"¡Sigue adelante, nunca te rindas!"

"¡Eres más fuerte de lo que piensas!"

"¡Cada día es una nueva oportunidad!"

"¡La perseverancia te llevará lejos!"

"¡Cree en ti mismo y en tus sueños!"

📸 Vista previa
