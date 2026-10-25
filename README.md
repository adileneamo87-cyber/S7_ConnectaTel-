El objetivo es identificar patrones de uso, detectar comportamientos atípicos 
y comprender qué segmentos de clientes muestran necesidades diferenciadas, con el fin de optimizar 
la oferta comercialy mejorar la experiencia del usuario.

Para ello trabajamos con tres fuentes de datos:
plans.csv: los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).
users_latam.csv: información de clientes: edad, ciudad, fecha de registro, plan contratado.
usage.csv: el detalle de uso real: llamadas (duración) y mensajes (longitud).

Las etapas del análisis realizadas fueron:
1. Cargar y explorar
2. Contar nulos, detectar sentinels, revisar fechas fuera de rango.
3. Reemplazar sentinels, convertir fechas, imputar o marcar NA según reglas.
4. Revisar las medidas clave en variables categóricas y numéricas
5. Creación de histogramas y boxplots
6. Crear segmentaciones basadas en reglas claras; visualizar proporciones con countplots
7. Redactar conclusiones y recomendaciones comerciales basadas en los pasos anteriores.

   Se recomienda ejecutar en Google Colab.
