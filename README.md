# SRE om AWS

## Section 1: The basics of Site Realiability Engineering
### Intro

![Intro](./img/1.png)
![Intro](./img/2.png)
![Intro](./img/3.png)

Repo: https://github.com/mt2h/Site-Reliability-Engineering-on-AWS

### Reability in Moder Applications

![Reability in Moder Applications](./img/4.png)
![Reability in Moder Applications](./img/5.png)
![Reability in Moder Applications](./img/6.png)
![Reability in Moder Applications](./img/7.png)

### The impact of Failure and Determinating Your Realiability Objetives

![The impact of Failure and Determinating Your Realiability Objetives](./img/8.png)
![The impact of Failure and Determinating Your Realiability Objetives](./img/9.png)
![The impact of Failure and Determinating Your Realiability Objetives](./img/10.png)
![The impact of Failure and Determinating Your Realiability Objetives](./img/11.png)
![The impact of Failure and Determinating Your Realiability Objetives](./img/12.png)

### Accepting Failure and Making It Part of the Design Process

![Accepting Failure and Making It Part of the Design Process](./img/13.png)
![Accepting Failure and Making It Part of the Design Process](./img/14.png)
![Accepting Failure and Making It Part of the Design Process](./img/15.png)
![Accepting Failure and Making It Part of the Design Process](./img/16.png)

### SRE is a Mindset

![SRE is a Mindset](./img/17.png)
![SRE is a Mindset](./img/18.png)
![SRE is a Mindset](./img/19.png)
![SRE is a Mindset](./img/20.png)

## Section 2: Gaining Resilence and Realiability on AWS

### AWS Global, Regional and Zonal Architecture Design

![AWS Global, Regional and Zonal Architecture Design](./img/21.png)
![AWS Global, Regional and Zonal Architecture Design](./img/22.png)
![AWS Global, Regional and Zonal Architecture Design](./img/23.png)
![AWS Global, Regional and Zonal Architecture Design](./img/24.png)
![AWS Global, Regional and Zonal Architecture Design](./img/25.png)

### Amazon's Global Storage Service - S3

![Amazon's Global Storage Service - S3](./img/26.png)
![Amazon's Global Storage Service - S3](./img/27.png)
![Amazon's Global Storage Service - S3](./img/28.png)
![Amazon's Global Storage Service - S3](./img/29.png)

### Running Resilient Databases on AWS - RDS and DynamoDB

![Running Resilient Databases on AWS - RDS and DynamoDB](./img/30.png)
![Running Resilient Databases on AWS - RDS and DynamoDB](./img/31.png)
![Running Resilient Databases on AWS - RDS and DynamoDB](./img/32.png)
![Running Resilient Databases on AWS - RDS and DynamoDB](./img/33.png)

### Fault Tolerant Computation on AWS - Lamba and EC2

![Fault Tolerant Computation on AWS - Lamba and EC2](./img/34.png)
![Fault Tolerant Computation on AWS - Lamba and EC2](./img/35.png)
![Fault Tolerant Computation on AWS - Lamba and EC2](./img/36.png)
![Fault Tolerant Computation on AWS - Lamba and EC2](./img/37.png)
![Fault Tolerant Computation on AWS - Lamba and EC2](./img/38.png)

### Core Resilience Principles for AWS - Load Balacing and Auto Scaling

![Core Resilience Principles for AWS - Load Balacing and Auto Scaling](./img/39.png)
![Core Resilience Principles for AWS - Load Balacing and Auto Scaling](./img/40.png)
![Core Resilience Principles for AWS - Load Balacing and Auto Scaling](./img/41.png)

### Using Kubernetes and ECS on AWS

![Using Kubernetes and ECS on AWS](./img/42.png)
![Using Kubernetes and ECS on AWS](./img/43.png)
![Using Kubernetes and ECS on AWS](./img/44.png)
![Using Kubernetes and ECS on AWS](./img/45.png)
![Using Kubernetes and ECS on AWS](./img/46.png)
![Using Kubernetes and ECS on AWS](./img/47.png)

## Section 3: Accepting Failure in Multi-Tier Applications

### Typical Three-Tier Application Resilience and Why it fails in Cloud

![Typical Three-Tier Application Resilience and Why it fails in Cloud](./img/48.png)
![Typical Three-Tier Application Resilience and Why it fails in Cloud](./img/49.png)
![Typical Three-Tier Application Resilience and Why it fails in Cloud](./img/50.png)

### Desinging in Resilience with Microservices

![Desinging in Resilience with Microservices](./img/51.png)
![Desinging in Resilience with Microservices](./img/52.png)
![Desinging in Resilience with Microservices](./img/53.png)

## Managing State

![Managing State](./img/54.png)
![Managing State](./img/55.png)
![Managing State](./img/56.png)
![Managing State](./img/57.png)
![Managing State](./img/58.png)
![Managing State](./img/59.png)
![Managing State](./img/60.png)

Un proxy de Amazon RDS (Relational Database Service) es una herramienta que permite administrar conexiones a bases de datos de Amazon RDS y Aurora de manera eficiente y segura. Los microservicios son una arquitectura de desarrollo de aplicaciones en la que las aplicaciones se dividen en componentes más pequeños e independientes llamados microservicios. Usar un proxy RDS en esta arquitectura puede proporcionar varios beneficios:

Administración de conexiones: En una arquitectura de microservicios, múltiples microservicios pueden necesitar acceder a la misma base de datos. Un proxy RDS puede administrar y gestionar de manera centralizada las conexiones a la base de datos, evitando la necesidad de que cada microservicio maneje su propia conexión. Esto reduce la sobrecarga en la base de datos y mejora el rendimiento.

Escalabilidad y elasticidad: Un proxy RDS puede manejar automáticamente la escalabilidad y la elasticidad de las conexiones a la base de datos. A medida que el número de microservicios o la carga de trabajo aumenta, el proxy puede ajustar la cantidad de conexiones disponibles para garantizar un rendimiento óptimo y evitar la saturación de la base de datos.

Seguridad: El proxy RDS actúa como un punto de entrada controlado a la base de datos. Puede implementar autenticación y autorización, lo que significa que solo los microservicios autorizados pueden acceder a la base de datos a través del proxy. Esto refuerza la seguridad y protege la base de datos de accesos no autorizados.

Aislamiento: Los microservicios pueden aislarse de los detalles de conexión y configuración de la base de datos subyacente. El proxy puede manejar la administración de conexiones, el almacenamiento en caché de consultas y otros aspectos técnicos, permitiendo que los equipos de desarrollo se centren en la lógica de negocio y no en los detalles de implementación de la base de datos.

Monitorización y análisis: Un proxy RDS puede proporcionar métricas y registros de rendimiento de las consultas realizadas por los microservicios. Esto permite a los equipos de operaciones y desarrollo monitorear y analizar el rendimiento de las consultas, identificar cuellos de botella y optimizar el acceso a la base de datos.

En resumen, usar un proxy RDS en una arquitectura de microservicios en AWS puede ayudar a optimizar el rendimiento, la escalabilidad, la seguridad y la administración de conexiones a la base de datos, permitiendo a los equipos de desarrollo concentrarse en la funcionalidad de los microservicios en lugar de preocuparse por los detalles de la conexión y gestión de la base de datos.