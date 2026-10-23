# Detección de objetos

Localiza objetos de una fotografía y presenta sus detecciones.

- Entrada: Fotografía de cámara; umbrales de confianza e IoU.
- Resultado: Imagen anotada, tabla por categoría y gráfico de detecciones.
- Tecnología: Ultralytics · YOLOv5su

## Uso

Ajusta los umbrales en el panel lateral y toma una foto. Compara las cajas con la tabla de resultados.

## Límites

La confianza del modelo no garantiza acierto. Las clases disponibles dependen del modelo preentrenado.

## Evidencia de ejecución

La ficha describe el funcionamiento del código. Una ejecución del modelo o una conexión a un dispositivo debe documentarse con su entrada, resultado observado y captura real; no se presentan resultados simulados como evidencia académica.

[Demo](https://yolov5-jpqn7hy6ah3tav84phcifb.streamlit.app/) · [Código](https://github.com/Jhuza/Yolov5)
