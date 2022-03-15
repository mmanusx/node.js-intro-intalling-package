# node.js-intro-intalling-package
node.js intro, installing package

: Terminalden/prompt dan bir programın yüklü olup olmadığını kontrol etmek.
Ör: node, >> node --version
>> node index.js // index.js i node ile aç demek // wow sonuç harika js kodu terminale yazsı 
The Node REPL: Read Evalueation Print // kodların satır satır terminale yazılmasını sağlıyor
:Node u yüklediğimizde node repl ı da yüklemiş oluyoruz, terminalde > node komutunu çalıştırdığımızda terminalin içinde açılıyor
: örnek: con la başlayan funk bulmak için con + tab + tab
 REPL dan çıkmak için, .exit yada ctr + c *2 defa basıla bilir ! bu yalnızca repl dan çıkmak için
 clear console : >clear
 Node.js ile birlikte bir çok native modüle geliyor
Node native modülleri import etmek:
const fs = require('fs/promises');
const: var gibi bir değişken tanımlama yön. Ancak constant sonradan değiştirilemez
const, sadece es versiyon 6 da var uyarı   verirse yorum satırı olarak aşağıdaki satırı eklememiz gerekiyor.
//jshint esversion:6 
fs= file sisteme refere edecek bir değişken olarak atadık
//jshint esversion:6
const fs = require('fs');

fs.copyFileSync("file1.txt", "file2.txt");

#npm: node package manager, external package manager, npm, paketleri kendi projene eklemeni sağlıyor
Çalıştırma: > npm init // komutu çalıştıktan sonra bir dizi bilgi alıyor ve sonunda package.json dosyası oluşturuyor // daha sonra yüklemek istediğimiz paketi npm install paket ismi şeklinde terminale yazıyoruzz 
External vs native packages

