# Predicciones sobre precios de alojamiento utilizando los datos de Airbnb

# Objetivos  

A lo largo de este proyecto vamos a trabajar con los datos de la plataforma digital de Airbnb dedicada a ofrecer servicios de alojamientos de terceros. A través de la misma, es posible que anfitriones y huéspedes pueden valorarse mutuamente y ofrecerse referencias. Teniendo en cuenta este contexto el objetivo principal del trabajo será, entonces, entrenar un algoritmo que nos permita predecir los precios de los alojamientos en Estados Unidos a partir de los datos que provee la plataforma. 

**El dataset debe descargarse de la siguiente url:**

https://www.kaggle.com/datasets/paramvir705/airbnb-data/data

# Contexto

Obtuvimos un dataset que contiene 74111 registros de propiedades, con sus características y respectivos precios de alojamiento. Nuestro proyecto buscará generar un modelo que sea capaz de predecir los precios con precisión y que nos de algún tipo de información acerca de qué características pueden ser relevantes para explicar los resultados. 

Teniendo en cuenta que nuestra variable es cuantitativa, utilizaremos diferentes algoritmos de aprendizaje automático supervisados de regresión, principalmente modelos de ensamble basados en Árboles de Decisión (Random Forest, Gradient Boosting y XGBoost).

# Hipótesis

Las preguntas que nos hacemos para abordar en este proyecto son:

¿Cuáles son las variables principales que pueden ayudarnos a explicar los precios de alojamiento en Estados Unidos?

En base a esta pregunta general podemos realizar las siguientes preguntas específicas:

¿El tipo de habitación en alquiler influye en los precios de alquiler?

¿Que impacto tienen las distintas ciudades?

¿Los distintos ambientes juengan algún tipo de papel (baños, habitaciones)?

¿Y los servicios particulares con los que cuenta el alojamiento (internet, tv, etc.)?

A partir de estas preguntas realizamos la siguiente hipótesis:

Los precios del alquiler están positivamente relacionados con el tipo de alquiler, la ciudad en donde se alquila y los distintos servicios con los que cuenta el inmueble.
