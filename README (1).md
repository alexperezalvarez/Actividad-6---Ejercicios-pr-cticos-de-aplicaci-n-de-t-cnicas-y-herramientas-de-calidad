# Actividad 6: Aplicación de técnicas y herramientas de calidad

## Descripción

Este repositorio contiene el informe académico **“Actividad 6 - Ejercicios prácticos de aplicación de técnicas y herramientas de calidad”**, elaborado para la asignatura **Calidad de Software** de Ingeniería de Software en la Corporación Universitaria Iberoamericana.

El documento presenta un análisis de calidad del software del sistema Therac-25 como caso de estudio, tomando como referencia los problemas documentados en este sistema y proponiendo acciones para mejorar su seguridad, confiabilidad y mantenibilidad.

## Objetivo

Analizar la calidad del software mediante técnicas y herramientas de evaluación, identificando problemas potenciales y planteando recomendaciones de mejora.

## Herramientas consideradas

- **SonarQube:** análisis estático de código, identificación de errores, vulnerabilidades, *code smells* y duplicidad.
- **Apache JMeter:** pruebas de concurrencia y estrés sobre la entrada de datos.
- **Jira Software:** registro, seguimiento y trazabilidad de hallazgos e incidentes.

## Contenido del informe

- Introducción y metodología del análisis.
- Criterios y umbrales de evaluación de calidad.
- Resultados de hallazgos por severidad y categoría.
- Indicadores de calidad frente a los umbrales establecidos.
- Análisis de impacto y priorización de resolución.
- Recomendaciones técnicas y mejoras del proceso.
- Conclusiones y referencias bibliográficas.

## Principales resultados reportados

El informe presenta **47 hallazgos estimados** para el análisis descriptivo: 5 críticos, 7 altos, 15 medios y 20 bajos. También señala oportunidades de mejora en cobertura de pruebas, duplicidad de código, complejidad ciclomática, deuda técnica y fiabilidad.

> **Nota:** como se indica en el documento, no se tuvo acceso al código original del Therac-25. Por ello, las cifras y los indicadores presentados son supuestos utilizados para el ejercicio académico y no resultados de una ejecución real sobre el código fuente original.

## Recomendaciones destacadas

- Atender primero los hallazgos críticos relacionados con la seguridad.
- Verificar el estado del hardware y fortalecer los mecanismos de protección.
- Mejorar la cobertura de pruebas y automatizar pruebas de concurrencia.
- Reducir la duplicidad y la complejidad del código.
- Incorporar controles de calidad en el proceso de integración y despliegue.
- Mantener la trazabilidad de los incidentes y las acciones correctivas.

## Archivo incluido

- `Actividad 6 - aplicación de técnicas y herramientas de calidad.pdf`: informe académico de la actividad.

## Autoría académica

- **Estudiante:** Breynner Alexander Pérez Álvarez
- **Programa:** Ingeniería de Software
- **Asignatura:** Calidad de Software
- **Docente:** William Ruiz
- **Institución:** Corporación Universitaria Iberoamericana
- **Fecha del informe:** 11 de octubre de 2026

## Referencias

Las referencias bibliográficas completas se encuentran al final del documento PDF e incluyen fuentes sobre el caso Therac-25, calidad de software, SonarQube, Apache JMeter y Jira Software.
