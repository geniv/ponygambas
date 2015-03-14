https://pbs.twimg.com/media/A4hRHl_CcAAsOuB.png:large

PonyGambas is a fork of old windows program called [PonyProg2000](http://www.lancos.com/ppwin95.html).

Because the original software is no longer developed and there is no
suitable GUI tool for linux (Ubuntu, to be more precise) I have
decided to make my own - with Gambas 3.3.1 and with original icons
from ponyprog.

This tool uses utility **avrdude** and for testing I used the **stk500v2**
programmer (avrdude supports more types of course).

Please check the ports and programmer type in the settings.
Be sure to have set correct MCU and programmer-id before you do
your Probe test.

You can load flash/eeprom from a file and from MCU. Loaded program
can be saved to a file or flashed to device.

As the compiler for hex translating is used a **gcc-avr**, but you can
either use translator from avr assembler.

TODO: implement the security and fuse bit configuration

If you are interested in helping with the project (let it be
translations or GUI and functionality improvements), please feel
free to contact me.

Project is managed throught GIT: http://code.google.com/p/ponygambas


---


PonyGambas je forknutý program pro windows [PonyProg2000](http://www.lancos.com/ppwin95.html), jelikož se tento program už několik dlouhých let nevyvijí a neexistuje pořádný GUI nástroj pro linux (ubuntu), tak jsem se rozhodl i z vlastní potřeby že udělám fork tohoto programu který jsem dříve hojně využíval. Proto jsem využil i ikony z původního PonyProg-u.

Program používá linux utilitu: **avrdude** a progamátor na kterám probíhaly programovací testy byl **stk500v2**, samozřejmě avrdude podporuje více typů programátorů.

Nastavení portů a typu programátoru je v nastavení.
Před testem připojení programátoru (Probe) zkontrolujte jestli máte vybraný typ MCU který máte aktuálně připojený a máte korektně vybraný port a programmer-id.

Program umožnuje Našíst flash/eeprom ze souboru a z mcu, načtený program umožňuje uložit nebo naprogramovat do flash nebo eeprom.

Konfigurace security a fuse bitu ještě není úplně hotová.
TODO je nutno tuto funkcionalitu doimplementovat.

Jako kompilátor pro překládání do hex používám **gcc-avr**, ale samozřejmě lze použít i překladaž z avr assembleru.

Program je vytvořen v Gambas 3.3.1

Pokud by jste někdo měl zájem na tomto projektu pomáhat ať už s překlady, vylepšováním  GUI nebo funkcionality tak mě můžete kontaktovat.

Projekt je spravován přes GIT: http://code.google.com/p/ponygambas