# Learnings

## Tele Samsung
- Para abrir Developer Mode se marca `12345` en Apps. Si el control no trae números, el botón 123 (o el de los puntitos de colores) saca un teclado en pantalla, o se usa el control virtual de la app SmartThings.
- Instalar como app de Tizen pide modo desarrollador, conectar la tele con `sdb` y un certificado de Samsung con el ID de la tele. Abrirlo en el navegador de la tele no pide nada de eso.
- El 2026-11-11 se quitó la app de Tizen: `config.xml` e `icon.png` del repo y el SDK de la Mac. Si se quiere volver a instalar como app, esos dos archivos están en el commit `dbf6086`.
- La extensión de Tizen escribe en `~/.zshrc` un autocompletado de bash, y cada Terminal nueva marca `command not found: complete`. Al quitarla también hay que quitar esas líneas.
- Servirlo desde la Mac con `python3 -m http.server` abrió en el celular pero no en la tele. Por eso se publicó en GitHub Pages.

## Navegador de la tele
- El navegador Internet de la tele usa el control como un cursor lento y no le pasa las flechas a la página. El manejo con flechas y foco solo sirve en la app de Tizen.
- Para el cursor, lo que importa es cuánto hay que moverlo: botones pegados y cerca del ejercicio, y cada `:hover` resaltado igual que el foco.
- Hoja del día revisa sola al escribir todos los dígitos de la respuesta, para no cruzar la pantalla hasta un botón de revisar. El costo es que no se puede corregir un dígito equivocado.
