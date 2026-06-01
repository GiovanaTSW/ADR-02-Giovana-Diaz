# ADR-02: Definición y Adopción de Vistas Arquitectónicas para el Sistema Dressly

| Campo  | Valor |
|--------|-------|
| Autor  | Giovana Ruby Díaz Anduze |
| Fecha  | 31/05/2026 |
| Estado | `Propuesto` |

---

## Contexto

Hoy en día, muchas personas se responden una pregunta que se realizan todos los días: *¿Qué outfit me pondré hoy?*, esto puede llegar a ser cansado, pues a pesar de contar con la ropa suficiente dentro de su armario, ocurre ese sentimiento de no saber qué ponerse debido a que no recuerdan las prendas con las que cuentan y no saben cómo combinarlas, sumándole el hecho de que muchos usuarios realizan compras innecesarias desconociendo datos acerca de su propio tipo de cuerpo y colorimetría, como al no saber qué tipos de cortes y tonos les favorecen, adquiriendo prendas que terminan sin un solo uso; esto formando parte del consumo desmedido e innecesario de ropa, y acumulación de desperdicio textil que pierde la oportunidad de ser aprovechado por otros. 

Sabiendo esto, para garantizar que el desarrollo de Dressly sea comprensible, ordenado y cumpla estrictamente con los estándares de diseño de software de la Unidad 2, no basta sólo con definir un estilo lógico general, pues es importante documentar de forma multidimensional la arquitectura por medio de vistas que describan el sistema desde diferentes perspectivas: 

- La organización de los componentes lógicos
- El flujo de los procesos en tiempo de ejecución
- La distribución física del código fuente
- La topología de la infraestructura de despliegue

El sistema de Dressly se maneja mediante flujos críticos como el análisis de colorimetría y morfología para la generación de outfits, el almacenamiento local temporal en archivos `.json` y la comunicación con el catálogo externo de ONGs para la economía circular. Esta complejidad requiere documentación formal para guiar el desarrollo y evitar ambigüedades técnicas en las siguientes fases del proyecto.

---
