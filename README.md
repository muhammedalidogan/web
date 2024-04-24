# web
html bölümü ve genel yapı
Sayfanın stili style.css adlı bir dış CSS dosyasına bağlanarak yönetiliyor. Bu dosyada sayfanın görsel tasarımı için gerekli stil kuralları bulunur.
Tarayıcı sekmesinde görünen ikon (favicon) belirlenmiş. Bu, kullanıcıların siteyi sekmeler arasında kolayca tanımasını sağlar
Header (Başlık) ve Navigasyon: Sayfanın üst kısmında bir başlık (<header>) ve bir navigasyon menüsü (<nav>) bulunuyor. Menüde "Anasayfa", "Menüler", "Masalar", "Hakkımızda" ve "İletişim" gibi bağlantılar var.
Arama Kutusu: Sayfanın üst kısmında bir arama kutusu bulunuyor. Kullanıcılar buradan belirli yemekleri arayabilirler.
Ana İçerik Bölümleri: Sayfa, indirimli yemekler, popüler yemekler ve tüm yemekler olmak üzere üç ana bölümden oluşuyor.
İndirimli Yemekler ve Popüler Yemekler: Her iki bölümde de yemek resimleri, isimleri, açıklamaları, fiyatları ve "Sipariş Ver" butonları bulunuyor. Bazı yemeklerin "Popüler" olduğunu belirten etiketler var.
css bölümü
Resetleme ve Kutu Modeli Ayarları: * selektörüyle tüm öğelerin dış boşluklarını ve dolgularını sıfırlıyor (margin: 0; padding: 0;) ve box-sizing: border-box; ile kutu modelini belirliyor. Bu, öğelerin içeriğinin, dolgu ve kenar boşlukları ile birlikte belirtilen genişlik ve yükseklikte olmasını sağlar.
Body Stili: body öğesi için arka plan rengi, yazı rengi ve yazı tipi tanımlanıyor
Header Stili: header öğesi için arka plan rengi, yazı rengi, dolgu ve metin hizalaması ayarlanıyor
Navigasyon Menüsü Stili: Navigasyon menüsü öğeleri (nav ul li) yan yana hizalandı, aralarında bir kenar boşluğu bırakıldı ve bağlantılar beyaz renge dönüştürüldü.
Arama Kutusu Stili: Arama kutusu ve arama butonu öğeleri (input ve button) yan yana hizalandı ve stille ilgili özellikler belirlendi.
Hero (Kahraman) Alanı Stili: Büyük bir görsel arka planın üzerinde metin içeren bir kahraman alanı oluşturuldu.
Promosyon, Öne Çıkan ve Menü Bölümleri Stili: Bu bölümler için maksimum genişlik, kenar boşluğu, arka plan rengi, dolgu, gölgeler ve konumlandırma gibi stil özellikleri belirlendi.
Menü Öğesi Stili: Her menü öğesi (menu-item) için genişlik, arka plan rengi, dolgu, kenar boşluğu, köşe yuvarlatma, gölgeler ve konumlandırma tanımlanmış. Ayrıca, fare üzerine gelindiğinde menü öğelerinin büyütülmesini sağlayan bir geçiş efekti tanımlandı
Özel Etiket Stili: del etiketi için özel bir stil tanımlandı, bu etiketler kırmızı renkte ve az saydamlıkta oluyor.
Footer (Alt Bilgi) Stili: Altbilgi öğesi için arka plan rengi, yazı rengi, dolgu ve metin hizalaması tanımlandı.
Duyarlılık (Responsive) Stili: Küçük ekranlı cihazlar için bazı stiller belirlendi. Bu, özellikle menü ve bölüm öğelerinin düzgün bir şekilde görüntülenmesini sağlandı
