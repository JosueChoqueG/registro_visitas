## REGISTRO DE VISITAS
<p>Sistema especializado para el registro de visitas</p>

## LENGUAJES, FRAMEWORKS UTILIZADOS Y HERRAMIENTAS <g-emoji class="g-emoji" alias="hammer_and_wrench" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f6e0.png">🛠️</g-emoji>
<ul>
	<li><b>PHP</b></li>
	<li><b>LARAVEL VER: 8.5</b></li>
	<li><b>MYSQL</b></li>
	<li><b>AXIOS</b></li>
	<li><b>VUEX</b></li>
	<li><b>VUE.JS</b></li>
	<li><b>VUE ROUTER</b></li>
	<li><b>ADMIN-LTE</b></li>
</ul>

## INSTALACIÓN <g-emoji class="g-emoji" alias="wrench" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f527.png">🔧</g-emoji>

<h3>Sigue paso a paso nuestras intrucciones para ejecutar correctamente el sistema</h3>

<em>Clonamos el repositorio</em>
<pre><code><b>git clone https://github.com/elyugos/sistema-de-regristro-de-visitas.git</b></code></pre>
<em>Instalamos nuestras dependencias con</em>
<pre><code><b>composer install</b></code></pre>
<em>Realizamos una copia de nuestro archivo .env con el siguiente comando</em>
<pre><code><b>cp .env.example .env</b></code></pre>
<em>Generamos la key para nuestro .env</em>
<pre><code><b>php artisan key:generate</b></code></pre>
<em>Instalamos nuestros paquetes necesarios </em>
<pre><code><b>npm install</b></code></pre>
<em> Compilamos </em>
<pre><code><b>npm run dev</b></code></pre>
<em> Importar base de datos </em>
<pre><code>La base de datos esta incluida en la carpeta <b>base-de-datos</b></code></pre>
<h3>Una vez terminemos con los pasos anteriores, procedemos a configurar nuestro archivo .env </h3>
<pre><code>DB_DATABASE=registro-de-visitas
DB_USERNAME=root
DB_PASSWORD="tupassword" 
APP_PATH_LOCAL_VUE=/registro-de-visitas/public/  ###ubicación de la carpeta public
SANCTUM_STATEFUL_DOMAINS=localhost   ###  nombre del dominio</pre></code>
<h3>Terminada las configuraciones acceder al sistema</h3>
<pre><code>USUARIO=admin@incared.net</br>
CLAVE: 12345678 </pre></code>

