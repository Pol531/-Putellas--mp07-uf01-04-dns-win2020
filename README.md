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

**Pas4:**

Per verificar que funciona, hem fet servir les següents comandes al cmd: 

- nslookup
- set type=CNAME
- set type=A
- I posem la direcció que volguem:

![image](https://github.com/Pol531/-Putellas--mp07-uf01-04-dns-win2020/assets/145341969/21f2929c-69a4-432f-a317-86b769c580f2)

![image](https://github.com/Pol531/-Putellas--mp07-uf01-04-dns-win2020/assets/145341969/88f1ff52-8b06-4b6a-82f3-f61f4a318c5d)

![image](https://github.com/Pol531/-Putellas--mp07-uf01-04-dns-win2020/assets/145341969/c06abddb-9f0e-492a-b43b-8b1eade2fd95)

![image](https://github.com/Pol531/-Putellas--mp07-uf01-04-dns-win2020/assets/145341969/e479ac16-b9f3-4369-8666-924b797aa02a)

![image](https://github.com/Pol531/-Putellas--mp07-uf01-04-dns-win2020/assets/145341969/58391160-e5f4-44c4-a7b1-b627333ab39d)

![image](https://github.com/Pol531/-Putellas--mp07-uf01-04-dns-win2020/assets/145341969/9f693ab0-7c23-43a5-aac4-13702f014331)

![image](https://github.com/Pol531/-Putellas--mp07-uf01-04-dns-win2020/assets/145341969/c0725523-c5a7-4483-bfc9-fb00d93569d2)

![image](https://github.com/Pol531/-Putellas--mp07-uf01-04-dns-win2020/assets/145341969/17c15a93-4754-4289-8051-fc05b33c0d33)

![image](https://github.com/Pol531/-Putellas--mp07-uf01-04-dns-win2020/assets/145341969/034df095-040a-47b0-bed9-a4a5d2653f8a)

![image](https://github.com/Pol531/-Putellas--mp07-uf01-04-dns-win2020/assets/145341969/133876c3-9776-4b1a-9917-9ab386fc6c16)

![image](https://github.com/Pol531/-Putellas--mp07-uf01-04-dns-win2020/assets/145341969/e3d588f0-699d-4d1b-b79e-1e31006208cb)

![image](https://github.com/Pol531/-Putellas--mp07-uf01-04-dns-win2020/assets/145341969/4c849c2c-487e-4796-908c-fd1f2b6b5016)

![image](https://github.com/Pol531/-Putellas--mp07-uf01-04-dns-win2020/assets/145341969/21e05dec-cba1-42ac-9c2f-4133625a13a2)

![image](https://github.com/Pol531/-Putellas--mp07-uf01-04-dns-win2020/assets/145341969/93b9656c-ad3e-4147-a4f1-aba902bb507e)
