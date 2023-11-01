# Tutorial github

 - Pentru descarcare pe windows:
   - https://git-scm.com/downloads

 - Pentru descarcare pe linux(ubuntu) scrieti in terminal:
   - sudo apt install git

## Comenzi de baza:

In continuare comenzile pentru linux(terminal) si windows(git bash) sunt comune.
- ls -> pentru a vedea toate fisierele si folderele din locatia curenta
- pwd -> pentru a vedea calea absoluta din locatia curenta
- touch exemplu.txt -> creare fisier exemplu.txt(inlocuiti exemplu.txt cu fisierul pe care doriti sa il creati)
- mkdir exemplu -> creare folder cu numele exemplu
- cd exemplu -> pentru a schimba locatia curenta si a intra in folder-ul exemplu

## Pasii pentru incarcarea laboratorului

- Pasul 1 -> Intrati pe link-ul de la laborator
<p align="center">
  <img src="https://github.com/Laborator-POO-2022-2023/Tutorial/blob/main/1.png" />
</p>

- Pasul 2.0 -> Asteptati pana cand se creeaza repository-ul apoi dati refresh la pagina
<p align="center">
  <img src="https://github.com/Laborator-POO-2021/Tutorial-upload/blob/master/pasul2.0.png" />
</p>

- Pasul 2.1 -> Accesati link-ul de la repository
<p align="center">
  <img src="https://github.com/Laborator-POO-2021/Tutorial-upload/blob/master/pasul2.png" />
</p>

- Pasul 2.2 -> Schimbati-va numele repository-ului de la Settings
   - <b>Formatul va fi laborator-nr-Grupa-nume-prenume, exemplu: laborator-1-322AB-Trifu-Marius</b>

<p align="center">
  <img src="https://github.com/Laborator-POO-2022-2023/Tutorial/blob/main/5.png" />
</p>

- Pasul 3 -> La unul din pasii urmatori veti avea nevoie de link-ul din poza
<p align="center">
  <img src="https://github.com/Laborator-POO-2021/Tutorial-upload/blob/master/pasul3.png" />
</p>

- Pasul 4 -> Deschideti folder-ul de pe calculatorul vostru si dati click dreapta + Git bash here
<p align="center">
  <img src="https://github.com/Laborator-POO-2021/Tutorial-upload/blob/master/pasul4.png" />
</p>

- Pasul 5 -> Scrieti comanda: git init
<p align="center">
  <img src="https://github.com/Laborator-POO-2021/Tutorial-upload/blob/master/pasul5.png" />
</p>

- Pasul 6 -> Scrieti comanda: git remote add origin LINK(de la pasul 3)
<p align="center">
  <img src="https://github.com/Laborator-POO-2021/Tutorial-upload/blob/master/pasul6.png" />
</p>

- Pasul 7 -> Scrieti comanda: git add .
<p align="center">
  <img src="https://github.com/Laborator-POO-2021/Tutorial-upload/blob/master/pasul7.png" />
</p>

- Pasul 8 -> Scrieti comanda: git config --global user.name "Numele vostru"
<p align="center">
  <img src="https://github.com/Laborator-POO-2021/Tutorial-upload/blob/master/pasul8.png" />
</p>

- Pasul 9 -> Scrieti comanda: git config --global user.email "email cont github"
<p align="center">
  <img src="https://github.com/Laborator-POO-2021/Tutorial-upload/blob/master/pasul9.png" />
</p>

- Pasul 10 -> Scrieti comanda: git commit -m "mesaj"
<p align="center">
  <img src="https://github.com/Laborator-POO-2021/Tutorial-upload/blob/master/pasul10.png" />
</p>

- Pasul 11 -> Scrieti comanda: git push -u origin master
<p align="center">
  <img src="https://github.com/Laborator-POO-2021/Tutorial-upload/blob/master/pasul11.png" />
</p>

- Pasul 12 -> Dati un refresh la pagina din browser
<p align="center">
  <img src="https://github.com/Laborator-POO-2021/Tutorial-upload/blob/master/pasul12.png" />
</p>

- Pasul 13 -> O sa va apara fisierele pentru laborator
<p align="center">
  <img src="https://github.com/Laborator-POO-2021/Tutorial-upload/blob/master/pasul13.png" />
</p>

## Modificare laborator incarcat

- Scrieti comanda: git status
<p align="center">
  <img src="https://github.com/Laborator-POO-2021/Tutorial-upload/blob/master/pas1.png" />
</p>

- Ce este scris cu rosu sunt fisierele modificate
<p align="center">
  <img src="https://github.com/Laborator-POO-2021/Tutorial-upload/blob/master/pas2.png" />
</p>

- Scrieti comanda: git add .
<p align="center">
  <img src="https://github.com/Laborator-POO-2021/Tutorial-upload/blob/master/pas3.png" />
</p>

- Scrieti comanda: git commit -m "mesaj"
<p align="center">
  <img src="https://github.com/Laborator-POO-2021/Tutorial-upload/blob/master/pas4.png" />
</p>

- Scrieti comanda: git push origin master
<p align="center">
  <img src="https://github.com/Laborator-POO-2021/Tutorial-upload/blob/master/pas5.png" />
</p>

- Intoarceti-va in browser si dati un refresh la pagina, astfel o sa vedeti modificarile
<p align="center">
  <img src="https://github.com/Laborator-POO-2021/Tutorial-upload/blob/master/pas6.png" />
</p>

## Extra (optional)

**Cum sa adaugati cheia de ssh**

Rulati comanda:
- ssh-keygen\
Apoi in folder-ul .ssh din folder-ul principal al userului vostru (/home/marius.trifu/ pt linux) si C:\Users\marius.trifu sau /c/Users/marius.trifu pentru Windows.
- cd\
sau
- cd ~\
Pentru a intra in folder-ul .ssh dati:
- cd .ssh
- ls # pentru a vedea continutul, aici ar trebui sa aveti fisierele id_rsa si id_rsa.pub\
Fisierul id_rsa contine cheia voastra privata(niciodata sa nu o dati la nimeni) si fisierul id_rsa.pub contine cheia publica pe care o puteti da oricui.
- cat id_rsa.pub # ca sa va afiseze continutul fisierului
- copiati intreg continutul fisierului id_rsa.pub
- intrati pe site-ul github, va logati si urmariti pasii de mai jos

<p><b>Intrati la setari in colt dreapta sus</b></p>

<p align="center">
  <img src="https://github.com/Laborator-POO-2021/Tutorial-upload/blob/master/Screenshot_4.png" />
</p>
<p><b>Selectati SSH and GPG keys</b></p>

<p align="center">
  <img src="https://github.com/Laborator-POO-2021/Tutorial-upload/blob/master/Screenshot_5.png" />
</p>
<p><b>Selectati New SSH key</b></p>

<p align="center">
  <img src="https://github.com/Laborator-POO-2021/Tutorial-upload/blob/master/Screenshot_7.png" />
</p>
<p><b>Introduceti datele din fisierul id_rsa.pub si un titlu</b></p>

<p align="center">
  <img src="https://github.com/Laborator-POO-2021/Tutorial-upload/blob/master/Screenshot_6.png" />
</p>
