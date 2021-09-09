---
theme: seriph
background: https://i.ibb.co/VCN6vrg/Group-1.png
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
title: Café Virtual CIT
---

# Café Virtual CIT

#DevsCafé

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <a href="https://culturait.com.ar/" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-wikis />
  </a>
  <a href="https://www.linkedin.com/company/culturait/mycompany/" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-linkedin />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
preload: false
---

# ¿Quiénes Somos?

Somos parte del equipo de desarrolladores de Cultura IT

<div class="w-80 relative mt-12">
  <div class="relative w-30 h-30">
    <img
      v-motion
      :initial="{ x: 800, y: -100, scale: 1.5, rotate: -50 }"
      :enter="final"
      class="absolute top-0 left-0 right-0 bottom-0"
      src="https://i.ibb.co/7RZqVT8/foto.jpg"
    />
  </div>

  <div 
    class="w-100 text-3xl absolute top-2 left-50 text-[#2B90B6] -z-1"
    v-motion
    :initial="{ x: -80, opacity: 0}"
    :enter="{ x: 0, opacity: 1, transition: { delay: 2000, duration: 1000 } }">
    <div class="text-3xl">Sergio Romano</div>
    <div class="text-1xl">.NET Software Developer</div>
    <ul class="text-1xl">
      <li> Cultura IT
      </li>
      <li> Ministerio de Educación
      </li>
    </ul>
  </div>
</div>
<br/>
<br/>
<div class="w-80 relative mt-12">
  <div class="relative w-30 h-30">
    <img
      v-motion
      :initial="{ x: 800, y: -100, scale: 1.5, rotate: -50 }"
      :enter="final"
      class="absolute top-0 left-0 right-0 bottom-0"
      src="https://i.ibb.co/ZTtWwqS/fede.jpg"
    />
  </div>

  <div 
    class="w-100 text-3xl absolute top-2 left-50 text-[#2B90B6] -z-1"
    v-motion
    :initial="{ x: -80, opacity: 0}"
    :enter="{ x: 0, opacity: 1, transition: { delay: 2000, duration: 1000 } }">
    <div class="text-3xl">Federico Fia Sare</div>
    <div class="text-1xl">Senior Software Engineer | Technical Leader</div>
    <ul class="text-1xl">
      <li> Cultura IT
      </li>
    </ul>
  </div>
</div>
<!-- vue script setup scripts can be directly used in markdown, and will only affects current page -->
<script setup lang="ts">
const final = {
  x: 0,
  y: 0,
  rotate: 0,
  scale: 1,
  transition: {
    type: 'spring',
    damping: 10,
    stiffness: 20,
    mass: 2
  }
}
</script>

<div
  v-motion
  :initial="{ x:35, y: 40, opacity: 0}"
  :enter="{ y: 0, opacity: 1, transition: { delay: 3500 } }">

</div>

<style>
img{
  clip-path: circle(40%);
}
</style>
---

# Stack Tecnológico

- .NET Framework
- .NET Core
- SQL Server
- Vuejs
- Razor pages + jQuery
- Kendo framework
- Bootstrap
- Ionic
- Angular 7
- Sqlite
- Entity + OrmLite
- Fluent

<style>
h1 {
  background-color: #67a555;
  background-image: linear-gradient(45deg, #67a555 10%, #67a555 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>
---

# Stack Tecnológico

- .NET 5
- Reactjs
- Angularjs

<style>
h1 {
  background-color: #67a555;
  background-image: linear-gradient(45deg, #67a555 10%, #67a555 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>
---

# Proyectos de CIT en .net

* **PROSYS**
  - Turismo
  - Hoteleria
* **GDM**
  - Agricultura
  - Investigación
* **MAE**
  - Economico

<style>
h1 {
  background-color: #67a555;
  background-image: linear-gradient(45deg, #67a555 10%, #67a555 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

---

# Equipo SCRUM

* **Análisis funcional y técnico**
* **Desarrolladores**
* **Testing**
* **Integración/Despliegue**

<style>
h1 {
  background-color: #67a555;
  background-image: linear-gradient(45deg, #67a555 10%, #67a555 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

---

# Infraestructura

* **Control de Versiones**
  - Git
  - TFS
* **Server**
  - On premise CIT (IIS)
  - On premise Cliente (IIS)
  - Cloud (Microsoft Azure): AppService, Blob Storage, SQL Database
* **Canal de comunicación**
  - Google Chat
  - Discord

<style>
h1 {
  background-color: #67a555;
  background-image: linear-gradient(45deg, #67a555 10%, #67a555 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent; 
  -moz-text-fill-color: transparent;
}
</style>

---
layout: center
class: text-center
---

# FIN

<br>

Visitanos en nuestra página [https://culturait.com.ar](https://culturait.com.ar)

<br>

O también por LinkedIn 
[https://www.linkedin.com/company/culturait](https://www.linkedin.com/company/culturait/mycompany/)

<style>
h1 {
  font-size: 80px
}
</style>
