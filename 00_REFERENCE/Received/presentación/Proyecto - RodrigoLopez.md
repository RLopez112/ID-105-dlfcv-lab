
<div style="font-family: Arial, sans-serif; max-width: 800px; margin: 0 auto; margin-top:-10ps ">
    <h2 style="color: #3f3f3fff; font-size: 24px; font-weight: normal; margin-bottom: 10px;">
    DlfCV - Proyecto - Rodrigo Lopez </h2>
    <hr style="border: none; border-top: 1px solid #cccccc; margin: 0 0 10px 0;">
    <div style="display: flex; justify-content: space-between; color: #3b3b3bff; font-size: 12px;">
        <span>SePtiembre 2026</span>
    </div>
</div>


### PAPER A ESTUDIAR
-  Emulating Human-like Adaptive Vision for Efficient and Flexible Machine Visual Perception Wang, Y., et.al (2025).https://doi.org/10.48550/arXiv.2509.15333

### PORQUE ESTE PAPER
Mi tema de tesis se basa en procesos atencionales. Por lo que me interesan algoritmos de visión que incluyan una capa cognitiva. En este paper particularmente encontré que implementan algo similar a la diferencia de resolución entre fovea y periferia. E implementan una búsqueda con un modelo pequeño en la representación de baja resolución para luego hacer una inferencia con un modelo más grande en la ubicación de interés. Como resultado dicen que este enfoque es mucho más eficiente y que presenta comportamientos emergentes similares a los procesos de búsqueda visual en humanos. 


### OBJETIVOS
- Entender la estructura del paper
- Entender el concepto de Adaptive Neural Networks
- Entender la arquitectura del modelo
- Entender los resultados 
- Intentar correr el código

### PREGUNTAS A RESPONDER
- ¿Las Adaptive NN modifican weights en runtime o usar distintos modelos ya lo hace una Adaptive NN?
- ¿Como es la arquitectura del modelo de baja resolución?
- ¿Qué datos usaron para el entrenamiento del modelo de baja resolución?
- ¿Cómo definen las regiones de interés?
