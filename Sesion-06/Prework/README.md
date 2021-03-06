# Prework

## Objetivo

Conocer los fundamentos de las bases de datos no relacionales

## Instrucciones

Ve el siguiente vídeo y lee los artículos, posteriormente contesta el cuestionario adjunto.

## Desarrollo

# SQL vs NoSQL ¿Cuál debo usar?

![sqlVSnosql](https://cdn.website-editor.net/192387ccd8824fdcac0b5ed96f855ec3/dms3rep/multi/nosql-vs-sql-overview-1.png)

SQL es un sistema de gestión de bases de datos relacional, multihilo y multiusuario con más de seis millones de instalaciones; usado por muchos sitios web grandes y populares, como Wikipedia, Google (no para búsquedas), Facebook, Twitter, Flickr, y YouTube.

La diferencia conceptual entre SQL y NoSQL, es que resuelven escenarios completamente diferentes y excluyentes el uno del otro; ya que para lo que resulta ideal SQL, no lo es NoSQL y al revés.

**Diferencias:**

SQL permite combinar de forma eficiente diferentes tablas para extraer información relacionada, mientras que NoSQL no lo permite o muy limitadamente.

NoSQL permite distribuir grandes cantidades de información; mientras que SQL facilita distribuir bases de datos relacionales.
SQL permite gestionar los datos junto con las relaciones existentes entre ellos, en NoSQL no existe este tipo de utilidades.

NoSQL permite un escalado horizontal sin problemas  por su capacidad de distribución; mientras que escalar SQL resulta más complicado.

## ¿CUÁNDO USAR SQL?

No existe una respuesta concreta, porque se presume que cualquier cosa que se deba guardar, debe ser en una base de datos relacional . Sin embargo los programadores podrían sugerir que en gaming o desarrollos de animación, no sería necesario.

En la mayoría de las opiniones, una base de datos relacional puede ser usada los siguientes ámbitos:

+ **Educación:** para estructurar información y aportar conocimiento lógico al estudiante.
+ **Desarrollos web:** para mantener jerarquía de datos, siempre y cuando la capacidad de concurrencia, almacenamiento y mantenimiento no sean de considerable dificultad y la información sea consistente .
+ **Negocios:** inteligencia y análisis de negocios, son temas que requieren el uso de SQL para facilitar el consumo de la información y la identificación de patrones en los datos.
+ **Empresarial:** porque tanto el software a la medida y el software empresarial, poseen la característica de mantener información con estructura consistente .

## Desventajas

+ **Menos flexibilidad:** Hay que planificar con tiempo el esquema ya que luego es más complicado actualizarlo.
+ **El uso de relaciones** Puede conllevar consultas JOIN complejas.
A veces el escalado horizontal se torna demasiado complicado.

## ¿CUÁNDO USAR NOSQL?

Básicamente se utilizan en:

+ **Redes sociales:** Casi obligatorio.
+ **Desarrollo Web:** Debido a la poca uniformidad de la información que se encuentra en Internet; aun cuando también puede emplearse SQL.
+ **Desarrollo Móvil:** Debido a la tendencia  en crecimiento de Bring Your Own Device.
+ **BigData:** Debido a la administración de grandísimas cantidades de información y su evidente heterogeneida.
+ **Cloud (XaaS):** “Everything as a service”; NoSQL puede adaptarse casi a cualquier necesidad del cliente, y sus particularidades.

## Desventajas

La **flexibilidad** puede conllevar a posponer decisiones de estructura importantes.
Alta posibilidad de tener **datos duplicados.**

### Bases de Datos NoSQL en el mercado

![img/Screen_Shot_2020-06-22_at_1.52.06.png](img/Screen_Shot_2020-06-22_at_1.52.06.png)

## Quiz

1. ¿Una BD relacional puede ser NoSQL?

1. ¿Cuáles son las principales características que ofrecen las BD NoSQL?

1. ¿Cuáles son los tipos de BD NoSQL? Crea un esquema, si consideras necesario, que te ayude a identificar cada tipo.

1. Si tuvieras que implementar una BD donde la velocidad de lectura y escritura es lo primordial ¿ocuparías SQL o NoSQL? Justifica tu respuesta.

1. Explica cómo funciona la atomicidad en las BD NoSQL.
