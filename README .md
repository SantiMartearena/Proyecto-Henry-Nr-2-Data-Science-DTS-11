
# PI02-DTS11-DataAnalyst-Henry
Proyecto Individual Numero 2, bootcamp Soy Henry 

Santiago Martearena

## Contexto
Los MOOCs (cursos masivos abiertos y online, por sus siglas en inglés) han revolucionado el mundo de la educación desde principios de la década pasada, cuando el profesor Sebastian Thrun comenzó con la transmisión online de su curso introductorio a la Inteligencia Artificial. Poco tiempo después, Thrun fundó Udacity y con el pasar de los años se han ido sumando otras plataformas como edX y Coursera, brindando servicios similares: acceso a contenido específico, de calidad y de manera práctica, desde la comodidad del hogar. Muchas de estas plataformas tienen contenido gratuito, mientras que el modelo de negocio en general se basa en el pago de suscripciones recurrentes para acceso general o únicas, para acceder a certificaciones o a cursos premium. Con el aumento de la popularidad de los MOOCs, no solo han aparecido nuevas plataformas privadas como las mencionadas anteriormente, sino que también muchas universidades y organizaciones sin fines de lucro han sumado a la oferta haciendo el mercado mucho más competitivo. En este contexto, resulta imperante para cada plataforma ajustar sus modelos de negocio, los cursos y el contenido que se ofrece en ellos para lograr captar y retener a la mayor cantidad de clientes.

## Propuesta de trabajo
A raíz de esta solicitud, nuestro Project Manager nos encarga una serie de tareas a cumplir:

Nuestra PM se dirigió a nosotros con un nuevo ticket de trabajo. Una startup de tecnología está interesada en sumarse al mercado de cursos online, pero de una manera eficiente, por lo que compró datasets de posibles competidores para analizar y sacar conclusiones de los datos recolectados.

## Pasos que Utilice para Realizar el Proyecto
1)Importamos las tablas en python.
2)Realizamos un proceso de ETL a las tablas poder trabajar con las columnas que realmente aportar informacion, hubieron varias como: los urls, o los comentarios sobre los mismo que no me parecieron importantes a para poder hacer los graficos asi que se borraron de los data sets, una vez que terminamos con el ETL y quedaron las mas importantes importamos los datasets a Power Bi

3)Despues de eso creamos 3 dashboards con los datos mas relevantes de cada tabla Udemy, EDX y Coursera, no se encontro una relacion entre las 3 para poder unirlas asi que se decidio trabajarlas de manera independiente para poder dar un analisis mas profundon de cada una. Se tuvo que cambiar los valores de varias tablas por que me las reconocia como Texto cuando eran numeros enteros, de ciertas fechas se trabajo nada mas con los años de las mismas para poder crear filtros de los mismos. Dentro de los dashboards donde se encuentran los respectivos graficos tambien se encuentran los KPIS que fui aportando y creo que son importantes para el analisis. 

4) Por ultimo se creo un word cloud en visual studio trabajando con pandas, donde importamos  pandas, wordcloud y matplotlib para poder realizar las 3 nubes con los titulos de cada dataset.
