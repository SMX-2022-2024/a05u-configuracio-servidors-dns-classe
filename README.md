# Configuració de la xarxa classe per que tots els servidors es vegin entre ells

> ## MP07 UF01 A05U - Activitat 5

## Assignació dels grups

|Grup|Alumne/a|
|---|---|
|Grup 1|Agustí Corbella, Oriol|
|Grup 1|Lamela Garcia, Alvaro Haoan|
|Grup 1|Román Robles, Àlex|
|Grup 1|Soler Sampere, Arnau|
|Grup 2|Boada Cirera, Jan|
|Grup 2|Cot Fontanella, Marc|
|Grup 2|Putellas Martín, Pol|
|Grup 2|Vázquez Pelàez, Alex|
|Grup 3|Navarro Galan, Gerard|
|Grup 3|Rueda Guàrdia, Marc|
|Grup 3|Sellés Puyol, Aniol|
|Grup 4|Capel Vallbona, Marc|
|Grup 4|Codina Garcia, Aleix|
|Grup 4|Deus Jurado, Izan|
|Grup 4|Ortiz Guerrero, Antoni|
|Grup 5|Pan , Jiahao|
|Grup 5|Pan , Le|
|Grup 5|Sacristan Castillo, Marc|
|Grup 5|Sardaña Trinh, Marc|
|Grup 6|Córdoba Xandri, Oriol|
|Grup 6|Garcia Romero, Arnau|
|Grup 6|Puriy Puriy, Nicolas|
|Grup 6|Royuela Martín, Oriol|
|Grup 7|Gálvez Comajuan, Marc|
|Grup 7|Martinez Segú, Eric|
|Grup 7|Moreno Fernández, Nil|
|Grup 7|Sohl Brenes, Martin Albert|
|Grup 8|Bollero Ruzafa, Ivan|
|Grup 8|Casas Lopez, Raul|
|Grup 8|Garcia Fernández, Adrià|
|Grup 8|Morales Gonzalez, Jan|


Podeu comprovar quina és l'adreça IP que us toca i quin és el vostre grup al següent [enllaç](https://script.google.com/a/macros/ginebro.cat/s/AKfycbwyXcC3_d4qYKO2lxQMkS_GXYfajSFB1BP9CX98d9DAN9s3QCf-jfbAvzj5-1Se8_O9gA/exec)

## Creació del repositori del grup

### **Pas 1** Nom del **repositori remot** del grup

El **nom** del **repositori del grup** contindrà els **cognoms**, (**i només els cognoms, no hi haurà cap nom**), de cadascun dels membres del grup, **ordenats alfabeticament** i en minúscules, separats per guions i desprès de l'últim dels cognoms, un guió i el text **```-a05u```**.

> ### Per exemple si els membres del grup son:
> 
> 1. **Iván Nieto** 
> 1. **Vladi Bellavista** 
> 1. **Rubén Martinez** 
> 1. **Joan Pardo** 
> 
> El nom del **repositori del grup** seria:
> 
> **```bellavista-martinez-nieto-pardo-a05u```**

### **Pas 2** Creació de la carpeta pel **repositori local**

Cal que **TOTS** els membres del grup crein al seu portatil un **repositori local** a la ruta **```c:\smx2\repos\<cognom1>-<cognom2>-<cognom3>-<cognom4>-a05u```**.

> on:
> **```<cognom1>```** serà el cognom del primer dels alumnes ordenats alfabèticament,
> **```<cognom2>```** serà el cognom del segon dels alumnes ordenats alfabèticament,
> **```<cognom3>```** serà el cognom del tercer dels alumnes ordenats alfabèticament,
> **```<cognom4>```** serà el cognom del quart dels alumnes ordenats alfabèticament (si n'hi ha).

Seguint l'exemple anterior el **repositori local** seria **```c:\smx2\repos\bellavista-martinez-nieto-pardo-a05u```**.

### **Pas 3** Creació del **repositori remot** del grup

**Un dels membres del grup** crearà el **repositori remot** del grup al seu compte de [**github.com**](https://github.com):

* Amb el nom **```<cognom1>-<cognom2>-<cognom3>-<cognom4>-a05u```**
* De **tipus** **```privat```**,
* Sense el fitxer **```README.md```**.

A continuació, i seguint els passos de sembre, vincularà el **repositori remot** del grup amb el seu **repositori local**.

### **Pas 4** Convidar als col·laboradors del **repositori remot**

Un que ja tingui el seu **repositori local** vinculat amb el **repositori remot** del grup:

* convidarà a la resta dels membres i
* convidarà a l'usuari **```joanpardogine```**.

### **Pas 5** Clonació dels col·laboradors del **repositori remot**

**La resta dels membres del grup** clonarà el **repositori remot** del grup amb el **repositori local** del seu portàtil.

Per fer-ho caldrà copiar la URL del **repositori remot** del grup

![a05u-get-url-per-clonar.png](./images/a05u-get-url-per-clonar.png)

I a continuació, des de la finestra de terminal de Visual Studio Code,

![a05u-03-obrir-terminal-vsc.png](./images/a05u-03-obrir-terminal-vsc.png)

Cal executar la comanda de git per **clonar** un repositori.

> # ÉS MOLT IMPORTANT QUE AL FINAL DE LA COMANDA HI HAGI, DESPRÉS DE LA URL, UN ESPAI I UN PUNT.

```
git clone <URL> .
```

Un cop ja teniu clonat en el **repositori local** del vostre portàtil, el **repositori remot** del grup.


Ara ja podeu començar a fer l'activitat!


## Objectiu

L'objectiu d'aquesta activitat és aconseguir que **TOTS** els servidors de **TOTS** alumnes es vegin entre ells. 


## Diagrama de Xarxa de l'activitat

![a05u-diagrama-de-xarxa.png](./images/a05u-diagrama-de-xarxa.png)

## Repartició de les tasques

Un cop que estiguin fets els grups caldrà que a cada grup es reparteixi la següent feina:

A continuació us passo un llistat de algunes de les tasques que cal fer:

- Preparar el switch per connectar els servidors del diferents membres del grup.

- Comprovar del servidor de cada membre del grup:
    * que tingui l'interficie de xarxa ben configurada
    * que tingui l'adreça IP corresponent

- Comprovar que **TOTS** els servidors de **TOTS** els companys es veuen entre sí.

<!-- 
Proposta de configuració del Servidor per Actuar com a **Servidor de DNS Recursiu**

* A la consola DNS, seleccioneu el servidor i feu clic amb el botó dret. Trieu "Propietats".

![Alt text](./images/a05u-04-dns-properties.png)

* Aneu a la pestanya ***Forwarders*** (**Reenviadors**) i marqueu l'opció "Actuar com a servidor DNS".


![Alt text](image.png)

* A la mateixa pestanya, afegeix les adreces IP dels servidors DNS externs (poden ser els de Google, per exemple: 8.8.8.8 i 8.8.4.4).
 -->