<<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3 
      h1 Plan de Acción
    .bloque-texto-a.color-primario.p-4.p-md-5.mb-5 
      .row.m-0.align-items-center.justify-content-between
        .col-lg-4.mb-4.mb-lg-0
          h2.mb-0 
          img(src='@/assets/curso/tema3-img1.svg', alt='Texto que describa la imagen') 
        .col-lg-8
          .bloque-texto-a__texto.p-4
            p Elaborar un plan de acción es un procedimiento importante para organizar la implementación de una estrategia que determinará qué, quién, cuándo y con qué costo necesita hacerse cada actividad. El mismo debe ser organizado teniendo en cuenta los objetivos estratégicos, resultados, y productos a ser logrados; además, deberá incluir un plan de financiamiento, un presupuesto y un proceso de monitoreo y evaluación.
              br
              br

    p.mb-5
      strong Los pasos que se debe seguir para elaborar un plan de acción son los siguientes:

    .row.justify-content-center
      .col-lg-10
        .row.mb-5
          .col-lg-4.d-flex
            .tarjeta-numerada.color-primario.p-5
              .tarjeta-numerada__numero
                .h2 1
              p.text-center
                b Define los objetivos.
              p.text-center Dicho plan de acción debe tener un objetivo claro, conciso y medible. No puedes iniciar un plan de acción si no sabes lo que quieres lograr con él ni en cuánto tiempo.
          .col-lg-4.d-flex
            .tarjeta-numerada.color-primario.p-5
              .tarjeta-numerada__numero
                .h2 2
              p.text-center
                b Detalla las estrategias.
              p.text-center A partir de este punto se deben especificar las estrategias que se seguirán para lograr dicho objetivo. Estas deben mostrar el camino a seguir durante el desarrollo y ejecución del plan de acción.
          .col-lg-4.d-flex
            .tarjeta-numerada.color-primario.p-5
              .tarjeta-numerada__numero
                .h2 3
              p.text-center
                b Plantea las tareas.
              p.text-center Luego, se deben establecer los pasos a seguir o tareas de cada una de las estrategias planteadas. Las tareas deben ser lo más específicas y detalladas posibles, reflejando cada paso necesario.
        .row
          .col-lg-4.d-flex
            .tarjeta-numerada.color-primario.p-5
              .tarjeta-numerada__numero
                .h2 4
              p.text-center
                b Elabora una carta Gantt.
              p.text-center Las tareas deben tener tiempos específicos, fechas de inicio y de finalización, para lo cual es aconsejable adaptar al formato del plan de acción una gráfica de Gantt para tal propósito.
          .col-lg-4.d-flex
            .tarjeta-numerada.color-primario.p-5
              .tarjeta-numerada__numero
                .h2 5
              p.text-center
                b Designa responsables.
              p.text-center Se deben asignar los responsables de cada tarea, quienes preferentemente deben ser los que están involucrados en la elaboración del plan de acción.
          .col-lg-4.d-flex
            .tarjeta-numerada.color-primario.p-5
              .tarjeta-numerada__numero
                .h2 6
              p.text-center
                b Ejecuta el plan.
              p.text-center Se procede a la ejecución del plan de acción. Cada responsable ya sabe las tareas que debe ejecutar para cumplir con las estrategias planteadas y lograr el objetivo final del plan.

    Separador

    #t_3_1.titulo-segundo.color-primario
      h2 3.1  Direccionamiento estratégico

    p.mb-5

    .titulo-sexto.color-acento-botones.mb-4
      h5 Figura 6
      span Enfoque

    .row
      .col-lg-11
        figure.mb-5
          img(src="@/assets/curso/tema3-img2.svg")

    p.mb-5

    #t_3_2.titulo-segundo.color-primario
      h2 3.2  Objetivos y metas

    p.mb-5
      br
      br
      | Por su parte, las metas son el resultado de una serie de condiciones que una empresa desea alcanzar en un determinado espacio de tiempo. Se componen de acciones y objetivos que permiten el logro de un propósito organizacional.

    .row.justify-content-center.mb-5
      .col-lg-2
        figure.p-3
          img(src="@/assets/curso/tema3-img3.svg")
      .col-lg-5
        .bloque-texto-d.color-acento-contenido.p-4
          .bloque-texto-d__texto.mb-2
            i.fas.fa-quote-left
            h2 Según la Universidad <br>ESAN (2019)
            br
            br
            h3.text-regular Los objetivos y las metas describen el logro de un propósito particular de una organización. Sin embargo, ambos se diferencian en tres aspectos importantes: <strong>espacio, tiempo y efecto</strong>.
            i.fas.fa-quote-right
    .row.justify-content-center.mb-5.g-0
      .col-lg-4
        figure
          img(src="@/assets/curso/tema3-img4.svg")
      .col-lg-5.other-before
        p.px-4.py-5.ps-5 Una de las diferencias más importantes entre los objetivos y las metas es la medición. Los objetivos, al tener resultados específicos, pueden ser medidos con facilidad. Las metas, en cambio, al tener resultados abstractos no permiten ser medidas con exactitud.
          br
          br
          | Es decir, <strong>la meta está asociada a la visión de la organización, es a donde se quiere llegar con los resultados esperados,</strong> mientras que <strong>los objetivo son la misión, el paso a paso que se debe seguir para lograr la meta. </strong>

    .titulo-sexto.color-acento-botones.mb-4
      h5 Tabla 3
      span Diferencias entre meta y objetivo

    .tabla-b.color-acento-contenido.mb-5
      table
        tr
          td(style="width: 25%").left.table-header-especial.text-white.fw-bolder
          td(style="width: 35%").table-header-especial.text-white.fw-bolder Meta
          td(style="width: 40%").right.table-header-especial.text-white.fw-bolder Objetivo
        tr
          td(style="width: 25%").left.fw-bolder Definición
          td(style="width: 35%") Aspiración o deseos que se quieren cumplir en el futuro.
          td(style="width: 40%").right Propósito concreto que se quiere realizar para alcanzar una meta.
        tr
          td(style="width: 25%").left.fw-bolder Características
          td(style="width: 35%")
            ul.lista-ul
              li
                i.fas.fa-angle-right
                | Emotiva.
              li
                i.fas.fa-angle-right
                | Ambiciosa.
              li
                i.fas.fa-angle-right
                | Abstracta.
              li
                i.fas.fa-angle-right
                | No establece un tiempo específico para alcanzarla.
              li
                i.fas.fa-angle-right
                | Según el tiempo, puede ser a corto, a mediano o a largo plazo.
              li
                i.fas.fa-angle-right
                | Según su intención, puede ser de dominio, de desempeño o de evitación.
          td(style="width: 40%").right
            ul.lista-ul
              li
                i.fas.fa-angle-right
                | Serio y sin emotividad.
              li
                i.fas.fa-angle-right
                | Realista.
              li
                i.fas.fa-angle-right
                | Medible.
              li
                i.fas.fa-angle-right
                | Establece un tiempo determinado para su cumplimiento..
              li
                i.fas.fa-angle-right
                | Generales.
              li
                i.fas.fa-angle-right
                | Específicos.
        tr
          td(style="width: 25%").left.fw-bolder Tipos
          td(style="width: 35%")
            ul.lista-ul
              li
                i.fas.fa-angle-right
                | Según el tiempo, puede ser a corto, a mediano o a largo plazo.
              li
                i.fas.fa-angle-right
                | Según su intención, puede ser de dominio, de desempeño o de evitación.
          td(style="width: 40%").right
            ul.lista-ul
              li
                i.fas.fa-angle-right
                | Generales.
              li
                i.fas.fa-angle-right
                | Específicos.
        tr
          td(style="width: 25%").left.fw-bolder Ejemplos
          td(style="width: 35%")
            ul.lista-ul
              li
                i.fas.fa-angle-right
                | Bajar de peso.
              li
                i.fas.fa-angle-right
                | Conseguir trabajo.
              li
                i.fas.fa-angle-right
                | Ahorrar dinero.
              li
                i.fas.fa-angle-right
                | Ser mejor estudiante.
          td(style="width: 40%").right
            ul.lista-ul
              li
                i.fas.fa-angle-right
                | Inscribirse en un gimnasio.
              li
                i.fas.fa-angle-right
                | Comprar un carro dentro de un año.
              li
                i.fas.fa-angle-right
                | Sacar notas las más altas en la clase.

    h4 Nota. Tomada de Lugo (2020)
    Separador


    #t_3_3.titulo-segundo.color-primario
      h2 3.3  Actividades, recursos y responsables

    p.mb-5
      br
      | El diagrama de Gantt es una herramienta muy efectiva en este proceso, la cual es denominada “hoja de ruta”, a través de ella se gestionan las actividades, recursos y responsables necesarios para dar cumplimiento a los objetivos y alcanzar las metas.
      br
      br
      strong Según la Universidad Unade (2020), los componentes que se deben tener en cuenta al elaborar un diagrama de Gantt son los siguientes:

    .row.justify-content-center.mb-5
      .col-lg-11
        ImagenInfografica.color-acento-contenido
          template(v-slot:imagen)
            figure
              img(src="@/assets/curso/tema3-img6.svg")

          .row.tarjeta.color-acento-botones.p-3(x="1.5%" y="52%")
            .col-lg-2
              figure
                img(src="@/assets/curso/tema3-img7.svg")
            .col-lg-9
              p.mb-0
                strong Tareas
                br
                | Aquí deben incluirse todas las actividades necesarias para lograr completar el proyecto. Desde las más sencillas hasta las más complejas; olvidar alguna de ellas puede generar retrasos.
          .row.tarjeta.color-acento-botones.p-3(x="42%" y="21%")
            .col-lg-2
              figure
                img(src="@/assets/curso/tema3-img8.svg")
            .col-lg-9
              p.mb-0
                strong Tareas independientes
                br
                | Algunas acciones pueden realizarse sin que afecten a otras, sin embargo, existen otras que, si no se completan, frenan el proceso. Por esta razón, deben tenerse en cuenta para no cometer errores.
          .row.tarjeta.color-acento-botones.p-3(x="65.1%" y="7.6%")
            .col-lg-2
              figure
                img(src="@/assets/curso/tema3-img9.svg")
            .col-lg-9
              p.mb-0
                strong Fechas
                br
                | El proyecto debe tener fijado un principio y un final, de lo contrario puede extenderse en el tiempo sin lograr los objetivos; o no comenzar nunca por un aplazamiento continuo. Marque las fechas de forma realista y teniendo en cuenta su viabilidad.
          .row.tarjeta.color-acento-botones.p-3(x="36.2%" y="2.2%")
            .col-lg-2
              figure
                img(src="@/assets/curso/tema3-img10.svg")
            .col-lg-9
              p.mb-0
                strong Progreso Evolución
                br
                | El gráfico mostrará cómo se está desarrollando el proyecto. Podremos visualizar las tareas finalizadas, las pendientes y las que están en proceso. Así verá a tiempo real si el proyecto está funcionando según lo previsto.
          .row.tarjeta.color-acento-botones.p-3(x="71.1%" y="65.6%")
            .col-lg-2
              figure
                img(src="@/assets/curso/tema3-img12.svg")
            .col-lg-9
              p.mb-0
                strong Plazos Preventivos
                br
                | Una vez marcado el comienzo y el final, es importante planificar los tiempos para cada tarea. De este modo, podremos garantizar que cada acción se desarrolla en su momento y no perjudica al resto.

    h3.titulo-tercero

    p.mb-5

    figure
      img(src="@/assets/curso/tema3-img13.svg")

</template>

<script>
import Card2 from '../components/Card2.vue'
export default {
  name: 'Tema3',
  components: {
    Card2,
  },
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
