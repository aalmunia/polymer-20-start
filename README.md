# Primeros pasos con Polymer

Este proyecto ha sido creado a partir del que está en https://github.com/PolymerLabs/polymer-2-first-element, modificándolo y trasteando
con ello para poder aprender mas sobre Polymer. La documentación original del proyecto / tutorial está en https://www.polymer-project.org/2.0/start/first-element/intro

## Ejecutando el código

1. Descarga Node de la página https://nodejs.org/, viene con npm incluído, que es el gestor de dependencias de node y entornos de desarrollo JavaScript, aunque también está bower (to-do: Quitar, si es posible, Bower del entorno de desarrollo de esta app)

2. Si no los tienes instalados ya, instalar bower y polymer-cli:

        npm install -g bower polymer-cli

3. Instala las dependencias del proyecto con bower, en la carpeta del proyecto:

        bower install

4. Sirve y abre la aplicación (en el navegador por defecto)

        polymer serve --open

5. El navegador debería estar apuntando a localhost:8080/components/icon-toggle/demo/
