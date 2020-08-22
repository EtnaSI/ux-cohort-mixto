# Aplicación financiera
## Introducción
Banqui es una fintech peruana que busca brindar una experiencia financiera
digital simple, rápida y  personalizada para sus clientes. Banqui inició
operaciones en 2019 en Perú y en 2020 en México, encontrando coincidencias en
ambas culturas financieras en relación al ahorro, la percepción de la banca
tradicional, los altos intereses en tarjetas de crédito, entre otros. Un dato
de ejemplo es que en México solo el 15% de personas que ahorran lo hacen a
través de una institución financiera formal (bancos, cooperativas, fondos de
inversión), mientras que en Perú es un 14%.

### Contexto
Al revisar los resultados del uso de la aplicación con los usuarios beta
y de haber realizado una investigación de UX con usuarios de México, el
equipo de Banqui concluyó lo siguiente:

- La aplicación tiene aún problemas de diseño visual y de interacción que
  hacen que la aplicación no sea entendible ni fácil de usar para muchos
  usuarios:
  * Existen inconsistencias en el uso de ciertos componentes de la interfaz.
  * Los contrastes de color utilizados hacen que algunos elementos no
    sean vistos por los usuarios.
- El lenguaje utilizado en la aplicación a veces induce al error a los
  usuarios. 
- Los usuarios valoran mucho la funcionalidad de ahorro, sin embargo, se les
  hace complicado utilizarla.
- Existe un problema en el sign up. Según la data que han podido recolectar,
  solo el 10% de las personas que descargan el up logran crearse una cuenta.
- Es imperativo diseñar una aplicación para dispositivos Android. El [landing
  page](http://banqui.pagedemo.co/) donde se anuncia la llegada de Banqui ha
  identificado que el 70% de los intersados en Banqui navegan el landing page
  desde un dispositivo Android.
### Recursos
- [Resultados de la investigación](https://docs.google.com/presentation/d/1EzfS-bl0Wyl29WH34LZancc_Qo-3Gewt9P0lYfEPN4E/edit#slide=id.g7fac357d58_0_202)
- El [diseño del app en Figma](https://www.figma.com/file/S2NwVUvMYU5J30EhTBrnEK/LIM-App-Financiera?node-id=810%3A7200)
, con una guía de componentes y el [Prototipo navegable](https://marvelapp.com/1hj56576).

## Objetivos iniciales del proyecto
-Investigar a la competencia para obtener mayor informacion de que le falta a nuestro producto.  
-Validar los user persona propuestos por el cliente.  
-Identificar posibles nuevos usuarios.
-Lograr alinear los objetivos del usuario con las metas del cliente.  
-Identificar pain points de los usuarios y encontrar la forma de resolverlos y mejorar su  experiencia.  
-Rediseñar la aplicación efectuando testing con usuarios.  
-Encontrar un diferenciador que haga que las personas empiecen a usar la app.  
-Buscar la manera de trabajar con productos financieros activos.

## Research
### Benchmarck
Se realizó un análisis del mercado de fintech existentes en el mundo, para poder aprender de los demás y darnos cuenta de qué cosas ellos ven como importante en sus apps,cómo veían al usuario,qué objetivos ellos se planteaban tener,qué necesidades ellos consideraban que debían satisfacer y de qué manera las abordaban. Además del diseño que tiene cada una de estas.  


![img-5](https://github.com/claudiacortezb/ux-cohort-mixto/blob/master/01-redesign/img/bench.jpg)

#### Competencia de Banqui en Perú
Al igual que mundialmente,en el Perú tambien existen muchas fintech y recabamos algunos datos de cada una de ellas y las comparamos en cuanto a funciones que ofrecen.  


![img-7](https://github.com/claudiacortezb/ux-cohort-mixto/blob/master/01-redesign/img/compe.jpg)  

#### User Persona 
Banqui ya contaba con un user persona predefinido el cual fue María:  


![img-6](https://github.com/claudiacortezb/ux-cohort-mixto/blob/master/01-redesign/img/user.png)  

### Entrevistas con usuarios
Después del research se procedió con la busqueda de usuarios que se acerquen a las caracteristicas y necesidades del user persona que teníamos,es así que pudimos corroborar este arquetipo, encontrar patrones y tratar de definir qué modelos mentales regían los patrones de nuestros usuarios.  
## Diseño de la aplicación
Gracias al proceso del research y las entrevistas pudimos definir un diseño incluyendo la información que se nos dió además de ciertas herramientas y funcionalidades que nos parecieron resaltantes y que pudimos apreciarque nuestro usuario valoraría.  
### Inicio
Planteamos la importancia de la identidad de Banqui, ya que los usuarios manifiestan la necesidad de confiar en las app donde tienen su dinero,empezamos mejorando el diseño visual respetando los colores anteriormente elegidos por Banqui pero resaltando los puntos que podrían ser más importantes para los usuarios. 


![img-1](https://github.com/claudiacortezb/ux-cohort-mixto/blob/master/01-redesign/img/1.jpg)  


![icons](https://github.com/claudiacortezb/ux-cohort-mixto/blob/master/01-redesign/img/icons.jpg)  

### Registro
-Al considerar que solo el 10% de los usuarios que descargan la app, terminan registrándose a Banqui, comprendemos que acompañar a nuestros usuarios durante el proceso es clave por ello complementamos una cadena numérica para que los usuarios sepan acerca del proceso,y no lo vean como algo muy largo y tedioso, sino que sepa cuantas y en qué etapa se encuentra del registro.


![registro-1](https://github.com/claudiacortezb/ux-cohort-mixto/blob/master/01-redesign/img/regis.jpg)     



-Los usuarios buscan identificarse y sentirse parte de Banqui, para esto crear un perfil nos ayuda a saber mas de ellos y los usuarios entienden a dónde va la información requerida, desde el principio. Además de la posibilidad de editar su información por si le parece conveniente.


![registro-2](https://github.com/claudiacortezb/ux-cohort-mixto/blob/master/01-redesign/img/regisPic.jpg)  

### Mis cuentas 
-Uno de los hallazgos del research fue que los usuarios prefieren tener varias cuentas para administrarlas de distintas maneras, es por eso que suelen tener multicuentas, inclusive de distintos bancos porque uno tiene ciertas funcionalidades que el otro no,es así que de acuerdo a esto implementamos tener tarjetas virtuales con la opción de tener varias cuentas.


-Además cada una de estas cuentas tendrá un código,al ser estos códigos largos y dificil de memorizar,este tendrá la funcionalidad de poder ser compartido.  
![cuentas](https://github.com/claudiacortezb/ux-cohort-mixto/blob/master/01-redesign/img/cuentas.jpg)  

### Operaciones
-Siguiendo con la línea de la practicidad, rediseñamos la instancia de operaciones donde se encontraría todos los movimientos que podria hacer el usuario desde Banqui, con botones directos, como el de agregar a favoritos este permite tener señalar una entidad frecuente o número de cuenta a la que se le quiere ejecutar alguna transacción y guardarla a simple vista en favoritos.  


![img-2](https://github.com/claudiacortezb/ux-cohort-mixto/blob/master/01-redesign/img/2.jpg)    


-Nuestros usuarios presentan un valoración alta hacia las notificaciones, para ellos decidimos crear notificaciones que cubren casi por completo la pantalla,con un lenguaje claro e imágenes referenciales que les permita comprender sus movimientos realizados, recalcando lo que han hecho o reafirmando movimientos, así como recordatorios oportunos.  Por ejemplo una transacción:


![transferencias](https://github.com/claudiacortezb/ux-cohort-mixto/blob/master/01-redesign/img/transfer.jpg)  



### Movimientos
-En esta sección se detectó que los gráficos mostrados no guardaban relación alguna con los movimientos mostrados,es por esto que se decidió incorporar en este apartado las secciones de ingresos y gastos, de acuerdo a esto se muestran unos gráficos de barra de estos indicadores,correspondiente a los últimos 4 meses. De esta manera el usuario puede tener una idea a simple vista de cómo está llevando sus finanzas.  


-Pudimos darnos cuenta de que los usuarios no suelen llevar un control de sus gastos de una manera regular,es debido a esto que después de cierto tiempo el dinero se les agota y no recuerdan en qué lo gastaron.Es así que decidimos incorporar una sección de gastos y otra de ingresos, en la cual cada uno tiene un diagrama que muestra mes a mes en qué categorías se tuvieron estos gasto para poder de cierta manera tener un control sobre ellos.Pudiendo además planificarlos y darles un límite.  


-En la parte del diseño 5 de los 5 usuarios consideran importante que cada instancia de Banqui sea práctica y visualmente atractiva, por ellos incluimos gráficos claros y precisos que les de aproximaciones en relación a porcentajes que les da una idea concreta sobre sus gastos, ingresos y ahorros.  


![img-3](https://github.com/claudiacortezb/ux-cohort-mixto/blob/master/01-redesign/img/3.jpg) 

### Ahorros
-El estudio arrojó que 4 de los 5 entrevistados no ahorra por metas, es más 2 de ellos ni siquiera ahorran constantemente, esto demuestra la poca cultura financiera que tienen.  


-Se pudo hallar también que 3 de estos usuarios aveces ahorraban en juntas/panderos y les iba bien, este hecho se debía basicamente a la presión social y responsabilidad que el usuario tenía con los demás, lo que hacía que cumpla mensualmente con este ahorro,situación que no era igual cuando el usuario ahorraba de forma personal.  


-Basandonos en estos hallazgos pudimos determinar que los ahorros se podían dividir de dos maneras:  


* Metas personales
* Metas Compartidas


![img-4](https://github.com/claudiacortezb/ux-cohort-mixto/blob/master/01-redesign/img/5.jpg)  

### Amigo Banqui
-Uno de los hallazgos que marcaron más el comportamiento de los usuarios entrevistados fue el entorno social, ellos basan su forma de interactuar con su alrededor en las relaciones interpersonales y en sus seres queridos.


-Partiendo del anterior hallazgo y de la idea de captar más usuarios, vemos óptimo crear una comunidad Banqui, ya que al hacer a nuestros usuarios parte de una familia, nos garantiza su preferencia. Vemos necesario hacer que los usuarios se identifiquen con Banqui, es aquí donde nace nuestra propuesta de Amigo Banqui, esto nos permite crear lazos con nuestros usuarios y entre nuestros usuarios, permitiéndoles realizar transacciones inmediatas con contactos frecuentes, con esto los ayudamos a ahorrar mutuamente a través de alianzas, e incluso ayudarlos a dividirse el gasto entre grupo y abonarse directamente al instante.  


-La idea de una propuesta como Amigo Banqui tiene muchos beneficios sin salir de casa creando un aura de confianza que es un punto necesario que se repite en 3 de 5 de nuestros entrevistados.Estos mismos usuarios tienen uso y gusto por las redes sociales y esta propuesta nos aproxima y que estos se vean más partícipes de la misma.  


![img-4](https://github.com/claudiacortezb/ux-cohort-mixto/blob/master/01-redesign/img/4.jpg)

