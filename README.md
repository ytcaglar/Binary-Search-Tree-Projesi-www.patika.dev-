# Binary-Search-Tree-Projesi-www.patika.dev-

Patika - Veri Yapıları ve Algoritmalar Derslerinin Alıştırma Projeleri Kapsamında Yapılmıştır. Binary Search Tree Projesi'dir. [www.patika.dev]


## Binary Search Tree Projesi

 **[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.**

 1. Burada Root Olarak 7 Değerini Seçecek Olursak Aslında Bu Değer Bizim Bir Bakıma İlk Elemanımız Oluyor. Bu ilk elemanı baz alarak diziye eleman ekliyormuş gibi düşünelim.

 2. Ekleme işlemi ise yeni eklenecek eleman 7 sayısından büyükse sağa, küçükse sola doğru eklenerek dallanacaktır.

 3. İlk olarak yukarıda bulunan dizide soldan sağa doğru Binary Search ağacına sırasıyla ekleme yapacağız. Dizinin ilk elemanı bizim root yani ilk elemanımız. 

 4. Dizinin ikinci elamanı olan 5 sayısı ağaç yapımıza eklerken şu soru sorulur: "5 sayısı 7 sayısından büyük mü ?" Cevap "Hayır" olacağından yani küçük olacağından sola yazılır.

 5. Dizinin Üçüncü elamanı olan 1 sayısı ağaç yapımıza eklerken şu soru sorulur: "1 sayısı 7 sayısından büyük mü ?" Cevap "Hayır" olur ve bir sonraki solda bulunan elemana geçer. Bir önceki aşamada eklediğimiz 5 sayısına gelir ve aynı soruyu bir daha sorar: "1 sayısı 5 sayısından büyük mü ?" Cevap "Hayır" olacağından ve sorulacak başka eleman olmadığından 1 sayısı 5 sayısının soluna yazılır. 

 6. Dizinin dördüncü elamanı olan 8 sayısı ağaç yapımıza eklerken şu soru sorulur: "8 sayısı 7 sayısından büyük mü ?" Cevap "Evet" olacağıdan 8 sayısı 7 sayısının sağına yazılır.

 7. Dizinin beşinci elamanı olan 3 sayısı ağaç yapımıza eklerken 7 sayısından küçük olduğundan solda bulunan bir sonraki elemana geçer. Bir sonraki eleman ise 5 elemanıdır. 3 sayısı 5 sayısından da küçük olduğundan bir sonraki soldaki 1 elemanına geçer ve 3 sayısı 1 sayısından büyük olduğundan sağına yazılır.
 
 8. Dizinin altıncı elamanı olan 6 sayısı 7 sayısından küçük fakat 5 sayısından büyük olduğundan sağ tarafına yazılır.

 9. Dizinin yedinci elamanı olan 0 sayısı 7 sayısından küçük, 5 sayısından küçük ve 1 sayısından küçük olduğu için 1 sayısının soluna yazılır.

 10. Dizinin sekizinci elamanı olan 9 sayısı 7 sayısından ve 8 sayısından büyük olduğundan 8 sayısının sağına yazılır.

 11. Dizinin dokuzuncu elamanı olan 4 sayısı 7 sayısından ve 5 sayısından küçük fakat 1 sayısından ve 3 sayısından büyük olduğundan 3 sayısının sağına yazılır.
 
 12. Dizinin onuncu elamanı olan 2 sayısı 7 sayısından ve 5 sayısından küçük fakat 1 sayısından büyük ve 3 sayısından küçük olduğundan 3 sayısının soluna yazılır.


 

    
    

