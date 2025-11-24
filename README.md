🃏 PokerHack – Clasificación automática de manos de póker

PokerHack es un proyecto orientado a analizar y clasificar manos de póker utilizando técnicas de Machine Learning.
El objetivo principal es sentar las bases de una futura aplicación capaz de asistir al jugador online ayudándole a evaluar la calidad de sus manos y decidir de forma más informada si debe continuar o no en una ronda.

Este repositorio incluye la primera fase del proyecto: detección automática de tipos de mano a partir de datos reales.
🎯 Objetivo del proyecto

El primer gran objetivo es crear un modelo capaz de clasificar automáticamente manos de póker, detectando combinaciones como pareja, doble pareja, trío, color, etc.

Para ello se utiliza un dataset compuesto por:

25.000 manos para entrenamiento

1.000.000 manos para evaluación

Cada mano contiene 5 cartas, con su palo y valor
🤖 Modelos evaluados

Se probaron múltiples modelos de clasificación antes y después del reequilibrado, evaluando su classification report.
Los mejores resultados se dieron clasificando manos malas (0), pero con bajo rendimiento en manos mediocres (1) y buenas (2).

📌 Conclusiones de la Fase 1

El dataset real del póker es altamente desequilibrado.

Las técnicas de oversampling/undersampling/SMOTE no preservan la probabilidad real del juego.

Los modelos funcionan bien para manos malas, pero fallan en casos relevantes de decisión.

Es necesario explorar nuevas técnicas y ampliar la base de datos.

Este proyecto ahora avanza hacia la Fase 1.2, donde se evaluarán nuevas herramientas, más datos y posibles cambios de estrategia.
🧭 Próximos pasos (Roadmap)

🔄 Generación de un dataset mayor y más equilibrado sin perder realismo probabilístico.

🧠 Probar arquitecturas más complejas (árboles ensamblados, redes profundas, embeddings).

🃏 Considerar simulaciones de Montecarlo para estimar la fortaleza real de una mano.

📱 Sentar la base para una futura app de asistencia al jugador.

📄 Licencia

Este proyecto está bajo licencia MIT, permitiendo su uso libre y abierto.

