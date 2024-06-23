_**ANOTACIONES**_

> [!IMPORTANT]
> La librería solamente está disponible para Sysmac Studio de Omron


> [!TIP]
>**MODO PARA IMPORTAR LA LIBRERÍA:**
>- **1**  Dentro de tu proyecto en Sysmac Studio, accede a la sección PROYECTO/BIBLIOTECA/MOSTRAR REFERENCIAS
>- **2**  Pulsar sobre el icono + y seleccionar la ubicación donde hayas descargado este archivo
>- **3**  Una vez que tengas Library MultiAxes ST dentro del proyecto, abrir la librería y dentro estarán inclidos 3 bloques de función.
>- **4**  Arrastra la sección FB que se encuentra dentro de la librería hasta el bloque principal main e introduce las variables correspondientes de la estructura de datos. Estas variables están presentes en la documentación.


> [!NOTE]
>**MODO DE FUNCIONAMIENTO:**
>- La librería funciona utilizando un contador que recorre una estructura de datos en la cual esta asignada la librería. La primera función Power es la encargada de recoger los datos principales.
>- El objetivo de la función es declarar en programa un solo bloque para controlar varios servo ejes.
>- En futuras versiones estarán disponibles los movimientos grupales de ejes.



