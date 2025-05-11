# Infraestructura EC2 con NGINX y Load Balancer en AWS

Este repositorio contiene una plantilla en formato YAML que crea una infraestructura en AWS con:

- VPC y subnets públicas
- Dos instancias EC2 en alta disponibilidad (Auto Scaling Group)
- Load Balancer
- NGINX instalado automáticamente usando `UserData`
- Seguridad configurada para HTTP y SSH

## ¿Cómo usarlo?

1. Abre el servicio AWS CloudFormation.
2. Carga el archivo `cloudformation_alta_disponibilidad.yaml`.
3. Proporciona un par de claves (KeyName) para acceso SSH.
4. Espera a que la pila llegue a `CREATE_COMPLETE`.
5. Accede al sitio web desde la URL del Load Balancer.

## Autor

Jonathan Ricardo Hernández Leiva  
Maestría en Tecnologías de la Información y Comunicación - USAC  
📧 jonathanrhleiva@gmail.com
