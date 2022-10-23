Patika.dev Veri Yapıları ve Algoritmalar Proje Ödevleri 1
Inserting Sort Projesi 
                         İnsertion Sort Project
Sorting algoritmaları arasında en basitlerindendir.
Mevcut urruyı en baştan sona kadar inceler ve en küçük elemanı bulana kadar bu işleme devam eder.
En küçük sayıyı bulunca en başa yazarız.
En baştaki sayıyı en küçük sayının yerine yaz.
İkinci en küçük sayıyı bul ve ikinci sıradaki sayının yerine yaz.
Eğer o sayı doğru yerdeyse ona dokunma. Bir sonraminden devam et.
Bu sorting yöntemiyle n tane işlem yapılmış olur. 
Bu işlemlerin toplamı (n2+n)/2 oluır.
Bu toplamın da Big(O) Notationu n2 olur.
Soru 1
(22, 27. 16, 2, 18, 6) 
Aşamaları;
1* (2, 27, 16, 22, 18, 6)
2* (2, 6, 16, 22, 18, 27)
3* (2, 6, 16, 18, 22, 27, )
Soru 2
Bu sorting sisteminde daha önce de ifade ettiğim üzere n den son sayıya kadar n, (n-1), (n-2),......(1) şeklinde işlem yaparız. Bu işlemlerin toplamı da (n2+n)/2 olur. Bu toplamın Big (O) notation gösterimi O(n) dir.
Soru 3 
Dizi sıralandıktan sonra 18 sayısı dizinin ne başında ne sonunda değildir, ortasındadır. Bu sebeple 18 sayısı awarage case e girer. 
Diğer Soru: 
(7, 3, 5, 8, 2, 9, 4, 15, 6)
Aşamaları;
1* (2, 3, 5, 8, 7, 9, 4, 15, 6)
2* (2, 3, 4, 8, 7, 9, 5, 15, 6)
3* (2, 3, 4, 5, 7, 9, 8, 15, 6)
4* (2, 3, 4, 5, 6, 9, 8, 15, 7) ilk 4 aşaması bu şekilde olur.
