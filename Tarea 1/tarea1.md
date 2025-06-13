# Tarea 1

## Descripción de la base de datos a utilizar

Una institución de salud ha desarrollado un sistema para registrar y analizar información de 800,000 pacientes diagnosticados con cáncer de pulmón. El objetivo es entender patrones de diagnóstico, tratamiento y evolución de la enfermedad, a través de 16 variables estructuradas.

Este registro permite identificar factores clave para la detección temprana y el pronóstico, apoyando a investigadores y profesionales de la salud en la lucha contra la principal causa de muerte por cáncer a nivel mundial. Más allá de los datos, cada caso representa una historia real que puede ayudar a salvar vidas mediante ciencia, análisis y prevención.

### Tipos de datos en la base de datos seleccionada

- id **(integer)**: identificador único del paciente  
- age **(integer)**: edad del paciente al momento del diagnóstico  
- gender **(categorical)**: género del paciente (por ejemplo, masculino, femenino)  
- country **(str)**: país o región de residencia del paciente  
- diagnosis_date **(date)**: fecha de diagnóstico de cáncer de pulmón  
- cancer_stage **(categorical)**: etapa del cáncer al momento del diagnóstico  
- family_history **(categorical)**: indica si hay historial familiar de cáncer (sí/no)  
- smoking_status **(categorical)**: estado de tabaquismo del paciente  
- bmi **(float)**: índice de masa corporal al momento del diagnóstico  
- cholesterol_level **(float)**: nivel de colesterol del paciente  
- hypertension **(categorical)**: indica si el paciente tiene hipertensión (sí/no)  
- asthma **(categorical)**: indica si el paciente tiene asma (sí/no)   
- other_cancer **(categorical)**: indica si ha tenido otros tipos de cáncer (sí/no)  
- treatment_type **(categorical)**: tipo de tratamiento recibido  


## ¿Qué es un SGBD?

Sistema de Gestión de Bases de Datos (SGBD) es un software que permite almacenar, gestionar y recuperar datos de manera eficiente. Actúa como una interfaz entre los usuarios y las bases de datos, facilitando operaciones como la lectura, creación, eliminación y actualización de datos. Los SGBD están compuestos por varios componentes integrados que realizan tareas específicas, como el motor de almacenamiento, el lenguaje de consulta (por ejemplo, SQL), el procesador y optimizador de consultas, el catálogo de metadatos, el administrador de registros, herramientas de informes y monitorización, y utilidades de datos. Estos sistemas son fundamentales para mantener la integridad de los datos y permitir el acceso concurrente por parte de múltiples usuarios.

### SGBD Seleccionado
**MySQL**
Para este proyecto decidí utilizar MySQL como sistema de gestión de bases de datos. Aunque no tengo conocimientos avanzados en el tema, me lo recomendaron por ser uno de los SGBD más utilizados a nivel mundial. MySQL es gratuito, fácil de instalar y cuenta con una gran comunidad que facilita encontrar soluciones y documentación. Además, es compatible con muchos lenguajes de programación y plataformas, lo cual lo hace una opción flexible y accesible para principiantes como yo.

## Referencias

[Hostinger. (2025, marzo 5). ¿Qué es un sistema de gestión de bases de datos (SGBD)?](https://www.hostinger.com/es/tutoriales/sgbd)
