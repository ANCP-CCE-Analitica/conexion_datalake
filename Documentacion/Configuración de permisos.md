# Configuración de permisos para el uso de SAS

En este documento, se presenta información sobre cómo configurar correctamente los permisos al utilizar SAS (Shared Access Signature) para acceder a los recursos de almacenamiento en Azure. La SAS proporciona una forma segura de otorgar acceso limitado y temporal a los datos almacenados en un datalake.

## Generación de la SAS

Para generar una SAS, se deben seguir los siguientes pasos:

1. Acceda al portal de Azure y navegue hasta el servicio de almacenamiento correspondiente.

2. Seleccione la cuenta de almacenamiento y el contenedor específico al que se desea otorgar acceso mediante la SAS.

3. Configure los permisos necesarios para la SAS, como lectura, escritura, lista, etc. Es importante asignar solo los permisos necesarios para limitar el acceso.

4. Establezca la duración de la SAS, especificando el período durante el cual la SAS estará activa. Es importante establecer una duración adecuada para evitar accesos no autorizados después de que la SAS haya expirado.

5. Genere la SAS y obtenga la cadena de caracteres que la representa.

## Asignación de permisos en la SAS

En una SAS, se pueden asignar los siguientes permisos:

- **Lectura**: Permite leer los recursos especificados en la SAS.
- **Escritura**: Permite escribir en los recursos especificados en la SAS.
- **Lista**: Permite enumerar los recursos dentro de un contenedor o directorio.
- **Eliminación**: Permite eliminar los recursos especificados en la SAS.
- **Adición**: Permite agregar nuevos recursos al contenedor especificado en la SAS.

Asigne los permisos adecuados según los requisitos de acceso a los recursos de almacenamiento.

## Vigencia y renovación de la SAS

Es importante establecer una duración adecuada para la SAS, asegurándose de que sea lo suficientemente larga para cumplir con los requisitos, pero no demasiado larga para evitar accesos no autorizados después de su expiración. Si es necesario extender la vigencia de una SAS, se puede generar una nueva SAS con una duración actualizada.

## Consideraciones de seguridad

Aquí se presentan algunas consideraciones importantes para garantizar la seguridad al utilizar SAS:

- **Mantenga las SAS confidenciales**: No comparta las cadenas de SAS en texto plano y asegúrese de restringir el acceso a las personas autorizadas.
- **Revoque las SAS innecesarias**: Si ya no se necesita una SAS, se debe revocar para evitar accesos no autorizados.
- **Monitoree el uso de las SAS**: Realice un seguimiento del uso de las SAS y revise los registros de auditoría para detectar cualquier actividad sospechosa o no autorizada.

Es importante seguir buenas prácticas de seguridad para proteger los recursos de almacenamiento y garantizar el acceso seguro a través de SAS.