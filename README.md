# learn-prestashop
Repositorio para aprender a hacer tiendas online con Prestashop

Instalación: https://help-center.prestashop.com/en/articles/10672892369170-install-prestashop-locally-on-your-computer

![prestashop](https://github.com/cesarlpb/learn-prestashop/assets/25636436/a7287726-db75-4a39-8b8a-4ad27eef3a34)

---

PrestaShop es una plataforma de comercio electrónico de código abierto que permite a los comerciantes crear tiendas en línea de manera eficiente. Aquí hay una descripción general de PrestaShop:

1. **Código Abierto:** PrestaShop es un software de comercio electrónico de código abierto, lo que significa que su código fuente es accesible y modificable. Esto permite a los desarrolladores personalizar y adaptar la plataforma según las necesidades específicas de sus negocios.

2. **Tiendas en Línea Profesionales:** PrestaShop facilita la creación y gestión de tiendas en línea profesionales. Proporciona una interfaz intuitiva para administrar productos, clientes, pedidos y otras funciones esenciales de comercio electrónico.

3. **Amplia Gama de Funcionalidades:** La plataforma ofrece una amplia gama de funcionalidades, incluyendo la gestión de catálogos de productos, procesamiento de pagos, administración de inventarios, cupones y descuentos, y herramientas de marketing, entre otras.

4. **Personalización y Temas:** PrestaShop permite la personalización de la apariencia de la tienda mediante el uso de temas. Hay una variedad de temas disponibles, y los usuarios también pueden crear o modificar temas para adaptarse a la identidad de su marca.

5. **Módulos y Extensiones:** La comunidad de PrestaShop ha desarrollado numerosos módulos y extensiones que amplían las capacidades de la plataforma. Estos módulos pueden incluir integraciones con servicios de pago, métodos de envío, herramientas de SEO, entre otros.

6. **Gestión de Múltiples Tiendas:** PrestaShop permite a los comerciantes gestionar varias tiendas desde un solo panel de administración. Esto es útil para aquellos que operan en diferentes regiones o tienen múltiples líneas de productos.

7. **Comunidad Activa:** PrestaShop cuenta con una comunidad activa de desarrolladores, comerciantes y usuarios que comparten conocimientos y ofrecen soporte. La comunidad contribuye al desarrollo continuo de la plataforma mediante la creación de módulos, temas y aportando mejoras al código.

8. **Internacionalización:** La plataforma está diseñada para ser utilizada a nivel internacional, admitiendo múltiples idiomas, monedas y métodos de pago.

9. **Seguridad:** PrestaShop se preocupa por la seguridad de las transacciones en línea y ofrece funciones de seguridad, como el cifrado SSL para proteger la información confidencial de los clientes.

10. **Escalabilidad:** PrestaShop es adecuado tanto para pequeñas empresas como para grandes empresas, ya que es escalable y puede crecer con el negocio a medida que aumentan las necesidades.

En resumen, PrestaShop proporciona una solución robusta y flexible para aquellos que desean crear y gestionar tiendas en línea de manera efectiva, ya sea para pequeños emprendimientos o para empresas más grandes.

## Pasos para instalar Prestashop

Instalar PrestaShop en Windows utilizando XAMPP es un proceso relativamente sencillo. Aquí tienes los pasos detallados:

### Paso 1: Descargar PrestaShop

1. Ve al sitio oficial de [PrestaShop](https://www.prestashop.com/) y descarga la última versión del software.

### Paso 2: Instalar XAMPP

1. Descarga e instala [XAMPP](https://www.apachefriends.org/es/index.html) en tu sistema. Durante la instalación, asegúrate de seleccionar Apache y MySQL como servicios para instalar.

### Paso 3: Iniciar Servidores

1. Abre el Panel de Control de XAMPP y asegúrate de que los servicios de Apache y MySQL estén iniciados. Si no lo están, haz clic en "Start" junto a cada uno de ellos.

### Paso 4: Crear una Base de Datos MySQL

1. Abre tu navegador y accede a http://localhost/phpmyadmin/.
2. Crea una nueva base de datos para PrestaShop. Puedes hacerlo haciendo clic en "Bases de datos" y luego en "Crear base de datos". Asigna un nombre a la base de datos y haz clic en "Crear".

### Paso 5: Descomprimir PrestaShop

1. Descomprime el archivo de PrestaShop que descargaste en el directorio `htdocs` de tu instalación de XAMPP. Puedes encontrar `htdocs` en la carpeta donde instalaste XAMPP, por ejemplo, `C:\xampp\htdocs`.

### Paso 6: Iniciar la Instalación de PrestaShop

1. Abre tu navegador y visita http://localhost/tu_carpeta_de_PrestaShop. Sustituye "tu_carpeta_de_PrestaShop" con el nombre de la carpeta de PrestaShop que creaste en `htdocs`.

2. Selecciona tu idioma y haz clic en "Siguiente".

3. PrestaShop realizará una verificación del sistema. Si todo está bien, haz clic en "Siguiente".

4. Lee y acepta los términos de la licencia. Haz clic en "Siguiente".

5. Ingresa la información de la base de datos que creaste en el Paso 4. Esto incluye el nombre de la base de datos, el nombre de usuario (por defecto es "root"), y la contraseña (deja esto en blanco por defecto en XAMPP).

6. Completa la información requerida para la configuración de la tienda y del administrador.

7. Haz clic en "Siguiente" y, finalmente, en "Instalar".

8. Después de la instalación, PrestaShop te pedirá que elimines la carpeta `/install` por motivos de seguridad. Puedes hacerlo manualmente desde tu sistema de archivos.

¡Listo! Ahora deberías tener PrestaShop instalado y listo para ser configurado según tus necesidades. Accede al panel de administración utilizando la URL http://localhost/tu_carpeta_de_PrestaShop/administracion/.

### Pasos para instalar en Mac

Instalar PrestaShop en Mac utilizando XAMPP es un proceso similar al de Windows. Aquí están los pasos detallados:

### Paso 1: Descargar PrestaShop

1. Ve al sitio oficial de [PrestaShop](https://www.prestashop.com/) y descarga la última versión del software.

### Paso 2: Instalar XAMPP en Mac

1. Descarga XAMPP para Mac desde [la página de descargas de XAMPP](https://www.apachefriends.org/es/download.html).

2. Abre el archivo `.dmg` que descargaste y arrastra el icono de XAMPP a la carpeta de "Aplicaciones" para instalarlo.

3. Abre XAMPP desde la carpeta de Aplicaciones y luego inicia los servicios de Apache y MySQL.

### Paso 3: Crear una Base de Datos MySQL

1. Abre tu navegador y accede a http://localhost/phpmyadmin/.
2. Crea una nueva base de datos para PrestaShop haciendo clic en "Bases de datos" y luego en "Crear base de datos". Asigna un nombre a la base de datos y haz clic en "Crear".

### Paso 4: Descomprimir PrestaShop

1. Descomprime el archivo de PrestaShop que descargaste en el directorio `htdocs` de tu instalación de XAMPP. Puedes encontrar `htdocs` en la carpeta donde instalaste XAMPP, por ejemplo, `/Applications/XAMPP/xamppfiles/htdocs`.

### Paso 5: Iniciar la Instalación de PrestaShop

1. Abre tu navegador y visita http://localhost/tu_carpeta_de_PrestaShop. Reemplaza "tu_carpeta_de_PrestaShop" con el nombre de la carpeta de PrestaShop que creaste en `htdocs`.

2. Selecciona tu idioma y haz clic en "Siguiente".

3. PrestaShop realizará una verificación del sistema. Si todo está bien, haz clic en "Siguiente".

4. Lee y acepta los términos de la licencia. Haz clic en "Siguiente".

5. Ingresa la información de la base de datos que creaste en el Paso 3. Esto incluye el nombre de la base de datos, el nombre de usuario (por defecto es "root"), y la contraseña (deja esto en blanco por defecto en XAMPP).

6. Completa la información requerida para la configuración de la tienda y del administrador.

7. Haz clic en "Siguiente" y, finalmente, en "Instalar".

8. Después de la instalación, PrestaShop te pedirá que elimines la carpeta `/install` por motivos de seguridad. Puedes hacerlo manualmente desde tu sistema de archivos.

¡Listo! Ahora deberías tener PrestaShop instalado y listo para ser configurado según tus necesidades. Accede al panel de administración utilizando la URL http://localhost/tu_carpeta_de_PrestaShop/administracion/.
