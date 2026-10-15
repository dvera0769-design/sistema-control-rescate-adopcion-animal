# Patrones de diseño del sistema de control de rescate y adopción animal

Los patrones de diseño son soluciones que sirven como guía para organizar el software y resolver problemas comunes durante su desarrollo. Para este proyecto se proponen tres patrones que podrían ayudar a mantener el sistema ordenado y facilitar futuras mejoras.

## 1. Singleton (patrón creacional)

**Objetivo:** controlar que una clase tenga una única instancia compartida.

**Aplicación en el sistema:** podría utilizarse para administrar una configuración general de la aplicación, como ciertos parámetros comunes del sistema.

**Beneficio:** evita tener varias instancias de un mismo administrador de configuración cuando no son necesarias.

## 2. Factory Method (patrón creacional)

**Objetivo:** organizar la creación de objetos sin depender directamente de una clase concreta.

**Aplicación en el sistema:** podría utilizarse para crear diferentes tipos de notificaciones, por ejemplo, avisos de rescate registrado, solicitud de adopción recibida o adopción aprobada.

**Beneficio:** permite añadir nuevos tipos de notificaciones sin modificar toda la lógica del sistema.

## 3. Observer (patrón de comportamiento)

**Objetivo:** permitir que varios componentes reciban avisos cuando ocurre un cambio en otro componente.

**Aplicación en el sistema:** podría utilizarse para notificar a las personas responsables cuando una solicitud de adopción cambie de estado o cuando se registre un nuevo rescate.

**Beneficio:** facilita la comunicación entre las partes del sistema y ayuda a mantener actualizada la información.

## Conclusión

Los tres patrones propuestos tienen funciones diferentes. Singleton permite compartir una configuración, Factory Method organiza la creación de objetos y Observer facilita las notificaciones cuando ocurre un cambio. Su implementación dependerá de los requisitos definitivos y de cómo se programe el sistema.
