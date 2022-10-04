# Binary-Search-Tree-Projesi-www.patika.dev-

Patika - Veri Yapıları ve Algoritmalar Derslerinin Alıştırma Projeleri Kapsamında Yapılmıştır. Binary Search Tree Projesi'dir. [www.patika.dev]


## Binary Search Tree Projesi

 **[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.**

 1. Burada Root Olarak 7 Değerini Seçecek Olursak Aslında Bu Değer Bizim Bir Bakıma İlk Elemanımız Oluyor. Bu ilk elemanı baz alarak diziye eleman ekliyormuş gibi düşünelim.

![1](https://user-images.githubusercontent.com/93604446/193735217-080f31a7-d1ee-4725-91a2-8ecda186831a.PNG)

 2. Ekleme işlemi ise yeni eklenecek eleman 7 sayısından büyükse sağa, küçükse sola doğru eklenerek dallanacaktır.

 3. İlk olarak yukarıda bulunan dizide soldan sağa doğru Binary Search ağacına sırasıyla ekleme yapacağız. Dizinin ilk elemanı bizim root yani ilk elemanımız. 

 4. Dizinin ikinci elamanı olan 5 sayısı ağaç yapımıza eklerken şu soru sorulur: "5 sayısı 7 sayısından büyük mü ?" Cevap "Hayır" olacağından yani küçük olacağından sola yazılır.
 
 ![2](https://user-images.githubusercontent.com/93604446/193735270-816c96e9-d981-44a4-8180-d3ee3fb35ada.PNG)

 5. Dizinin Üçüncü elamanı olan 1 sayısı ağaç yapımıza eklerken şu soru sorulur: "1 sayısı 7 sayısından büyük mü ?" Cevap "Hayır" olur ve bir sonraki solda bulunan elemana geçer. Bir önceki aşamada eklediğimiz 5 sayısına gelir ve aynı soruyu bir daha sorar: "1 sayısı 5 sayısından büyük mü ?" Cevap "Hayır" olacağından ve sorulacak başka eleman olmadığından 1 sayısı 5 sayısının soluna yazılır. 
 
 ![3](https://user-images.githubusercontent.com/93604446/193735288-dce86794-f8bc-43f1-8490-96fbce3819b6.PNG)

 6. Dizinin dördüncü elamanı olan 8 sayısı ağaç yapımıza eklerken şu soru sorulur: "8 sayısı 7 sayısından büyük mü ?" Cevap "Evet" olacağıdan 8 sayısı 7 sayısının sağına yazılır.
 
 ![4](https://user-images.githubusercontent.com/93604446/193735313-f567f2d9-a181-4e3d-ad2e-f2c73a37c305.PNG)

 7. Dizinin beşinci elamanı olan 3 sayısı ağaç yapımıza eklerken 7 sayısından küçük olduğundan solda bulunan bir sonraki elemana geçer. Bir sonraki eleman ise 5 elemanıdır. 3 sayısı 5 sayısından da küçük olduğundan bir sonraki soldaki 1 elemanına geçer ve 3 sayısı 1 sayısından büyük olduğundan sağına yazılır.
 
 ![5](https://user-images.githubusercontent.com/93604446/193735340-93be9cc1-a746-49db-a56c-7974a5d5ffbc.PNG)
 
 8. Dizinin altıncı elamanı olan 6 sayısı 7 sayısından küçük fakat 5 sayısından büyük olduğundan sağ tarafına yazılır.
 
 ![6](https://user-images.githubusercontent.com/93604446/193735359-4dd8ef96-a56f-4394-b271-45ad60cd28b0.PNG)

 9. Dizinin yedinci elamanı olan 0 sayısı 7 sayısından küçük, 5 sayısından küçük ve 1 sayısından küçük olduğu için 1 sayısının soluna yazılır.
 
 ![7](https://user-images.githubusercontent.com/93604446/193735377-3c355560-cb88-479f-986f-f694a0eaf4c2.PNG)

 10. Dizinin sekizinci elamanı olan 9 sayısı 7 sayısından ve 8 sayısından büyük olduğundan 8 sayısının sağına yazılır.
 
 ![8](https://user-images.githubusercontent.com/93604446/193735389-efe2134b-814f-468c-86a2-ffb3478a7674.PNG)

 11. Dizinin dokuzuncu elamanı olan 4 sayısı 7 sayısından ve 5 sayısından küçük fakat 1 sayısından ve 3 sayısından büyük olduğundan 3 sayısının sağına yazılır.
 
 ![9](https://user-images.githubusercontent.com/93604446/193735410-575a3301-6591-46e7-9ea4-e3f0e67ba549.PNG)

 12. Dizinin onuncu elamanı olan 2 sayısı 7 sayısından ve 5 sayısından küçük fakat 1 sayısından büyük ve 3 sayısından küçük olduğundan 3 sayısının soluna yazılır.
 
 ![10](https://user-images.githubusercontent.com/93604446/193735446-d50e86c3-2ea8-44b8-83cd-90e14c96180d.PNG)



 

    
    

