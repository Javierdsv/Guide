---
title: "Homebrew Launcher (Mavegador)"
permalink: /homebrew-launcher-(browser).html
---

El Homebrew Launcher tiene diferentes puntos de entrada, o metodos de ser lanzado. El más comun es browserhax, el cual lanza el Homebrew Launcher usando unicamente el navegador incluido en la consola.

**Browserhax funcionará SOLO en las regiones EUR / JPN / USA / KOR!**
{: .notice--warning}

#### ¿Qué necesitas?

+ [`config.zip`](images/config.zip)
+ El [ropbin](https://smealum.github.io/3ds/#otherapp) correspondiente a la version de tu 3DS
+ El Homebrew [Starter Kit](http://smealum.github.io/ninjhax2/starter.zip)
+ Una conexion a internet configurada en el 3DS

#### Instrucciones

##### Sección I -  Preparación preliminar

1. Copiar los contenidos de `starter.zip` a la raíz de tu tarjeta SD
2. Copiar los contenidos de `config.zip` a la carpeta `/3ds/menuhax_manager/` en tu tarjeta SD
3. Crea la carpeta `menuhax` en la raíz de tu tarjeta SD si no existe todavía
4. Renombra el ropbon a `menuhaxmanager_input_payload.bin`
5. Copia `menuhaxmanager_input_payload.bin` a la carpeta `/menuhax/` de tu tarjeta SD
4. Reinserta tu tarjeta SD en la 3DS

##### Section II -  Version check bypass

**This section is only needed for versions from 9.9.0 to 10.6.0**

2. Open the theme menu, change your theme to any other theme, then switch back. This will initialize the theme data and is required
3. Launch the Settings application
4. Change the date to `January 1, 2000`
5. Change the time to `00:00`
6. Launch the browser, then open the browser settings as fast as possible
7. Scroll to the bottom and Initialize Savedata (it also may be called Clear All Save Data) as fast as possible

##### Section III -  Bookmark browserhax

**This section is only needed for New 3DS on version 10.7.0**

1. Launch the browser
2. Select the bookmarks menu star at the bottom left of the bottom screen
3. Edit the first bookmark to instead be the URL `http://plail.ueuo.com/3dsbrowserhax_auto.php`
4. Press "Done", then go back to the home menu
5. Select the home menu options at the top left of the bottom screen
6. Scroll down and turn off "Wireless Communication / NFC"
7. Use the power button to turn off your 3DS
8. Turn on your 3DS
9. Use the home menu options to turn back on "Wireless Communication / NFC"
10. Launch the browser as fast as possible, then launch your bookmark
11. This may take several tries; if you get the prompt to update your 3DS, restart at the step to turn off "Wireless Communication / NFC"
12. Your console should load the homebrew menu
13. Skip Section IV -  browserhax

##### Section IV -  browserhax

8. Navigate to `http://plail.ueuo.com/3dsbrowserhax_auto.php`
    + You can also load the page by scanning the following QR code (press (L + R) on the home menu, then tap the QR icon on the bottom screen)     
![browserhax_auto](http://plail.ueuo.com/3dsbrowserhax_auto_qrcode.png)
    + If you get an error, [follow this troubleshooting guide](troubleshooting#ts_browser)
9. Your console should load the homebrew menu

##### Section V -  menuhax

10. Open the menuhax_manager application
11. Press (A) to install, it may show some errors but that's fine as long as it shows "Install finished successfully" towards the end
    + If you are prompted to "override the detected system version," press (B) to decline
12. Go back to the main menuhax_manager menu, then select "Configure menuhax"
13. Press (A) to continue, then select "Type1"
14. Hold (Down) on the D-Pad, then tap the touch screen; this is the recommended button to use for launching menuhax in this guide because it does not interfere with any other functions of tools we will be using
15. Go back to the main menuhax_manager menu, press (B), then press (Start) to exit back into the Homebrew Launcher
16. Press the (Start) button then press (A) to reboot
17. You can now hold D-Pad (Down) while the system is booting to launch the Homebrew Launcher

You can now launch the Homebrew Launcher by holding D-Pad (Down) while the system is booting
{: .notice--info}

If you are above the version 9.2.0, continue to [9.2.0 Downgrade](9.2.0-downgrade)
{: .notice--primary}

If you are on the version 9.2.0 or below, continue to [Decrypt9 (Homebrew Launcher)](decrypt9-(homebrew-launcher))
{: .notice--primary}
