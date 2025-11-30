# Proyecto: Entorno Azure

Este proyecto representa la creación de un entorno cloud en Azure

El objetivo es demostrar dominio de conceptos fundamentales:

- Networking
- Seguridad (NSG)
- Storage
- Compute (VM)
- Observabilidad (alertas y métricas)
- Identidad (RBAC)

---

# 1. Arquitectura del Proyecto

El entorno creado incluye:

VNet-Sebas
┗ Subnet: Sebas-Subnet-01
┗ VM: Sebas-VM-Test
┣ NSG: Bloqueo general + puerto habilitado
┗ Métricas + alerta configurada

Storage Account: sebasstoragebasic
┗ Contenedor: /testing
┗ Archivo de prueba + SAS Token generado

