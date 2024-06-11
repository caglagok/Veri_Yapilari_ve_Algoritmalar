# Veri_Yapilari_ve_Algoritmalar

Binary Search Tree (BST) - İkili Arama Ağacı

Tanım: İkili arama ağacı (BST), her düğümün iki alt düğüme (sol ve sağ) sahip olduğu, belirli bir düzen içinde sıralanmış bir veri yapısıdır.

Özellikler:
-Her düğümün değeri, sol alt düğümdeki tüm değerlerden büyük ve sağ alt düğümdeki tüm değerlerden küçüktür.
-Bu özellik, ağaçta hızlı arama, ekleme ve silme işlemlerine olanak tanır.

Kullanım Alanları:
-Veritabanları
-Arama motorları
-Sıralı veri saklama


Merge Sort - Birleştirme Sıralaması

Tanım: Merge Sort, "böl ve fethet" (divide and conquer) prensibine dayanan bir sıralama algoritmasıdır. Dizi ikiye bölünür, her iki yarı ayrı ayrı sıralanır ve ardından birleştirilir.

Adımlar:
Dizi ortadan ikiye bölünür.
Her iki alt dizi ayrı ayrı merge sort ile sıralanır.
İki sıralı alt dizi birleştirilir.

Özellikler:
-Zaman karmaşıklığı: O(n log n)
-Kararlı bir sıralama algoritmasıdır, yani eşit elemanların relative sırası korunur.
-Bellek kullanımı: O(n) ek bellek kullanır.

Kullanım Alanları:
-Büyük veri setlerinin sıralanması
-Kararlı sıralamanın önemli olduğu durumlar


Selection Sort - Seçme Sıralaması
Tanım: Selection Sort, bir listeyi sıralamak için sürekli olarak en küçük (veya en büyük) öğeyi seçip listenin sıralanmamış kısmının başına yerleştirerek çalışan basit bir sıralama algoritmasıdır.
Adımlar:
Sıralanmamış listedeki en küçük öğe bulunur.
Bu öğe listenin başına taşınır.
Liste iki kısma ayrılır: sıralı ve sıralanmamış.
Sıralanmamış kısımda bu işlem tekrarlanır.
Özellikler:
*Zaman karmaşıklığı: O(n²)
*Bellek kullanımı: O(1), ek bellek gerektirmez.
*Kararsız bir sıralama algoritmasıdır.
Kullanım Alanları:
*Küçük veri setlerinin sıralanması
*Basitlik ve kolaylık gerektiren durumlar
