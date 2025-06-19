Práctica Formativa Obligatoria 03 – DevOps | Kubernetes + Minikube

Este proyecto es parte de la entrega de la Práctica Formativa Obligatoria N°3 de la materia DevOps. El objetivo fue familiarizarse con Kubernetes a través de Minikube y deployar una pequeña app web escrita en PHP utilizando contenedores.

¿Qué incluye?

    Un Dockerfile que construye una imagen con PHP y una página simple.

    Un archivo YAML para crear el deployment en Kubernetes.

    Un index.php que muestra un mensaje dinámico con el nombre del contenedor.

Tecnologías usadas

    Docker

    Minikube

    Kubernetes

Pasos clave del trabajo

    Se levantó Minikube localmente y se accedió al dashboard.

    Se creó y expuso un deployment de prueba.

    Se construyó la imagen de la app y se cargó en Minikube.

    Se agregó imagePullPolicy: Never para evitar errores de carga.

    Se deployó y expuso la app final con un servicio tipo NodePort.

Resultado esperado

Al acceder al servicio, el navegador muestra algo como:

Seminario Devop! Bienvenido a mi repo mi-repo-php-xxxx
