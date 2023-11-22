# Challenge For Software Engineer

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

 1. Usuarios:
    * Endpoint para agregar usuarios con la posibilidad de generar cuentas en pesos, dólares y bitcoin (ficticias).
    * Funcionalidad de inicio de sesión para los usuarios.

2. Seguridad:
    * Posibilidad para que los usuarios generen un PIN de seguridad para llevar a cabo operaciones.

3. Transacciones:
    * Implementación de endpoints para realizar transacciones de entrada y salida en todas las cuentas.
    * Capacidad de realizar transacciones de convertibilidad entre las cuentas propias de los usuarios.

4. Historial:
    * Mantenimiento de un historial detallado de todas las transacciones realizadas en cada cuenta.

5. Saldos:
    * Acceso a los saldos individuales de cada cuenta.
    * Acceso al balance general de cada usuario.

6. Seguridad en Transacciones:
    * Precauciones para garantizar que las transacciones no afecten los saldos de manera incorrecta.
    * Manejo adecuado de problemas de simultaneidad en las transacciones.

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

* Es recomendable que utilices un diagrama (draw.io / lucidchart pueden servir) explicandonos como consideras la mejor opcion para el proceso CI/CD.
   
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
