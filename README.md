DOCUMENTACIÓN DE LA APLICACIÓN 

VENTANA DE INICIO DE SESIÓN 

En esta ventana, su función principal es cargar las demás interfaces si es que aún no están inicializadas, una vez iniciada la sesión, nos lleva a nuestra ventana principal, por ultimo, se lanza el monitoreo de la red, y se establece como un atributo del frame principal para facilitar el acceso

<img width="1000" height="551" alt="image" src="https://github.com/user-attachments/assets/08ac64f3-cec9-41ae-8cbd-d32ab22edfb3" />

![WhatsApp Image 2025-07-06 at 9 13 57 PM](https://github.com/user-attachments/assets/313938a8-b372-48d6-9c47-5ac26b01646a)


VENTANA PRINCIPAL 

En esta, ya iniciamos mostrando nuestro menú, al cual se le agregaron iconos para una mejor interpretación, esto trabajandose con botones para poder navegar a las siguientes interfaces, asimismo se hace la declaración del panel de notificaciones que estará de manera centrada

<img width="1107" height="1000" alt="image" src="https://github.com/user-attachments/assets/7201c6e5-0e40-490f-bee6-38c5dc2bf4f7" />
<img width="1397" height="924" alt="image" src="https://github.com/user-attachments/assets/c0024c52-f9e2-48ba-bac2-a677ab585e34" />
<img width="1215" height="240" alt="image" src="https://github.com/user-attachments/assets/b70f73ce-c307-4e79-ae10-1f1b5397b14e" />

<img width="1919" height="1133" alt="image" src="https://github.com/user-attachments/assets/fdc4c741-1305-4d82-b7fd-5d2171976cc0" />

VENTANA DE USUARIO 

Nuevamente en esta interfaz se vuelve a poner a poner lo del menú, pues la idea es que este quede "fijo", se inicia creando el frame de usuario, se configura la cuadrícula, el tamaño, se vuelve a declarar el mismo menú que está en la interfaz interior, finalmente se declara el contenido principal, que es el perfil del usuario

<img width="1118" height="950" alt="image" src="https://github.com/user-attachments/assets/2119eafe-e437-4e25-8aac-459dc9740381" />

<img width="1398" height="901" alt="image" src="https://github.com/user-attachments/assets/a699a412-b7fe-4483-b4ec-f9400caf7921" />

<img width="1390" height="173" alt="image" src="https://github.com/user-attachments/assets/450cbe82-fe9e-4c5b-a9e4-e73611547866" />

<img width="1919" height="1136" alt="image" src="https://github.com/user-attachments/assets/1db0892f-0559-49ec-89da-f2cfdc80274c" />

VENTANA HISTORIAL

Esta parte del sistema construye una pantalla dedicada al historial de anomalías o eventos registrados en una base de datos MySQL. La interfaz está diseñada usando customtkinter y tiene dos secciones principales:
🔹 Barra lateral: Incluye un menú de navegación con botones e íconos personalizados para moverse entre distintas vistas del sistema (como usuario, historial, soporte, etc.). También muestra el nombre de usuario y su imagen, si están disponibles.
🔹 Área de contenido: Aquí se muestra un título, un cuadro de búsqueda (de momento decorativo), y una sección scrollable donde se listan las últimas 20 anomalías registradas. Cada evento se presenta con su fecha, mensaje, origen y destino. Si no hay eventos, muestra un mensaje indicando que no hay registros.
Además, hay un botón para eliminar el historial, aunque aún no tiene funcionalidad implementada. Todo esto se conecta a una base de datos MySQL para consultar los datos en tiempo real, y se maneja con cuidado cualquier posible error de conexión o carga.

<img width="1828" height="971" alt="image" src="https://github.com/user-attachments/assets/469ebc70-804d-4980-bf0c-81fb1678b722" />
<img width="1833" height="952" alt="image" src="https://github.com/user-attachments/assets/5fc22b51-839a-44f0-8d0f-82c8fb168831" />
<img width="1821" height="934" alt="image" src="https://github.com/user-attachments/assets/cac830b7-9377-4461-b5e1-153b6ba775f3" />
<img width="1828" height="927" alt="image" src="https://github.com/user-attachments/assets/e2b8c064-3038-490a-b127-8f7c0af97519" />
<img width="1826" height="75" alt="image" src="https://github.com/user-attachments/assets/6410eae8-8243-43c6-a8fd-885f92a7a256" />
<img width="1600" height="845" alt="image" src="https://github.com/user-attachments/assets/b6b1de1b-5c3e-4672-b3af-7bd2f3e9f146" />

VENTANA SOPORTE

Crea la pantalla de soporte técnico en tu app. Incluye un menú lateral para navegar entre secciones (como principal, historial y configuración) y un área principal que muestra la información de contacto del soporte, como correos y teléfonos, todo con estilo visual usando customtkinter. 

<img width="1820" height="979" alt="image" src="https://github.com/user-attachments/assets/78ff0ac1-0d5c-4c8a-9112-fdaa9e3a1ed8" />
<img width="1830" height="947" alt="image" src="https://github.com/user-attachments/assets/3287979e-503c-446d-af24-76395859c3c0" />
<img width="1826" height="75" alt="Captura de pantalla 2025-07-12 024627" src="https://github.com/user-attachments/assets/e3f6516f-1a08-45b7-858a-91ab70b46d81" />
<img width="1600" height="846" alt="image" src="https://github.com/user-attachments/assets/4323e739-f4a8-421b-84ea-4175a4552bc2" />

VENTANA CONFIGURACIÓN

Muestra opciones del sistema, incluyendo un menú lateral con íconos para navegar entre secciones y un área principal donde se puede cambiar el idioma entre Español e Inglés mediante un combo desplegable.

<img width="1827" height="976" alt="image" src="https://github.com/user-attachments/assets/9835daec-e89f-4a6c-8be6-a983bb6d460e" />
<img width="1803" height="894" alt="image" src="https://github.com/user-attachments/assets/623d94cb-5cdd-49a2-99b6-fcc5bed9f228" />
<img width="1831" height="900" alt="image" src="https://github.com/user-attachments/assets/d82a5232-278b-4694-99fd-56a6410a6d75" />
<img width="1823" height="974" alt="image" src="https://github.com/user-attachments/assets/c0a6c609-f839-4d1a-9624-22d612d7f37c" />
<img width="1825" height="448" alt="image" src="https://github.com/user-attachments/assets/b849290c-d691-4169-bf36-4c7013c96d97" />
<img width="1600" height="842" alt="image" src="https://github.com/user-attachments/assets/6c3b03b9-542a-4505-bee6-58f5a7a18706" />

TODAS LAS VENTANAS TRADUCIDAS

<img width="1600" height="846" alt="image" src="https://github.com/user-attachments/assets/13c5b794-d467-49e9-87a8-ff04c92150fa" />
<img width="1600" height="848" alt="image" src="https://github.com/user-attachments/assets/1a874240-44fc-443e-9ec8-a926df585ae5" />
<img width="1600" height="847" alt="image" src="https://github.com/user-attachments/assets/16cf4022-c18e-43d7-ac50-cae544203317" />
<img width="1600" height="846" alt="image" src="https://github.com/user-attachments/assets/2abe7612-c0d2-4b45-ba37-549d79454f8f" />
<img width="1600" height="848" alt="image" src="https://github.com/user-attachments/assets/bb3b02f2-221f-4084-acee-920aa6a0c520" />


BASE DE DATOS 

Modelo Entidad-Relación

<img width="1931" height="1040" alt="entidad_relacion drawio" src="https://github.com/user-attachments/assets/3ea370b3-3c6c-4a44-9409-693d43050dfe" />

Modelo Relacional 


<img width="1071" height="781" alt="RelacionalProyecto drawio" src="https://github.com/user-attachments/assets/3d3a55a5-5002-4307-ae74-84e5e03d4a72" />







