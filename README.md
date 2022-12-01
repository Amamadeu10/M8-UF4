# M8-UF4
## Instal·lació MOODLE
# Primer accedirem al servidor mitjançant el SSH

<img width="680" alt="image" src="https://user-images.githubusercontent.com/100061627/203821999-d19142c5-f9c0-44e6-8f34-6984ab1769af.png">

# Instal·lacio Apache2

<img width="820" alt="image" src="https://user-images.githubusercontent.com/100061627/203822282-79dbe49a-25fb-4e19-b402-48dfe0165bd5.png">

# Instal·lar MariaDB

<img width="845" alt="image" src="https://user-images.githubusercontent.com/100061627/203825103-10dfb40a-1ff5-46f1-9292-2f756e8c5fb8.png">

<img width="647" alt="image" src="https://user-images.githubusercontent.com/100061627/203825338-079445b5-8f89-4ebd-89dd-64f870c7ed11.png">

<img width="670" alt="image" src="https://user-images.githubusercontent.com/100061627/203825421-d260cce9-2d51-40af-aaed-5fc3c9f28e7f.png">

# Instal·lació PHP 7.3

<img width="857" alt="image" src="https://user-images.githubusercontent.com/100061627/205078489-ce99809e-96b1-496a-aba5-7ffac513e365.png">

<img width="608" alt="image" src="https://user-images.githubusercontent.com/100061627/205078660-a36aaf2c-8a47-48fc-b809-ddd0bd7d1c67.png">


<img width="858" alt="image" src="https://user-images.githubusercontent.com/100061627/203827835-c52680dc-cbc0-4b3c-bb69-3baabb5556cc.png">

## Fem un restart a Apache2

<img width="843" alt="image" src="https://user-images.githubusercontent.com/100061627/203828175-8c269d49-fc58-4de1-8606-ee32991bf1a7.png">

## Entrem a l'arxiu de Index.php



<img width="661" alt="image" src="https://user-images.githubusercontent.com/100061627/203828413-4b461e3a-ab10-4328-93a2-514c3b5c0f7d.png">

## Comprovar el localhost

![image](https://user-images.githubusercontent.com/100061627/203860529-ce9bd0b9-5175-4060-b7ec-a830a69f6036.png)

Borrar fitxer index.php i ja tenim LAMP instal·lat.

# Ara descarreguem Moodle

## Aquí vaig tindre el problema que al seleccionar la URL superior no em descarregava perquè no era un enllaç de descàrrega, es té que seleccionar la descàrrega manual.

<img width="766" alt="image" src="https://user-images.githubusercontent.com/100061627/205075844-de3b7d11-ace5-4012-9078-236ae8c64eb2.png">


<img width="824" alt="image" src="https://user-images.githubusercontent.com/100061627/205078003-fe86b0cf-8fe9-4a33-b0d0-f7fbea85f226.png">

# Ara configurarem el Moodle.

<img width="661" alt="image" src="https://user-images.githubusercontent.com/100061627/205080159-6212f595-1f5e-4afb-b159-2b3be48a3939.png">

<img width="590" alt="image" src="https://user-images.githubusercontent.com/100061627/205080272-4a1ce08b-1e6d-4d36-a105-18d74c48993b.png">

<img width="579" alt="image" src="https://user-images.githubusercontent.com/100061627/205080805-d9f8f83c-ce17-4168-950b-7fec3c4426b2.png">

<img width="856" alt="image" src="https://user-images.githubusercontent.com/100061627/205080975-3c8c745d-4038-4d5c-991d-c16223febbbd.png">

<img width="854" alt="image" src="https://user-images.githubusercontent.com/100061627/205081452-bdaca30b-475f-41f1-8af8-fc2a76da20e0.png">

## Un cop trobada, descarregada e instal·lada la versió CURL per a PHP, reiniciem Apache2 i comprovem que està OK l'estat.


<img width="854" alt="image" src="https://user-images.githubusercontent.com/100061627/205081656-735afeb7-aa2d-4db4-80e7-9939359fcdf7.png">

## Si tot ha anat bé en sortirà la pàgina de confirmació de rutes, en direcció de dades hem de ficar /home/moodledata.


<img width="693" alt="image" src="https://user-images.githubusercontent.com/100061627/205083148-7def41f5-a4b0-4be4-8777-fa4d0d997f2b.png">


Ara seleccionem quina base de dades utilitzar, en el nostre cas a l'utilitzar MariaDB és la que seleccionem.


<img width="647" alt="image" src="https://user-images.githubusercontent.com/100061627/205084479-aff1cb39-fb18-4d12-82b6-b8d233154775.png">


<img width="642" alt="image" src="https://user-images.githubusercontent.com/100061627/205085062-8a2b8d93-f456-4893-96d0-eead51c1b9a5.png">

## A la següent pàgina ens dona el següent error, ara hem d'instal·lar unes llibreries del PHP.



<img width="618" alt="image" src="https://user-images.githubusercontent.com/100061627/205086701-2f460d59-ba60-483e-a922-979b7c6b9800.png">


<img width="693" alt="image" src="https://user-images.githubusercontent.com/100061627/205087299-6bb2b6e5-6918-404d-9047-2ede6cccaf74.png">

<img width="634" alt="image" src="https://user-images.githubusercontent.com/100061627/205088709-7d858c04-5e92-4ad7-a13c-280d11c2e913.png">

## Ara instal·lem les extensions que ens falta de PHP.

<img width="761" alt="image" src="https://user-images.githubusercontent.com/100061627/205091844-32207d5f-fb36-4caf-9126-a47f41245a1c.png">

## Reiniciem Apache2 i comprovem l'estat, segueix en la mateixa pantalla donat que també he d'instal·lar l'extensió de PHP.xml
## Un cop instal·lat ja funciona la pàgina.


<img width="657" alt="image" src="https://user-images.githubusercontent.com/100061627/205094105-8bb8d454-6bb8-4717-b6b0-18192551f287.png">



<img width="611" alt="image" src="https://user-images.githubusercontent.com/100061627/205094508-d06b4e29-0087-4163-985d-1f0f0fdc801e.png">

## Ara donem a següent i Moodle farà comprovacions per comprovar que tot ha anat bé.

<img width="622" alt="image" src="https://user-images.githubusercontent.com/100061627/205095249-87947e56-2bb0-4841-a798-f670a1b24f4b.png"> 

## Ara configurem el compte d'administrador.

<img width="700" alt="image" src="https://user-images.githubusercontent.com/100061627/205096487-9d70c6b5-6b2c-4cf1-bc36-a3b176987381.png">


























