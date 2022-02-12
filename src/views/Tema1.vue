<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Diagnóstico empresarial
      
    .bloque-texto-a.color-acento-contenido.p-4.p-md-5.mb-5 
      .row.m-0.align-items-center.justify-content-between
        .col-lg-4.mb-4.mb-lg-0
          img(src="@/assets/curso/tema1/img01.svg") 
        .col-lg-8
          .bloque-texto-a__texto.p-2
            .tarjeta.color-white.p-0
              p También llamado diagnóstico organizacional es un estudio que permite evaluar la situación de una empresa en un momento dado, partiendo de factores del microentorno y macroentorno que pueden impactar positiva o negativamente en su proceso productivo, siempre es fundamental conocer el contexto organizacional de cualquier empresa a nivel interno y externo, entendiendo estos como las herramientas para conocer su estructura si se desea hacer cambios a cualquier nivel: comercial, corporativo, económicos y tecnológicos que permitan conocer la realidad de la empresa.

    figure.mb-4
      .video
        iframe(width="560" height="315" src="https://youtu.be/PHwgIYMHomY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      
      
    h3.text-center.titulo-tercero Según SENA (2014):
 
    .bloque-texto-f.color-secundario.pt-4.px-5.mb-5
      .bloque-texto-f__comillas
        i.fas.fa-quote-left
        i.fas.fa-quote-right
      h4.text-regular.bloque-texto-f__texto  El microentorno está compuesto por factores que interactúan e influyen en la dinámica de una empresa. Entre ellos podemos encontrar a los clientes, los proveedores, las entidades financieras, la competencia, socios, intermediarios y la empresa como tal. Así mismo, en un ámbito general se estudian los factores del macroentorno compuesto por fuerzas difíciles de controlar para la organización y que pueden convertirse en amenazas u oportunidades en un momento dado, dependiendo del radar que posea la empresa para aprovechar o mitigar su impacto. Entre ellos podemos encontrar factores económicos, políticos, legales, tecnológicos, sociales y ambientales”.
      .bloque-texto-f__autor.mb-3
       
      .bloque-texto-f__avatar
        .bloque-texto-f__avatar__img
          img(src='@/assets/curso/tema1/img02.svg')

    p.text-bold.mb-4 Los grupos de interés que influyen dentro del microentorno de una organización son los siguientes:
        
    TabsA.color-primario.mb-5
    
      .tarjeta.color-acento-botones.p-4(titulo="Clientes")
        h4 Clientes
        .row
          .col-9
            p.mb-0 Generalmente, los clientes conforman el grupo de interés más grande de una organización, en tanto que son ellos quienes, a través de sus preferencias e intereses, determinan posibles áreas de acción para que una empresa pueda incursionar. Cualquier cambio en sus preferencias y gustos puede suponer en muchos casos una excelente oportunidad o, por el contrario, puede constituirse en un grave riesgo. Estos cambios pueden darse muy rápido o muy lento, pero es imprescindible que las empresas los detecten y puedan adaptarse fácilmente a ellos.
          .col-3
            img(src='@/assets/curso/tema1/img03.svg')
      .tarjeta.color-acento-botones.p-4(titulo="Competencia")
        h4 Competencia

        .row
          .col-9
            p.mb-0  Es de vital importancia conocer cuáles son los elementos básicos que permiten establecer la actividad competitiva o el grado de rivalidad de las empresas que hacen parte del sector específico donde se desempeña una organización. Así mismo, el tipo de competencia se podrá identificar teniendo en cuenta el número de competidores, la diversidad de estrategias, la estructura de costes, la evolución de la demanda, entre otros elementos, lo cual puede precisarse en un conjunto de ventajas competitivas.
          .col-3
            img(src='@/assets/curso/tema1/img03.svg')

      
      .tarjeta.color-acento-botone.p-4(titulo="Proveedores")
        h4 Proveedores
        .row
          .col-9
            p.mb-0  Constituyen otro grupo de interés de gran relevancia para la organización, en tanto que son ellos quienes proporcionan los recursos e insumos que la empresa necesita para producir bienes y servicios. Los proveedores tienen un efecto directo en la eficiencia de la compañía y un efecto indirecto frente a su capacidad de ganar clientes, si una empresa cuenta con recursos e insumos de alta calidad, así mismo, producirá productos de buena calidad y atraerá más clientes.

          .col-3
            img(src='@/assets/curso/tema1/img04.svg')
      
      .tarjeta.color-acento-botones.p-4(titulo="Accionistas")
        h4 Accionistas
        .row
          .col-9
            p.mb-0  Son las personas que proporcionan capital e inversiones a la empresa; su principal interés está dirigido a la rentabilidad, transparencia e integridad administrativa. Allí se destaca todo lo relacionado con el gobierno corporativo que está compuesto por los accionistas, los directivos y el consejo administrativo, y se basa en establecer y controlar la dirección estratégica y su desempeño en lo que respecta a las expectativas de la empresa; es un mecanismo que da fuerza estratégica a las organizaciones y refleja las normas de la organización.
          .col-3
            img(src='@/assets/curso/tema1/img06.svg')

      .tarjeta.color-acento-botones.p-4(titulo="Sector financiero")
        h4 Sector financiero 

        .row
          .col-9
            p.mb-0 Es la agrupación de las entidades públicas y privadas encargadas de desarrollar actividades de administración, utilización, aprovechamiento e inversión de los recursos captados en el país.

          .col-3
            img(src='@/assets/curso/tema1/img07.svg')

    p.text-bold.mb-4 El macroentorno está compuesto por fuerzas que no se pueden controlar y pueden impactar en el proceso productivo de una organización.
    .row.justify-content-center.mb-4
      .col-2
        img(src='@/assets/curso/tema1/img08.svg')
        p.text-center.text-bold.mb-0 Factores Económicos
      .col-2
        img(src='@/assets/curso/tema1/img09.svg')
        p.text-center.text-bold.mb-0 Factores Político - Legales

      .col-2
        img(src='@/assets/curso/tema1/img10.svg')
        p.text-center.text-bold.mb-0 Factores Tecnológicos

      .col-2
        img(src='@/assets/curso/tema1/img11.svg')
        p.text-center.text-bold.mb-0 Factores Sociales
      .col-2
        img(src='@/assets/curso/tema1/img12.svg')
        p.text-center.text-bold.mb-0 Factores Ambientales

    .row.justify-content-center.mb-4
      .col-lg-9.BG01.p-4.mb-2
        h4 Factores Económicos
        p.mb-4 #[strong Nivel de inflación.] Ocurre cuando el Gobierno sube el nivel de inflación, como consecuencia se genera aumento de los diferentes costos para las empresas y esto conlleva a que esta deba vender a precios más altos, impactando negativamente el aumento de las ventas.
        p.mb-4 #[strong Política Fiscal.] El Gobierno nacional decide subir los impuestos afectado a una organización de forma negativa, por ello la obliga a pagar más gravámenes y disminuyendo la circulación de dinero, es decir, las ventas
        p.mb-4 #[strong Política monetaria.] Se presenta cuando se disminuyen las tasas de interés, por ello una organización podrá conseguir préstamos más baratos y las personas se motivan a comprar más.
     
      .col-9
        h4 Factores Político - Legales
        p.mb-4 
  
</template>

<script>
import Muestras from '../components/Muestras' // borrar una vez el componente "Muestras" no se necesite
export default {
  name: 'DiagnSticoEmpresarial',
  components: {
    Muestras, // borrar una vez el componente "Muestras" no se necesite
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
