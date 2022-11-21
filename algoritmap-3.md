Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
---------------------------------------------
cevap:

root:7 olsun;

- 7' den küçük rakamlar solda, büyükler sağ tarafta sıralanır
----------------------
 -----------7---------
 ---------------------
 ----------/--\ ------
 ---------------------
 ---------5----8------
 ---------------------
 ------/--\ ------\ -
 ---------------------
 -----1-----6------9---
 ---------------------
 ---/--\ --------------
 ---------------------
 --0----3-------------
 ---------------------
 ------/----\ ---------
 ---------------------
 -----2-------4--------
 ----------------------

 1.aşama da 5  7 den küçük olduğu için sola 

 2.aşama da 1 7 ve 5 den küçük olduğu için 5 ın altına sola 

 3.aşama da 8 7 den büyük olduğu için sağ dalda

 4.aşama da 3 7 den ve 5 den küçük olduğu için sola 1 den büyük olduğu 
     için 1 in sağına yerleşir

 5.aşama 6 7 den küçük sola 5 den büyük 5 in sağına yerleşir

 6.aşama 0 7 den 5 ve 1 den küçük olduğu için sol dalın en altında yer alır

 7.aşama 9 7 den büyük ve 8 den büyük olduğu için en sağda 8 ın sağında 
    yer alır

 8.aşama 4 7 den ve 5 den küçük 1 ve 3 den büyük olduğu için 3 ün sağına yerleşir

 9.aşama 2 7 den ve 5 küçük oluğu için solda 1 den büyük olduğu için sağda 3 den küçük olduğu için ise 3 ün solunda yer alır