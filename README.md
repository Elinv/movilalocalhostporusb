# Editar HTML en simult谩neo en PC y MOVIL.

---

# 馃敡 ACTUALIZACI脫N MIERCOLES 1 DE FEBRERO DE 2023.
## 馃敡 DEPURAR JAVASCRIPT PAGINA WEB EN DISPOSITIVO M脫VIL EN EDGE
[Ir a la Seccion agregada de depuraci贸n en dispositivos m贸viles.](#moviles)
---
## 馃 Elinv <a name = "Elinv"></a>

----------------------------------------
<p align="center">
  <a href="" rel="noopener">
 <img width=400px height=400px src="./imgconexusb/naha-elinv.png" alt="Editar HTML en simult谩neo en PC y MOVIL"></a>
</p>

## 馃弫 Iniciemos 鉀忥笍
----------------------------------------
```
La posibilidad de editar 
un sitio web en localhost, 
pudiendo tener el resultado 
final a la vista en simult谩neo, 
tanto sea en la PC 
donde se edita 
como en un tel茅fono m贸vil 
testigo, conectado v铆a USB a 
esta computadora.

Y una ventaja increible, 
la actualizaci贸n de la 
vista previa 
en la PC o en el MOVIL
ocurren autom谩ticamente.

La aceleraci贸n de la 
programaci贸n y la optimizaci贸n 
de los recursos 
al servicio del programador.
```

## 
----------------------------------------
```
Esta posibilidad no solo ofrece 
una mayor comodidad 
al programador, 
tambi茅n el hecho de que no es 
necesario tener conectada la 
computadora o el tel茅fono 
a ninguna red wifi o cableada.
```

## 
----------------------------------------
```
Si se utiliza este sistema, 
cualquier edici贸n 
en el proyecto de pagina web 
en Visual Studio Code, 
sera visualizado en simult谩neo 
en el monitor de la PC 
y en el display del M贸vil, 
pudi茅ndose as铆 corregir 
de inmediato 
cualquier eventualidad 
que no nos agrade.
```
----------------------------------------

## 馃摑 Herramientas:
----------------------------------------
- Visual Studio Code.
- Extensi贸n de VSC. Live Server
```
    Nombre: Live Server
    ID: ritwickdey.LiveServer
    Descripci贸n: Launch a 
                 development 
                 local Server 
                 with live 
                 reload feature 
                 for static 
                 & dynamic pages
    Versi贸n: 5.7.9
    Editor: Ritwick Dey
    id de la extensi贸n: 
          ritwickdey.LiveServer
```
- adb instalado.
```
    En nuestro caso:
    adb
    Android Debug Bridge 
              version 1.0.39
    Version 1:8.1.0+r23-5ubuntu2
    Installed as 
    /usr/lib/android-sdk/platform-tools/adb
```
- Desarrollar nuestro proyecto 
  en un espacio de trabajo VSC.

- Info de nuestra PC.
```
    Linux Mint 20.1 Cinnamon    version 4.8.6
    N煤cleo de Linux:            5.4.0-135-generic
    Procesador:                 Intel漏 Core鈩? i7-3770 CPU @ 3.40GHz 脳 4
    Memoria:                    15.5 GiB
    Tarjeta gr谩fica:            NVIDIA Corporation GP107 [GeForce GTX 1050 Ti]
```

- Telefono: Galaxy A51 con Android 12.
----------------------------------------

## Como iniciar r谩pidamente la conexi贸n:
----------------------------------------
- En una carpeta dedicada, crear el arch铆vo index.html y como espacio de trabajo abrir Visual Studio Code.
- Abrir el archivo index.html, editarlo a gusto, y luego en el menu contextual elegir Open with Live Server.

<p align="center">
  <a href="" rel="noopener">
 <img src="./imgconexusb/live-server-ejecutar.png" alt="Ejecutar Live Server en Visual Studio Code."></a>
</p>

- Y se visualizar谩 nuestra pagina o siti贸 web en: 
```
    http://127.0.0.1:5500/index.html
    o similar respecto al puerto.
  
    Hasta aqu铆 estamos viendo 
    el resultado de nuestro 
    trabajo en la PC. 
```
----------------------------------------

## Ahora toca conectar el m贸vil v铆a USB.
----------------------------------------
- te aparecer谩 un mensaje de alerta as铆:

<p align="center">
  <a href="" rel="noopener">
 <img src="./imgconexusb/permitir depuraci贸n USB.jpg" alt="Permitir depuraci贸n USB."></a>
</p>

- En mi caso, presiono "Permitir!"
----------------------------------------

## Ahora abrimos la c贸nsola de Linux, o Terminal de Gnome o lo que tengas como terminal escribes esta orden: 
----------------------------------------
```
  adb reverse tcp:5500 tcp:5500

  Nota: el puerto debe ser 
  el mismo que el del servidor.

      Mir谩 la imagen...
```
----------------------------------------
<p align="center">
  <a href="" rel="noopener">
 <img src="./imgconexusb/adb.png" alt="Permitir depuraci贸n USB."></a>
</p>

## Abrimos nuestro navegador en el tel茅fono m贸vil e ingresamos la misma direcci贸n que antes 
es decir:
```
http://127.0.0.1:5500/index.html

donde Live est谩 mostrando 
nuestro proyecto.
      y listo!

Estar谩s viendo el resultado 
de tu proyecto, 
en simult谩neo 
en la PC y en el formato m贸vil
con actualizaci贸n de la vista 
previa autom谩tica
en cada dispositivo.
```
----------------------------------------
## 馃敡 Creeme acelera mucho tu trabajo.
----------------------------------------
```
  Y en el camino no necesitas 
  tener tu equipo conectado 
  a Internet ni a ninguna red, 
  lo que te da un margen 
  de seguridad inmenso.

  En mi caso si no uso Internet
  con un juego de teclas 
  conecto o desconecto Internet
  en menos de lo se pesta帽ea.      
```

# Mas seguridad
----------------------------------------
- Funciona con el cortafuegos activado. 
- Impidiendo todas las conexiones entrantes
<p align="center">
  <a href="" rel="noopener">
 <img src="./imgconexusb/cortafuegos_activado.png" alt="Aun con el cortafuegos activado, la conexi贸n es posible."></a>
</p>
----------------------------------------

----------------------------------------
# moviles
# 馃敡 ACTUALIZACI脫N MIERCOLES 1 DE FEBRERO DE 2023.
## 馃敡 DEPURAR JAVASCRIPT PAGINA WEB EN DISPOSITIVO M脫VIL EN EDGE
----------------------------------------
```
Ver la consola de las acciones llevadas a cabo en el tel茅fono m贸vil.  

Ver los mensajes de alertas por nosotros programados para depurar errores de la aplicaci贸n web, pero respecto de los eventos propios del tel茅fono m贸vil.

Es posible, es bastante f谩cil, y se puede realizar en segundos, a trav茅s de los navegadores que hoy nos proveen Google, Microsoft, e inclusive alg煤n otro. 

Para esta prueba hemos utilizado 
Microsoft Edge, en su 102.0.1245.33 (Compilaci贸n oficial) (64 bits) en la PC, 

y en el m贸vil instalada 
la 煤ltima versi贸n de EDGE, a trav茅s de GOOGLE PLAY.
```

----------------------------------------
## 馃敡 En nuestro espacio de trabajo en VISUAL STUDIO CODE
----------------------------------------
```
  Ejecutamos en el servidor en este caso nuestro server.

  PHP server y se nos despliega nuestro localhost en el puerto 3000.

  En la PC se ver铆a as铆.

```
<p align="center">
  <a href="" rel="noopener">
 <img src="./imgetapadepuracion/vsc-ejecutar-php-server.jpg" alt="En visual studio code ejecutamos php server."></a>
</p>
<p align="center">
  <a href="" rel="noopener">
 <img src="./imgetapadepuracion/localhostpc.jpg" alt="Vista del localhost y la pagina web en edici贸n en Visual Studio Code."></a>
</p>

----------------------------------------
## 馃敡 CONECTAR EL TELEFONO VIA USB AL PC
----------------------------------------
```
  Y ejecutan en la consola de Linux(nuestro caso) 
  la siguiente directiva:
  
  adb reverse tcp:3000 tcp:3000

```

<p align="center">
  <a href="" rel="noopener">
 <img src="./imgetapadepuracion/adbreverse.jpg" alt="Adb reverse tcp:3000 tcp:3000."></a>
</p>

## En el tel茅fono aparecer谩 la solicitud de permiso.

<p align="center">
  <a href="" rel="noopener">
 <img src="./imgetapadepuracion/telefono movil permitir depuracion.jpeg" alt="Adb reverse tcp:3000 tcp:3000."></a>
</p>

## En la consola veran lo siguiente:

<p align="center">
  <a href="" rel="noopener">
 <img src="./imgetapadepuracion/adb confirmado.jpg" alt="Adb confirmado."></a>
</p>

## Y en el celular al recargar el navegador acceder谩n al localhost as铆.

<p align="center">
  <a href="" rel="noopener">
 <img src="./imgetapadepuracion/localhost en movil.jpeg" alt="Localhost en el tel茅fono m贸vil"></a>
</p>

## Aqu铆 tienen una vista de depuraci贸n en EDGE en la PC.

<p align="center">
  <a href="" rel="noopener">
 <img src="./imgetapadepuracion/vistapcdepuracionedge.jpg" alt="Vista depuraci贸n en Edge"></a>
</p>

## Ahora para tener en paralelo la depuraci贸n del tel茅fono celular.
### abrimos una nueva ventana de edge en el PC, y escribimos:
### edge://inspect/#devices y se ver谩 as铆:

<p align="center">
  <a href="" rel="noopener">
 <img src="./imgetapadepuracion/inspector edge para el movil.jpg" alt="Inspector Edge para el m贸vil"></a>
</p>

## Vemos que aparece 

### 鈿? Remote browser is newer than client browser. Try `inspect fallback` if inspection fails.

### Planilla de calculo Elinv. http://127.0.0.1:3000/calculadora.html

### Hacemos click en "inspect" y emerge una nueva ventana que se ve as铆.

<p align="center">
  <a href="" rel="noopener">
 <img src="./imgetapadepuracion/inspector edge del movil 1.jpg" alt="Inspector Edge del m贸vil en acci贸n"></a>
</p>


# En nuestra aplicacion web he puesto una directiva que solo aplica al tel茅fono m贸vil ejemplo:
```
let ontouchendFunc = (event) => { 
	alert('Evento on touch end exitoso!');
	console.log('Evento on touch end exitoso!');
};

```

### aplicado al campo de la formula

```
$id('formula').ontouchend = ontouchendFunc;

```
### Resultados en el tel茅fono y en el Inspector de Edge:

<p align="center">
  <a href="" rel="noopener">
 <img src="./imgetapadepuracion/mensaje depuracion movil no pc0.jpg" alt="Mensaje de depuraci贸n de c贸digo en dispositivo m贸vil con Alert en el propio dispositivo."></a>
</p>

## Observen que en el inspector Edge de la pagina web de la PC, 
## no se observan los mensajes on touch end del m贸vil, y si en el 
## inspector Edge del m贸vil

<p align="center">
  <a href="" rel="noopener">
 <img src="./imgetapadepuracion/mensaje depuracion movil no pc1.jpg" alt="Mensaje de depuraci贸n de c贸digo en dispositivo m贸vil en inspector movil de Edge"></a>
</p>

# Por 煤ltimo:

## Observen que cualquier acci贸n que lleven adelante en el inspector de Edge se reflejar谩 en el dispositivo m贸vil, y a la inversa, pasar谩 lo mismo.

### Prueben en el inspector Edge del m贸vil a hacer click en alguna parte de la pagina web, y veran como el foco hacia elemento cambia en el m贸vil y a lo mismo en direcci贸n contraria.
---

## Saludos y bendiciones!
----------------------------------------
Espero no haber olvidado nada.!

# Mail [elinv.elinv@gmail.com]()

