# 📁 TP N°5: Modelo Adaptativo de Base de Datos Relacional

**Cátedra:** Base de Datos  
**Carrera:** Analista de Sistemas  
**Institución:** ISFT N°151  

---

## 🎯 Objetivo del Proyecto
Este repositorio contiene la resolución del Trabajo Práctico N°5. El enfoque principal es el análisis, diseño y puesta en prueba de un **modelo de base de datos adaptativo** (variante del patrón Entity-Attribute-Value). Este esquema permite asignar características dinámicas a entidades (opciones múltiples y únicas) asegurando la escalabilidad del sistema sin necesidad de alterar la estructura física (DDL) de la base de datos.

---

## 🚀 Entorno de Desarrollo (Codespaces)

El proyecto está configurado para ejecutarse de forma aislada y estandarizada en **GitHub Codespaces** utilizando contenedores de desarrollo (`.devcontainer`). 
El entorno ya incluye **MariaDB** configurado mediante Docker. La base de datos principal (`relacional_db`) se inicializa automáticamente a través de las directivas del archivo `devcontainer.json`.

### Acceso al motor de Base de Datos
Para acceder a la consola de MariaDB directamente desde la terminal del Codespace, ejecutá el siguiente comando:
```bash
sudo mariadb