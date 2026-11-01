##PilarBus##

Sistema movil y plataforma web para monitorear recorridos de transporte publico en tiempo real.
Metodologia

El proyecto utiliza Scrum debido a la naturaleza cambiante de los requisitos y la necesidad de incorporar mejoras continuas basadas en comentarios de usuarios beta.
Flujo de trabajo GitHub

    Cada desarrollador trabaja en una rama independiente.

    Los cambios se envian mediante Pull Request.

    El codigo es revisado por otro miembro del equipo.

    GitHub Actions ejecuta automaticamente:
        Build
        Test
        Verificacion de calidad

    Si todas las validaciones son exitosas:
        Merge a main.

    El pipeline CI/CD despliega automaticamente la aplicacion en la nube.

Beneficios del uso de Pull Requests

    Revision de codigo.
    Deteccion temprana de errores.
    Mejor colaboracion.
    Historial completo de cambios.

Beneficios de CI/CD
Integracion Continua (CI)

    Compila automaticamente el proyecto.
    Ejecuta pruebas automaticas.
    Detecta errores antes de fusionar codigo.

Entrega Continua (CD)

    Publica nuevas versiones automaticamente.
    Reduce tiempo de despliegue.
    Evita interrupciones del servicio.

Tecnologias

    GitHub
    GitHub Actions
    Trello
    Scrum
    Docker
    Flutter
    React
