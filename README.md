# BİFENER
Eskişehir Borsa İstanbul Fen Lisesi'nin BİFENER projesinin arşivlenmesi amacıyla kurulmuş repo.
Bununla daha sonra ilgilenmeyi düşündüğüm için bu repo şimdilik sadece "placeholder" olarak duracak.

# Orijinal Projenin İçeriği
Bir pil tarafından güç sağlanan, düğmelere basıldığında led ile ışık veya buzzer ile ses uyarısı veren bir led & buzzer devresi.

## Yaptığım Değişiklikler
Orijinal devre şeması ve PCB çizimi elimde bulunmadığı için projenin aynısını KiCad üzerinde oluşturdum. Devre şemasında herhangi bir değişiklik olmasa da PCB çiziminde değişiklikler yaptım. Asıl devre şeması ve PCB 
çizimi bir şekilde elime geçerse kendi yaptıklarımın yanına eklerim.

1- Kullanılan pil olarak CR2032 pili seçtim. (Sadece footprint üzerinden tahmin yürüttüğüm için projenin aslında da CR2032 kullanılmış olabilir, ama yine de yazmak istedim.)
2- Buzzer ve düğme footprintlerini ulaşılması kolay 6x6 tact button ve 12mm çaplı buzzer footprintleri ile değiştirdim. (Yukarıdaki madde ile aynı sebep)
3- Çizimde kolaylık sağlaması adına ledleri + pinleri birbirine bakacak şekilde yerleştirdim (Daha sade ve üretimi daha kolay PCB)
4- GND hattını çizmek yerine bütün PCB'de bir GND havuzu oluşturdum. (Hem PCB çiziminde GND hattı çizmek ile uğraşmıyorum, hem de PCB üretimini çok daha kolaylaştırıyor.)
