# Yol Haritası

Bu projenin amacı ülkemizde yazılım alanına giriş yapmak isteyen veya bu alanın üniversitede okumak isteyen herkese bir yol haritası sunmak ve hemen hemen herkesin aklında bulunan sorulara cevap olabilmektir. Projeye eklenmesini istediğiniz değişikler ve bir sonraki versiyonda hangi özelliklerin geleceğini [buradan](https://trello.com/b/hUf6j69F) görebilirsiniz.

* Bu proje gönüllülük esasına dayalı bir projedir.
* Bu projeden herhangi bir maddi kazanç elde edilmemektedir.

# Nasıl Katkıda Bulunabilirim?
Katkıda bulunabilmek için öncelikle projeyi pull-request yapmanız gerekmektedir. Bu işlemi gerçekleştirdikten sonra projede Docsify kullanılmıştır. Docsify hakkında ayrıntılı bilgiye [buradan](https://docsify.js.org/#/quickstart) ulaşabilirsiniz.

### Bilgisayaranıza Docsify Yükleme

Bu işlemi gerçekleştirebilmek için linux işletim sistemlerinde terminal ekranına, windows işletim sistemlerinde komut satırına aşağıdaki kodu yazmanız gerekmektedir;

```bash
npm i docsify-cli -g
```

Daha sonra projeyi ayağa kaldırabilmek için yine terminal veya komut satırına aşağıdaki kod yazmalısınız. Fakat yazmadan önce termianl veya komut satırında yol haritası projesinin içerisinde olmanız gerekiyor. Klasör içerisine girdikten sonra şu komutu yazmanız yeterli;

```bash
docsify serve docs
```

veya

```bash
docsify serve
```

Proje üzerinde örnek vermek gerekirse, giris dosyasının altında yenisayfa.md isimli bir sayfa oluşturduğunuz taktirde guncellemegecmisi.md sayfasında sizin katkıda bulunduğunuz herhangi bir gün güncelleme yapılmamış ise şu şekilde bir yapı eklemeniz gerekmektedir;

## [0.1.4]() (Değişiklik yapılan günün tarihi)

#### Yapılan Değişiklikler

* Yeni sayfa yazısı eklendi.

Burada versiyon işlemini şu şekilde yapmanız gerekmektedir;

* Yeni bir sayfa eklediğiniz zaman minor(ara versiyon) değişiklik yapmanız gerekmektedir. Yani 0.2.4 şeklinde olacaktır.
* Eğer herhangi bir hatayı düzelttiniz veya yeni bir kaynak eklemişseniz düzetlme(bug fix, build) yaptığınız için en sonda bulunan versiyonu güncellemeniz gerekmektedir. Yani 0.2.5 şeklinde olacaktır. Versiyonlama hakkında daha ayrıntılı bilgiye [buradan](http://hrzafer.com/yazilim-versiyon-numaralari) ulaşabilirsiniz.
