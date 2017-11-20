---
layout: post
title: Como empezar a bloggear
---


En este *post*  voy a mostrar como configurar un blog usando *jekyll* y *github pages*, con soporte de comentarios mediante *Disqus*.

Este *post* está orientado a personas sin mucho conocimiento técnico.

### Paso 1: Crear una cuenta de *Github*.

Debido a que el servicio estará disponible usando *github pages*, lo primero que necesitas es tener una cuenta de github.

  * **Obs:** Tu nombre de usuario generará el link de tu blog, es decir, si tu usuario es *TuUsuario*, el link a tu blog sera *https:// "TuUsuario" .github.io*

### Paso 2: Haz un fork de *Jekyll Now*.

Para que todo sea sencillo ve al siguiente link **https://github.com/barryclark/jekyll-now**, y haz click en *fork*, con esto, vas a tener una copia del repositorio en tus repositorios.
Luego, ve a la configuración del repositorio que acabas de copiar, y cambiale el nombre a *TuUsuario.github.io*.

Con esto ya deberías poder acceser a *https:// "TuUsuario" .github>.io* y ver cierto contenido, si no, sigue el Paso 3.

### Paso 3: modifica el archivo *_config.yml*.

En el archivo *_config.yml*, que se encuentra en la carpeta *raíz* del repositorio que copiaste, se encuentra toda la configuración de tu blog:
  * Autor.
  * Nombre.
  * Extensiones (Disqus, GoogleAnalytics, etc).
  * Otras.

Modifica los campos que encuentres pertinentes.

### Paso 4: Crea una cuenta en *Disqus*.

Con esto podrás habilitar los comentarios. Una vez creada tu cuenta, ve a *Get Started* y luego *I want to install Disqus in my site*, sigue las instrucciones.

### Paso 5: Agrega *Disqus* a *_config.yml*.

Edita nuevamente el archivo *_config.yml*, donde dice *disqus:* agrega *tusitiodisqus*. *Kchau* ya están habilitados los comentarios en tu sitio.

### Paso 6: Agrega un nuevo *post*:

En la carpeta *_posts* de tu repositorio, agrega un nuevo archivo con el formato *YYYY-MM-DD-TU-Primer-Post.md*, editalo desde *Github*. Recuerda que este archivo es en formato *Markdown*, asique te será conveniente buscar una *Cheat-Sheet*.
Finalmente, no olvides modificar el archivo *about.md* con tu información, y si eres aventurado con *html*, el archivo *index.html*

Con esto debería estar todo OK!
