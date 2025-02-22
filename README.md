# Syslog Okuma Uygulaması

Bu uygulama, Linux syslog günlüklerini okuyarak tek yönlü bağlı listeye ekler ve ekrana yazdırır.

## Gereksinimler

- C derleyicisi (gcc gibi)
- Linux işletim sistemi
- `/var/log/syslog` dosyasına okuma izni


## Kod Açıklaması

- `Node` Yapısı: Her syslog mesajını saklamak için kullanılır.
- `yeniDugum` Fonksiyonu: Yeni bir düğüm oluşturur.
- `sonaEkle` Fonksiyonu: Liste sonuna eleman ekler.
- `syslogOku` Fonksiyonu: Syslog dosyasını okuyarak günlükleri bağlı listeye ekler.
- `listeYazdir` Fonksiyonu: Bağlı listedeki günlükleri ekrana yazdırır.
- `main` Fonksiyonu: Syslog dosyasını okuyarak günlükleri bağlı listeye ekler ve ekrana yazdırır.

