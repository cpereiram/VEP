# Virtual Exhibition Platform

Plataforma modular en Unity para crear y visualizar exposiciones virtuales tridimensionales, usando como caso de estudio un Museo Virtual de Jachkar (Khachkar) de Armenia.

## Propósito

El proyecto busca separar el dominio de la exposición, la lógica de aplicación, la presentación y la infraestructura para mantener una sola base de código compatible con Desktop y Realidad Virtual.

## Alcance inicial

- Modo Espectador para recorrer el museo e inspeccionar piezas.
- Modo Editor para importar modelos, editarlos y guardar la exposición.
- Persistencia en JSON.
- Soporte prioritario para Windows.
- Preparación para VR mediante OpenXR y XR Interaction Toolkit.

## Tecnología prevista

- Unity 6
- URP
- Input System
- XR Interaction Toolkit
- GLB / glTF
- JSON

## Documento de arquitectura

El detalle de la solución está descrito en [SAD.md](SAD.md), donde se explican los requisitos, módulos, decisiones de diseño, persistencia y roadmap del proyecto.

## Estado actual

Este repositorio contiene la documentación base del proyecto. La implementación podrá evolucionar a partir de la arquitectura definida en el SAD.
