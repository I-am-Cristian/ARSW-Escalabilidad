# Laboratorio: Escalabilidad, Alta Disponibilidad y Observabilidad en AWS

Propósito del Laboratorio 

En una arquitectura moderna no basta con desplegar una aplicación y esperar que responda correctamente. Los sistemas deben ser capaces de:
- Atender más usuarios cuando aumenta la demanda
- Mantenerse disponibles cuando una instancia falla
- Distribuir tráfico entre múltiples servidores
- Detectar fallos mediante health checks
- Observar métricas de carga, disponibilidad y rendimiento
- Tomar decisiones con base en datos reales

Este laboratorio integra tres conceptos fundamentales:
| Concepto                | Definición                                                                | Enfoque en el lab                                                                                    |
| ----------------------- | ------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| **Escalabilidad**       | Capacidad del sistema para adaptarse al aumento o disminución de la carga | Escalabilidad horizontal con Amazon EC2 Auto Scaling                                                 |
| **Alta Disponibilidad** | El sistema sigue funcionando aunque falle alguno de sus componentes       | Application Load Balancer distribuyendo tráfico entre múltiples instancias y zonas de disponibilidad |
| **Observabilidad**      | Entender qué ocurre dentro de la arquitectura mediante señales            | Métricas, logs y eventos en Amazon CloudWatch                                                        |

