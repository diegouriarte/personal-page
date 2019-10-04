---
date: "2019-10-03T00:00:00Z"
external_link: ""
image:
  caption: 
  focal_point: Smart
links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/diegouriarte
slides: 
summary: Se realizó el seguimiento de un red de intercambio de calor, evaluando el desempeño de un aditivo antiensuciante y calculando de manera prográmatica la temperatura normalizada de ingreso a horno para el cálculo del ahorro en combustible.
tags:
- Python
title: Análisis de la influencia en ensuciamiento en la recuperación de calor de un tren de intercambio de calor
url_code: ""
url_pdf: "files/Paper_Fouling_CIIQ.pdf"
url_slides: "files/CIIQ PPT.pptx"
url_video: ""
---

En la industria de refinación, el ensuciamiento de los intercambiadores de calor es uno de los principales problemas puesto que reduce el desempeño térmico e hidráulico de la red de intercambio. Como el desempeño de la red de intercambio juega un papel importante en la reducción del consumo energético de la Unidad de Destilación de Crudo, debemos monitorearla para detectar problemas operacionales. En este trabajo desarrollamos una metodología para analizar la influencia del ensuciamiento en la recuperación de calor en el tren de precalentamiento y el efecto en la temperatura de ingreso al horno de la unidad, determinando un impacto económico.

El procedimiento propuesto ha sido codificado utilizando el lenguage de programación Python. Se calculan los coeficientes de transferencia de calor limpio, sucio y el factor de ensuciamiento de cada intermcambiador en la red, comparando el resultado del programa con los del simulador detallado Aspen EDR de Aspen Technology. De esta manera, se lleva de a una misma base los valores de temperatura de ingreso al horno, independiente de las condiciones de operación, y se puede realizar un seguimiento al ensuciamiento de la red de intercambio y el incremento en el gasto por mayor consumo de combustible debido a este.