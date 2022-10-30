# Caso Práctico de Laboratorio #2 [![.NET](https://github.com/raedmiranda/DirectoryBrowseLab/actions/workflows/dotnet.yml/badge.svg)](https://github.com/raedmiranda/DirectoryBrowseLab/actions/workflows/dotnet.yml)

### Pasos iniciales
1. Clone el repositorio.
2. Ejecute el proyecto.

## Workaround: No se puede encontrar la ruta .../bin/roslyn/csc.exe 
Si te aparece este mensaje de error al ejecutar:
![csc.exe path not found](https://i.imgur.com/PsFneC1.png) 
Realiza lo siguiente:

1. Abrir la Consola del Administrador de paquetes desde Ver > Otras Ventanas  ![PackageManagerConsole](https://i.imgur.com/RAfFOFK.png)
2. Ejecutar el siguiente comando:
``
Install-Package Microsoft.CodeDom.Providers.DotNetCompilerPlatform
``
o este comando (es indistinto):
``
Update-Package Microsoft.CodeDom.Providers.DotNetCompilerPlatform -r
``


### Notas adicionales

- La aplicación MVC inicialmente mostrará la vista Home/Index *por defecto*.
- Deberá ingresar a las rutas **indicadas en el examen** (/Contents/Site.css, /Controllers, /Scripts o /fonts) y capturar la pantalla.
- Deberá corregir el código y hacer una posterior captura de pantalla de la solución y su ejecución.
- Es requerido que tenga instalado [NET Framework 4.5](https://www.microsoft.com/es-es/download/details.aspx?id=30653).
- Al cargar el proyecto, si aparece el mensaje: "La solución no se puede cargar...", aparecen también 2 opciones:
    1. Migrar a .NET Framework 4.6 (recomendado)
    2. Descargar [.NET Framework 4.8] (https://dotnet.microsoft.com/en-us/download/dotnet-framework/net48).
- Puede usar [Visual Studio Community](https://visualstudio.microsoft.com/es/vs/community/) 2012 o superior.
