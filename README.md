# SocketProgramming# Socket Sunucu Uygulaması

Bu proje, Python'da soket programlama kullanılarak geliştirilmiş bir çoklu sunucu uygulamasını içerir. Uygulama, odalar, etkinlikler ve rezervasyonlar gibi kaynakları yönetmek için üç farklı sunucu içerir.

## Nasıl Çalışır?

Bu uygulama, `main.py` dosyası aracılığıyla başlatılır. Ana dosyada, odaları yöneten bir `RoomServer`, etkinlikleri yöneten bir `ActivityServer` ve rezervasyonları yöneten bir `ReservationServer` oluşturulur. Her sunucu, gelen istekleri dinlemek için ayrı bir iş parçacığı üzerinde çalışır.

## Gereksinimler

Bu uygulamayı çalıştırmak için Python 3 gereklidir. Ayrıca, aşağıdaki Python kütüphanelerine ihtiyacınız olacaktır:
- `socket`: Soket programlama için
- `sys`: Sistem işlemleri için
- `threading`: İş parçacıklarını yönetmek için

## Kurulum

1. Bu projeyi yerel bilgisayarınıza klonlayın veya ZIP olarak indirin.
2. Projeyi indirdikten sonra, terminal veya komut istemcisinde projenin kök dizinine gidin.
3. Ana dosya olan `main.py` dosyasını çalıştırarak sunucuyu başlatın.

## Kullanım

Ana dosyayı çalıştırmak için terminal veya komut istemcisinde aşağıdaki komutu kullanabilirsiniz:
