## Ventoy
L'eina de programari lliure [Ventoy](https://ventoy.net/en/index.html "Web oficial Ventoy") ens proporciona un mètode àgil i senzill per generar pendrives d'arrancada a partir de fitxers iso. Si més no, aquesta és la funcionalitat més coneguda, tot i que veurem que és molt més potent que això.

Ventoy recopila una sèrie de gestors d'arrancada i ens permetrà iniciar des d'un dispositiu d'emmagatzematge a diferents plataformes. Mitjançant diferents afegits, podem millorar l'eina aconseguint iniciar un ordinador des d'un fitxer .vdi, .vhd o .img entre altres, tant per distribucions GNU/Linux com Windows.

Altres millores són:
* Es pot personalitzar el dispositiu d'arrancada amb temes gràfics, que ens ajuden a visualitzar si el sistema engega en mode EFI o BIOS si ho configurem així
* Permet generar espai persistent per tal que es puguin desar dades al dispositiu d'emmagatzematge sense la necessitat d'instal·lar un sistema operatiu. Això permet disposar d'un espai d'intercanvi d'informació, utilitzar una iso per encendre un sistema operatiu i desar dades a l'emmagatzematge o per exemple, desar les imatges generades amb clonezilla per tenir-ho tot amb un sol dispositiu.
* Permet preparar l'entorn d'instal·lació de Windows 11 sense la necessitat de complir els requeriments de maquinari ni l'obligació de disposar d'un compte Microsoft
* Es pot engegar un sistema de fitxers virtualitzat des d'una altra partició on hi hagi un fitxer .vdi o .vhd per exemple
* Es pot intercanviar el dispositiu extern com a intern si disposa de connector SATA o PCIe
* També permet canviar el mode d'arrancada a [Wimboot](https://learn.microsoft.com/es-es/windows/win32/w8cookbook/windows-image-file-boot--wimboot- "Aclariment"), cosa que ajuda davant de problemes amb l'inici normal
* Et permet disposar del teu entorn laboral, de formació, de proves o personal sempre sota el teu control, doncs es pot iniciar el sistema operatiu que hagis generat amb qualsevol ordinador real que et permeti iniciar per USB
* Permet intercanviar els fitxers .vtoy com a fitxers de màquina virtual, el que permet utilitzar-ho tant en real com virtualitzat, i reparar possibles problemes o recuperar dades
* Permet utilitzar els fitxers .vhd des d'una instal·lació de Windows per accedir a les dades

#### Alguns exemples d'ús
* Ventoy instal·lat a una màquina virtual de l'entorn al núvol IsardVDI. La imatge mostra un tema associat a arrancada per BIOS (configurat per qui ho va instal·lar, no ve així de sèrie). Es veuen algunes iso per iniciar el sistema i un fitxer .vtoy que és un disc virtual perfectament utilitzable des de l'ordinador real gràcies a Ventoy.
<img width="680" height="537" alt="RA2-ventoy-01" src="https://github.com/user-attachments/assets/978e50db-0019-443c-9d5f-ff863ee6bef0" />

* Ventoy instal·lat a una SD interna d'una Steam Deck
![RA2-ventoy-02](https://github.com/user-attachments/assets/c37a7459-b0c0-4e00-8f13-6831c7506751)

* Ventoy a un SSD. El tema està associat a EFI. Es poden apreciar múltiples sistemes operatius instal·lats (els .vtoy) i un Windows 11 funcional (.vhd)
<img width="818" height="535" alt="RA2-ventoy-03" src="https://github.com/user-attachments/assets/184c719a-4584-484a-ad1a-72d57686cd8a" />

El mateix disc iniciat amb un sistema BIOS (legacy)
<img width="939" height="573" alt="RA2-ventoy-04" src="https://github.com/user-attachments/assets/360c6322-a62e-4962-92da-0e2f3a313c49" />
