

    <template>
    <div class="navbar bg-base-300 shadow-lg fixed z-10">
    <img alt="logo" src="@/assets/logo.png" class="w-16 mx-4" />
        <h1 class="navbar-center text-3xl text-primary">Desarrollo Plataforma Full-Stack</h1>
        </div>
        <div class="pt-20">
        <div tabindex="0" class="collapse hover:border-2 hover:border-success">
    <input type="checkbox" class="peer"> 
    <div class="collapse-title bg-primary text-primary-content peer-checked:bg-success peer-checked:text-secondary-content">
        Resumen
    </div>
    <div class="collapse-content bg-primary text-primary-content peer-checked:bg-black peer-checked:text-white "> 
        <p class="p-8">La presente es una propuesta con un alcance técnico tentativo descrito líneas debajo acorde al requerimiento enviado por GrowBy, marca de HUB NEGOCIOS CREATIVOS S.A.C. y detallado en el <a href="https://drive.google.com/file/d/1LKDEAod76TwsbwkAS-QWUJXs2Dts-Ldy/view?usp=sharing" class="link">presente</a> documento.</p>
    </div>
    </div>
    <div tabindex="0" class="collapse hover:border-2 hover:border-success">
        <input type="checkbox" class="peer"> 
        <div class="collapse-title bg-primary text-primary-content peer-checked:bg-success peer-checked:text-secondary-content">Objetivo</div>

        <div class="collapse-content bg-primary text-primary-content peer-checked:bg-black peer-checked:text-white"> <p class="p-8">Desarrollar una plataforma full-stack que cumpla con las características, integraciones y funcionalidades descritas en el requerimiento adjunto.</p>
        </div>
            </div>
      <div tabindex="0" class="collapse hover:border-2 hover:border-success">
    <input type="checkbox" class="peer"> 
    <div class="collapse-title bg-primary text-primary-content peer-checked:bg-success peer-checked:text-secondary-content">
Tecnologías a Utilizarse
</div>

        <div class="collapse-content bg-primary text-primary-content peer-checked:bg-black peer-checked:text-white overflow-y-scroll"> <p class="p-8">
    MEVN (Siglas para MongoDB, Express, VueJS y NodeJS) es un stack reconocido en la industria y fuertemente consolidado por su robustez, flexibilidad, versatilidad tanto para el desarrollo como para la operación del mismo, para este caso en particular se estarán empleando artefactos de última generación para el desarrollo y despliegue del proyecto</p> 
    <img src="./assets/img/mevn.jpg" alt="mevn" class="invert" /> 
    
           <div class="dropdown">
  <label tabindex="0" class="btn m-1">  <i class="mdi mdi-chevron-down mr-4"></i>  Tecnología por capa</label>
  <ul tabindex="0" class="dropdown-content menu p-2 shadow bg-base-100 rounded-box w-96 text-black">
    <li> Bases de Datos: <a href="https://www.mongodb.com/" class="link hover:text-green-500"><i class="icon icon-mongodb "></i>MongoDB (NoSQL)</a> <a href="https://www.postgresql.org" class="link hover:text-blue-800"><i class="icon icon-postgres "></i>Postgres (SQL)</a> <a href="https://redis.com/" class="link hover:text-red-800"><i class="icon icon-redis "></i>Redis (Caché)</a></li>
    <li>Backend:<a href="https://expressjs.com/"  class="link hover:text-lime-500"><i class="mdi mdi-nodejs "></i>  ExpressJS (Framework de NodeJS)</a></li>
<li>Frontend:<a href="https://nuxtjs.org/"  class="link hover:text-green-400"  ><i class="mdi mdi-nuxt "></i>NuxtJS (Framework de VueJS)</a></li>
<li>Plataforma: <a href="https://www.docker.com/"  class="link hover:text-blue-400"><i class="mdi mdi-docker "></i>Docker (Infraestructura como código)</a></li>
  </ul>
</div>
        </div>
    </div>

<div tabindex="0" class="collapse hover:border-2 hover:border-success overflow-hidden">
    <input type="checkbox" class="peer"> 
    <div class="collapse-title bg-primary text-primary-content peer-checked:bg-success peer-checked:text-secondary-content">Etapas del Proyecto</div>
     <div class="collapse-content bg-primary text-primary-content peer-checked:bg-white peer-checked:text-black overflow-hidden"> <div class="p-8">
         <ul class="steps">
  <li data-content="🖌️" class="step step-neutral"><label for="modal1" class="btn btn-secondary modal-button">Fase 1</label><input type="checkbox" id="modal1" class="modal-toggle">
        <div class="modal">
        <ul class="modal-box relative">
            <label for="modal1" class="btn btn-sm btn-circle absolute right-2 top-2">X</label>
           <strong>Maquetado y funcionalidades del Frontend</strong> 
            <li>Se crea el frontend con el framework de desarrollo NuxtJS</li>
            <li>Se crean los componentes y vistas del frontend según diseño entregado por Growby/Cliente</li>
            <li>Se crean las funcionalidades básicas: formulario de suscripcion, formulario de contacto, libro de reclamaciones</li>
        </ul>
        </div></li>
  <li data-content="⚙️" class="step step-neutral"><label for="modal2" class="btn btn-primary modal-button">Fase 2</label><input type="checkbox" id="modal2" class="modal-toggle"><div class="modal">
        <ul class="modal-box relative">
            <label for="modal2" class="btn btn-sm btn-circle absolute right-2 top-2">X</label>
              <strong>Funcionalidades Core</strong> 
            <li>Módulo Autenticación Multinivel</li>
            <li>Módulo Ecommerce</li>
            <li>Módulo Gestión de Usuarios</li>
            <li>Módulo CMS</li>
        </ul>
        </div></li>
  <li data-content="🔗" class="step step-neutral"><label for="modal3" class="btn btn-secondary modal-button">Fase 3</label><input type="checkbox" id="modal3" class="modal-toggle"><div class="modal">
        <ul class="modal-box relative">
            <label for="modal3" class="btn btn-sm btn-circle absolute right-2 top-2">X</label>
            <strong>Integraciones con Terceros</strong> 
            <li>Integración con Google Analytics y Dashboard Admin</li>
            <li>Integración con Hotjar y Dashboard Admin</li>
            <li>Integración con MercadoPago</li>
            <li>Integración con Mailchimp o AWS SESv2</li>
            <li>Integración con Hubspot CRM (sólo SSO)</li>
            <li>Integración con Titanx LMS (sólo SSO)</li>
        </ul>
        </div></li>
    <li data-content="💎" class="step step-neutral"><label for="modal4" class="btn btn-primary modal-button">Fase 4</label><input type="checkbox" id="modal4" class="modal-toggle"> <div class="modal">
        <ul class="modal-box relative">
            <label for="modal4" class="btn btn-sm btn-circle absolute right-2 top-2">X</label>
             <strong>Despliegue y pruebas finales</strong> 
            <li>Despliegue en plataforma AWS o Digital Ocean sobre nodos Docker autoescalables orquestados por DockerSwarm o Kubernetes Engine</li>
            <li>
                Despliegue del modelo de base de Datos (MongoDB, MySQL y Redis) a solicitud del cliente: On-Premise, Cloud, Hosting, Docker, Serverless, etc.
            </li>
            <li>Testing y QA automatizado mediante el framework JEST</li>
        </ul>
        </div></li>
</ul>
</div>
</div>
 <div tabindex="0" class="collapse hover:border-2 hover:border-success">
    <input type="checkbox" class="peer"> 
    <div class="collapse-title bg-primary text-primary-content peer-checked:bg-success peer-checked:text-secondary-content">
        Costos y Tiempos
    </div>
    <div class="collapse-content bg-primary text-primary-content peer-checked:bg-black peer-checked:text-white "> 
        <div>        <button class="btn btn-primary my-4">Fase 1</button>
        <button class="btn btn-success my-4">S/ 1200</button> <button class="btn btn-primary my-4">18d</button>
        </div>
     <div>        <button class="btn btn-primary my-4">Fase 2</button>
        <button class="btn btn-success my-4">S/ 800</button> <button class="btn btn-primary my-4">12d</button>
             <div>        <button class="btn btn-primary my-4">Fase 3</button>
        <button class="btn btn-success my-4">S/ 2000</button> <button class="btn btn-primary my-4">21d</button>
        </div>
             <div>        <button class="btn btn-primary my-4">Fase 4</button>
        <button class="btn btn-success my-4">S/ 800</button>  <button class="btn btn-primary my-4">9d</button>
        </div>
        </div>
    </div>
 </div>
</div>
</div>
<h1 class="btn btn-success w-full">Oferta <strong><small>- vigente hasta el 15/03/2022 -</small></strong> Recibe adicionalmente un bot para automatización de <i class="mdi mdi-instagram text-3xl mx-4" aria-hidden="true"></i></h1>

    </template>
