# Requisitos previos

Antes de realizar la conexión al datalake, es importante asegurarse de cumplir con los siguientes requisitos:

## Versión de Python

Es necesario contar con la versión adecuada de Python instalada en el entorno de trabajo. Se recomienda utilizar Python 3.x. Para verificar la versión de Python instalada, se puede ejecutar el siguiente comando en la terminal:

```bash
python --version
```

En caso de no tener instalada la versión correcta, se puede descargar e instalar Python desde el sitio oficial: [python.org](https://www.python.org/).

## Bibliotecas adicionales

Es necesario instalar las bibliotecas o paquetes adicionales necesarios para la conexión al datalake. En particular, se requiere la instalación de la biblioteca `azure-storage-blob` para interactuar con Azure Storage. Se puede instalar utilizando el siguiente comando:

```bash
pip install azure-storage-blob
```

## Credenciales de acceso

Para realizar la conexión al datalake, se necesitará contar con las credenciales de acceso correspondientes. Esto incluye el nombre de la cuenta de almacenamiento y la clave de acceso asociada. Antes de proceder, asegúrese de tener a mano estas credenciales.

## Configuración de permisos

Recuerde que si tiene dificultades de acceso debe contactarse con los encargados de infraestructura de IDT para que le otorguen los permisos necesarios.
