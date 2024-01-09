---
theme: seriph
background: https://images.unsplash.com/photo-1454789548928-9efd52dc4031?q=80&w=1480&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
class: text-center font-quicksand
highlighter: shikiji
lineNumbers: false
info: |
  Plataforma creada por Space<span class="text-[#f34250]">Group</span>
fonts:
  sans: 'Quicksand'
  serif: 'Quicksand'
drawings:
  persist: false
transition: slide-left
download: true
mdc: true
level: 1
---

# Bienvenido a Space<span class="text-[#f34250]">EV</span>

Plataforma de información y social sobre el espacio

## <h2>Space<span class="text-[#f34250]">Group</span></h2>
&nbsp;
<span>Brais Rivera Fidalgo</span>

<span>Christian Souto Souto</span>

<span>David Santeiro Conde</span>

<span>Paulo Francisco Iglesias Cabaleiro</span>

<!--
<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>
-->

<div class="abs-br m-6 flex gap-2">
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub" title="Abrir documentación técnica"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <img src="/assets/icons/carbon-document.svg" style="filter: invert(1);"/>
  </a>
</div>

<style>
  h1 {
    font-weight: bold;
  }
  
  h2 {
    font-weight: bold;
  }
</style>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
layout: default
level: 1
---

# Índice de contenidos

<div class="grid grid-cols-2 gap-4">
  <div class="col-span-1">
    <ul>
      <li><a href="/1">Bienvenido a SpaceEV</a></li>
      <li><a href="/2">Índice de contenidos</a></li>
      <li><a href="/3">🚀 Qué es SpaceEV?</a></li>
      <li><a href="/4">Requisitos Técnicos</a></li>
      <li><a href="/5">🚀 Proceso de Instalación</a></li>
      <li>
        <a href="/6">🖥️ Interfaz de Usuario I</a>
        <ul class="ml-4">
          <li><a href="/7">📰 Feed de posts</a></li>
          <li><a href="/8">➕📰 Nuevo post</a></li>
          <li><a href="/9">📅 Calendario</a></li>
          <li><a href="/10">➕📅 Añadir evento al calendario</a></li>
          <li><a href="/11">🔍📅 Búsqueda de eventos</a></li>
        </ul>
      </li>
    </ul>
  </div>
  <div class="col-span-1">
    <ul>
      <li>
        <a href="/12">🖥️ Interfaz de Usuario II</a>
        <ul class="ml-4">
          <li><a href="/13">📝 Registro de usuario</a></li>
          <li><a href="/14">🔑 Inicio de sesión</a></li>
          <li><a href="/15">🔒 Recuperación de contraseña</a></li>
          <li><a href="/16">🔁 Cambio de contraseña</a></li>
          <li><a href="/17">⚙️ Ajustes de usuario</a></li>
          <li><a href="/18">✅ Solicitar verificación de usuario</a></li>
        </ul>
      </li>
      <li><a href="/19">Referencias Bibliográficas</a></li>
      <li><a href="/20">¡Te esperamos en SpaceEV!</a></li>
    </ul>
  </div>
</div>


---
transition: fade-out
---

# 🚀 Qué es SpaceEV?

&nbsp;

Space<span class="text-[#f34250]">EV</span> es una **interfaz web** para la visualización de información personalizada sobre el espacio, así como para la interacción entre usuarios. Entre los principales apartados incluye:

&nbsp;

1. **Sistema de Información y Recomendación**
   - 💾 Almacena datos verificados sobre eventos astronómicos.
   - ♾️ Algoritmo de recomendación personalizado.

2. **Capa Social**
   - 🧑‍🤝‍🧑 Comunidad interactiva.
   - 🧑‍🚀 Compartir experiencias y visiones.
   - 📝 Comentar y valorar eventos.

<img
  class="absolute bottom-9 right-7 w-60 rounded-lg mr-4 mb-4"
  src="/assets/iconSpaceEV.png"
  alt="Icono de SpaceEV"
/>

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>


---
transition: slide-up
level: 1
---

# Requisitos Técnicos
 
 
- 🌐 **Servidor web** Apache HTTP server o Node.js, compatible con ejecución PHP.
- 🗃️ **Base de datos** relacional para almacenar los datos de eventos. Por ejemplo, MySQL.
- 📧 **Servidor de correo** Wild Duck para el envío de correos electrónicos.
- <mdi-account-circle /> **Servidor de autenticación** Auth0 para la gestión de usuarios.
- 📦 **Servidor de almacenamiento** Minio para el almacenamiento de contenido multimedia.
- 🎯 **Algoritmno de recomendación** de Space<span class="text-[#f34250]">EV</span>, escrito en Python para el cálculo de recomendaciones.
- 🙋 **Servidor de comentarios** Commento para la gestión de comentarios.

<div class="flex justify-end">
  <img src="/assets/diagramaServicios.drawio.png" alt="Icono de SpaceEV" width="100%">
</div>

---
transition: slide-up
level: 1
---

# 🚀 Proceso de Instalación

1. 📥 Descargar el **código fuente** de Space<span class="text-[#f34250]">EV</span>.
2. 🧩 Instalar las **dependencias** necesarias.
3. 🌐 Configurar el **servidor web**.
4. 🗃️ Configurar la **base de datos**.
5. 📧 Configurar el **servidor de correo**.
6. 🔒 Configurar el **servidor de autenticación**.
7. 📦 Configurar el **servidor de almacenamiento**.
8. 🎯 Configurar el **servidor de recomendación**.
9. 💬 Configurar el **servidor de comentarios**.
10. 🏃‍♂️ Ejecutar el **servidor web**.

&nbsp;

## <center>✅ ¡Listo!</center>

---
transition: slide-up
level: 1
---

# 🖥️ Interfaz de Usuario I

El sitio web de Space<span class="text-[#f34250]">EV</span> cuenta con una **interfaz de usuario intuitiva y fácil de usar**. Las principales interfaces coinciden con las dos características principales:

## 📰 Feed

* 📝 Feed de posts
* ➕ Nuevo post

## 📅 Calendario

* 🌌 Calendario con eventos astronómicos verificados
* ➕ Añadir evento al calendario
* 🔍 Búsqueda de eventos

<div class="pt-12 flex justify-center items-center">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    ¡Vamos a ver esas interfaces! <carbon:arrow-right class="inline"/>
  </span>
</div>

---
level: 2
---

# 📰 Feed de posts

Aquí puedes ver la **interfaz del feed** 📰. Como puedes ver, es muy intuitiva y fácil de usar. Puedes ver los posts de otros usuarios <mdi-account-circle /> a los que sigues. En la parte inferior de cada post se muestra el usuario <mdi-account-circle /> al que pertenece así como botones para acceder a **comentarios** 💬 e indicar que **te gusta** ❤️.

![Interfaz de usuario de feed](/assets/interfacesABP/feed.png){: class="w-3/4 mx-auto"}

---
level: 2
---

# ➕📰 Nuevo post

La interfaz de **Nuevo post** 📝 permite crear y **publicar tus propios posts 📰**. Aquí se presenta un formulario intuitivo 🧠 que te permite ingresar el **título** 📖 de tu post, **fecha** 📅 del contenido, una **descripción** 📝 y **contenido multimedia** 🎥. Al publicarlo, será visible para otros usuarios en su feed 📲.

![Interfaz de usuario de nuevo post](/assets/interfacesABP/newPost.png){: class="w-3/4 mx-auto"}

---
level: 2
---

# 📅 Calendario

La interfaz de **Calendario** 📅 ofrece una vista **temporal** ⏰ global, permitiendo a los usuarios navegar 🗓️ entre los días de un mes y visualizar los eventos espaciales 🚀 para las fechas seleccionadas. Esta interfaz es intuitiva 🧠 y fácil de usar, proporcionando una forma eficiente 🚀 de explorar los eventos espaciales.

![Interfaz de usuario de calendario](/assets/interfacesABP/calendario.png){: class="w-3/4 mx-auto"}

---
level: 2
---

# ➕📅 Añadir evento al calendario

En la interfaz de **Añadir evento al calendario** 📅 los **usuarios verificados** 👥 pueden proponer **nuevos eventos** 📝. La interfaz presenta un formulario con el **título** 📖 del evento, **fecha** 📆, **descripción** 📄 y **contenido multimedia** 🎥. Al enviar, se **revisa** 👀 y, si se **aprueba** ✅, será visible en el **calendario** 🗓️.

![Interfaz de usuario de calendario](/assets/interfacesABP/añadirPost.png){: class="w-3/4 mx-auto"}

---
level: 2
---

# 🔍📅 Búsqueda de eventos


La interfaz "**Búsqueda de eventos**" 🔍 permite **filtrar** y **buscar eventos** 📅 en el calendario. Puedes buscar por **palabras clave** 🔑, **autor** 👤, **nombre del evento** 📝, **eventos similares** 🔄 y **fechas** 📆. Gracias al **algoritmo de Space<span class="text-[#f34250]">EV</span>** 🚀, encontrar los eventos que te interesan es más fácil.

![Interfaz de usuario de búsqueda de Eventos](/assets/interfacesABP/busquedaEventos.png){: class="w-3/4 mx-auto"}

---
transition: slide-up
level: 1
---

# 🖥️ Interfaz de Usuario II

Space<span class="text-[#f34250]">EV</span> también cuenta con diferentes interfaces para los **procesos de registro y autenticación de usuarios**, así como para diferentes **gestiones de la cuenta** de usuario:

 * 📝 Registro de usuario
 * 🔑 Inicio de sesión
 * 🔒 Recuperación de contraseña
 * 🔁 Cambio de contraseña de usuario
 * ⚙️ Panel de ajustes de usuario
 * ✅ Solicitar verificación de usuario

 <div class="pt-12 flex justify-center items-center">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    ¡Vamos a ver esas interfaces! <carbon:arrow-right class="inline"/>
  </span>
</div>


---
level: 2
---
# 📝 Registro de usuario

El **Registro** 📝 es tu puerta de entrada 🚪 a **Space<span class="text-[#f34250]">EV</span>** 🚀. Aquí puedes crear tu cuenta con un **nombre de usuario (alias)** 👤, **email** 📧 y **contraseña** 🔒. Al registrarte, podrás navegar como **usuario registrado** 👥, disfrutar de un **feed personalizado** 📰 y participar de forma activa 💬 en la plataforma.

![Interfaz de usuario de registro](/assets/interfacesABP/register.png){: class="w-3/4 mx-auto"}


---
level: 2
---
# 🔑 Inicio de sesión

La interfaz de **Inicio de sesión** 🔑 es tu punto de acceso 🚪 a la plataforma **Space<span class="text-[#f34250]">EV</span>** 🚀. Aquí puedes iniciar sesión proporcionando tu **nombre de usuario (alias)** 👤 o **email** 📧 y **contraseña** 🔒. Al iniciar sesión, podrás navegar como **usuario registrado (o verificado)** 👥 y disfrutar de todas las ventajas.

![Interfaz de usuario de inicio de sesión](/assets/interfacesABP/login.png){: class="w-3/4 mx-auto"}


---
level: 2
---
# 🔒 Recuperación de contraseña

La opción de **Recuperación de contraseña** 🔒 es tu salvavidas 🆘 cuando olvidas tu **contraseña**. Solo necesitas proporcionar tu **email** 📧 y seguir las instrucciones que te enviaremos al correo 📬 para **restablecer tu contraseña** y **recuperar el acceso** a tu cuenta en la plataforma **Space<span class="text-[#f34250]">EV</span>** 🚀.

![Interfaz de usuario de recuperación de contraseña](/assets/interfacesABP/resetPassword.png){: class="w-3/4 mx-auto"}

---
level: 2
---
# 🔁 Cambio de contraseña

La interfaz de **Cambio de contraseña** 🔁 es donde puedes **actualizar tu contraseña** 🔑 en la plataforma **Space<span class="text-[#f34250]">EV</span>** 🚀. Este formulario solicita tu **contraseña actual** y la **nueva contraseña** que deseas establecer. Accesible desde los **ajustes de tu cuenta** ⚙️, esta función te permite mantener tu cuenta segura 🔒.

![Interfaz de usuario de cambio de contraseña](/assets/interfacesABP/cambiarContraseña.png){: class="w-3/4 mx-auto"}


---
level: 2
---
# ⚙️ Ajustes de usuario

La interfaz **Ajustes de usuario** ⚙️ te permite **personalizar tu perfil** 👤 en la plataforma **Space<span class="text-[#f34250]">EV</span>** 🚀. Aquí puedes ver y cambiar tu **alias**, **nombre**, **apellidos**, **descripción** (una biografía pública) y **tipo de usuario**. Tu tienes el control 🎮 sobre tus **datos personales** y cómo te presentas a la comunidad Space<span class="text-[#f34250]">EV</span>.

![Interfaz de usuario de ajustes de usuario](/assets/interfacesABP/userSettings.png){: class="w-3/4 mx-auto"}


---
level: 2
---
# ✅ Solicitar verificación de usuario

En los **ajustes de usuario** ⚙️ puedes solicitar **promocionar tu cuenta a verificada** ✅ proporcionando un **documento de identidad** 🆔 y un **certificado** 📜 que valide tu membresía en la **comunidad científica astronómica** 🌌. Al convertirte en un **usuario verificado**, podrás disfrutar de **beneficios adicionales** 🎁.

![Interfaz de usuario de solicitar verificación de usuario](/assets/interfacesABP/acreditacion.png){: class="w-3/4 mx-auto"}


---
transition: slide-up
layout: image-right
image: https://images.unsplash.com/photo-1501862700950-18382cd41497?q=80&w=1419&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
---

# Referencias Bibliográficas

1. [Documentación técnica](https://emojipedia.org/es/) del proyecto Space<span class="text-[#f34250]">EV</span>.
2. Imágenes del espacio de [Unsplash](https://unsplash.com/).
2. Emoticonos con ayuda de [Emojipedia](https://emojipedia.org/es/).
3. Codificado con ayuda de [GitHub Copilot](https://copilot.github.com/).
4. Presentación realizada con [Slidev](https://sli.dev/).

---
transition: slide-up
image: https://images.unsplash.com/photo-1444703686981-a3abbc4d4fe3?q=80&w=1470&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
layout: image
class: text-center
---

<h1> ¡Te esperamos en Space<span class="text-[#f34250]">EV</span>!</h1>

## Creado con ❤️ por Space<span class="text-[#f34250]">Group</span>


[Documentación técnica]()
  · [Algoritmo de recomendación](https://colab.research.google.com/drive/1uUTbyFfyo6GDnuiq2MJw4vHJzY7VMz_f?usp=sharing) 
  · [Algoritmo de valoración](https://colab.research.google.com/drive/1Kj609BCPEtK-CthLB4O-uAO0zR-otc8s?usp=sharing)

<img
  class="absolute bottom-9 right-7 w-20 rounded-lg mr-4 mb-4"
  src="/assets/iconSpaceEV.png"
  alt="Icono de SpaceEV"
/>

<div class="absolute bottom-9 left-7 w-50 rounded-lg mr-4">

  ## Space<span class="text-[#f34250]">Group</span>
  Brais Rivera Fidalgo
  Christian Souto Souto
  David Santeiro Conde
  Paulo Francisco Iglesias Cabaleiro
</div>

<style>
h1 {
  /*Texto blanco, en negrita, más grande, en el centro de la diapositiva*/
  color: white !important;
  font-weight: bold;
  font-size: 2.5em;
  text-align: center;
}
h2{
  text-align: center;
}
</style>