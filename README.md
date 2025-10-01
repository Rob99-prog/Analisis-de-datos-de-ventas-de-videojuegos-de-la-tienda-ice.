# Analisis de datos de ventas de videojuegos de la tienda ice.

Indicaciónes resumidas: Análisis de datos de ventas de videojuegos de la tienda Ice (hasta 2016) con reseñas, géneros, plataformas y rating ESRB para detectar patrones de éxito y planear la campaña 2017. Limpiarás y preparación del dataset, evaluarás plataformas y géneros por región, correlaciones con reseñas, y probarás hipótesis. Entrega en Jupyter.


Conclusión general

Objetivo del proyecto:
Analizar patrones de éxito de videojuegos usando datos hasta diciembre de 2016 para planificar campañas de marketing en 2017.

0.2. Principales hallazgos
Tendencia de lanzamientos

Tres fases: crecimiento inicial (1980–1994), pico de publicaciones (1995–2009) y estabilización/descenso (2010–2016).

Plataformas líderes
NA: X360, PS2 y Wii.
EU: PS2, PS3 y X360.
JP: DS, PS y PS2.

Géneros más rentables por mediana de ventas globales:
Platform, Shooter y Sports.
Action y Role‑Playing lideran en número de títulos, pero sus medianas de venta son menores.

Correlación crítica‑ventas:
En PS3, la puntuación de críticos muestra una correlación moderada (r≈0.43) con las ventas globales.
Pruebas de hipótesis
Xbox One vs PC (user_score): t = −4.671, p < 0.001 ⇒ medias significativamente diferentes.
Action vs Sports (user_score): t = 1.789, p = 0.074 ⇒ no se rechaza H₀ (sin evidencia de diferencia).


0.3. Implicaciones para la campaña 2017
Canales de promoción: enfocar esfuerzos publicitarios en X360 y PS2/PS3 para mercados occidentales, y en DS/PS para Japón.
Selección de títulos: priorizar géneros Platform y Shooter, que presentan medianas de venta más altas.
Uso de reseñas: combinar puntuaciones de críticos como indicador de calidad con métricas de mercado para optimizar listado de lanzamientos.

0.4. Limitaciones y pasos futuros
Cobertura de datos: más del 50 % de juegos carecen de puntuaciones de crítica o usuario; conviene ampliar fuentes o imputar datos.
Variables adicionales: incorporar presupuesto de marketing, fecha exacta de lanzamiento y campañas previas para mejorar el modelo.
Validación temporal: probar las conclusiones con datos de 2017–2018 para ajustar estrategias.
--Ha sido todo un reto trabajar con este dataset, pero me encantó descubrir estos patrones y validar hipótesis; el proyecto está muy bien diseñado para aprender Y practicar :)---

Comentario del revisor (1ra Iteracion)
Buen trabajo con el proyecto realizado, tienes un notebook con buena presentación y los análisis están correctamente redactados en cada parte del proyecto. Te felicito por la excelente presentación que le has dado a tu notebook, es importante que nuestros proyectos queden claros y legibles porque a menudo se deben compartir entre compañeros de equipo y me alegro mucho que pudiste disfrutar del aprendizaje de este proyecto!

Saludos!

