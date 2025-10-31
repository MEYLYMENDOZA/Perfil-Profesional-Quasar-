<template>
  <q-page>
    <div class="row">
      
      <div class="col-xs-12 col-md-4">
        <ProfileSidebar />
      </div>

      <div class="col-xs-12 col-md-8 q-pa-xl">
        
        <h1 class="text-h3 text-weight-bolder text-grey-9 q-mb-lg">
          Meyly Mendoza Cobeñas
        </h1>

        <SectionHeader title="Experiencia" icon="work" />
        <div class="q-pl-sm">
          
          <Experiencia 
            title="Proyecto “Dave Octopus”" 
            dates="Primaver - 2024" 
            description="Coautora y creadora de Dave Octopus, proyecto enfocado en el desarrollo de un prototipo interactivo utilizando Arduino R3 y programación en C++ para la asistencia emocional de niños con síndrome de Asperger."
            link-url="https://link.springer.com/book/10.1007/978-981-97-4780-1"
            link-text="Ver Publicación (Springer)"
          />

          <Experiencia 
            title="Creación de página web de IGD Group SAC" 
            dates="Mayo - Septiembre 2024" 
            description="Creación de la página web de IGD Group SAC, utilizando .NET Core para backend, PostgreSQL como gestor de base de datos, y tecnologías frontend en .NET. Control de versiones implementado con Git."
            link-url="https://igdgroupsac.com/#/"
            link-text="Ver Sitio Web"
          />

          <Experiencia
            title="Coordinadora de Finanzas y Desarrolladora Full Stack en CIIDESOFT" 
            dates="Mayo 2025 - Actualidad" 
            description="Me desempeño como Coordinadora de Finanzas y Desarrolladora Full Stack en CIIDESOFT de la Universidad ESAN, donde apoyo en la gestión financiera y participo en el desarrollo de soluciones tecnológicas tanto en frontend como en backend."
            :link-url="null"
            link-text=""
          />
        </div>

        <SectionHeader title="Cursos | Idiomas" icon="bookmark" class="q-mt-xl" />
        <div class="q-pl-sm">
          
          <Experiencia
            title="Idioma Inglés" 
            dates="Nivel Oral Bilingüe, Nivel Escrito Intermedio." 
            description=""
            :link-url="null"
            link-text=""
          />
          
          <Experiencia
            title="Curso de Power BI" 
            dates="27 de agosto al 17 de septiembre de 2024" 
            description=""
            :link-url="null"
            link-text=""
          />

          <Experiencia
            title="SQL Server" 
            dates="27 de agosto al 17 de septiembre de 2024" 
            description=""
            :link-url="null"
            link-text=""
          />
          
          <Experiencia
            title="Tablas Dinámicas y Dashboards" 
            dates="27 de agosto al 17 de septiembre de 2024" 
            description=""
            :link-url="null"
            link-text=""
          />
        </div>

      </div>
    </div>
  </q-page>
</template>

<script setup>
import ProfileSidebar from 'src/components/ProfileSidebar.vue';
import SectionHeader from 'src/components/SectionHeader.vue';
import Experiencia from 'src/components/Experiencia.vue';
// Nota: La foto se importa dentro de ProfileSidebar.vue para mantener la lógica encapsulada.
</script>

<style scoped>
/* Puedes eliminar el estilo del h3 que tenías antes */
</style>