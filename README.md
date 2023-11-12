**Activitat 4: Creació d'una nova zona de DNS en un servidor Windows 2020 Server**

**Pas1:**
He creat els registres tipus A, seguint el criteri corresponent:

|Nom**|**Adreça IP**|
|---|---|
|**Pol_Putellas**|**80.20.11.6**|
|**Nil_Putellas**|**80.20.11.6**|
|**Aleix_Gomez**|**80.20.11.6**|
|**Berta_Gallego**|**80.20.11.6**|
|**Bruno_Chicca**|**80.20.11.6**|
|**Emma_Ferrer**|**80.20.11.6**|
|**Eric_Alcaraz**|**80.20.11.6**|
|**Eric_Cayetano**|**80.20.11.6**|
|**Jordi_Fernandez**|**80.20.11.6**|
|**Laura_Hernandez**|**80.20.11.6**|
|**Luis_Dueñas**|**80.20.11.6**|
|**Marc_Capel**|**80.20.11.6**|
|**Oriol_Santamaria**|**80.20.11.6**|
|**Pau_Andres**|**80.20.11.6**|
|**Roger_Legido**|**80.20.11.6**|
![image](https://github.com/Pol531/-Putellas--mp07-uf01-04-dns-win2020/assets/145341969/5c6ac1c9-8de2-4c94-9677-328d06e60d3c)

**Pas2:**
A continuació, he posat els registres CNAME:

|**CNAME**|Nom |
|---|---|
|**jomateix**|**Pol_Putellas**|
|**germà**|**Nil_Putellas**|
|**Amic1**|**Aleix_Gomez**|
|**Amic2**|**Berta_Gallego**|
|**Amic3**|**Bruno_Chicca**|
|**Amic4**|**Emma_Ferrer**|
|**Amic5**|**Eric_Alcaraz**|
|**Amic6**|**Eric_Cayetano**|
|**Amic7**|**Jordi_Fernandez**|
|**Amic8**|**Laura_Hernandez**|
|**Amic9**|**Luis_Dueñas**|
|**Amic10**|**Marc_Capel**|
|**Amic11**|**Oriol_Santamaria**|
|**Amic12**|**Pau_Andres**|
|**Amic13**|**Roger_Legido**|
![image](https://github.com/Pol531/-Putellas--mp07-uf01-04-dns-win2020/assets/145341969/422d32c5-3407-47ee-8d0b-9ca07053011d)

**Pas3:**
|Domini|Nom|
|---|---|
|**correuputellas.cat**|**jomateix.putellas.cat**|

![image](https://github.com/Pol531/-Putellas--mp07-uf01-04-dns-win2020/assets/145341969/008eebcb-8b64-4181-a27c-26bd8a2b993c)
(dins de cada carpeta està el MX de cada persona)
![image](https://github.com/Pol531/-Putellas--mp07-uf01-04-dns-win2020/assets/145341969/ce4e37bf-e6af-48d4-a0a3-64e60c394792)




