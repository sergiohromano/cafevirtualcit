---
theme: seriph
class: text-center
background: https://source.unsplash.com/user/sergiohromano
highlighter: shiki
lineNumbers: false
info: |
  ## Café Virtual CIT
  Presentation for devs.

  Visit us [Cultura IT](https://culturait.com.ar/)
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
  <a href="https://culturait.com.ar/" target="_blank" alt="Cultura IT"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-green">
    <carbon-wikis />
  </a>
  <a href="https://www.linkedin.com/company/culturait/mycompany/" target="_blank" alt="LinkedIn"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-green">
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
      class="pic absolute top-0 left-0 right-0 bottom-0"
      src="https://i.ibb.co/7RZqVT8/foto.jpg"
    />
  </div>

  <div 
    class="w-100 text-3xl absolute top-2 left-50 text-[#2B90B6] z-0"
    v-motion
    :initial="{ x: -80, opacity: 0}"
    :enter="{ x: 0, opacity: 1, transition: { delay: 2000, duration: 1000 } }">
    <div class="text-3xl">Sergio Romano</div>
    <div class="text-1xl italic">.NET Software Developer</div>
    <ul class="!list-disc text-1xl">
      <li> Cultura IT
      </li>
      <li> Ministerio de Educación
      </li>
      <div>
        <a href="https://www.linkedin.com/in/sergio-h-romano/" target="_blank" alt="GitHub"
          class="text-xl icon-btn opacity-50 !border-none !hover:text-green">
          <carbon-logo-linkedin />
        </a>
        <a href="https://sergiohromano.vercel.app/" target="_blank" alt="LinkedIn"
          class="text-xl icon-btn opacity-50 !border-none !hover:text-green">
          <carbon-wikis />
        </a>
      </div>
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
      class="pic absolute top-0 left-0 right-0 bottom-0"
      src="https://i.ibb.co/ZTtWwqS/fede.jpg"
    />
  </div>

  <div 
    class="w-100 text-3xl absolute top-2 left-50 text-[#2B90B6] z-0"
    v-motion
    :initial="{ x: -80, opacity: 0}"
    :enter="{ x: 0, opacity: 1, transition: { delay: 2000, duration: 1000 } }">
    <div class="text-3xl">Federico Fia Sare</div>
    <div class="text-1xl italic">Senior Software Engineer | Technical Leader</div>
    <ul class="!list-disc text-1xl">
      <li> Cultura IT
      </li>
      <div>
        <a href="https://www.linkedin.com/in/federico-gabriel-fia-sare-193709146/" target="_blank" alt="LinkedIn"
          class="text-xl icon-btn opacity-50 !border-none !hover:text-green">
          <carbon-logo-linkedin />
        </a>
      </div>
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

<div class="abs-tr m-6">
  <a href="https://culturait.com.ar/" target="_blank" alt="Cultura IT"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <img width="48" height="48" src="https://i.ibb.co/kQQd2LT/logocit.png">
  </a>
</div>

<style>
img.pic{
  clip-path: circle(40%);
}
</style>
---

# Stack Tecnológico

<ul class="!list-disc">
  <li v-click> .NET Framework </li>
  <li v-click> .NET Core </li>
  <li v-click> SQL Server </li>
  <li v-click> Vuejs </li>
  <li v-click> Razor pages + jQuery </li>
  <li v-click> Kendo framework </li>
  <li v-click> Bootstrap </li>
  <li v-click> Ionic </li>
  <li v-click> Angular 7 </li>
  <li v-click> Sqlite </li>
  <li v-click> Entity + OrmLite </li>
  <li v-click> Fluent </li>
</ul>

<div class="abs-tr m-6">
  <a href="https://culturait.com.ar/" target="_blank" alt="Cultura IT"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <img width="48" height="48" src="https://i.ibb.co/kQQd2LT/logocit.png">
  </a>
</div>

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


<ul class="!list-disc">
  <li v-click> .NET 5 </li>
  <li v-click> Reactjs </li>
  <li v-click> Angularjs </li>
</ul>


<div class="abs-tr m-6">
  <a href="https://culturait.com.ar/" target="_blank" alt="Cultura IT"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <img width="48" height="48" src="https://i.ibb.co/kQQd2LT/logocit.png">
  </a>
</div>

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

<ul class="!list-disc">
  <li v-click class="font-bold"> PROSYS
    <ul class="!list-circle">
      <li class="font-normal">Turismo</li>
      <li class="font-normal">Hoteleria</li>
    </ul>
  </li>
  <li v-click class="font-bold"> GDM
    <ul class="!list-circle">
      <li class="font-normal">Agricultura</li>
      <li class="font-normal">Investigación</li>
    </ul>
  </li>
  <li v-click class="font-bold"> MAE
    <ul class="!list-circle">
      <li class="font-normal">Hoteleria</li>
    </ul>
  </li>
</ul>

<div class="abs-tr m-6">
  <a href="https://culturait.com.ar/" target="_blank" alt="Cultura IT"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <img width="48" height="48" src="https://i.ibb.co/kQQd2LT/logocit.png">
  </a>
</div>

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


<ul class="!list-disc">
  <li v-click class="font-bold"> Análisis funcional y técnico
  </li>
  <li v-click class="font-bold"> Desarrolladores
  </li>
  <li v-click class="font-bold"> Testing
  </li>
  <li v-click class="font-bold"> Integración/Despliegue
  </li>
</ul>

<div class="abs-tr m-6">
  <a href="https://culturait.com.ar/" target="_blank" alt="Cultura IT"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <img width="48" height="48" src="https://i.ibb.co/kQQd2LT/logocit.png">
  </a>
</div>

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

<ul class="!list-disc">
  <li v-click class="font-bold"> Control de Versiones
    <ul class="!list-circle">
      <li class="font-normal">Git</li>
      <li class="font-normal">TFS</li>
    </ul>
  </li>
  <li v-click class="font-bold"> Server
    <ul class="!list-circle">
      <li class="font-normal">On premise CIT (IIS)</li>
      <li class="font-normal">On premise Cliente (IIS)</li>
      <li class="font-normal">Cloud (Microsoft Azure): AppService, Blob Storage, SQL Database</li>
    </ul>
  </li>
  <li v-click class="font-bold"> Canal de comunicación
    <ul class="!list-circle">
      <li class="font-normal">Discord</li>
    </ul>
  </li>
</ul>

<div class="abs-tr m-6">
  <a href="https://culturait.com.ar/" target="_blank" alt="Cultura IT"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <img width="48" height="48" src="https://i.ibb.co/kQQd2LT/logocit.png">
  </a>
</div>

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


<div class="abs-tr m-6">
  <a href="https://culturait.com.ar/" target="_blank" alt="Cultura IT"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <img width="48" height="48" src="https://i.ibb.co/kQQd2LT/logocit.png">
  </a>
</div>

<style>
h1 {
  font-size: 80px
}
</style>
