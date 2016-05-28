Title:El nuevo Firebase
Date: 2016-05-28
Category:Firebase
Tags:Firebase, Google
Slug:el-nuevo-firebase
Author:Jobsamuel Nuñez
author_pic_url:https://secure.gravatar.com/avatar/dd12db4aafc12a9619cb2b981749c1ec
twitter:jobsamuel
author_bio:
author_location:Maracaibo, Venezuela
Summary:Si las aplicaciones web y móviles son lo tuyo pero los servidores, balanceadores de cargas, configuración de certificados SSL, bases de datos, encriptación de datos, copias de seguridad y muchísimas otras cosas más relacionadas al backend te parecen abrumadoras al momento de iniciar un proyecto cuyo potencial es increíblemente grande, seguramente tuviste la oportunidad de utilizar o toparte con Firebase.
image:images/firebase-logo.jpg

Para los que no tienen idea de qué es Firebase (*Shame on you*), les cuento es que un Platform as a Service adquirido por Google en el 2014, que literalmente se encarga de TODO (o casi todo), lo necesario para que tu aplicación (esa idea millonaria en la que trabajas) pueda llegarle a miles de personas sin que tu DevOps tenga que sufrir tanto.

Durante el pasado Google I/O, Firebase le presentó al mundo su nuevo look, el cual vino lleno de nuevas funcionalidades y mejoras increíbles en sus servicios. Así que, si ya eras usuario de ésta plataforma o tenias gran interés de trabajar con ella, aquí te dejamos un breve resumen de los cambios para que no pierdas tiempo y puedas sacarle provecho.

## Un look “Material”

El haber sido adquiridos por Google, me hacía sospechar una cosa: en algún momento lucirían como ellos. La noticia es que sí, ahora su UI es similar a la de cualquier producto de Google; desde su nueva documentación hasta su nuevo Dashboard (que ahora se llama Firebase Console). Todo, absolutamente TODO cambió. 

Aunque les confieso que ciertas cosas me encantaron (ahora puedes exportar JSONs de gran tamaño) hay otras que no; la documentación ya no es tan detallada, agradable y simple como la anterior.

## API renovada

Firebase cambió. Si eras de lo que utilizaba el servicio para crear tus aplicaciones, tendrás que actualizar un par de cosas al momento de migrar al nuevo SDK  o atenerte a las consecuencias; a que todo tu código se rompa y probablemente te despidan de tu trabajo (estoy exagerando, pero ustedes me entienden).

No detallo todos lo cambios ya que hay muchos que aún no he estudiado ni verificado, pero la buena noticia es, **no tienes que migrar ya**. Tu código anterior seguirá funcionando perfectamente (se los aseguro) con la diferencia que no podrás sacarle provecho a las nuevas funcionalidades de la plataforma hasta que actualices tu SDK.

## Storage, storage, storage

Uno de los cambios más grandes que cualquier usuario  notará cuando comience a trabajar es que... **¡Ahora puedes guardar fotos, audio y video en Firebase!**

Les cuento que antes eso no era posible y causaba muchísimas incomodidades al momento de desarrollar tu aplicación, ya que debías utilizar servicios de terceros (como S3 de AWS) para almacenar ese tipo de archivos. Esto traía consigo la frase “Si Firebase dijo que me olvidara del backend, porqué tengo que hacer esto” y demás configuraciones que al final del día te hacían cuestionar los beneficios del servicio para tu caso de uso. Usuarios como estos no estaban tan felices y pedían a gritos esta nueva funcionalidad. Eso sí, necesitarás migrar al nuevo SDK para utilizarla.

## Nuevos precios (y cosas gratis)

Previamente, Firebase tenía 5 planes a elegir, y sus precios iban desde los 5USD hasta pasar los 1400USD. A juzgar por la calidad de sus servicios y todas las ventajas que ellos ofrecían, ciertos planes parecían un poco costosos para pequeñas empresas o incompletos para otras.

Ahora, sólo hay 3 y son exageradamente simples: Gratis, 25USD y Paga lo que uses. Y no solo eso, sino que ahora el hosting + dominio personalizado + SSL está incluído sin costo alguno en todos los planes (antes debías pagar 5USD si deseabas utilizar tu propio dominio), asi como todas las nuevas funcionalidades (Analytics, App Indexing, Authentication, Dynamic Links, Invites, Notifications, Crash Reporting, & Remote Config).

Sin duda alguna, todos estos cambios les han sacado una sonrisa a los usuarios de este increíble servicio y han hecho aún más atractiva la propuesta para lo que dudaban en comenzar a utilizarlo.


Me despido con el video que resume todo lo que les escribí:

https://www.youtube.com/watch?v=fgT6r4f9Apc

Enlaces relacionados:

[Firebase](https://www.firebase.com/)