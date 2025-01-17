# BitcoinBulmaca
Milyon Dolarlık Bitcoin Bulmacalarını Çözmeye Çalışıyoruz!

Gelişmeleri X'den paylaşıyorum! https://x.com/BitcoinBulmaca

KURULUM:
Kurulum gerekmez. Kodlar Python dilinde yazıldı, pyinstaller ile kolay çalıştırılabilir duruma getirildi. Dosyaları indirip, bir klasöre açın. "bulmaca67-68.exe" dosyasına dıkladığınızda bulmacayı çözmek için çalışmaya başlayacak. 

YÖNTEM:
"bulmaca67-68.exe" dosyasına tıkladığınızda random olarak 14 karaktere sahip bir private key oluşturulur. Bu keyin ilk basamağına sırasıyla "456789abcdef" karakterler("4567" 67 nolu bulmacanın başlangıç ihtimalleri; "89abcdef" ise 68 nolu bulmacanın başlangıç ihtimalleri), ikinci ve üçüncü basamağına ise yine sırasıyla "0123456789abcdef" karakterleri eklenip, 17 karaktere tamamlanır ve her aşamada bulmacanın özelliği olarak sıkıştırılmış bitcoin adresi oluşturulur. Her döngüden sonra 14 karaktere +1 basamak eklenerek sıralı tarama yapılır. 

Aynı anda istediğiniz kadar "bulmaca67-68.exe" çalıştırabilirsiniz. Standart olarak aynı anda üç dosya çalıştırmanız önerilir. Programı her çalıştırdığınızda yeni ve benzersiz bir 14 karakter oluşturur. Bunun için random kütüphanesi kullanılmıştır.

ÖDÜLÜ BULDUĞUNUZDA:
Bulmacayı çözmeniz durumunda ekranda "BİNGOOOOO" şeklinde bir uyarı ile privkey ve adres bilgilerini göreceksiniz. Privkey ve adres bilgileri programın bulunduğu klasöre "BULMACA.txt" adında bir dosya oluşturularak bu dosyaya yazılacaktır. 

Ödül paylaşımı %50 oranında yapılacaktır.
