# State Tasarım Deseni
State tasarım deseni behavior grubununa ait, nesnelerin farklı durumlarda farklı çalışmalarını düzenleyen bir tasarım desenidir.

State tasarım deseni; bir nesnedeki bir özellik değiştirildiğinde o nesnenin çalışmasını değiştirmesini veya o durum için kod işlemesini düzenler. Bunu basit bir şekilde gerçekleştirir. Şöyle ki; içinde bir arayüzün referansını tutar ve property si değiştiğinde o arayüze o arayüzden türeyen başka bir nesne atar. Senaryoya göre bu arayüzde ki işlemi kendi tetikler veya sonraki istekte bu arayüzde ki işlem tetiklenir.

Kodumun sınıf diagramı şu şekildedir

![Class Diagram](https://github.com/glahkerez/Yaz-l-mmimarisivetasar-m-/blob/master/State_class.jpg)
