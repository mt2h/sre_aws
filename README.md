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

### Managing State

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

### Typical Application Realiability Patterns

![Typical Application Realiability Patterns](./img/61.png)
![Typical Application Realiability Patterns](./img/62.png)
![Typical Application Realiability Patterns](./img/63.png)

En el contexto de los microservicios y la disciplina de Site Reliability Engineering (SRE), un "circuit breaker" (interruptor de circuito) es un patrón de diseño que se utiliza para mejorar la resiliencia y la estabilidad de un sistema distribuido. Su función principal es prevenir que un servicio siga enviando solicitudes a un servicio remoto (ya sea otro microservicio, una base de datos, API externa, etc.) que está experimentando problemas o fallas. Esto se hace para evitar una carga excesiva en el servicio remoto y para proteger la integridad del sistema en su conjunto.

El nombre "circuit breaker" proviene de una analogía con los interruptores eléctricos en una casa. Al igual que un interruptor de circuito se abre automáticamente para evitar daños en el sistema eléctrico cuando hay un cortocircuito o una sobrecarga, un circuit breaker en el contexto de la arquitectura de microservicios "abre" temporalmente la conexión con un servicio remoto cuando se detecta un fallo, evitando así que más solicitudes se envíen hasta que el problema se resuelva.

El patrón de circuit breaker generalmente opera de la siguiente manera:

1. **Estado cerrado (Closed)**: En este estado, el circuit breaker permite que las solicitudes fluyan normalmente entre el servicio y el servicio remoto. Se monitorea constantemente la tasa de errores o respuestas fallidas. Si la tasa de errores supera un umbral predefinido, el circuit breaker se activa y cambia al siguiente estado.

2. **Estado abierto (Open)**: Una vez que se supera el umbral de errores, el circuit breaker se abre. En este estado, el circuito está "abierto" y todas las solicitudes subsiguientes al servicio remoto se bloquean temporalmente. Esto evita que el servicio siga enviando solicitudes a un componente que está fallando, lo que podría empeorar la situación.

3. **Estado semi-abierto (Half-Open)**: Después de un período de tiempo definido, el circuit breaker pasa al estado semi-abierto. En este estado, se permite pasar una pequeña cantidad de solicitudes al servicio remoto para probar si el problema se ha resuelto. Si estas solicitudes son exitosas y no se observan más errores, el circuit breaker regresa al estado cerrado. Si persisten los problemas, vuelve al estado abierto.

El patrón de circuit breaker es una parte fundamental de la estrategia de resiliencia en arquitecturas de microservicios y SRE, ya que ayuda a prevenir la propagación de problemas y permite que los sistemas se recuperen de manera más efectiva. También es útil para gestionar la carga durante picos de tráfico o caídas temporales de componentes.

![Typical Application Realiability Patterns](./img/64.png)

En el contexto de la arquitectura de microservicios y la ingeniería de confiabilidad del sitio (SRE), el patrón de diseño de "bulkhead" (mamparo o compartimentación) se utiliza para mejorar la resiliencia de un sistema distribuido al aislar componentes y limitar el impacto de las fallas. Este patrón toma su nombre de las divisiones resistentes en un barco llamadas "bulkheads" que previenen que el agua ingrese a otras secciones en caso de colisión o daño.

En términos simples, un bulkhead implica separar diferentes partes de un sistema para evitar que la falla o el colapso de una sección afecte negativamente a las otras secciones. Esto se logra al asignar recursos y limitar la capacidad de cada componente, de manera que si un componente falla o experimenta una sobrecarga, las demás partes del sistema no se vean perjudicadas.

Un ejemplo práctico de bulkheads en una arquitectura de microservicios es el uso de pools de conexiones separados para diferentes microservicios que acceden a bases de datos. Si un microservicio experimenta un aumento repentino de tráfico y agota sus conexiones en el pool, no afectará la capacidad de otros microservicios para acceder a la base de datos, ya que cada microservicio tiene su propio pool de conexiones aislado.

En resumen, el patrón de bulkhead se trata de crear compartimentos aislados en un sistema distribuido para limitar el alcance de las fallas y mejorar la resistencia general del sistema. Esto es especialmente útil en microservicios y SRE para mitigar el impacto de los fallos y garantizar que el rendimiento y la disponibilidad de todo el sistema no se vean comprometidos por problemas en un componente específico.

![Typical Application Realiability Patterns](./img/65.png)

### The Architecture of our example microservices


![The Architecture of our example microservices](./img/66.png)
![The Architecture of our example microservices](./img/67.png)
![The Architecture of our example microservices](./img/68.png)

AWS X-Ray es un servicio proporcionado por Amazon Web Services (AWS) que se utiliza para rastrear y analizar el flujo de solicitudes a través de aplicaciones distribuidas y en la nube. Es especialmente útil en el contexto de arquitecturas de microservicios y sistemas basados en la nube, donde múltiples componentes interactúan para cumplir con una solicitud. X-Ray permite a los desarrolladores y equipos de operaciones visualizar y analizar cómo se comportan estas solicitudes a medida que atraviesan diferentes servicios.

En el contexto de la malla de aplicaciones (application mesh), que es un conjunto de servicios interconectados que colaboran para ofrecer una aplicación, X-Ray se utiliza para rastrear y registrar información sobre cada paso de una solicitud a medida que viaja a través de los diferentes servicios en la malla. Algunos de los conceptos clave de cómo X-Ray rastrea la malla de aplicaciones incluyen:

1. **Segmentos y subsegmentos**: X-Ray divide una solicitud en segmentos, que representan un componente de la aplicación, como un microservicio. Cada segmento puede contener subsegmentos para desglosar aún más las operaciones internas dentro de ese componente.

2. **Traza de solicitud**: X-Ray crea una "traza" que muestra el recorrido completo de una solicitud a medida que atraviesa diferentes segmentos y subsegmentos. Esto permite a los equipos identificar cuellos de botella, retrasos o problemas en el flujo de la solicitud.

3. **Tiempo y latencia**: X-Ray registra el tiempo que lleva cada segmento y subsegmento para procesar una solicitud. Esto ayuda a identificar áreas donde se está produciendo una latencia significativa.

4. **Mapa de servicio**: X-Ray genera un mapa visual de los componentes de la aplicación y sus relaciones, lo que ayuda a comprender la topología de la malla de aplicaciones y cómo se conectan los diferentes servicios.

5. **Información de contexto**: X-Ray permite agregar metadatos y etiquetas personalizadas a los segmentos y subsegmentos para proporcionar información adicional sobre el contexto de la solicitud.

En resumen, AWS X-Ray es una herramienta poderosa para rastrear y analizar el flujo de solicitudes a través de aplicaciones distribuidas y mallas de aplicaciones. Ayuda a los equipos a identificar problemas de rendimiento, comprender las interacciones entre los servicios y mejorar la visibilidad en entornos complejos de microservicios y arquitecturas basadas en la nube.

## Deploying Py-Simple on AWS


### Optimizing and Migratingf Our Code

![Deploying Py-Simple on AWS](./img/69.png)
![Deploying Py-Simple on AWS](./img/70.png)
![Deploying Py-Simple on AWS](./img/71.png)
![Deploying Py-Simple on AWS](./img/72.png)
![Deploying Py-Simple on AWS](./img/73.png)
![Deploying Py-Simple on AWS](./img/74.png)

- Repo Project Code: https://github.com/mt2h/Site-Reliability-Engineering-on-AWS/tree/master/packt-sre-code/packt-sre/pysimple

- Helper AWS to Create Custom Metrics in AWS: https://github.com/mt2h/Site-Reliability-Engineering-on-AWS/blob/master/packt-sre-code/packt-sre/pysimple/carLister/awsHelper.py

- Use custom Metrics SLI: https://github.com/mt2h/Site-Reliability-Engineering-on-AWS/blob/master/packt-sre-code/packt-sre/pysimple/carLister/main.py

- Repo IAC for CodeCommit: https://github.com/mt2h/Site-Reliability-Engineering-on-AWS/tree/master/packt-sre-code/packt-sre/IAC/1-codecommit 

After Terraform apply....

![Deploying Py-Simple on AWS](./img/75.png)

Clone repository from CodeCommit AWS

![Deploying Py-Simple on AWS](./img/76.png)

Push files to the repository

![Deploying Py-Simple on AWS](./img/77.png)
![Deploying Py-Simple on AWS](./img/78.png)

### Creating our Container with CodeBuild

![Creating our Container with CodeBuild](./img/79.png)

Repo Create CodeBuild: https://github.com/mt2h/Site-Reliability-Engineering-on-AWS/tree/master/packt-sre-code/packt-sre/IAC/2-codebuild

![Creating our Container with CodeBuild](./img/80.png)

Repo Create ECR: https://github.com/mt2h/Site-Reliability-Engineering-on-AWS/tree/master/packt-sre-code/packt-sre/IAC/3-ecr

![Creating our Container with CodeBuild](./img/81.png)

Pipeline: https://github.com/mt2h/Site-Reliability-Engineering-on-AWS/blob/master/packt-sre-code/packt-sre/build/buildspec.yml

![Creating our Container with CodeBuild](./img/82.png)
![Creating our Container with CodeBuild](./img/83.png)
![Creating our Container with CodeBuild](./img/84.png)
![Creating our Container with CodeBuild](./img/85.png)
![Creating our Container with CodeBuild](./img/86.png)
![Creating our Container with CodeBuild](./img/87.png)
![Creating our Container with CodeBuild](./img/88.png)
![Creating our Container with CodeBuild](./img/89.png)

### Deploying ECS and RDS

![Deploying ECS and RDS](./img/90.png)

Repo Create RDS: https://github.com/mt2h/Site-Reliability-Engineering-on-AWS/tree/master/packt-sre-code/packt-sre/IAC/4-rds

Repo Create Load Balancer And ECS: https://github.com/mt2h/Site-Reliability-Engineering-on-AWS/tree/master/packt-sre-code/packt-sre/IAC/5-ecs

### Deploying and Testing our Py-Simple Application

![Deploying and Testing our Py-Simple Application](./img/91.png)
![Deploying and Testing our Py-Simple Application](./img/92.png)
![Deploying and Testing our Py-Simple Application](./img/93.png)
![Deploying and Testing our Py-Simple Application](./img/94.png)

Un servidor EC2 bastion, también conocido como "bastión host" o "bastion instance" en inglés, es un tipo de instancia en Amazon Web Services (AWS) que se utiliza para administrar y acceder de manera segura a otras instancias ubicadas en una red privada. La función principal de un servidor EC2 bastion es proporcionar un punto de entrada seguro para los administradores o usuarios autorizados que necesitan acceder a las instancias dentro de una red privada o un VPC (Virtual Private Cloud).

En arquitecturas de red, a menudo se establecen zonas de seguridad. Las instancias en una red privada no tienen acceso directo desde Internet, lo que aumenta su seguridad, pero puede dificultar la administración. Aquí es donde entra en juego el servidor EC2 bastion. Este servidor se coloca en una zona de seguridad menos restringida, como una red pública, y se configura con los adecuados mecanismos de seguridad, como claves SSH y reglas de seguridad de grupo. Cuando un administrador necesita acceder a las instancias en la red privada, se conecta primero al servidor bastion y, desde allí, puede iniciar una conexión segura hacia las instancias de la red privada.

El servidor bastion actúa como un punto de entrada controlado, limitando las posibles superficies de ataque y protegiendo las instancias en la red privada al no exponerlas directamente a Internet. Esto ayuda a reducir el riesgo de ataques maliciosos y mejora la seguridad en general. Es una práctica común en la administración de sistemas y en la configuración de la infraestructura en la nube, como en AWS.

![Deploying and Testing our Py-Simple Application](./img/95.png)

Repo: https://github.com/mt2h/Site-Reliability-Engineering-on-AWS/tree/master/packt-sre-code/packt-sre/IAC/6-ecs-task

Tarea (Task) en Amazon ECS:
Una tarea en Amazon ECS representa la unidad más pequeña de trabajo que puedes enviar a la plataforma. Puede consistir en uno o más contenedores que se ejecutan juntos en la misma instancia EC2 o en la misma instancia Fargate (en este caso). Los contenedores en una misma tarea comparten recursos, como red y almacenamiento. En otras palabras, una tarea define cómo se ejecutarán uno o más contenedores juntos, y qué recursos (CPU, memoria, puertos, variables de entorno, etc.) estarán disponibles para cada contenedor.

Servicio en Amazon ECS:
Un servicio en Amazon ECS es un recurso que define cómo se ejecutan y escalan las tareas en una plataforma de contenedores. Un servicio se encarga de administrar un conjunto de tareas idénticas (definidas por la misma definición de tarea). Cuando creas un servicio, le indicas a ECS cuántas instancias (tareas) de la tarea definida debe mantener en ejecución. Además, un servicio controla la manera en que las tareas se distribuyen en las instancias y cómo se escalan en función de la demanda.

#### ECS Task

![Deploying and Testing our Py-Simple Application](./img/96.png)
![Deploying and Testing our Py-Simple Application](./img/97.png)
![Deploying and Testing our Py-Simple Application](./img/98.png)
![Deploying and Testing our Py-Simple Application](./img/99.png)
![Deploying and Testing our Py-Simple Application](./img/100.png)
![Deploying and Testing our Py-Simple Application](./img/101.png)
![Deploying and Testing our Py-Simple Application](./img/102.png)

#### Cluster

![Deploying and Testing our Py-Simple Application](./img/103.png)
![Deploying and Testing our Py-Simple Application](./img/104.png)
![Deploying and Testing our Py-Simple Application](./img/105.png)
![Deploying and Testing our Py-Simple Application](./img/106.png)
#### CloudWatch

![Deploying and Testing our Py-Simple Application](./img/107.png)
![Deploying and Testing our Py-Simple Application](./img/108.png)
![Deploying and Testing our Py-Simple Application](./img/109.png)
![Deploying and Testing our Py-Simple Application](./img/110.png)
![Deploying and Testing our Py-Simple Application](./img/111.png)
![Deploying and Testing our Py-Simple Application](./img/112.png)
![Deploying and Testing our Py-Simple Application](./img/113.png)


La métrica (100 - (total_requests\requests_ok)) se utiliza para medir la disponibilidad de un servicio y es comúnmente conocida como "Error Rate" o tasa de errores. En el contexto de Site Reliability Engineering (SRE), esta métrica se considera un Service Level Indicator (SLI), que es una medida cuantitativa de un aspecto específico del rendimiento o confiabilidad de un servicio.

En términos simples:

- `total_requests`: Es el total de solicitudes realizadas al servicio durante un período de tiempo determinado.
- `requests_ok`: Es el número de solicitudes que se completaron correctamente (sin errores) durante ese mismo período de tiempo.

La métrica (100 - (total_requests\requests_ok)) calcula la proporción de solicitudes que resultaron en algún tipo de error. Un valor bajo de esta métrica indica una alta disponibilidad, ya que hay menos errores en relación con el total de solicitudes. Por otro lado, un valor alto indica una menor disponibilidad debido a una mayor cantidad de errores.

En un contexto de ingeniería de confiabilidad de sitios (SRE), las métricas como esta se utilizan para evaluar el rendimiento y la disponibilidad de los sistemas y para identificar áreas que requieren mejoras. Los SLIs son una parte fundamental de la práctica de SRE, ya que ayudan a establecer objetivos cuantitativos y medibles para la confiabilidad del servicio y permiten a los equipos monitorear y mejorar continuamente su infraestructura y aplicaciones para alcanzar esos objetivos.

![Deploying and Testing our Py-Simple Application](./img/114.png)

## Designing Py-Global

### The Architecture of Py-Global and Failure Mode Analysis

![The Architecture of Py-Global and Failure Mode Analysis](./img/115.png)
![The Architecture of Py-Global and Failure Mode Analysis](./img/116.png)

### Multi-Regional Support

![Multi-Regional Support](./img/117.png)

Repos:
 - https://github.com/mt2h/Site-Reliability-Engineering-on-AWS/tree/master/packt-sre-code/packt-sre/IAC/7-multiregion-ecs
 - https://github.com/mt2h/Site-Reliability-Engineering-on-AWS/tree/master/packt-sre-code/packt-sre/IAC/8-multiregion-rds

 ![Multi-Regional Support](./img/118.png)
 ![Multi-Regional Support](./img/119.png)

 ### Microservices Design

  ![Microservices Design](./img/120.png)

  Repo: https://github.com/mt2h/Site-Reliability-Engineering-on-AWS/tree/master/packt-sre-code/packt-sre/py-cars/cars

  ### Authentication and Authorization

![Microservices Design](./img/121.png)
![Microservices Design](./img/122.png)
![Microservices Design](./img/123.png)
![Microservices Design](./img/124.png)
![Microservices Design](./img/125.png)
![Microservices Design](./img/126.png)
![Microservices Design](./img/127.png)
![Microservices Design](./img/128.png)
![Microservices Design](./img/129.png)
![Microservices Design](./img/130.png)
![Microservices Design](./img/131.png)
![Microservices Design](./img/132.png)
![Microservices Design](./img/133.png)
![Microservices Design](./img/134.png)
![Microservices Design](./img/135.png)
![Microservices Design](./img/136.png)
![Microservices Design](./img/137.png)
![Microservices Design](./img/138.png)

### Application Telemetry and Tracing

![Application Telemetry and Tracing](./img/139.png)

Repo: https://github.com/mt2h/Site-Reliability-Engineering-on-AWS/tree/master/packt-sre-code/packt-sre/py-cars/cars

![Application Telemetry and Tracing](./img/140.png)
![Application Telemetry and Tracing](./img/141.png)
![Application Telemetry and Tracing](./img/142.png)
![Application Telemetry and Tracing](./img/143.png)
![Application Telemetry and Tracing](./img/144.png)

Repo: https://github.com/mt2h/Site-Reliability-Engineering-on-AWS/tree/master/packt-sre-code/packt-sre/rds-cdc

Amazon Kinesis es un servicio de transmisión de datos en tiempo real proporcionado por Amazon Web Services (AWS). Permite capturar, procesar y analizar grandes volúmenes de datos en tiempo real, lo que lo hace ideal para aplicaciones que requieren el procesamiento y análisis de datos en tiempo real, como el análisis de registros, la generación de informes en tiempo real, la detección de anomalías, la monitorización de aplicaciones, entre otros.

Kinesis ofrece diferentes servicios para satisfacer diferentes necesidades:

1. Amazon Kinesis Data Streams: Es el servicio principal de transmisión de datos en tiempo real. Permite capturar y almacenar grandes volúmenes de datos en tiempo real, divididos en fragmentos (shards), que pueden ser procesados por múltiples aplicaciones o consumidores.

2. Amazon Kinesis Data Firehose: Es un servicio que permite cargar datos en tiempo real en destinos de almacenamiento y análisis, como Amazon S3, Amazon Redshift o Amazon Elasticsearch Service, sin necesidad de escribir código adicional.

3. Amazon Kinesis Data Analytics: Es un servicio que permite procesar y analizar datos en tiempo real utilizando consultas SQL estándar. Permite realizar transformaciones, agregaciones y análisis en tiempo real sobre los datos que fluyen a través de Kinesis Data Streams.

4. Amazon Kinesis Video Streams: Es un servicio que permite capturar, procesar y almacenar flujos de video en tiempo real para aplicaciones de análisis de video y aprendizaje automático.

Es importante tener en cuenta que la replicación lógica en PostgreSQL no crea una réplica de solo lectura de la base de datos. En cambio, captura los cambios realizados en la base de datos y los envía a un destino externo para su procesamiento. En este caso, los cambios se envían al servicio de Kinesis para su posterior procesamiento.

![Application Telemetry and Tracing](./img/145.png)
![Application Telemetry and Tracing](./img/146.png)
![Application Telemetry and Tracing](./img/147.png)
![Application Telemetry and Tracing](./img/148.png)

### Autora and it Advantages over MySQL

![Autora and it Advantages over MySQL](./img/149.png)
![Autora and it Advantages over MySQL](./img/150.png)
![Autora and it Advantages over MySQL](./img/151.png)

## Deploying a Resilient, Fault Tolerant Py-Global Application

### Running/Scaling our Application on EKS

![Running/Scaling our Application on EKS](./img/152.png)
![Running/Scaling our Application on EKS](./img/153.png)

Repo: 
  - https://github.com/mt2h/Site-Reliability-Engineering-on-AWS/tree/master/packt-sre-code/packt-sre/IAC/10-eks
  - https://github.com/mt2h/Site-Reliability-Engineering-on-AWS/blob/master/packt-sre-code/packt-sre/py-cars/skaffold.yaml
  - https://github.com/mt2h/Site-Reliability-Engineering-on-AWS/tree/master/packt-sre-code/packt-sre/py-cars/k8/std

![Running/Scaling our Application on EKS](./img/154.png)  
![Running/Scaling our Application on EKS](./img/155.png)
![Running/Scaling our Application on EKS](./img/156.png)
![Running/Scaling our Application on EKS](./img/157.png)

```bash
skaffold dev
```

Skaffold es una herramienta de código abierto desarrollada por Google que facilita el proceso de desarrollo y despliegue de aplicaciones en contenedores dentro de un clúster de Kubernetes. Su objetivo principal es agilizar y simplificar el flujo de trabajo al permitir a los desarrolladores iterar rápidamente en sus aplicaciones mientras las desarrollan y despliegan en un entorno de Kubernetes.

El comando `skaffold dev` es uno de los comandos clave proporcionados por Skaffold. Cuando ejecutas `skaffold dev`, Skaffold se encarga de monitorear los archivos de tu proyecto y detectar cambios en el código fuente, las configuraciones de Docker y otros archivos relevantes. Una vez que detecta cambios, Skaffold automatiza la construcción de imágenes de contenedor, la actualización de los recursos de Kubernetes y el despliegue de tus aplicaciones actualizadas en el clúster de Kubernetes.

```bash
skaffold delete
```

### Creating a Resilient and Reliable Data Store for Python with Amazon Aurora

![Creating a Resilient and Reliable Data Store for Python with Amazon Aurora](./img/158.png)

Repo: https://github.com/mt2h/Site-Reliability-Engineering-on-AWS/tree/master/packt-sre-code/packt-sre/IAC/11-aurora

![Creating a Resilient and Reliable Data Store for Python with Amazon Aurora](./img/159.png)
![Creating a Resilient and Reliable Data Store for Python with Amazon Aurora](./img/160.png)

### Deploying App-Mesh

![Deploying App-Mesh](./img/161.png)

Un service mesh, en español "malla de servicios", es una infraestructura de red diseñada para gestionar la comunicación entre los distintos servicios que conforman una aplicación distribuida. Las aplicaciones modernas a menudo están compuestas por múltiples componentes o microservicios que interactúan entre sí para brindar funcionalidad completa. Sin embargo, a medida que el número de servicios crece, la gestión de la comunicación y la coordinación entre ellos puede volverse complicada.

Un service mesh proporciona una capa de abstracción sobre la red subyacente y ofrece una serie de características que facilitan la administración de la comunicación entre microservicios. Algunas de las funcionalidades comunes de un service mesh son:

1. **Descubrimiento de servicios:** Un service mesh permite a los microservicios descubrir y localizar dinámicamente a otros microservicios con los que necesitan comunicarse, sin requerir configuraciones estáticas.

2. **Balanceo de carga:** Distribuye el tráfico de manera equitativa entre las instancias de un mismo servicio para garantizar la disponibilidad y la escalabilidad.

3. **Seguridad:** Proporciona capacidades de autenticación y autorización para proteger las comunicaciones entre microservicios. Puede cifrar el tráfico entre ellos y autenticar las solicitudes.

4. **Monitorización y observabilidad:** Un service mesh puede recopilar métricas, trazas y registros de las interacciones entre microservicios, lo que facilita la depuración y el análisis del rendimiento.

5. **Control de tráfico:** Permite configurar reglas y políticas de enrutamiento para dirigir el tráfico de manera específica, como pruebas A/B, enrutamiento por canarios, etc.

6. **Gestión de fallos:** Ofrece mecanismos para detectar y gestionar fallos en las comunicaciones entre microservicios. Puede realizar reintentos automáticos, circuit breaking y otros mecanismos de recuperación.

Istio y Linkerd son ejemplos populares de implementaciones de service mesh. Estas herramientas se integran en la capa de comunicación entre los microservicios sin requerir cambios significativos en el código de la aplicación. En resumen, un service mesh es una solución que ayuda a las organizaciones a manejar las complejidades de las aplicaciones distribuidas al proporcionar control, seguridad y visibilidad en la comunicación entre microservicios.

![Deploying App-Mesh](./img/162.png)
![Deploying App-Mesh](./img/163.png)
![Deploying App-Mesh](./img/164.png)
![Deploying App-Mesh](./img/165.png)
![Deploying App-Mesh](./img/166.png)
![Deploying App-Mesh](./img/167.png)

Repo: https://github.com/mt2h/Site-Reliability-Engineering-on-AWS/tree/master/packt-sre-code/packt-sre/IAC/12-appmesh

![Deploying App-Mesh](./img/168.png)
![Deploying App-Mesh](./img/169.png)
![Deploying App-Mesh](./img/170.png)
![Deploying App-Mesh](./img/171.png)

## Surviving Failure of a Global Scale

#### Review: AWS Global Architecture and What We Have Just Built

![Review: AWS Global Architecture and What We Have Just Built](./img/172.png)
![Review: AWS Global Architecture and What We Have Just Built](./img/173.png)
![Review: AWS Global Architecture and What We Have Just Built](./img/174.png)
![Review: AWS Global Architecture and What We Have Just Built](./img/175.png)

### Global Tools: Route 53, CloudFront

![Global Tools: Route 53, CloudFront](./img/176.png)
![Global Tools: Route 53, CloudFront](./img/177.png)
![Global Tools: Route 53, CloudFront](./img/178.png)
![Global Tools: Route 53, CloudFront](./img/179.png)
![Global Tools: Route 53, CloudFront](./img/180.png)
![Global Tools: Route 53, CloudFront](./img/181.png)
![Global Tools: Route 53, CloudFront](./img/182.png)

### Going Global: What Does This Mean For Your Users/Developers

![Going Global: What Does This Mean For Your Users/Developers](./img/183.png)
![Going Global: What Does This Mean For Your Users/Developers](./img/184.png)

### Operational Changes Required For a Global Application

![Going Global: What Does This Mean For Your Users/Developers](./img/185.png)
![Going Global: What Does This Mean For Your Users/Developers](./img/186.png)
![Going Global: What Does This Mean For Your Users/Developers](./img/187.png)
![Going Global: What Does This Mean For Your Users/Developers](./img/188.png)

## Summary

![Summarys](./img/189.png)
![Summarys](./img/190.png)
![Summarys](./img/191.png)
![Summarys](./img/192.png)
![Summarys](./img/193.png)
![Summarys](./img/194.png)
![Summarys](./img/195.png)