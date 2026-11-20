# Usa las imágenes de Gemini en Arrumo

[English](../en/images.md) · [Português](../pt/images.md)

En los ajustes de Arrumo, abre el plugin de Gemini y guarda una clave de API en su campo secreto. La clave del espacio de trabajo tiene prioridad sobre la de la aplicación; Arrumo guarda ambas en el almacén de credenciales del sistema y nunca las muestra a los agentes.

Cuando un formato pide miniaturas, el agente del proceso escribe una indicación por miniatura y Arrumo pregunta a los proveedores de imágenes en el orden guardado del proceso. Gemini se omite si no tiene clave. Las miniaturas se guardan como recursos del espacio de trabajo y esperan tu revisión junto a los títulos y descripciones.

## Elige el modelo

El plugin usa `gemini-2.5-flash-image` por defecto. Para usar un modelo más reciente, indica **Modelo de imagen** en los ajustes del plugin para la aplicación o un espacio de trabajo. Déjalo vacío para seguir el modelo predeterminado del plugin.
