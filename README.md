# -ISO-Soft360

En esta guía vas a aprender a crear un pendrive booteable de Windows 10 o Windows 11 con Rufus, usando una imagen ISO oficial de Microsoft. Es una opción muy útil cuando ya tenés la ISO descargada, cuando el asistente de Microsoft falla o cuando necesitás elegir manualmente entre GPT/UEFI y MBR/BIOS.

Vamos a hacerlo por el camino seguro: Rufus desde su web oficial y Windows desde Microsoft. Nada de ISOs misteriosas, activadores, cracks, KMS raros ni archivos que vienen con “regalitos” adentro. Acá el pendrive se arma bien, sin magia negra tecnológica.

Esta guía aplica para Windows 10 y Windows 11. En Windows 10 puede existir compatibilidad con 32 o 64 bits según la ISO elegida; en Windows 11, lo normal es trabajar con equipos compatibles de 64 bits/x64.

Importante: Rufus va a borrar el contenido del pendrive. Si tenés archivos importantes, copialos antes. El botón “Empezar” de Rufus no pregunta por tus recuerdos de vacaciones: borra y sigue.
Contenido
Antes de empezar
Qué es Rufus y cuándo conviene usarlo
¿Puedo usar Rufus en Windows 7, 8 u 8.1?
Descargar Rufus e ISO oficial de Windows
Cómo crear el pendrive booteable con Rufus
GPT, MBR, UEFI y BIOS: qué elegir
Opciones especiales de Rufus para Windows 11
Cómo iniciar la PC desde el pendrive
Instalación de Windows paso a paso
Activación de Windows después de instalar
Errores comunes y soluciones
Tabla resumen
Preguntas frecuentes
Antes de empezar
Antes de abrir Rufus y empezar a tocar opciones, prepará lo básico. Esto evita errores, pérdidas de datos y esa clásica frase de “yo juraba que ese pendrive estaba vacío”.

✅ Un pendrive de mínimo 8 GB. Recomendado: 16 GB o más.
✅ Una ISO oficial de Windows 10 o Windows 11 descargada desde Microsoft.
✅ Rufus descargado desde su web oficial.
✅ Copia de seguridad del contenido del pendrive.
✅ Permisos de administrador en Windows.
✅ Conexión a internet para descargar la ISO y revisar actualizaciones.
✅ Saber si la PC es moderna con UEFI o antigua con BIOS/Legacy.
✅ Desconectar otros pendrives o discos externos para no elegir el dispositivo equivocado.
Qué es Rufus y cuándo conviene usarlo
Rufus es una herramienta que permite formatear y crear unidades USB arrancables, como pendrives de instalación de Windows. Es liviana, práctica y muy usada cuando se necesita crear un USB booteable desde una imagen ISO.

Conviene usar Rufus cuando: ya tenés una ISO oficial descargada, la herramienta de Microsoft falla, necesitás controlar GPT/MBR, querés preparar un USB para una PC específica o estás trabajando con un equipo más antiguo.

Rufus no activa Windows ni reemplaza una licencia. Solo prepara el pendrive de instalación. Para activar Windows después, necesitás una licencia válida o una licencia digital asociada al equipo o cuenta Microsoft.

¿Puedo usar Rufus en Windows 7, Windows 8 o Windows 8.1?
Si estás en Windows 7, Windows 8 o Windows 8.1, lo más recomendable sigue siendo crear el pendrive desde una PC con Windows 10 u 11. Es más simple, más compatible y evita errores por sistemas antiguos.

Rufus puede servir en equipos viejos, pero hay una aclaración importante: para Windows 7, la última versión compatible fue Rufus 3.22, disponible en el archivo oficial de descargas de Rufus. Si usás una versión actual en un sistema antiguo, puede que directamente no abra.

Compatible Windows 7
Descargar Rufus 3.22
Versión portable
Rufus 3.22 Portable
Nota: estos enlaces apuntan al archivo oficial de descargas de Rufus. Usalos solo si realmente necesitás trabajar desde Windows 7. Para Windows 10 u 11, conviene usar la versión actual desde la página principal de Rufus.

Recomendación: si tu PC principal tiene Windows 7 u 8.1 y Rufus falla, armá el pendrive desde otra computadora más nueva. Menos drama, más instalación.
Descargar Rufus e ISO oficial de Windows
Para esta guía necesitás dos cosas: Rufus y una ISO oficial de Windows. Descargá todo desde fuentes oficiales para evitar archivos modificados o inseguros.

Web oficial
Descargar Rufus actual
Para Windows 7
Rufus 3.22
Microsoft oficial
ISO Windows 10
Microsoft oficial
ISO Windows 11
Qué descargar exactamente
Rufus actual: descargalo desde rufus.ie/es. Podés usar la versión normal o portable.
Rufus para Windows 7: usá Rufus 3.22 desde el archivo oficial de descargas de Rufus. No descargues versiones antiguas desde páginas de terceros.
Windows 10: descargá la ISO o usá las opciones oficiales de Microsoft para obtener el archivo.
Windows 11: descargá la ISO oficial desde la sección de imagen de disco para dispositivos compatibles.
Descarga oficial de Rufus desde la web oficial
Página oficial de Rufus con la zona de descarga visible.
Descarga ISO oficial de Windows desde Microsoft
Página oficial de Microsoft mostrando la descarga ISO de Windows 10 o Windows 11.
Cómo crear el pendrive booteable con Rufus
Con Rufus abierto, el proceso es directo. Lo importante es elegir bien el pendrive, seleccionar la ISO correcta y configurar el esquema de partición según el tipo de PC.

Conectá el pendrive a la PC.
Abrí Rufus. Si Windows pide permisos de administrador, aceptá.
En Dispositivo, elegí el pendrive correcto.
En Selección de arranque, elegí Disco o imagen ISO.
Hacé clic en Seleccionar y buscá la ISO oficial de Windows que descargaste.
En Opciones de imagen, dejá la opción recomendada por Rufus, normalmente instalación estándar de Windows.
Elegí el esquema de partición: GPT para equipos modernos con UEFI, MBR para equipos antiguos con BIOS/Legacy.
Revisá el sistema de destino: UEFI o BIOS/UEFI-CSM según corresponda.
Dejá el sistema de archivos recomendado por Rufus, salvo que tengas una necesidad técnica específica.
Hacé clic en Empezar.
Confirmá la advertencia de que el pendrive se va a borrar.
Esperá a que Rufus termine. Cuando diga Preparado o Listo, cerrá Rufus y expulsá el USB de forma segura.
Ventana principal de Rufus con ISO seleccionada
Ventana principal de Rufus con el pendrive y la ISO de Windows seleccionados.
Configuración GPT y UEFI en Rufus
Rufus mostrando configuración GPT y UEFI para una PC moderna.
Advertencia de borrado del pendrive en Rufus
Advertencia de Rufus indicando que se borrarán los datos del pendrive.
Rufus finalizado y listo
Rufus finalizado con estado “Preparado” o “Listo”.
Tip rápido: antes de tocar “Empezar”, mirá dos veces el campo Dispositivo. Si elegís el USB equivocado, Rufus va a ser muy eficiente… borrando lo que no era.
GPT, MBR, UEFI y BIOS: qué elegir
Esta parte suena técnica, pero se resume así: las PCs modernas suelen usar UEFI + GPT; las PCs más antiguas suelen usar BIOS/Legacy + MBR.

Tipo de equipo	Esquema de partición	Sistema de destino	Recomendación
PC moderna	GPT	UEFI	Opción recomendada para la mayoría de equipos actuales.
PC antigua	MBR	BIOS o UEFI-CSM	Útil para equipos viejos que no arrancan en UEFI.
Windows 11	GPT	UEFI	Recomendado para respetar requisitos actuales.
Windows 10	GPT o MBR	UEFI o BIOS	Depende del equipo donde se va a instalar.
Cómo saber si elegir GPT o MBR
Si la PC es relativamente nueva, probá primero con GPT + UEFI.
Si la PC es muy antigua y no detecta el USB, probá MBR + BIOS/UEFI-CSM.
Si vas a instalar Windows 11, lo recomendado es usar un equipo compatible con UEFI.
Opciones especiales de Rufus para Windows 11
Cuando usás una ISO de Windows 11, Rufus puede mostrar una ventana con opciones adicionales para personalizar la instalación. Algunas opciones pueden estar relacionadas con requisitos del sistema, cuenta online o configuración regional.

Importante: esta guía recomienda instalar Windows 11 en equipos compatibles y respetando los requisitos oficiales de Microsoft. No promovemos parches, activadores ni métodos no oficiales para forzar instalaciones o activar Windows.

Si tu equipo no cumple los requisitos de Windows 11, lo más seguro es instalar Windows 10 o usar un equipo compatible. A veces lo más moderno no es lo más conveniente para una PC viejita que ya pide jubilación.

Cómo iniciar la PC desde el pendrive
Una vez creado el USB con Rufus, hay que arrancar la computadora desde ese pendrive para iniciar el instalador de Windows.

Conectá el pendrive en la PC donde vas a instalar Windows.
Apagá o reiniciá la computadora.
Apenas prende, presioná varias veces la tecla del menú de arranque.
Seleccioná el pendrive USB en la lista.
Confirmá con Enter y esperá a que cargue el instalador.
Teclas comunes del menú de arranque
F12: común en Dell, Lenovo, Acer y varias marcas.
F11: común en MSI y algunas placas madre.
F9: común en HP.
Esc: común en HP, Asus y otros equipos.
F2 o Supr/Delete: suele abrir BIOS/UEFI para cambiar el orden de arranque.
Si el pendrive no aparece, probá otro puerto USB, revisá si elegiste GPT/MBR correctamente o entrá al BIOS/UEFI para habilitar el arranque desde USB.

Instalación de Windows paso a paso
Cuando la PC arranque desde el USB creado con Rufus, vas a ver el instalador de Windows. Desde ahí, el proceso es el mismo que con cualquier medio oficial de instalación.

Elegí el idioma, el formato de hora y moneda, y el teclado.
Hacé clic en Siguiente.
Hacé clic en Instalar ahora.
Si pide clave y no la tenés a mano, podés elegir No tengo clave de producto, siempre que luego actives Windows con una licencia válida.
Elegí la edición correcta: Home, Pro u otra que corresponda a tu licencia.
Aceptá los términos de licencia.
Elegí Personalizada: instalar solo Windows para una instalación limpia.
Seleccioná el disco o partición donde vas a instalar Windows.
Si vas a borrar o formatear particiones, hacé backup antes. Esto elimina datos.
Hacé clic en Siguiente y esperá la copia de archivos.
Cuando la PC reinicie, quitá el pendrive o elegí arrancar desde el disco interno para no volver al instalador.
Completá la configuración inicial de Windows.
Después de instalar Windows
✅ Conectate a internet.
✅ Ejecutá Windows Update.
✅ Instalá drivers pendientes si hace falta.
✅ Revisá WiFi, audio, Bluetooth, cámara y gráficos.
✅ Activá Windows con una licencia válida si todavía no quedó activado.
Activación de Windows después de instalar
Rufus no activa Windows. Solo crea el pendrive. La activación debe hacerse siempre con métodos oficiales: clave válida, cuenta Microsoft, activación telefónica o licencia digital.

Activar con clave de 25 caracteres
Abrí Configuración.
Entrá en Sistema > Activación.
Seleccioná Cambiar clave de producto.
Ingresá la clave oficial de 25 caracteres.
Confirmá y esperá la validación.
Activar iniciando sesión
Si tu licencia está vinculada a una cuenta Microsoft, iniciá sesión con esa cuenta durante o después de la instalación. Luego revisá el estado en Configuración > Sistema > Activación.

Activación por teléfono
En algunos casos, Windows puede ofrecer activación telefónica. Usá únicamente las instrucciones oficiales que aparecen en pantalla.

Licencia digital o digital entitlement
Si el equipo ya tenía una licencia digital válida para la misma edición de Windows, normalmente se activa automáticamente al conectarse a internet.

Cómo verificar que Windows quedó activado
Abrí Configuración.
Entrá en Sistema.
Seleccioná Activación.
Revisá que indique que Windows está activado.
Errores comunes y soluciones
1. Rufus no detecta el pendrive
Causa: el USB puede estar mal conectado, dañado o protegido contra escritura.

Solución oficial/simple: probá otro puerto USB, evitá hubs/adaptadores y usá otro pendrive si el problema sigue.

2. La ISO no aparece o Rufus no la acepta
Causa: el archivo ISO puede estar incompleto, corrupto o no ser una imagen arrancable válida.

Solución oficial/simple: descargá nuevamente la ISO desde Microsoft y seleccioná el archivo correcto.

3. El USB no arranca
Causa: configuración incorrecta de GPT/MBR, orden de arranque mal configurado o puerto USB incompatible.

Solución oficial/simple: revisá el Boot Menu, probá otro puerto y recreá el USB con GPT/UEFI o MBR/BIOS según el equipo.

4. Elegí GPT y mi PC antigua no arranca
Causa: muchas PCs antiguas no arrancan correctamente con GPT/UEFI.

Solución oficial/simple: recreá el pendrive en Rufus usando MBR y destino BIOS o UEFI-CSM.

5. Elegí MBR y mi PC moderna no arranca
Causa: algunos equipos modernos están configurados para arrancar solo en UEFI.

Solución oficial/simple: recreá el pendrive usando GPT y destino UEFI.

6. Windows 11 dice que el equipo no cumple los requisitos
Causa: la PC puede no cumplir requisitos como TPM 2.0, Secure Boot, CPU compatible o arquitectura x64.

Solución oficial/simple: verificá compatibilidad del equipo. Si no cumple, instalá Windows 10 o usá un equipo compatible.

7. Error al copiar archivos en Rufus
Causa: puede haber un problema con el pendrive, la ISO o permisos de escritura.

Solución oficial/simple: ejecutá Rufus como administrador, usá otro USB y descargá nuevamente la ISO si hace falta.

8. El pendrive queda raro o no se puede formatear después
Causa: el USB puede quedar con particiones creadas para arranque.

Solución oficial/simple: formatealo desde Administración de discos de Windows o desde Rufus seleccionando formato normal.

9. La PC se reinicia y vuelve al instalador
Causa: después del primer reinicio, la PC vuelve a iniciar desde el pendrive.

Solución oficial/simple: quitá el USB cuando empiece el reinicio o elegí el disco interno desde el Boot Menu.

10. No hay internet durante la instalación
Causa: puede faltar el driver de red o WiFi.

Solución oficial/simple: conectá cable Ethernet si podés. Después de instalar, ejecutá Windows Update para descargar drivers.

11. Error 0x8007007B al activar Windows
Causa: suele estar relacionado con edición incorrecta, clave no válida para esa edición o configuración de activación.

Solución oficial/simple: verificá que instalaste la edición correcta e ingresá una clave oficial válida desde Configuración > Sistema > Activación.

Tabla resumen
Paso	Qué hacer	Tiempo estimado	Tip rápido
1. Descargar Rufus	Entrar a rufus.ie/es y descargar la herramienta.	1 a 3 minutos	Usá la web oficial, no mirrors raros.
2. Descargar ISO	Bajar Windows 10 o 11 desde Microsoft.	10 a 60 minutos	Depende de tu internet.
3. Configurar Rufus	Elegir USB, ISO, GPT/MBR y sistema de destino.	3 a 7 minutos	PC moderna: GPT + UEFI.
4. Crear USB	Presionar Empezar y esperar a que Rufus termine.	10 a 40 minutos	El pendrive se borra completo.
5. Arrancar desde USB	Usar Boot Menu y seleccionar el pendrive.	1 a 5 minutos	Probá F12, F11, F9, Esc, F2 o Supr.
6. Instalar Windows	Seguir el instalador y elegir disco/partición.	20 a 60 minutos	Hacé backup antes de formatear.
Preguntas frecuentes
¿Rufus es oficial de Microsoft?
No. Rufus no es de Microsoft, pero es una herramienta legítima para crear USB booteables. La ISO de Windows sí debe descargarse desde Microsoft.

¿Es seguro usar Rufus?
Sí, siempre que lo descargues desde su web oficial y uses ISOs oficiales. Evitá versiones modificadas o páginas de terceros.

¿Necesito una ISO oficial?
Sí. Para instalar Windows de forma segura, descargá la ISO desde Microsoft.

¿Qué elijo: GPT o MBR?
Para PCs modernas, elegí GPT. Para PCs antiguas con BIOS/Legacy, puede hacer falta MBR.

¿Qué elijo: UEFI o BIOS?
Si la PC es moderna, UEFI. Si es antigua, BIOS o UEFI-CSM.

¿Windows 11 sirve en 32 bits?
No. Windows 11 está orientado a equipos compatibles de 64 bits/x64.

¿Se borra el pendrive?
Sí. Rufus borra el contenido del USB durante el proceso.

¿Rufus activa Windows?
No. Rufus solo crea el USB. La activación se hace después con una licencia válida o licencia digital.

¿Puedo usar Rufus en Windows 7?
Sí, pero solo con versiones antiguas compatibles. La última versión compatible con Windows 7 es Rufus 3.22. 
Para Windows 10 u 11, usá la versión actual de Rufus desde la web oficial.

¿Conviene Rufus o la herramienta de Microsoft?
La herramienta de Microsoft es más simple para usuarios básicos.
Rufus conviene si necesitás usar una ISO, elegir GPT/MBR o resolver errores del asistente oficial.

Productos recomendados
Windows 11 Pro Retail
Windows 11 Pro Retail
Ideal para instalar Windows 11 en equipos compatibles.

Ver producto
Windows 10 Pro Retail
Windows 10 Pro Retail
Una opción estable para equipos compatibles con Windows 10.

Ver producto
Windows 11 Home Retail
Windows 11 Home Retail
Licencia Home Retail para instalar en una PC personal.

Ver producto
Windows 10 Home Retail
Windows 10 Home Retail
Licencia Retail Home para instalar Windows 10 en tu equipo.

Ver producto
Cierre
Listo: con estos pasos podés crear un pendrive booteable con Rufus para instalar Windows 10 o Windows 11 usando una ISO oficial. La clave está en descargar desde sitios confiables, elegir bien GPT/MBR y revisar dos veces el pendrive antes de formatear.

Rufus es una herramienta muy práctica, pero no hace milagros: si la ISO está mal, el USB está fallando o elegiste el modo incorrecto, puede tocar repetir el proceso. Tranquilo, repetir con calma 
