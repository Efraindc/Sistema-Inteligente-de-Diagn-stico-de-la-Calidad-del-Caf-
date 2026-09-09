Sistema Inteligente de Diagnóstico de la Calidad del Café

Sistema de Inteligencia Artificial desarrollado para representar conocimiento, evaluar la calidad del café y generar decisiones de clasificación a partir de diferentes características del producto.

El proyecto integra tres técnicas de Inteligencia Artificial:

Representación del conocimiento mediante una ontología
Lógica difusa para evaluar la calidad del café
Sistema experto basado en reglas para determinar el destino del café
El objetivo es construir un sistema capaz de transformar información sobre lotes y sublotes de café en una evaluación de calidad y, posteriormente, en una decisión como Exportación, Nacional, Retener o Descarte.

Video explicativo

En el siguiente video se presenta una explicación del funcionamiento y desarrollo del proyecto:

▶️ Ver video explicativo en YouTube: https://www.youtube.com/watch?v=fjcImqAqlEQ

📚 Información académica

Asignatura: Inteligencia Artificial Docente: Jaime Alberto Guzmán Luna Universidad: Universidad Nacional de Colombia Grupo: 01 Equipo: 11

Integrantes

Raphael Herve Marie De Vathaire
Efrain Alberto Diaz Caro
Sebastían Cano Olarte
Michael Garcia Quincos
Objetivo del proyecto

Desarrollar un sistema inteligente capaz de utilizar diferentes mecanismos de razonamiento para analizar información relacionada con la calidad del café.

El sistema parte de una representación estructurada del conocimiento mediante una ontología. Posteriormente, utiliza un sistema de lógica difusa para obtener un valor de calidad y finalmente emplea un motor de reglas para determinar el destino del café de acuerdo con las características y resultados obtenidos.

De esta manera, el proyecto combina diferentes enfoques de Inteligencia Artificial dentro de un mismo flujo de decisión.

Arquitectura del sistema

El proyecto está organizado en tres componentes principales:

                INFORMACIÓN DEL CAFÉ
                        │
                        ▼
             ┌─────────────────────┐
             │      ONTOLOGÍA      │
             │ Representación del  │
             │    conocimiento     │
             └──────────┬──────────┘
                        │
                        ▼
             ┌─────────────────────┐
             │    LÓGICA DIFUSA    │
             │ Evaluación de la    │
             │ calidad del café    │
             └──────────┬──────────┘
                        │
                        ▼
             ┌─────────────────────┐
             │   SISTEMA EXPERTO   │
             │ Reglas de decisión  │
             └──────────┬──────────┘
                        │
                        ▼
                DECISIÓN FINAL
                        │
      ┌─────────┬───────┼────────┐
      ▼         ▼       ▼        ▼
      Exportación  Nacional Retener Descarte
