# Sistema de Navegación y Guía por Voz Sintética para Recorridos Virtuales con Realidad Aumentada

## Descripción

Este proyecto corresponde al desarrollo de un **sistema de navegación y guía por voz sintética** integrado en una aplicación móvil de recorridos virtuales con realidad aumentada para el **Centro de Innovación y Tecnología (CIT)** de la Universidad del Valle de Guatemala.

La solución permite a los visitantes recorrer de forma autónoma las instalaciones del CIT, visualizando rutas de navegación en tiempo real y recibiendo información contextual mediante **voz sintética generada dinámicamente**, sincronizada con su posición dentro del entorno. El sistema fue desarrollado en **Unity** para dispositivos **iOS**, integrando posicionamiento interior mediante **sensores UWB**, navegación basada en **NavMesh**, una interfaz modular construida con **UI Toolkit** y un módulo de **Text-to-Speech (TTS)** de última generación.

Este repositorio corresponde a la **entrega académica del Proyecto de Graduación 2025**.

## Tecnologías Utilizadas

- Unity
- C#
- iOS
- Xcode
- UI Toolkit (Unity)
- NavMesh (Unity)
- Sensores UWB (Estimote)
- Text-to-Speech (Gemini 2.5 Pro TTS – Google)
- Plugins nativos Unity–iOS (P/Invoke)

## Requisitos Previos

Debido a la naturaleza del proyecto, su ejecución completa requiere **infraestructura y hardware específicos**:

- macOS con **Xcode** instalado
- **iPhone físico** compatible con UWB
- **Sensores UWB Estimote**
- Proyecto configurado en **Unity** con los SDK correspondientes
- Acceso a servicios de síntesis de voz (TTS)

> [!IMPORTANT] 
> Este proyecto **no es ejecutable mediante una simple clonación del repositorio**, ya que depende de hardware físico, servicios externos y configuraciones específicas de iOS. La validación funcional se realiza principalmente a través del video demostrativo y la documentación técnica.


## Instalación y Ejecución

Este repositorio **no está diseñado para ejecución local directa**.

El propósito del contenido es:
- Documentar la arquitectura del sistema
- Presentar los principales scripts y módulos desarrollados
- Respaldar académicamente el funcionamiento del proyecto

Para una demostración funcional completa, consulte el **video demo** incluido en el repositorio.

## Demo

El video demostrativo del proyecto se encuentra en:
[video-demo](demo/demo%20AR%20Tour.mp4)

El video muestra:
- Introducción al proyecto
- Funcionamiento del sistema de navegación
- Interacción con la interfaz de usuario
- Guía por voz sintética en tiempo real durante el recorrido

El audio del video corresponde principalmente al **sistema de Text-to-Speech de la aplicación**, el cual forma parte central de la experiencia del usuario.

## Documentación

El informe final del proyecto está disponible en:
[informe-final](docs/Trabajo%20de%20Graduación-21752-Diego%20Leiva.pdf)

El documento incluye:
- Fundamentación teórica
- Arquitectura del sistema
- Metodología de desarrollo
- Resultados y discusión
- Limitaciones técnicas
- Conclusiones y recomendaciones

## Estructura del Código Fuente

La carpeta `/src` contiene una **selección representativa del proyetcto de Unity**, scripts principales en `Scripts` y elementos importantes(assets) del proyecto de **Unity**, como `Audio`, `3D Models`, etc. organizada con fines académicos.

Debido a restricciones de plataforma, licencias y dependencias físicas, **no se incluye el proyecto completo de Unity**. La estructura presentada permite evaluar la arquitectura, la lógica y los aportes técnicos desarrollados.

## Autor
- **Diego Alberto Leiva Pérez**  
- Carnet: 21752
