# Veri-Yapilari-ve-Algoritmalar
 "Veri Yapıları ve Algoritmalar" dersinin ödevlerini içermektedir
---
* GitHub: https://github.com/beyzaozdin
* Linkedin: https://www.linkedin.com/in/beyza-nur-%C3%B6zdin-391855217/
* Patika: https://academy.patika.dev/profile
---
# **Proje 1**
## ***Soru 1***
***
a) [22,27,16,2,18,6] dizisini <span style="color: red;">Insertion Sort </span>  algoritmasına göre aşamalarını yazınız.

b) <span style="color: red;">Big-O</span> gösterimini yapınız.

c)<span style="color: red;"> Time Complexity:</span>  Dizi sıralandıktan sonra 18 sayısı aşşağıdaki caselerden hangisinin kapsamına girer? 

1. Average Case
2. Worst Case
3. Best Case

***
***Cevap***

a) 
1. [**22**,27,16,2,18,6]  (ilk eleman sabitlenir.)
    
   - Sıralanmış bölüm: [22] 

   - Sıralanmamış bölüm:[27,16,2,18,6]
2. [22,**27**,16,2,18,6] (ikinci eleman karşılaştırılıp,sıralandırılır.) 
  
    - Sıralanmış Bölüm:[22,27] 
    - Sıralanmamış bölüm:[16,2,18,6]
3. [16,22,27,2,18,6]  (sıradaki eleman karşılaştırılıp,sıralandırılır.)
    -  Sıralanmış Bölüm:[16,22,27] 
    -  Sıralanmamış bölüm:[2,18,6]
4. [2,16,22,27,18,6]
    -  Sıralanmış Bölüm: [2,16,22,27] 
    -  Sıralanmamış Bölüm: [18,6]
5. [2,16,18,22,27,6]
    -  Sıralanmış Bölüm: [2,16,18,22,27] 
    -  Sıralanmamış Bölüm:[6]
6. [2,6,16,18,22,27]
   - Sıralanmış Bölüm:[2,6,16,18,22,27] 
  
b) O (n<sup>2</sup>) 
> - n + (n-1) + (n-2)+ ...
> = n*(n+1)\2 = (n<sup>2</sup> + n) \2 

c) Average Case
 
---
## ***Soru 2***
[7,3,5,8,2,9,4,15,16] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

---
***Cevap***

1. [2,3,5,8,7,9,4,15,16]
   - En küçük elemanı bul ve yer değiştir.

2. [2,3,5,8,7,9,4,15,16]
3. [2,3,4,8,7,9,5,15,16]
4. [2,3,4,5,7,9,8,15,16]



