# Basit Altyapı

Kullanımı basit ancak bir yandanda içinde birçek özellik barındıran discord bot altyapısı.

## Yapılacaklar

- ✅ Async ve aşırı hızlı.
- ✅ Komut başına _değişken_ yavaşlatma desteği.
- ✅ Komut başına bot gerekli yetki desteği.
- ✅ Komut başına kullanıcı gerekli yetki desteği.
- ✅ Özelleştirilebilir hata mesajları.
- ✅ Mantık hatası uyarı sistemleri.
- ✅ Bottan kullanıcı yasaklama.
- ✅ Komutlarda otomatik tamamlama.
- ✅ Global değişkenlerde otomatik tamamlama. (commands, events, config, client)
- ✅ İç içe klasör desteği.
- ✅ Komut açıp kapama desteği.
- ✅ Sadece geliştiricilerin kullanabildiği komut desteği.
- ✅ Genel event desteği.
- ✅ Event kapatabilme.
- ✅ Gelişmiş config dosyası. Hiç `index.js` dosyasını modifiye etmenize gerek kalmıyor.

## Kullanımı

Oldukça basit aslında. `config.js` içerisinde botunuzun genel ayarlarını yapabilir ve hata mesajlarını düzenleyebilirsiniz.

Komutlar için `commands` klasörünün içindeki [`ornekKomut.js`](./commands/ornekKomut.js) dosyasını dikkatlice okuyabilirsiniz.

Olaylar için `events` klasörünün içindeki [`ornekOlay.js`](./events/ornekOlay.js) dosyasını dikkatlice okuyabilirsiniz.