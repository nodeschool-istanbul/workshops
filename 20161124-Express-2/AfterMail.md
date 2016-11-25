Merhabalar,

24 kasım perşembe günü [NodeSchool Istanbul](http://nodeschool.ist/) olarak düzenlediğimiz Express #2 atölyesine geldiğiniz için çok teşekkür ederiz. Sizlere bazı bilgileri hatırlatmak adına bu mesajı gönderiyoruz.

Bu mesajın tamamını https://github.com/nodeschool-istanbul/etkinlikler/blob/master/20161124-Express-2/AfterMail.md adresinde bulabilirsiniz.

## Etkinlik Serisi

Etkinlikte ve duyurularda da belirttiğimiz gibi bu etkinlik birkaç atölyelik bir seriden oluşacaktır.
Amacımız, serinin sonunda Node.js üzerinde başta Express.js olmak üzere belli başlı temel modülleri kullanarak bir web sitesi, web uygulaması ve API geliştirebilecek kadar Node.js ve Express bilmeniz.

## Etkinlikte işlediğimiz konuların özeti
* Geçen haftanın özeti
* Express'in diğer framework'lerden farkı
* Express'te middlewareler, route'lar, controller'lar
 * Middleware için `app.use` veya HTTP-verbs/methods için `app.get`, `app.post`, `app.put` vs..
 * Middleware ve controller'ın `request`, `response`, `next` ve `error` parametreleri
 * Middleware'e gelen bir isteğin `response.end()`, `response.render()` veya `response.redirect()` ile sonlandırılması
 * Node.js'te server-side uygulama akış şeması
* Nunjucks template engine
 * Uygulamaya middleware olarak ekleme
 * **Template**, **Layout** ve **Partial/Component** kavramı
 * `{% extend` ve `{% include` ile layout ve partial kullanımı, `{% block` kavramı
 * sadsada
 * Modüler uygulama
 * Requre ve module exports
 * app i bölmek route ve middlewa
 * render ı bölmek
* bower ve statik ve bootstrap
* login post ve verify ı
* cookie ve session 

## Geri Bildirim
Her etkinlikte gelen artı ve eksiklerimize dikkat ediyor ve kendimizi geliştirmek istiyoruz. Bu sebeple etkinlikle ilgili her yorumunuz bizim için çok önemli.
Yorumlarınızı bize en hızlı şekilde etkinliğimizin [Meetup sayfası](https://www.meetup.com/nodeschool-istanbul/events/235619166/) üzerinden mesaj atarak iletebilirsiniz.

## Katılım
Salonumuzun kapasitesi 150 kişilik olduğu için Meetup üzerinden 200 kişilik yer açmıştık. Meetup üzerinden **105** kişi geleceğini bildirmişti. Etkinliğimize **40**ın üzerinde kişinin geldiğini söylemekten mutluluk duyarız.

Etkinlik saatinde aynı zamanda maç olduğu için etkinliğimize katılamayanlar oldu. Gelecekteki etkinliklerimizi planlarken bunu da göz önünde bulunduracağız :)

## Sunumda kullandığımız/paylaştığımız sayfalar:
- NPM: Node.js modülleri resmi sitesi: https://www.npmjs.com/
- NodeJs modüllerini aramak için kullandığımız sitelerden biri: http://www.npmsearch.com/
- Programlama dillerinin modül sayıları karşılaştırması: http://www.modulecounts.com/
- Node.js Frameworkleri listesi: https://node.ist/docs/nodejs-frameworks
- Node.js Şablon motorları listesi: https://node.ist/docs/nodejs-template-engines
- Express.js kendi sitesi: http://expressjs.com/
- Express.js'de route lar: http://expressjs.com/en/guide/routing.html
- Express.js'in NPM'deki paket sayfası: https://www.npmjs.com/package/express
- Kullandığımız şablon motoru Mozilla Nunjucks'ın sitesi: https://mozilla.github.io/nunjucks/

## Bir sonraki etkinlik
Express 102 kod adıyla hitap edebileceğimiz 2. etkinliğimiz ilkinden tam iki hafta sonra, aynı yerde ve aynı saatte olacaktır.
Bu haftasonu meetup üzerinden etkinliğimizi açıp duyurumuzu yapmayı planlıyoruz.

Konu listesini aşağıdaki gibi planlıyoruz (güncellenebilir)
- HTTP methodları için Express'i kullanmak
- Basit bir form eklemek ve veri POST etmek
- Bower ile Express kullanımı
- repsonse.render ile sayfaya parametre göndermek
- Nunjucks şablon motoruna giriş, layout'lar, partial'lar, filter'lar ve konfigürasyon
- Belli başlı express middleware'leri

Not: İlk etkinlikte Node.js kurulumu, hazırlığı yaptığımız ve temelini anlattığımız için, bir sonraki etkinliğe gelecek katılımcıların aşağıdaki uygulamaları kurulu bir şekilde gelmelerini bekliyoruz:
- Git (Windows için zorunlu)
- Node.js > 4
- Text editor (Sublime Text, Atom Editor, Visual Studio code, Webstorm, vb)
