Text Encoder Project
Este proyecto es un encriptador de texto desarrollado como parte del programa educativo de 6 meses de Oracle Next Education.

🔧 Descripción
Este proyecto es parte del primer Challenge del Programa ONE de Oracle Next Education y Alura Latam. Es una aplicación web simple que permite encriptar y desencriptar texto utilizando un conjunto de reglas de encriptación específicas. Utilicé Astro y Tailwind.

🚀 Proyecto en Vivo
Puedes interactuar con la aplicación en vivo en el siguiente enlace: Text Encoder en Netlify

📂 Estructura del Proyecto
Dentro del proyecto encontrarás una estructura de carpetas y archivos similar a la siguiente:

text
Copiar código
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
🛠️ Comandos Disponibles
Todos los comandos se ejecutan desde la raíz del proyecto, desde una terminal:

Comando	Acción
npm install	Instala las dependencias
npm run dev	Inicia el servidor de desarrollo local en localhost:4321
npm run build	Compila el sitio de producción en ./dist/
npm run preview	Previsualiza tu compilación localmente antes de desplegar
npm run astro ...	Ejecuta comandos CLI como astro add, astro check
npm run astro -- --help	Obtén ayuda usando la CLI de Astro
🧪 Código Principal
Aquí tienes una muestra del código principal del proyecto:

html
Copiar código
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link href="output.css" rel="stylesheet" />
    <title>Encriptador de texto</title>
  </head>
  <body>
    <header class="bg-black py-4 px-4 w-[100%]">
      <h1 class="text-white text-3xl font-bold text-center font-mono">
        Encriptador
      </h1>
    </header>
    <main>
      <section class="py-4 px-4 w-[100%] font-mono">
        <p class="text-center">
          Este proyecto corresponde al primer Challenge del Programa ONE de
          <a
            class="text-blue-600 font-semibold"
            href="https://www.oracle.com/co/education/oracle-next-education/"
            >Oracle Next Education</a
          >
          y
          <a
            class="text-blue-600 font-semibold"
            href="https://www.aluracursos.com/"
            >Alura Latam</a
          >
        </p>
      </section>
      <!-- Resto del código HTML -->
    </main>
    <footer class="bg-black flex flex-col justify-center items-center py-2">
      <p class="text-white">Developed by Paulo de los Reyes</p>
      <a
        class="text-white font-bold underline"
        href="https://paulowebdev.netlify.app/"
        >paulo.dev</a
      >
    </footer>
  </body>
  <script>
    // Código JavaScript aquí
  </script>
</html>
📚 Aprende más sobre Astro Framework
Siente la libertad de revisar nuestra documentación o unirte a nuestro servidor de Discord.
