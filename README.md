# Callenge For Software Engineer

* [Objetivo](#objetivo)
* [Requisitos Funcionales](#requisitos-funcionales)
* [Requisitos Técnicos](#requisitos-técnicos)
* [CI/CD (Continuous Integration / Continuous Deployment)](#cicd-continuous-integration-continuous-deployment)
* [Evaluación](#evaluación)
* [Entrega](#entrega)

<a name="objetivo"></a>
## Objetivo
Desarrollar un servidor HTTP que simule una cuenta corriente de saldos, con la capacidad de gestionar transacciones monetarias para usuarios y proporcionar el saldo actual de un usuario. Además, debes implementar un flujo de CI/CD para garantizar la calidad y la entrega continua del software.

<a name="requisitos-funcionales"></a>
## Requisitos Funcionales

1. Implementar un servidor HTTP con los siguientes endpoints:
   * POST /transaccion: Este endpoint permite a un usuario realizar una transacción monetaria. La transacción incluirá el ID del usuario, el monto de la transacción y el tipo (entrada o salida).
   * GET /saldo/{usuario_id}: Este endpoint devuelve el saldo actual de un usuario dado su ID.
2. Garantizar que no sea posible retirar dinero si un usuario no tiene suficiente saldo en su cuenta.
3. Manejar adecuadamente los problemas de simultaneidad en las transacciones.

<a name="requisitos-técnicos"></a>
## Requisitos Técnicos
1. El software debe ser ejecutable en máquinas Linux y MacOS.
2. Utilizar almacenamiento en memoria en proceso para gestionar los saldos de los usuarios (no es necesario utilizar bases de datos).
3. Implementar buenas prácticas de desarrollo, como pruebas unitarias y de integración, documentación (README), y seguir patrones de diseño adecuados.
4. Asegurarse de manejar correctamente los valores decimales para evitar problemas de precisión.
5. Implementar un manejo adecuado de errores y proporcionar respuestas HTTP apropiadas en caso de errores.

<a name="cicd-continuous-integration-continuous-deployment"></a>
## CI/CD (Continuous Integration / Continuous Deployment)
Implementa un sistema de CI/CD para el proyecto que incluya lo siguiente:

* Configuración de un sistema de integración continua para ejecutar pruebas automáticamente en cada confirmación de código.
* Configuración de un sistema de entrega continua para automatizar la implementación del software en un entorno de prueba o producción después de las pruebas exitosas.
* Utilización de herramientas populares de CI/CD, como Jenkins, Travis CI, CircleCI, GitLab CI/CD, o cualquier otra que prefieras.

<a name="evaluación"></a>
## Evaluación
Se evaluarán los siguientes aspectos:

* Diseño de API: La estructura y la facilidad de uso de los endpoints.
* Calidad del Código: Claridad, modularidad y legibilidad del código.
* Pruebas: Cobertura de pruebas unitarias y de integración.
* Manejo de Errores: La capacidad de manejar errores de manera adecuada y proporcionar respuestas apropiadas.
* Inmutabilidad y Separación de Intereses: Uso adecuado de conceptos como inmutabilidad y separación de intereses en el diseño.
* CI/CD: Implementación exitosa de un flujo de CI/CD.

<a name="entrega"></a>
## Entrega

El candidato debe entregar su solución como un archivo comprimido que contenga el código fuente, pruebas y la documentación necesaria. Asegúrate de que el código sea anónimo y no incluya archivos innecesarios como el repositorio de Git o binarios compilados. Además, no se debe cargar la solución en repositorios públicos en GitHub, BitBucket, etc.
