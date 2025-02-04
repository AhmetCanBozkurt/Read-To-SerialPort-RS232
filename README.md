# RS232 Seri Port Veri Okuma

Bu proje, bir **RS232 Seri Port** üzerinden gelen verileri okuyarak bir arayüzde görüntülemeyi sağlar. Windows Forms (WinForms) kullanılarak geliştirilmiştir ve **exe** formatında çalışmaktadır.

## Özellikler
- **Seri port seçimi**: Kullanıcı mevcut COM portlarını listeleyebilir ve bağlanmak istediği portu seçebilir.
- **Baud Rate ayarı**: Veri aktarım hızını belirlemek için seçenekler sunar.
- **Data Bit seçimi**: İletilecek veri uzunluğunu belirler.
- **Parity (Eşlik) kontrolü**: Veri iletiminde hata kontrolü için ayarlar.
- **Stop Bit seçimi**: İletimin bitişini belirleyen stop bit sayısını seçme imkanı.
- **Bağlan ve Veri Okuma**: Seçilen parametreler ile seri porta bağlanarak veri akışını gerçek zamanlı olarak ekranda gösterir.

## Gereksinimler
- .NET Framework 4.7.2 veya üzeri
- Windows işletim sistemi
- RS232 seri port destekleyen bir cihaz

## Kullanım
1. Programı çalıştırın.
2. "**Yenile**" butonu ile mevcut COM portlarını listeleyin.
3. Port, Baud Rate, Data Bit, Parity ve Stop Bit ayarlarını seçin.
4. "**BAĞLAN**" butonuna tıklayarak seri port bağlantısını başlatın.
5. Gelen verileri sağ taraftaki metin alanında görüntüleyin.

