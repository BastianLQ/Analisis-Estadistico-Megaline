# Analisis-Estadistico-Megaline
__Análisis a Megaline, estadística descriptiva, visualización de datos y verificación de hipótesis__

<image src="https://github.com/BastianLQ/Analisis-Estadistico-Megaline/blob/main/N4.jpg" alt="Collage de gráficos">

_Fragmentos del notebook, para ver proyecto completo hacer click [aquí](https://portfoliodabastianlopez.on.drv.tw/Portafolio/An%C3%A1lisis%20Estad%C3%ADstico%20Megaline.html)_

## Descripción del proyecto
Este proyecto se centró en analizar datos de la compañía Megaline para comparar dos de sus planes de servicio y determinar en cuál de ellos deberían invertir más en publicidad. Utilizando una muestra de 500 usuarios y cinco datasets proporcionados por la compañía, se realizó un proceso de limpieza y análisis de datos para llegar a conclusiones basadas en evidencia.

__*Nota:__ Megaline redondea los segundos a minutos y los megabytes a gigabytes. Para llamadas, cada llamada individual se redondea: incluso si la llamada duró solo un segundo, se contará como un minuto. Para tráfico web, las sesiones web individuales no se redondean. En vez de esto, el total del mes se redondea hacia arriba. Si alguien usa 1025 megabytes este mes, se le cobrarán 2 gigabytes.
  
## Herramientas Utilizadas
- __Lenguaje de Programación:__ Python.
- __Entorno de Desarrollo:__ Jupyter Notebook.
- __Bibliotecas:__ Pandas, Numpy, Matplotlib, Seaborn, Scipy, Math.
  
## Proceso del Proyecto
- __Inicialización:__ Se importan los 5 datasets proporcionados por Megaline (`calls`, `internet`, `messages`, `plans`, `users`) que tienen información sobre las llamadas, consumo de internet, mensajes enviados, detalles de los planes y de los usuarios, respectivamente.
- __Preparación de datos:__  Se preparan los datos para ser analizados, trabajando valores ausentes, duplicados y formateando datos según corresponda.
- __Cálculo de ingresos:__ Mediante el uso de funciones y combinaciones entre los DataFrames, se consigue calcular el ingreso en dólares de cada cliente.
- __Estudio de comportamiento de usuario:__ Se analizan los comportamientos de consumo de los clientes de ambos planes, se construyeron gráficos de caja, barras e histogramas para apoyar el análisis.
- __Pruebas de hipótesis estadísticas:__ Usando pruebas t, se realizan dos tests con hipótesis planteadas al inicio del informe.
- __Resultados:__ Al final del proyecto se profundiza en las conclusiones obtenidas sobre los planes investigados.
  
## Conclusiones
El análisis comparativo de los planes de Megaline proporcionó insights valiosos sobre en qué plan la compañía debería enfocar sus esfuerzos publicitarios. Las conclusiones se basaron en un riguroso análisis de datos y una prueba estadística, garantizando decisiones informadas y estratégicas.

## Ejecuta el proyecto [aquí](https://portfoliodabastianlopez.on.drv.tw/Portafolio/An%C3%A1lisis%20Estad%C3%ADstico%20Megaline.html)
Para ver el diccionario de datos, el desarrollo completo en código, todos los gráficos y las conclusiones, haga click en el enlace de arriba
