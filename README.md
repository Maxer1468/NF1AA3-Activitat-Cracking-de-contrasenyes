# NF1AA3-Activitat-Cracking-de-contrasenyes



![](/img/1.png)
![](/img/2.png)
## Configuració d'interfícies i xarxa
Es configuren els adaptadors de xarxa de les màquines virtuals i s'executa la comanda ip a a la Kali Linux per comprovar la connectivitat i veure la IP de l'atacant.

![](/img/3.png)

---
<br>
<br>
<br>


## Engegada i activació de SSH
S'activa i s'inicia el servei SSH a la màquina víctima mitjançant systemctl per permetre l'accés remot.

![](/img/4.png)
![](/img/6.png)
![](/img/7.png)

---
<br>
<br>
<br>


## Transferència d'arxius amb SCP
S'utilitza la comanda scp des de la víctima per transferir de manera remota els fitxers essencials de credencials cap a la Kali Linux.

![](/img/5.png)
![](/img/8.png)

---
<br>
<br>
<br>


## Instal·lació de John the Ripper i Johnny
S'instal·len al sistema operatiu les eines de auditoria de contrasenyes John the Ripper i la seva interfície gràfica Johnny utilitzant el gestor de paquets.

![](/img/9.png)

---
<br>
<br>
<br>


## Fusió de fitxers amb unshadow
S'executa la comanda unshadow per fusionar els fitxers passwd i shadow en un de sol que l'eina de cracking pugui processar.

![](/img/10.png)

---
<br>
<br>
<br>


## Obertura de credencials a Johnny i llistat d'usuaris
S'importa el fitxer combinat dins de la interfície gràfica de Johnny i es carrega la llista amb tots els usuaris i hashos del sistema.

![](/img/11.png)
![](/img/12.png)
![](/img/13.png)
![](/img/14.png)

---
<br>
<br>
<br>


Es descomprimeix el diccionari estàndard de contrasenyes i es configuran els paràmetres de l'atac.

![](/img/15.png)
![](/img/16.png)
![](/img/17.png)
![](/img/18.png)
![](/img/19.png)

---
<br>
<br>
<br>


## Execució del procés de desxifrat i resolució de les contrasenyes
S'executa finalment el procés de desxifrat indicant l'algoritme de xifratge corresponent per trencar les contrasenyes febles dels usuaris vulnerables.

---


## Planteja mesures de millora de la seguretat de l'equip a nivell lògic per evitar que un atacant real pugui replicar el mateix atac i per establir una política de contrasenyes segures.

1. Desactivar l'accés directe de root per SSH.

2. Exigir una longitud mínima de 12 caràcters.

3. Instal·lar programes per bloquejar automàticament les IPs d'atacants després d'intents fallits consecutius.