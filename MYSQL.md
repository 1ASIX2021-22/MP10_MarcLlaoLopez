
## Documentació Instal·lació sistema gestor de base de dades. MySQL

1. El primer que farem serà descarregar i instalar el mysql server, cosa que farem amb la comanda **"sudo apt-get install mysql-server"** i el descomprimim amb la comanda **"dpkg -L mysql-server"** 

![](Imatges/1.png)
![](Imatges/2.png)

2. A l`hora d'accedir al mysql ens demanarà un usuari y una contrasenya, les cuals les conseguirem anant a un fitxer que crea mysql per defecte que es diu **debian.cnf**, a l´hora d'iniciar ara el mysql el iniciarem amb el usuari que es troba en aquest fitxer i la contrasenya corresponent

![](Imatges/3.png)
![](Imatges/4.png)

3. Lo primer que farem una vegada instal·lat es crear una base de dades

![](Imatges/5.png)

I dins d'aquesta crearem una taula

![](Imatges/6.png)

Per a instal.lar el mysql workbench he tingut que descarregar els repositoris, els quals els he instal·lat amb **"sudo apt install ./mysql-apt-config_0.8.22-1_all.deb"**

Seguit d'aixó he fet un update i ja si que si he instal·lat l'aplicació amb **"sudo apt install mysql-workbench-community"**

![](Imatges/7.png)

4. Editem la Local Instance, el que farem serà modificar el usuari i la seua contrasenya

![](Imatges/8.png)

5. Altres eines que podem fer us es el PhpStorm

![](Imatges/9.png)

En aquest tenim que fer el matiex que en la anterior aplicació, anirem al aparta de mysql

![](Imatges/11.png)

Instal·larem els ultims drivers si no els tenim

![](Imatges/12.png)

I configurem el usuari i contrasenya per defecte

![](Imatges/10.png)

I veurem que tenim access

![](Imatges/13.png)

Una vegada fet aixó tindrem totes les taules carregades correctament

![](Imatges/14.png)

Anem i creem una nova tasca, la cual anomerarem **tasca 1**

![](Imatges/15.png)

Per a practicar una mica més en PDO ens anem a la carpeta que es mostrarà acontinuació

![](Imatges/16.png)

Així que dins de la carpeta que hem creat farem us de la comanda **phpstorm .**

I si ho hem fet be se mos obrirà el projecte

![](Imatges/17.png)

Crearem un fitxer anomenat **index.php** i fem una proba amb un Hola mon!

![](Imatges/18.png)
![](Imatges/19.png)


Modificarem el fitxer anterior de tal manera que ens puguesem connectar amb el usuari i la contrasenya, i també le afegirem els ultims recurso per a que sigui un PDO

![](Imatges/20.png)
