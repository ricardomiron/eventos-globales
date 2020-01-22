<p align="center">
<img src="http://codeandomexico.org/resources/img/codeandomexico.png" width="500" alt="Codeando México"><br>
<a href="http://www.codeandomexico.org/" target="_blank"><img src="https://img.shields.io/badge/website-CodeandoMexico-00D88E.svg"></a>
<a href="http://slack.codeandomexico.org/" target="_blank"><img src="https://img.shields.io/badge/slack-CodeandoMexico-EC0E4F.svg"></a>
</p>


# Eventos globales

**tl;dr:** Plataforma que alberga un mapeo de eventos a nivel global sobre tecnología cívica, datos abiertos y más.


## Tabla de contenidos

- [Acerca del proyecto](#acerca-del-proyecto)
- [Contribuye](#contribuye)
- [Atribuciones](#atribuciones)


## Acerca del proyecto

Este es un proyecto de la comunidad que busca mapear todos los eventos a nivel global sobre tecnología cívica, datos abiertos, innovación pública y más...

El proyecto busca centralizar la información de cada uno de estos eventos para disposición de la comunidad. El sitio puedes verlo en el [siguiente enlace](https://codeandomexico.github.io/eventos-globales/).

Si te interesa contribuir al proyecto, echa un vistazo a la siguiente sección.


## Contribuye

¡Cualquier sugerencia o contribución a este repositorio es bien recibida!

Si necesita ayuda, escribe directamente a <rodo@codeandomexico.org> o en nuestro [Slack](http://slack.codeandomexico.org/).

### Añade un evento

1. Crea un fork del repositorio a tu cuenta de GitHub.

2. Clona tu fork del repo:
   ```bash
   git clone https://github.com/<TU-USUARIO>/eventos-globales.git
   cd eventos-locales/
   ```

3. Crea una rama con el nombre del evento que deseas agregar, en este ejemplo supongamos que agregaré el evento [csv,conf,v5](https://csvconf.com/):
   ```bash
   git checkout -b csvconf  # esto creará una nueva rama de nombre 'csvconf' y se moverá a ella
   ```

4. Crea el archivo que contenga la información del evento. El archivo deberá ser guardado en la carpeta [`_posts`](https://github.com/CodeandoMexico/eventos-globales/tree/master/_posts) con el formato `AAAA-MM-DD-evento.md`, donde `AAAA`, `MM` y `DD` corresponden al año, mes y primer día de realización del evento, respectivamente. Puedes tomar como referencia el archivo del evento [csv,conf,v5](https://csvconf.com/), que encuentras como [`2020-05-13-csvconf.md`](https://github.com/CodeandoMexico/eventos-globales/blob/master/_posts/2020-05-13-csvconf.md).

5. Agrega una imagen del evento o una captura de pantalla de su sitio web en la carpeta [`assets/events`](https://github.com/CodeandoMexico/eventos-globales/tree/master/assets/events). Por favor asegúrate de que el nombre de la imagen sea el mismo que el del `evento` que agregaste en el nombre del archivo `AAAA-MM-DD-evento.md` (y no olvides agregar el nombre de la imagen en el campo correspondiente de dicho archivo).

6. Crea un Pull Request (PR) de la rama que has creado a la rama `master` del repositorio original y solicita una revisión a **@RodolfoFerro**.

**NOTA:** Por favor realiza un PR por evento.



### Modifica el sitio

Por favor abre un issue donde menciones los cambios que te gustaría agregar y menciona a **@RodolfoFerro**. En dado caso, se te asignaría el issue y esperaremos tu PR donde te pediremos solicites una revisión a **@RodolfoFerro** para revisar y aceptar tus cambios al sitio.

Si deseas correr el sitio de manera local, ejecuta los siguientes pasos:

1. Instala los requerimientos:
   ```bash
   bundle install
   ```

2. Corre el servidor:
   ```bash
   bundle exec jekyll serve
   ```

3. Abre <http://localhost:4000/eventos-globales> en tu navegador.

El comando del paso 2 te permite hacer modificaciones y visualizar los cambios en tiempo real dentro de tu localhost.


## Atribuciones

- Sitio web basado en [Pintereso Jekyll Theme](https://www.wowthemes.net/pintereso-free-bootstrap-jekyll-theme/)
- Gracias a [Richard](https://github.com/ricardomiron) y [Rodo](https://github.com/RodolfoFerro) por las contribuciones iniciales
- `{}` y contenidos con ❤️ por la [comunidad de Codeando México](http://slack.codeandomexico.org/)

---

Este sitio cuenta con una licencia MIT.
