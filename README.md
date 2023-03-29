# patikadevSelection-Sort-Projesi
Insersiton Sort işleminin ne olduğundan bahsedelim
  sayılar bütününü sıralamak istiyorsam en küçüğü bulur en baştakiyle yerini değiştiririm. bu bir sonraki aşamalarda da aynı devam eder.
worst case analiz etmek istersek n tane değerimin hepsini kontrol ettiğimi düşünürsem ikinci aşamada n-1 işlem yani n*(n+1/2) big o notation ile n^2 olarak
ekstra yer kaplamaz. 
1) Verilen dizi, insertion sort kullanılarak sıralanacak. İlk adımda, 22 sayısı yalnızca bir elemandan oluşan bir alt dizi olarak ele alınır ve sıralı olarak kabul edilir.
Daha sonra

[22,27,16,2,18,6] -> [2,27,16,22,18,6]

[2,27,16,22,18,6] -> [2,6,16,22,18,27]

[2,6,16,22,18,27] -> [2,6,16,22,18,27]

[2,6,16,22,18,27] -> [2,6,16,18,22,27]


2) Big-O-Notation
  Big-O gösterimi: En kötü durumda (dizi tamamen ters sıralı olduğunda) insertion sort'un çalışma zamanı O(n^2)'dir.
  
3)Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
  18 sayısı, sıralanmış dizide altıncı elemandır, bu nedenle aranan sayı ortalarda bulunmaktadır ve ortalama durum olarak kabul edilir.
  
4)[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

Verilen diziyi Selection Sort kullanarak sıralayacak olursak, ilk adımda dizinin en küçük elemanını bulup ilk elemanla yer değiştiririz. İkinci adımda, dizinin kalan kısmında en küçük elemanı bulup ikinci elemanla yer değiştiririz ve bu şekilde devam ederiz. İlk 4 adım şu şekildedir:

[7, 3, 5, 8, 2, 9, 4, 15, 6] -> En küçük eleman 2, ilk elemanla yer değiştirilir

[2, 3, 5, 8, 7, 9, 4, 15, 6] -> En küçük eleman 3, ikinci elemanla yer değiştirilir

[2, 3, 4, 8, 7, 9, 5, 15, 6] -> En küçük eleman 5, üçüncü elemanla yer değiştirilir

[2, 3, 4, 5, 7, 9, 8, 15, 6] -> En küçük eleman 6, dördüncü elemanla yer değiştirilir


Bu şekilde devam edilerek dizi tamamen sıralanır.
