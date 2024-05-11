# FrogGame
This is a frog game || for exercise


# Taş Oyunu
Bu oyun, bir taş oyunu. 
Oyunda amacımız, belirli kurallar çerçevesinde taşların konumunu değiştirerek hedefe ulaşmak.


# Algoritma
Öncelikle, oyun tahtası elimizde 7 adet hücreden oluşuyor. Bu hücrelerin her birinde ya 'B' (mavi) ya da 'G' (yeşil) bir taş var ya da taş olmayan bir boşluk var ('-'). Oyunun amacı, taşların konumunu değiştirerek taşların sıralamasını tersine çevirip (mavi taşlar solda, yeşil taşlar sağda olacak şekilde) hedefe ulaşmak.

Oyunda sıra bizde olduğunda, her zaman 7'den küçük bir sayı girmemiz gerekiyor. Bu, tahtanın indexlerini temsil ediyor. Ardından, seçtiğimiz hücrede taş var mı yok mu kontrol ediyoruz. Eğer seçtiğimiz hücre boşsa, geçersiz bir hamle yapmış oluyoruz. Ayrıca, çıkmak için 'q' tuşunu kullanabiliriz.

Eğer seçtiğimiz hücrede taş varsa, oyunun kurallarına göre o taşı farklı bir hücreye taşıyabiliriz. Örneğin, eğer mavi taşsa, sağa doğru (index artar şekilde) bir veya iki hücre ileri taşıyabiliriz. Eğer yeşil taşsa, sola doğru (index azalır şekilde) bir veya iki hücre ileri taşıyabiliriz.

Oyunun sonunda, taşların sıralamasını tersine çevirip kazanıyoruz. Yani, mavi taşlar solda, yeşil taşlar sağda olacak şekilde taşların konumunu değiştirmemiz gerekiyor.





