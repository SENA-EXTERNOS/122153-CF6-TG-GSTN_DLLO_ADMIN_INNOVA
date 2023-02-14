<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Archivos de gestión e instrumentos archivísticos

    .row.mb-5
      .col-md-5
        figure(data-aos='zoom-in')
          img(src='@/assets/template/tema03/t3-i1.jpg')

      .col-md-7
        p Los instrumentos archivísticos, de acuerdo con el Archivo General de la Nación en el decreto 1080 del 2015, son herramientas de gestión documental que permiten a la entidad, el manejo óptimo de su acervo documental, de acuerdo con los lineamientos establecidos (Capítulo V).

    p Existen dos principios básicos de archivo:

    .row.justify-content-center.mb-5
      .col-xl-4.col-lg-7.col-md-9.col-11.mb-4.mb-xl-0
        .crd_hover_txt(data-aos='flip-left')
          .crd_hover_txt--img
            figure
              img(src='@/assets/template/tema03/t3-i2.jpg', alt='alt')
          .crd_hover_txt--body
            h5.mb-3.text-center El principio de origen o procedencia
            p.mb-0.text-center Determina la clasificación, organización, descripción y distribución, permitiendo identificarlos con anticipación y facilitando su evaluación.

      .col-xl-4.col-lg-7.col-md-9.col-11.mb-4.mb-xl-0
        .crd_hover_txt(data-aos='flip-left')
          .crd_hover_txt--img
            figure
              img(src='@/assets/template/tema03/t3-i3.jpg', alt='alt')
          .crd_hover_txt--body
            h5.mb-3.text-center El ciclo de vida del documento
            p.mb-0.text-center Dando lugar a un diseño integrado de gestión de documentos sin comprometer la configuración de la red, los archivos servirán como residencias sucesivas para los documentos según su antigüedad.

    .row.mb-5
      .col-md-7
        p Las razones más comunes que pueden desperdiciar este principio inicial son:
        br
        ul
          li 
            i.fas.fa-check.color-icon-check
            |
            | Ignorancia o desconocimiento de las partes (los empleados de cada oficina).
          br
          li 
            i.fas.fa-check.color-icon-check
            |
            | No tener instrucciones para usar procedimientos.
          br
          li 
            i.fas.fa-check.color-icon-check
            |
            | Desconocimiento del manejo físico de los documentos porque el propio trámite o la administración dictan el arreglo correspondiente.
          br
          li 
            i.fas.fa-check.color-icon-check
            |
            | Deshabilite de las acciones, no permitir el seguimiento rápido de registros y el no especifique si una acción está en curso o en qué etapa se encuentra.
          br
          li 
            i.fas.fa-check.color-icon-check
            |
            | Los métodos incorrectos para ubicar documentos que dieron como resultado secuencias que no reflejan las operaciones existentes.
          br
          li 
            i.fas.fa-check.color-icon-check
            |
            | Agrupación por tipo de documento: pedido, certificado, correo recibido, correo enviado, factura, certificado.
          br
          li 
            i.fas.fa-check.color-icon-check
            |
            | El proceso de producción y distribución de documentos incorrectos como documentos duplicados o mala gestión en el envío de copias.
          br
          li 
            i.fas.fa-check.color-icon-check
            |
            | Desenfoque de la diferencia entre antecedentes y documentos de respaldo.
      .col-md-5
        figure(data-aos='zoom-in')
          img(src='@/assets/template/tema03/t3-i4.jpg')

    .row.mb-5
      .col-lg-12.px-5
        .cajon.color_primario_txt_destacado.p-4
          p.mb-0 Por ello, el mejor método organizativo que se puede aplicar en el archivo es recrear y respetar el orden original en el que los documentos estuvieron o debieron estar en manos de sus creadores. Después de completar los pasos de identificación se pueden clasificar los documentos.

    h3.mb-4
      i.fas.fa-square.color_texto_acento.me-3
      | Elementos del archivo

    p Tenga presente que al desarrollar la creación del archivo, es necesario registrar los datos necesarios para que el sistema pueda determinar la ubicación del archivo y controlar sus registros lógicos.
    br
    | Y las partes que lo conforman son:

    .row.d-flex.justify-content-center.mt-5
      .col-md-8
        ImagenInfografica.color-primario(data-aos='zoom-in')
          template(v-slot:imagen)
            figure
              img(src='@/assets/template/tema03/t3-i5.svg')

          .tarjeta.color-acento-botones_black.p-3(x='96%', y='11%', numero='+')
            p 1. Archivadores de anillas: permiten guardar documentos de forma vertical protegiéndolos y dándoles una clasificación, pueden ser de material plástico o cartón.

          .tarjeta.color-acento-botones_black.p-3(x='77%', y='30%', numero='+')
            p 2. Carpetas: son usadas para guardar los documentos y pueden ser de tamaño carta u oficio.

          .tarjeta.color-acento-botones_black.p-3(x='55%', y='71%', numero='+')
            p 3. Carpetas colgantes: son puestas dentro de los muebles archivadores con guías dentro.

          .tarjeta.color-acento-botones_black.p-3(x='82%', y='69%', numero='+')
            p 4. Subcarpetas: se utilizan dentro de las carpetas de archivo separando los documentos, son de cartulina y tienen un color diferente para una mejor organización.

          .tarjeta.color-acento-botones_black.p-3(x='89%', y='93%', numero='+')
            p 5. Guías para archivo: son tarjetas indicadoras hechas de cartón puestas en la parte superior de la carpeta, evidenciando el título o nombre del asunto del documento o el número.

    h3.mb-4
      i.fas.fa-square.color_texto_acento.me-3
      | Importancia de los archivos

    .row.mb-5
      .col-md-5
        figure(data-aos='zoom-in')
          img(src='@/assets/template/tema03/t3-i6.jpg')

      .col-md-7
        p Podemos así concluir que los documentos son importantes para cualquier aspecto de la vida ya que facilitan los procesos educativos, de investigación y garantizan la protección de los derechos. Los archivos son una parte esencial de cualquier negocio, empresa u organización porque sin ellos no hay historia, sin embargo, muchos se olvidan de la importancia que tiene el capturar, organizar y simplificar los documentos y archivos, ignorando las necesidades que tienen todas las operaciones dentro de la organización. En consecuencia de lo anterior, la Declaración Universal sobre los Archivos promueve la preservación y accesibilidad universal del patrimonio documental, debido a que los archivos protegen los derechos, fortalecen la memoria colectiva, sostienen los gobiernos y promueven los procesos transparentes.

    p El Archivo General de la Nación de acuerdo a lo establecido por el artículo 5 del Acuerdo No. 09 del año 2012, tiene como objetivos:

    .row
      .tarjeta--container.row.mb-5
        .col-md.tarjeta.color-primario-claro.p-5
          .row.justify-content-center.mb-4
            .col-6
              figure(data-aos='zoom-in')
                img(
                  src='@/assets/template/tema03/t3-i7.png',
                  alt='Texto que describa la imagen'
                )
          h2.text-center Velar
          p.text-center Velar por la preservación del patrimonio documental de la Nación y facilitar el acceso a dicho patrimonio por parte de la ciudadanía en general.
          
        .col-md.tarjeta.color-secundario-claro.p-5
          .row.justify-content-center.mb-4
            .col-6
              figure(data-aos='zoom-in')
                img(
                  src='@/assets/template/tema03/t3-i8.png',
                  alt='Texto que describa la imagen'
                )

          h2.text-center Custodiar
          p.text-center Custodiar, conservar, recuperar y difundir el patrimonio documental de la Nación.

        .col-md.tarjeta.color-primario-claro.p-5
          .row.justify-content-center.mb-4
            .col-6
              figure(data-aos='zoom-in')
                img(
                  src='@/assets/template/tema03/t3-i9.png',
                  alt='Texto que describa la imagen'
                )
          h2.text-center Coordinar
          p.text-center Coordinar las instituciones que integran el Sistema Nacional de Archivos para que sean factores de desarrollo Cultural y material del país, en armonía con el Plan Nacional Económico y Social adoptado por el Estado, así como también promover el establecimiento de adecuados servicios de referencia archivística de las instituciones que integran el Sistema Nacional de Archivos.


    .row.mb-5
      .tarjeta--container.row.mb-5
        .col-md.tarjeta.color-secundario-claro.p-5
          .row.justify-content-center.mb-4
            .col-6
              figure(data-aos='zoom-in')
                img(
                  src='@/assets/template/tema03/t3-i10.png',
                  alt='Texto que describa la imagen'
                )

          h2.text-center Asegurar
          p.text-center Asegurar el funcionamiento articulado del Sistema Nacional de Archivos.

        .col-md.tarjeta.color-primario-claro.p-5
          .row.justify-content-center.mb-4
            .col-6
              figure(data-aos='zoom-in')
                img(
                  src='@/assets/template/tema03/t3-i11.png',
                  alt='Texto que describa la imagen'
                )

          h2.text-center Promover
          p.text-center Promover y desarrollar acciones para establecer una cultura integradora de la archivística, la gestión documental y la gestión de la información útil y oportuna para la toma de decisiones y gestión eficiente de la administración.

        .col-md.tarjeta.color-secundario-claro.p-5
          .row.justify-content-center.mb-4
            .col-6
              figure(data-aos='zoom-in')
                img(
                  src='@/assets/template/tema03/t3-i12.png',
                  alt='Texto que describa la imagen'
                )

          h2.text-center Diseñar
          p.text-center Diseñar y vigilar la implantación del programa de gestión documental articulado con los sistemas de información en la administración pública.

    h3.mb-4
      i.fas.fa-square.color_texto_acento.me-3
      | Instrumentos archivísticos

    p De acuerdo con los lineamientos establecidos por el Archivo General de la Nación, los instrumentos archivísticos son herramientas de gestión documental que permiten a la organización el manejo óptimo de su acervo documental.

    .row.mb-5
      .col-lg-12.px-5.mb-2
        .cajon.color_primario_txt_destacado.p-4
          .row.px-5 
            .col-lg-2
              figure(data-aos='zoom-in')
                img(
                  src='@/assets/template/tema03/t3-i13.png',
                  alt='Texto que describa la imagen'
                )
            .col-lg-10
              p.mb-0 Adicionalmente, se encuentran las tablas de retención documental que son documentos construidos a partir de las funciones y de la estructura orgánica de cada entidad, son diseñadas a partir de las funciones de cada dependencia y relacionan los diferentes trámites que tiene cada una. En las entidades públicas estas tablas deben ser expuestas en sus sitios oficiales.
      .col-lg-12.px-5
        .cajon.acento-botones_txt_destacado.p-4
          .row.px-5 
            .col-lg-2
              figure(data-aos='zoom-in')
                img(
                  src='@/assets/template/tema03/t3-i14.png',
                  alt='Texto que describa la imagen'
                )
            .col-lg-10
              p.mb-0 De acuerdo con la Ley general de archivos en el artículo 24. Obligatoriedad de las tablas de retención, establece que será obligatorio para las entidades del Estado elaborar y adoptar las respectivas tablas de retención documental. Para ampliar la información, se invita a leer el <b>Acuerdo 39 del 2002</b>, por el cual se regula el procedimiento para la elaboración y aplicación de las tablas de retención documental en desarrollo del artículo 24 de la Ley 594 del 2000.

    .row.justify-content-center.mb-5 
      .col-lg-8 
        a.anexo.mb-4.mb-lg-0(
          href='https://www.alcaldiabogota.gov.co/sisjur/normas/Norma1.jsp?i=6351',
          target='_blank'
        )
          .anexo__icono
            img(src='@/assets/template/icono-link.svg')
          .anexo__texto
            strong Enlace Web.
            br
            | Acuerdo 39 de 2002, por el cual se regula el procedimiento para la elaboración y aplicación de las tablas de retención documental en desarrollo del artículo 24 de la Ley 594 de 2000.

    h3.mb-4
      i.fas.fa-square.color_texto_acento.me-3
      | Conservación documental

    .row.mb-5
      .col-lg-12.px-5.mb-2
        .cajon.color_primario_txt_destacado.p-4
          .row.px-5 
            .col-lg-2
              figure(data-aos='zoom-in')
                img(
                  src='@/assets/template/tema03/t3-i15.png',
                  alt='Texto que describa la imagen'
                )
            .col-lg-10
              p.mb-0 La protección de los materiales contenidos en archivos y bibliotecas requiere de la definición de estrategias y técnicas específicas basadas tanto en medidas preventivas como correctivas, con el fin de asegurar la integridad de los documentos y la garantía de su funcionalidad. Las medidas de conservación de documentos comprenden tanto a los impresos como a los digitales, esta acción pretende prolongar la posibilidad de utilización de los documentos en buenas condiciones durante el mayor tiempo posible.

    .row.mb-5
      .col-lg-12.px-5
        .cajon.acento-botones_txt_destacado.p-4
          p.mb-0 Recuerde explorar los demás recursos que se encuentran disponibles en este componente formativo; para ello, diríjase al menú principal, donde encontrará la síntesis, una actividad didáctica para reforzar los conceptos estudiados, material complementario, entre otros.
</template>

<script>
export default {
  name: 'Tema3',
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
