# Insertion Sort Projesi
 
 [22,27,16,2,18,6] -> Insertion Sort

* Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

* Insertion : Dizi deki elemanları tek tek bakarak küçüğü sola atmak kaydıyla dizinin üzerinde tek tek dolaşma ile yapılır.
* Işlem adımları şu şekilde olacaktır.
*Birinci aşama =
[22,27,16,2,18,6] Dizisinde en küçük sayıyı en başa alır.
[2,22,27,16,18,6]

* ikinci aşamada elemanlara tek tek bakarak devam eder 2,22 den küçük evet 22,27 küçük evet 27,16 dan küçük mü? hayır 16 yı bir önceki konuma getirir,Bu şekilde sürekli kontrol ederek sayının küçükten büyüğe konumlarını düzenler.

2. Big-O gösterimini yazınız.

* [22,27,16,2,18,6] Dizisi içinde n tane elemanı inceler.Bu dizide her elemanı tek tek gezerken Islem maliyeti n+(n-1)+(n-2)+....+1 = (n*n+1)/2 şeklinde hesaplanabilir.
 Sonuç olarak n^2 lik kısım bizim Big-O yu ifade eder.

 3. Time Complexity 
 
* Average case durumu sayımızın ortada olması 
* Worst case durumu sayımızın sonda olma ihtimalini 
* Best case durumu ise aradığımız sayının en başta olması ihtimali olarak değerlendirilebilir.

* [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
- [2,3,5,8,7,9,4,15,6]
- [2,3,5,7,8,9,4,15,6]
- [2,3,5,7,8,4,9,15,6]
- [2,3,4,5,6,7,8,9,15] şeklinde sonlanır.
-patika linkim https://app.patika.dev/zuhuratdady