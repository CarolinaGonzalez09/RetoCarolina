# Proyecto TypeScript con Playwright y Screenplay

## Exportar el proyecto desde GitHub

1. *Clonar el repositorio desde GitHub:*
   - Abre tu terminal (o línea de comandos).
   - Utiliza el comando git clone seguido de la URL del repositorio de GitHub para clonar el proyecto localmente.
     bash
     git clone https://github.com/CarolinaGonzalez09/RetoCarolina.git
     
   - Esto creará una copia local del repositorio en tu máquina.

## Instalación de dependencias

2. *Instalar las dependencias del proyecto:*
   - Navega hasta el directorio del proyecto clonado.
     bash
     cd RetoCarolina
     
   - Asegúrate de tener Node.js instalado en tu sistema.
   - Para instalar las dependencias definidas en package.json, ejecuta:
     bash
     npm install
     
   - Esto descargará e instalará todas las dependencias necesarias que están listadas en el archivo package.json.

## Instalación de Playwright y Playwright Screenplay

3. *Instalar Playwright y Playwright Screenplay:*
   - Asumiendo que ya tienes Node.js y npm instalados, puedes instalar Playwright y Playwright Screenplay como dependencias de desarrollo usando npm
   - npm init playwright@latest
   - npm install --save-dev @testla/screenplay-playwright
   - Esto instalará Playwright y Playwright Screenplay en tu proyecto y los añadirá como dependencias de desarrollo en package.json.

## Ejecución del proyecto

4. *Ejecutar el proyecto:*
   - Para ejecutar el proyecto que utiliza Playwright y Screenplay, ejecuta el script desde la línea de comandos:
     npm run test
   - Esto abrirá un IDE de pruebas donde solo se tiene que ejecutar el test en cuestión con un play ubicado en la parte lateral derecha.
  
   - Playwright genera un reporte en HTML el cual está en la carpeta de test-results, abrirlo y comprenderlo.
