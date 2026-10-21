<div align="center">

  <img src="/assets/banner-black.png" alt="Epora Banner" width="100%"/>
  <h1>Epora</h1>

  <p><strong>ERP y facturación electrónica de código abierto para PYMES —<br/>clásica y POS — con una arquitectura de microservicios diseñada para no caerse nunca.</strong></p>

  <p>
    <a href="https://github.com/epora-erp">github.com/epora-erp</a>
  </p>

  <p>
    <a href="#1-resumen-ejecutivo">Resumen</a> ·
    <a href="#2-propósito-del-proyecto">Propósito</a> ·
    <a href="#21-el-problema">El problema</a> ·
    <a href="#22-la-propuesta-de-epora">La propuesta</a> ·
    <a href="#23-triple-misión">Triple misión</a>
  </p>
</div>

---

## 1. Resumen ejecutivo

Epora es una plataforma de código abierto de **ERP** y facturación electrónica que nace de la insatisfacción con el software dominante del mercado: lento, anticuado y burocrático, hasta el punto de trabajar para el sistema en lugar de que el sistema trabaje para el negocio.

La propuesta es un servicio **abierto, disponible y comprensible**.

---

## 2. Propósito del proyecto

### 2.1 El problema

Los **ERP** actuales, sean para grandes empresas, PYMES o sectores específicos, comparten problemas recurrentes:

| **Problema**                                                                                       | **Impacto**                                                                                                   | **Enfoque de Epora**                                                    |
| -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------- |
| **Overhead:** requiere hardware potente para funcionar con fluidez.                                 | Dispositivos con pocas capacidades no pueden operar bien.                                                      | Optimización del software y uso eficiente de los recursos.             |
| **Alta latencia** entre servidor y cliente.                                                        | Inconsistencia de datos, condiciones de carrera, desfases de estado.                                            | Comunicación eficiente y mecanismos de consistencia.                    |
| **Interfaces anticuadas**                                                                          | Capacitaciones largas y menor facilidad operativa.                                                             | Interfaz moderna, clara y funcional.                                    |
| **Alto costo** para PYMES.                                                                         | Acceso difícil o poco provechoso.                                                                              | Accesibilidad económica y barreras de entrada bajas.                    |
| **Software cerrado.**                                                                              | Sin personalización ni integraciones propias; dependencia total de la nube.                                    | Código abierto, personalización e integración con sistemas externos.    |
| **Complejidad desmesurada:** pasos innecesarios.                                                   | Procesos confusos y poco eficaces para el personal operativo.                                                   | Procesos simplificados y flujos intuitivos.                             |
| **Disponibilidad cuestionable:** caídas frecuentes.                                                | "No hay sistema", menos tiempo de operación e incertidumbre.                                                   | Arquitectura orientada a estabilidad, resiliencia y disponibilidad.     |

> Son objetivos de diseño; no implican que los problemas estén resueltos por completo en la implementación actual.

### 2.2 La propuesta de Epora

Una alternativa de código abierto, eficiente, accesible y adaptable a las necesidades de cada negocio.

### 2.3 Triple misión

Tres misiones simultáneas condicionan toda la arquitectura:

> 1. **Ser un producto real** adoptado por los negocios —en especial los nacionales— como estándar operativo.
> 2. **Ser material de estudio vivo** sobre cómo se construye un producto real: arquitectura de software, diseño de sistemas y desarrollo de aplicaciones.
> 3. **Proveer un mecanismo efectivo para replicar el servicio en local.**

Ninguna puede sacrificarse por otra: el cumplimiento de las tres define el éxito del proyecto.
