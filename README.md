# Text Encoder Project

Este proyecto es un encriptador de texto desarrollado como parte del programa educativo de Oracle Next Education.

## 🔧 Descripción

Este proyecto es parte del primer Challenge del Programa ONE de [Oracle Next Education](https://www.oracle.com/co/education/oracle-next-education/) y [Alura Latam](https://www.aluracursos.com/). Es una aplicación web simple que permite encriptar y desencriptar texto utilizando un conjunto de reglas de encriptación específicas.

## 🛠️ Tecnologías Utilizadas

- HTML
- CSS
- JavaScript
- Astro
- Netlify

## 🚀 Proyecto en Vivo

Puedes interactuar con la aplicación en vivo en el siguiente enlace: [Text Encoder en Netlify](https://textencoder.netlify.app)
2. Añadir una captura de pantalla
markdown
Copy Code
## 🚀 Proyecto en Vivo

Puedes interactuar con la aplicación en vivo en el siguiente enlace: [Text Encoder en Netlify](https://textencoder.netlify.app)

![Captura de Pantalla](ruta/a/tu/captura.png)
3. Explicar la estructura del proyecto
markdown
Copy Code
## 📂 Estructura del Proyecto

Dentro del proyecto encontrarás las siguientes carpetas y archivos:
text
/
├── public/
│   └── favicon.svg  # Icono del sitio
├── src/
│   ├── components/
│   │   └── Card.astro  # Componente de tarjeta
│   ├── layouts/
│   │   └── Layout.astro  # Diseño principal
│   └── pages/
│       └── index.astro  # Página principal
└── package.json  # Archivo de configuración de npm

4. Añadir ejemplo de código JavaScript
markdown
Copy Code
## 🧪 Código Principal

Aquí tienes una muestra del código principal del proyecto:
html

<!DOCTYPE html> <html lang="en"> <head> <meta charset="UTF-8" /> <meta name="viewport" content="width=device-width, initial-scale=1.0" /> <link href="output.css" rel="stylesheet" /> <title>Encriptador de texto</title> </head> <body> <header class="bg-black py-4 px-4 w-[100%]"> <h1 class="text-white text-3xl font-bold text-center font-mono"> Encriptador </h1> </header> <main> <section class="py-4 px-4 w-[100%] font-mono"> <p class="text-center"> Este proyecto corresponde al primer Challenge del Programa ONE de <a class="text-blue-600 font-semibold" href="https://www.oracle.com/co/education/oracle-next-education/" >Oracle Next Education</a > y <a class="text-blue-600 font-semibold" href="https://www.aluracursos.com/" >Alura Latam</a > </p> </section>
</main>
<footer class="bg-black flex flex-col justify-center items-center py-2">
  <p class="text-white">Developed by Paulo de los Reyes</p>
  <a
    class="text-white font-bold underline"
    href="https://paulowebdev.netlify.app/"
    >paulo.dev</a
  >
</footer>
</body> <script> // Ejemplo de código JavaScript para encriptar texto function encriptar(texto) { const reglas = { 'a': '1', 'e': '2', 'i': '3', 'o': '4', 'u': '5' }; return texto.replace(/[aeiou]/g, letra => reglas[letra]); } console.log(encriptar("hola")); // h4l1 </script> </html>
5. Añadir recursos adicionales
markdown
Copy Code
## 📚 Quieres Aprender Más?

Siente la libertad de revisar [nuestra documentación](https://docs.astro.build) o unirte a nuestro [servidor de Discord](https://astro.build/chat).

### Recursos Adicionales
- [Documentación de JavaScript](https://developer.mozilla.org/es/docs/Web/JavaScript)
- [Guía de CSS](https://developer.mozilla.org/es/docs/Web/CSS)
- [Tutorial de Astro](https://docs.astro.build/es/getting-started/)
README Completo
Aquí tienes el README completo con todas las mejoras aplicadas:

markdown
Copy Code
# Text Encoder Project

Este proyecto es un encriptador de texto desarrollado como parte del programa educativo de Oracle Next Education.

## 🔧 Descripción

Este proyecto es parte del primer Challenge del Programa ONE de [Oracle Next Education](https://www.oracle.com/co/education/oracle-next-education/) y [Alura Latam](https://www.aluracursos.com/). Es una aplicación web simple que permite encriptar y desencriptar texto utilizando un conjunto de reglas de encriptación específicas.

## 🛠️ Tecnologías Utilizadas

- HTML
- CSS
- JavaScript
- Astro
- Netlify

## 🚀 Proyecto en Vivo

Puedes interactuar con la aplicación en vivo en el siguiente enlace: [Text Encoder en Netlify](https://textencoder.netlify.app)

![Captura de Pantalla](ruta/a/tu/captura.png)

## 📂 Estructura del Proyecto

Dentro del proyecto encontrarás las siguientes carpetas y archivos:
text
/
├── public/
│   └── favicon.svg  # Icono del sitio
├── src/
│   ├── components/
│   │   └── Card.astro  # Componente de tarjeta
│   ├── layouts/
│   │   └── Layout.astro  # Diseño principal
│   └── pages/
│       └── index.astro  # Página principal
└── package.json  # Archivo de configuración de npm


## 🛠️ Comandos Disponibles

Todos los comandos se ejecutan desde la raíz del proyecto, desde una terminal:

| Comando                   | Acción                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Instala las dependencias                         |
| `npm run dev`             | Inicia el servidor de desarrollo local en `localhost:4321` |
| `npm run build`           | Compila el sitio de producción en `./dist/`      |
| `npm run preview`         | Previsualiza tu compilación localmente antes de desplegar |
| `npm run astro ...`       | Ejecuta comandos CLI como `astro add`, `astro check` |
| `npm run astro -- --help` | Obtén ayuda usando la CLI de Astro               |

## 🧪 Código Principal

Aquí tienes una muestra del código principal del proyecto:

html

<!DOCTYPE html> <html lang="en"> <head> <meta charset="UTF-8" /> <meta name="viewport" content="width=device-width, initial-scale=1.0" /> <link href="output.css" rel="stylesheet" /> <title>Encriptador de texto</title> </head> <body> <header class="bg-black py-4 px-4 w-[100%]"> <h1 class="text-white text-3xl font-bold text-center font-mono"> Encriptador </h1> </header> <main> <section class="py-4 px-4 w-[100%] font-mono"> <p class="text-center"> Este proyecto corresponde al primer Challenge del Programa ONE de <a class="text-blue-600 font-semibold" href="https://www.oracle.com/co/education/oracle-next-education/" >Oracle Next Education</a > y <a class="text-blue-600 font-semibold" href="https://www.aluracursos.com/" >Alura Latam</a > </p> </section>
</main>
<footer class="bg-black flex flex-col justify-center items-center py-2">
  <p class="text-white">Developed by Paulo de los Reyes</p>
  <a
    class="text-white font-bold underline"
    href="https://paulowebdev.netlify.app/"
    >paulo.dev</a
  >
</footer>
</body> <script> // Ejemplo de código JavaScript para encriptar texto function encriptar(texto) { const reglas = { 'a': '1', 'e': '2', 'i': '3', 'o': '4', 'u': '5' }; return texto.replace(/[aeiou]/g, letra => reglas[letra]); } console.log(encriptar("hola")); // h4l1 </script> </html>

## 📚 Quieres Aprender Más?

Siente la libertad de revisar [nuestra documentación](https://docs.astro.build) o unirte a nuestro [servidor de Discord](https://astro.build/chat).

### Recursos Adicionales
- [Documentación de JavaScript](https://developer.mozilla.org/es/docs/Web/JavaScript)
- [Guía de CSS](https://developer.mozilla.org/es/docs/Web/CSS)
- [Tutorial de Astro](https://docs.astro.build/es/getting-started/)
