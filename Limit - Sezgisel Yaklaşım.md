# Limit : Sezgisel Yaklaşım


## Limit Tanımı
Matematikte limit kavramından bahsedildiğinde verilen bir fonksiyonun limiti anlaşılır. Bu sayede bir fonksiyondaki x değerleri belirli bir sayıya yaklaşırken fonksiyon grafiğinin nasıl davranacağı gözlemlenir.

## Örnek

Varsayalım ki başlangıç noktasından otobüs durağına doğru yürüyen arkadaşımızı evimizin balkonundan izliyoruz ve onun pozisyonunu belirtecek bir grafik çiziyoruz. Ve başlangıç noktası ile otobüs durağı arasında 100 metre var. Arkadaşımızın kat ettiği mesafe ile birlikte, yürüdüğü zamanı temsil edecek bir grafik çizelim. Ama ondan önce, birkaç varsayım/koşul belirtelim.

### Varsayımlar
- Arkadaşımızın ivmesini değiştirecek bir etken olmadığını ve düz yolda gittiğini varsayalım.
- Bulunduğumuz mesafe ile otobüs durağı arasında 100 metre olduğunu varsayıyoruz.
- 100 metrenin varsayım olarak 100 saniyede (1dk. 40sn.) yüründüğünü varsayalım.
- Arkadaşımızın temposunun stabil olduğunu varsayalım.

### Grafik
Grafiğimiz böyle gözükecektir:

<a href="https://imgbox.com/dd3Fxj5q" target="_blank"><img src="https://images2.imgbox.com/06/1b/dd3Fxj5q_o.jpg" alt="image host"/></a>

### Varsayımlar (2)
- Varsayalım ki grafiği çizmeye devam ederken ev içerisinden biri bize seslendi ve kısa süreli olarak dikkatimiz dağıldı. Dolayısıyla 60.saniyede arkadaşımızın hangi pozisyonda olduğunu kaçırdık.
- Dolayısıyla grafiğimizde belirsiz bir alan oluşacaktır.

### Grafik (2)
Grafiğimiz böyle gözükecektir:

<a href="https://imgbox.com/1hkILVfc" target="_blank"><img src="https://images2.imgbox.com/8f/49/1hkILVfc_o.jpg" alt="image host"/></a>

60.saniyede arkadaşımızın tam olarak nerede olduğunu bilemesek de nerede olduğunu tahmin edebiliriz değil mi? Muhtemelen 60 metre pozisyonundaydı.

***Nasıl bilebiliyoruz?***

Çünkü 60 saniyeden çok az önce 60 metre pozisyonunun çok az şekilde altında kalıyordu ve aynı zamanda 60 saniyeden çok az sonra 60 metre pozisyonunun çok az şekilde ilerisinde kalıyordu. Arkadaşımız biz kısa sürede başka yere bakarken ışınlanmadıysa veya sihirli bir şekilde yer değiştirmediyse, tahminimiz oldukça geçerli olacaktır.

Limitler kısaca şu bariz fikri temsil etmektedir:

Komşu noktalarda aldığı değere bağlı olarak bir fonksiyonun bir noktada hangi değerleri aldığı tahmin edilebilir.

Dolayısıyla böyle bir fonksiyon gördüğümüz zaman:

```
lim f(x)
x→h
```

Kendimize şunu sormak gerekir: Yalnızca fonksiyonun **h** değerine yaklaştığı değerlere dayanarak, **x**, **h** değerine yaklaşırken, ***f(x)*** fonksiyonu hangi değeri alabilir?

İfadedeki **→** işareti yaklaşmayı temsil etmektedir.

Eğer arkadaşımızın pozisyonu ***f(x)*** ise, limit böyle gözükecektir:

```
lim f(x) = 60
x→60
```
- Buradaki **x** zaman(saniye)'ı temsil etmektedir.

Örneğimizde, "Arkadaşımızın temposunun stabil olduğunu" varsaydık dolayısıyla fonksiyonumuz lineer oldu. Ancak lineer olmayan fonksiyonlarda da limit alabildiğimizi unutmayalım.

