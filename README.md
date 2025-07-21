Evaluación

Esto es una página web sencilla con Landing Page que se hizo para pasar la materia de desarrollo web. Se subió a GitHub y se publicó con GitHub Pages, y tambien se usó CI/CD para que se actualice sola cuando cambio algo.

Qué se necesita:

Un navegador (Chrome, Firefox, Edge, etc).
Tener Git instalado en tu compu.
Una cuenta en GitHub.

Cómo hacerle que funcione:

-Bajar el proyecto a tu compu con este comando en la terminal:
    -git clone https://github.com/usuario/mi-landing-page.git

-Métete a la carpeta que se creó:
    -cd mi-landing-page

-Abrir el archivo index.html en tu navegador:


Si quieres cambiarle algo y subirlo:

-Haz los cambios en los archivos.
-Escribe en la terminal:
    git add .
    git commit -m "Cambios que hice"
    git push origin main

Cómo se ve en internet:

La página se sube sola a GitHub Pages cada vez que le das “push” al código. La puedes ver aquí: https://Leomont07.github.io/ev

Contenido del proyecto

index.html: Lo que se ve en la página, como el esqueleto.
styles.css: Los colores y el estilo para que se vea bonito.
script.js: Un botón que muestra una alerta.
.github/workflows/deploy.yml: El archivo que hace que todo se suba solo a internet.

Licencia
-License (úsalo bajo tu propio riesgo).