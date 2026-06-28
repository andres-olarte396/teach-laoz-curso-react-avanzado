# ⚛️ React Avanzado para Ingenieros Frontend - Teach LaOz

[![Estado](https://img.shields.io/badge/Estado-Activo-success)](https://github.com/andres-olarte396/teach-laoz-curso-react-avanzado)
[![Licencia](https://img.shields.io/badge/Licencia-MIT-blue.svg)](LICENSE)
[![Módulos](https://img.shields.io/badge/Módulos-6-purple)](plan_curricular.md)
[![Duración](https://img.shields.io/badge/Duración-25%20horas-orange)](plan_curricular.md)
[![Nivel](https://img.shields.io/badge/Nivel-Avanzado-red)](plan_curricular.md)

## 📋 Descripción

Curso de **React Avanzado y Patrones de Arquitectura** diseñado para ingenieros frontend con al menos 2 años de experiencia que buscan dominar los internos de React, patrones de diseño avanzados y optimización de rendimiento a nivel profesional.

Este material forma parte del proyecto **Teach LaOz Learning Management System**.

## 🎯 Objetivos del Curso

1. **Comprender los internos de React**: rendering, reconciliación y Fiber Architecture
2. **Aplicar patrones de diseño avanzados**: Compound Components, Control Props, Headless UI
3. **Escalar el estado de la aplicación** sin prop-drilling ni re-renders innecesarios
4. **Diagnosticar y solucionar cuellos de botella** de rendimiento con Profiler
5. **Implementar estrategias de testing** robustas para aplicaciones complejas

## 👥 Audiencia y Prerrequisitos

**Audiencia objetivo**: Ingenieros Frontend con 2+ años de experiencia en React

**Prerrequisitos**:
- JavaScript Moderno (ES6+, Closures, Async/Await)
- React básico a intermedio (hooks, estado, ciclo de vida)
- TypeScript básico

## 📚 Estructura del Curso

### Información General

| Campo | Detalle |
|-------|---------|
| **Complejidad** | Alta |
| **Duración** | 25 horas |
| **Modalidad** | Autoestudio con proyectos |

### Módulos

#### 📍 Módulo 0: Fundamentos Sólidos y Nivelación
- JavaScript Moderno para React (Closures, `this`, Event Loop)
- TypeScript Esencial — Generics, Utility Types, Inferencias
- Arquitectura Interna de React — Virtual DOM vs Real DOM

#### 📍 Módulo 1: Deep Dive en Rendering y Reconciliación
- Fase de Render vs Fase de Commit
- El Algoritmo de Reconciliación (Diffing, importancia de las Keys)
- React Fiber Architecture — Units of work y priorización

#### 📍 Módulo 2: Gestión de Estado Avanzada
- Context API: Patrones de optimización (Split Context)
- State Machines con XState — Lógica de estado determinista
- Server State Management — React Query / TanStack Query

#### 📍 Módulo 3: Patrones de Diseño de Componentes
- Compound Components Pattern — Gestión de estado implícito
- Control Props Pattern — Inversión de control
- Polymorphic Components con TypeScript
- Headless UI Components — Separación total de lógica y vista

#### 📍 Módulo 4: Performance y Optimización
- Profiling en React — DevTools Profiler y Flamegraphs
- Memoization Strategies — `useMemo`, `useCallback`, `React.memo`
- Code Splitting y Lazy Loading — Por ruta y por componente
- Virtualización de listas — Windowing

#### 📍 Módulo 5: Testing y Calidad
- Pruebas de integración con React Testing Library
- Testing de Custom Hooks complejos
- Mocking avanzado con MSW (Mock Service Worker)

## 🗂️ Organización de Archivos

```
teach-laoz-curso-react-avanzado/
│
├── README.md                          # Este archivo
├── plan_curricular.md                 # Plan curricular detallado
│
└── modulos/                           # Contenido por módulos (en desarrollo)
    ├── modulo_0/                      # Fundamentos
    ├── modulo_1/                      # Rendering y Reconciliación
    ├── modulo_2/                      # Estado Avanzado
    ├── modulo_3/                      # Patrones de Diseño
    ├── modulo_4/                      # Performance
    └── modulo_5/                      # Testing
```

## 🛠️ Herramientas y Tecnologías

| Categoría | Herramientas |
|-----------|-------------|
| Framework | React 18+ |
| Lenguaje | TypeScript 5+ |
| Estado | XState, React Query, Zustand |
| Testing | Vitest, React Testing Library, MSW |
| Profiling | React DevTools Profiler |
| Patrones | Compound Components, Headless UI |

## 🚀 Cómo Usar Este Material

1. **Verifica tus prerrequisitos** — Este es un curso avanzado
2. **Empieza por el Módulo 0** para nivelar conceptos de JS/TS
3. **Construye proyectos** al finalizar cada módulo
4. **Aplica los patrones** en tu código de producción real

## 🤝 Contribuciones

Para añadir ejemplos, proyectos o corregir contenido:

1. Abre un **Issue** describiendo la mejora
2. Haz un **Fork** del repositorio
3. Envía un **Pull Request**

## 📄 Licencia

Material educativo disponible bajo la Licencia MIT.

## 👥 Créditos

**Proyecto**: Teach LaOz Learning Management System
**Autor**: Andrés Olarte
**Repositorio**: [github.com/andres-olarte396/teach-laoz-curso-react-avanzado](https://github.com/andres-olarte396/teach-laoz-curso-react-avanzado)

---

**¡Lleva tu React al siguiente nivel profesional! ⚛️🚀**
