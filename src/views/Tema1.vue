<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Historia y evolución de los archivos

    .row.mb-5
      .col-md-5
        figure(data-aos='zoom-in')
          img(src='@/assets/template/tema01/t1-i1.jpg')

      .col-md-7
        p Se hace necesario, iniciar este componente conociendo de dónde proviene la palabra archivo; esta procede del latín archivum, aunque su origen más remoto se encuentra en la lengua griega y puede traducirse como ‘residencia de los magistrados’. El término se utiliza para nombrar al conjunto ordenado de documentos que una sociedad, una institución o una persona, elaboran en el marco de sus actividades y funciones. 
          |
          strong (Definición. De, 2011, #[i definición de archivo], párr. 1).

    p Para conocer la importancia de la historia de los archivos en la sociedad se invita a ver el siguiente video:

    .row.mb-5
      .col-12
        figure
          .video
            iframe(
              width='560',
              height='315',
              src='https://www.youtube.com/embed/2L91WMqw96A',
              title='YouTube video player',
              frameborder='0',
              allow='accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture',
              allowfullscreen
            ) 

    h3.mb-4
      i.fas.fa-square.color_texto_acento.me-3
      | Historia institucional en el marco de la archivística

    p Es importante conocer, también, sobre el estudio de la historia institucional; este según Gómez, J. (s.f.), es el análisis histórico de las instituciones que integran la organización administrativa del Estado, desde el origen jurídico que las fundamenta. Se ocupa de comprender a las instituciones políticas en su función administrativa, estructura, evolución histórica y en su proceso de acción o intervención en la sociedad (p. 1).

    .row.mb-5
      .col-lg-12
        .cajon.color_primario_txt_destacado.p-4
          p.mb-0 En ella se resaltan los cambios que han tenido las instituciones a lo largo del tiempo, determinando aspectos trascendentales y necesarios como es el alcance, el cual permite reconocer y construir una recopilación memorial desde sus orígenes legales, antecedentes y desarrollo de funciones, hasta el contenido en donde se detalla la transformación administrativa estructural, resultante de la evolución de esta normativa o rediseño orgánico-funcional de la institución.

    .row.mb-5
      .col-md-7
        p Siendo así, la historia institucional enmarca diversos preceptos que sirven de orientación tanto en instituciones públicas como privadas, determinando factores como el entorno, los recursos tecnológicos o financieros, los objetivos, la estructura administrativa, entre otros.
        | Tomemos como referente las instituciones públicas, estas son las mayores productoras de documentos y archivos; teniendo en cuenta el grado de operaciones desarrolladas a lo largo de su existencia y con base en sus actividades esenciales. Es así como los archivos garantizan que estas instituciones puedan brindar información oportuna a quien lo requiera y dar cumplimiento a la normativa vigente.

      .col-md-5
        figure(data-aos='zoom-in')
          img(src='@/assets/template/tema01/t1-i2.jpg')

    .row.mb-5
      .col-lg-12.px-5
        .cajon.color_primario_txt_destacado.p-4
          p.mb-0 Por consiguiente, es entendible que las instituciones deban apelar a su historia, puesto que esta proporciona la evolución resultante a través de los cambios normativos, buscando mantener los archivos en conformidad con la estructura orgánica y respetando el principio de procedencia y orden original.

    h3.mb-4
      i.fas.fa-square.color_texto_acento.me-3
      | Naturaleza jurídica nacional e internacional

    .row.mb-5
      .col-md-5
        figure(data-aos='zoom-in')
          img(src='@/assets/template/tema01/t1-i3.jpg')

      .col-md-7
        p Al construir la historia institucional se debe tener en cuenta el aspecto legal, revisando las alteraciones o cambios surgidos en la legislación a través de las diferentes estructuras políticas y económicas detallando lo que cada una de ellas le haya aportado.
        | En las normas archivísticas encontramos gran variedad, entre las más conocidas están las que se relacionan con las normas de gestión documental como las ISAD (G), ISAAR (CPF), ISDF, ISDIAH, DTDs, NEDA, NODAC, NOGADA, ARANOR, y las que dan orientación en descripción archivística como la ISO 15489, ISO 303000, entre otras.

    .row.mb-5
      .col-lg-12.px-5
        .cajon.acento-botones_txt_destacado.p-4
          p.mb-0 Además de las normas, es importante conocer las leyes que tiene el Estado colombiano para reglamentar lo concerniente a los archivos, desde su creación hasta el acceso y uso de los mensajes de datos, del comercio electrónico y las firmas digitales, para, de esta forma, garantizar el uso correcto y adecuado de los documentos.

    p.mb-5 La siguiente imagen presenta la distribución gráfica de las normas de gestión documental y descripción archivística:

    .row.d-flex.justify-content-center.mb-5
      .col-lg-11.col-md-10.col-12
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Figura 1
          br
          span #[i Normas de gestión documental y descripción archivística]
      .col-lg-11
        figure(data-aos='zoom-in')
          img(src='@/assets/template/tema01/1.jpg', alt='')

    p.mb-5 A continuación, conocerá algunas de las normas de gestión documental y descripción archivística:

    .row.justify-content-center.mb-4
      .col-lg-11.col-md-10.col-12
        .row
          .col-lg-4
            figure(data-aos='zoom-in')
              img.img400.m-auto(
                src='@/assets/template/tema01/t1-i5.jpg',
                alt='alt'
              )
          .col-lg-8
            AcordionA.mb-5(tipo='a', clase-tarjeta='tarjeta acordeonA')
              .row(titulo='ISAAR (CPF)')
                .col-12
                  p.mb-0 Es una norma internacional y tiene como objetivo establecer encabezamientos autorizados para describir las entidades (instituciones, personas y familias) asociadas a la producción y a la gestión de los archivos. Esta norma fue aprobada en el año 2004 en el Congreso Internacional de Archivos (ICA), cuenta con 4 áreas que son: identificación, descripción, relaciones y control, además tiene 2 funciones puntuales: controlar la creación y empleo de los encabezamientos y describir una entidad, familia y/o persona proporcionando toda la información que disponga.

              .row(titulo='DTDS (EAD, EAC y EAG)')
                .col-12
                  p.mb-0 En estas se encuentran tres normas claves en el archivo de documentos y se basan principalmente en que todos los documentos de un mismo tipo posean una estructura común, de modo que se codifiquen usando el mismo conjunto de etiquetas o vocabulario. La primera es la norma de Descripción Archivística Codificada (EAD) usada para la codificación en formato electrónico de descripciones de documentos de archivo, la segunda es la Norma de Contexto Archivístico Codificado (EAC) que permite la codificación en formato XML de los registros de autoridad y la tercera es la Norma de Guía de Archivo Codificada (EAG) que es una herramienta para la redacción de guías de archivo en formato electrónico.

              .row(titulo='ISO (Organización Internacional de Normalización')
                .col-12
                  p.mb-0 Nació tras la Segunda Guerra Mundial y es la encargada de promover el desarrollo de normas internacionales de fabricación, comercio y comunicación para todas las ramas industriales. Su función principal es buscar la estandarización de normas de productos y de seguridad para las empresas u organizaciones a nivel internacional.

    p Igual que las normas, es importante conocer algunas de las leyes reglamentarias del archivo.
    br
    p Estas leyes son:

    .row.mb-5
      .col-lg-8.order-2.order-lg-1
        TabsA.color-acento-contenido.mb-5 
          .tarjeta.clr-paleYellow.p-4(titulo='Ley 80 de 1989')
            p Por la cual se crea el Archivo General de la Nación y se dictan otras disposiciones.

          .tarjeta.clr-paleYellow.p-4(titulo='Ley 4 de 1993')
            p Obligación de las entidades oficiales de entregar y recibir inventariados los documentos de los archivos.

          .tarjeta.clr-paleYellow.p-4(titulo='Ley 44 de 1993')
            p Sobre derechos de autor, funcionarios públicos.

          .tarjeta.clr-paleYellow.p-4(titulo='Ley 527 de 1999')
            p Por medio de la cual se define y reglamenta el acceso y uso de los mensajes de datos, del comercio electrónico y las firmas digitales, y se establecen las entidades de certificación y se dictan otras disposiciones.

          .tarjeta.clr-paleYellow.p-4(titulo='Ley 594 de 2000')
            p Por medio de la cual se dicta la Ley General de Archivos y se dictan otras disposiciones.

          .tarjeta.clr-paleYellow.p-4(titulo='Ley 734 de 2002')
            p Código Disciplinario Único.

      .col-lg-4.order-1.order-lg-2.mb-4.mb-lg-0(data-aos='zoom-in')
        figure
          img.m-auto(
            src='@/assets/template/tema01/t1-i6.jpg',
            alt='alt',
            style='width: 450px'
          )

    .row.mb-5
      .col-lg-12.px-5
        .cajon.acento-botones_txt_destacado.p-4
          p.mb-0 Recuerde que estas normas, en su naturaleza, definen y establecen el alcance y uso de los documentos, el método y la duración de la conservación; así como el flujo de documentos históricos que se transferirán a los archivos históricos y los estándares de calidad. Además se deben cumplir los procesos estipulados, y no se puede tomar ninguna decisión sin consultar la normativa vigente.

    h3.mb-4
      i.fas.fa-square.color_texto_acento.me-3
      | Estructura orgánico funcional de la empresa

    .row.mb-5
      .col-md-2.col-5
        figure(data-aos='zoom-in')
          img(src='@/assets/template/tema01/t1-i7.jpg')

      .col-md-10.col-7
        p Las instituciones emplean los organigramas como una herramienta visual que les ayuda, de manera gráfica, a delimitar y fijar jerarquías, funciones y responsabilidades. Estos a su vez permiten tener una mejor división del trabajo y un mayor control en la comunicación interna de los colaboradores. 
        | La normativa cambiante obliga a las entidades, en su mayoría estatales, a realizar modificaciones constantes en su estructura orgánica y funcional, mientras que en las entidades privadas, dependen más de sus políticas internas. 

    h3.mb-4
      i.fas.fa-square.color_texto_acento.me-3
      | Normograma

    .row.mb-5
      .col-md-5
        figure(data-aos='zoom-in')
          img(src='@/assets/template/tema01/t1-i8.jpg')

      .col-md-7
        p Las organizaciones deben entregar balances de todas sus actuaciones; por lo tanto, es de su competencia revisar a qué normas obedecen, con el objetivo de dar cumplimiento y, así mismo, estas deben ser socializadas con sus colaboradores. Es por eso que el uso de un ‘normograma’ facilita dicha tarea, porque es una herramienta que permite a las entidades públicas y privadas, delimitar las normas que regulan sus actuaciones, en desarrollo con su objeto misional. (Normograma y gestión documental, Ministerio de justicia y derecho, 2015, p. 3)

        a.anexo.mb-4.mb-lg-0(
          href='https://www.minjusticia.gov.co/programas-co/SIG/Informes/Memoria%20-%20Normograma%20y%20documental.pdf',
          target='_blank'
        )
          .anexo__icono
            img(src='@/assets/template/icono-link.svg')
          .anexo__texto
            strong Enlace web.
            | Para conocer un ejemplo de normograma haga clic en #[b Normograma y Gestión documental.]

    p El normograma debe incluir la normativa tanto externa como interna (Ministerio de justicia y derecho, 2015).

    .row.mb-5
      .col-lg-12.mb-5
        .row.d-flex.justify-content-center
          .col-sm-6.col-lg-4.mb-4.mb-lg-0
            .col-lg-12.t-2-nivel1-tarjeta
            .tarjeta--boton.p-4.t-2-nivel2-tarjeta
              .row.justify-content-center.mb-3.t-2-nivel3-tarjeta
                .col-lg-4.col-3
                  figure
                    img(
                      src='@/assets/template/tema01/t1-i9.png',
                      alt='Texto que describa la imagen'
                    )

              h3.text-center Normativa externa
              p.text-small.text-center Se encuentran las leyes, decretos, acuerdos, circulares, resoluciones, que afectan la gestión de la entidad.

          .col-sm-6.col-lg-4.mb-4.mb-lg-0
            .col-lg-12.t-2-nivel1-tarjeta
            .tarjeta--boton.p-4.t-2-nivel2-tarjeta
              .row.justify-content-center.mb-3.t-2-nivel3-tarjeta
                .col-lg-4.col-3
                  figure
                    img(
                      src='@/assets/template/tema01/t1-i10.png',
                      alt='Texto que describa la imagen'
                    )

              h3.text-center Normativa interna
              p.text-small.text-center Están los reglamentos, estatutos, manuales y, en general, los actos de interés para la entidad que permiten identificar las competencias, responsabilidades y funciones de las dependencias de la organización.

      .col-lg-12.px-5
        .cajon.acento-botones_txt_destacado.p-4
          p.mb-0 Es importante tener presente que cada institución puede diseñar su formato, no existe uno genérico para las instituciones, sin embargo, en las organizaciones privadas este va de la mano con las políticas internas en las que debe definir, personalizar y aplicar lo que se considere, además este se debe ajustar a la organización, consultando los requisitos y directrices bajo su respectivo ordenamiento jurídico.
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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
