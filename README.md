# ☄️ pixeldb

bir JSON veritabanı modülü

## Kurulum

Modülü kurmak için öncelikle konsola aşağıdaki yazıyı yazmalısınız.

```bash
npm i pixeldb@latest
```

Bunu yazdıktan sonra modülün indirilmesiniz bekleyin. Modül kurulunca `main (bot.js / server.js / index.js / main.js, vb)` dosyanıza aşağıdaki kodu ekleyin. Kodu en başa eklemeniz main dosyanızın daha hoş durmasını sağlayacaktır.

```javascript
const db = require("pixeldb")
```

Paket otomatik olarak `database.json` dosyası oluşturacak verileriniz bu dosyaya kayıt edilecek.

## Fonksiyonlar

```javascript
    yaz => set
    db.set('prefix', '!')
    <DB>.yaz('prefix', '!')
```

```javascript
    depola => push
    db.push('prefix', '!')
    <DB>.depola('prefix', '!')
```
    
```javascript
    bul => fetch/get 
    db.fetch('prefix')
    <DB>.bul('prefix')
```

```javascript
    kontrol => has
    db.has('prefix')
    <DB>.kontrol('prefix')
```

```javascript
    sil => delete/remove
    db.delete('prefix')
    <DB>.sil('prefix')
```

```javascript
    yedekle => backup
    db.backup('veri.json')
    <DB>.yedekle('veri')
```
    
```javascript
    topla => add
    db.add('puan', 5)
    <DB>.topla('puan', 5)
```

```javascript
    çıkar => substr
    db.substr('puan', 5)
    <DB>.çıkar('puan', 5)
```

```javascript
    sıfırla => -
    <DB>.sıfırla()
```

## Destek

Desteğe ihtiyacınız olursa [destek sunucumuzu](https://discord.gg/a422yhxDg8) ziyaret edebilirsiniz.

## pixel.db

Discord Adresim: Kiarea#0001
