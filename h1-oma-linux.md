# x) Raportointi

- Raportoi samalla kun teet

- raportoi mahdollisimman tarkasti kaikki vaiheet, myös virheet

- tee helppolukuiseksi ja muista lähdevitteet

# a) Linuxin asentaminen virtualboxiin

- Lataan debian-live 13.3.0 version ja avaan virtualboxin. Omassa koneessani on windows käyttöjärjestelmä.

- Teen uuden virtuaalikoneen. Valitsen OS imageksi debian liven ja ruksaan pois "Proceed With Unattended Installation"

![Add file: Upload](vm1.png)

- Määritän koneelle virtuaalisen muistin ja prosessorien määrän sekä ruksaan "Use EFI"

![Add file: Upload](vm2.png)

- Määritän virtuaalisen kovalevyn koon

![Add file: Upload](vm3.png)

- Kun asetukset ovat valmiina käynnistän virtuaalikoneen

- Käynnistys epäonnistui 

![Add file: Upload](vm5.png)

- Asetusten tarkistamisen jälkeen, huomasin, että unohdin laittaa OS version 64-bitiksi

![Add file: Upload](vm6.png)

- Tällä kertaa onneksi käynnistyy. Bootataan live systeemillä

![Add file: Upload](VirtualBox_vm_1.png)

- Netti ja komentorivi toimivat moitteettomasti, joten siirryn debian asentamiseen.
- Käyttökielen, aikavyöhykkeen ja näppäimistön säätämisen jälkeen valitsen kovalevyn osioinnissa "Erase disk"

 ![Add file: Upload](VirtualBox_vm_3.png)

 - Kaikki asetukset näyttävät olevan kunnossa --> install
  
 - Kymmenisen minuutin jälkeen on käyttövalmis linux-pohjainen virtuaalikone!
   ![Add file: Upload](VirtualBox_vm_4.png)

## Viittaukset

Kurssi: ICI003AS2A-3016

Tehtävänannot: https://terokarvinen.com/linux-palvelimet/#schedule

Debian lataussivu: https://www.debian.org/distrib/


