# Bash Shell Nedir ve Neden Önemlidir?

# Giriş

Günümüz bilgisayar işletim sistemleri, kullanıcıların komutlar girerek işletim sistemine talimat vermesine olanak tanıyan bir kullanıcı arayüzüne sahiptir. 
Ancak, birçok işletim sistemi bu komut arayüzünü sabit bir şekilde sunar ve kullanıcılara yalnızca sınırlı bir etkileşim imkanı tanır. 
Unix işletim sistemi, komut arayüzünü (shell) diğer sistem bileşenlerinden ayırarak devrim niteliğinde bir yaklaşım geliştirmiştir.

## Shell Nedir?

Shell, kullanıcıların komut yazdığı bir programdır. 
Temel görevi, bu komutları alıp ilgili programları çalıştırmaktır. 
Unix, shell kavramını popüler hale getirerek, bu arayüzü işletim sisteminin diğer bileşenlerinden bağımsız hale getirmiştir. 
Bu sayede, kullanıcılar standart shell'i değiştirebilir veya kendi shell'lerini oluşturabilirler.

## Shell'in Tarihçesi

Unix'in ilk yıllarında, iki ana shell ortaya çıktı: Bourne Shell (sh) ve C Shell (csh). 
Zamanla Korn Shell (ksh) ve Bash Shell (bash) gibi yeni alternatifler eklendi. 
Bu durum, yazılım geliştiricilerine daha iyi shell'ler yazma fırsatı sundu.

# Modern Shell'lerin Avantajları

## Kullanıcı Kolaylığı

Modern shell'ler, kullanıcı deneyimini geliştiren birçok özellik sunar:

- Komut Geçmişi: Daha önce yazdığınız komutları hatırlama ve tekrar kullanma imkanı.
- Komut Düzenleme: Yazdığınız komutları düzenleyerek her seferinde aynı şekilde tekrar etme gereğini ortadan kaldırır.
- Kısa Yol Tanımları: Kendi komut kısayollarınızı ve kısaltmalarınızı tanımlamanıza olanak tanır.

Bu özellikler, deneyimli kullanıcılar için komut girmeyi daha verimli hale getirir.

## Programlanabilirlik

Shell, sadece komutları çalıştırmakla kalmaz, aynı zamanda bir programlama dili olarak da işlev görür. 
Sık tekrar eden işlemleri otomatikleştirmek için shell scriptleri yazabilirsiniz. 

Örneğin:

- WAV dosyalarından binlerce MP3 dosyası oluşturmak için bir shell scripti yazabilirsiniz.
- Sistem log dosyalarınızı sıkıştırmak için bir shell scripti kullanabilirsiniz.

# Neden Bash?

## Bash Nedir?

Bash, "Bourne Again SHell" anlamına gelir ve Unix tabanlı işletim sistemlerinde yaygın olarak kullanılan bir komut shelldir. 
Bash, hem kullanıcı arayüzü hem de programlama dili olarak işlev görür.

## Tarihsel Arka Plan

İlk shell'ler, iyi programlama araçlarıydı ancak kullanıcılar için pek pratik değildi. 
C shell, kullanıcı konforunu artıran birçok özellik ekledi (örneğin, son yazılan komutun tekrarını yapabilme), ancak programlama dili olarak tuhaflıklar içeriyordu. 

Korn shell (ksh), 1980'lerin başında ortaya çıktı ve hem kullanıcı konforunu artırdı hem de programlama dilini geliştirdi. 
Ancak, başlangıçta açık kaynak yazılım değildi; bu nedenle Linux gibi ücretsiz işletim sistemleriyle birlikte dağıtılması zordu. 
Korn shell’in lisansı 2000 ve 2005 yıllarında değişti.

## POSIX Standartları

1980'lerin sonlarında, Unix topluluğu standartlaşmanın önemli olduğunu düşündü ve POSIX çalışma grupları (IEEE tarafından organize edilen) kuruldu. 
POSIX, Unix kütüphanelerini ve yardımcı programlarını standartlaştırdı, bunların arasında shell de vardı. 
Standart shell, esasen Korn Shell'in 1988 versiyonuna dayanıyordu.

Bash, GNU projesinin bir parçası olarak, tam bir POSIX sistemi üretme çabasıyla geliştirildi. 
Bash, shell programcılarının ihtiyaç duyduğu programlama özelliklerini sağlarken, komut satırı kullanıcılarının da hoşlandığı kolaylıkları sundu. 
Başlangıçta Korn shell'e alternatif olarak tasarlandı, ancak özgür yazılım hareketi önem kazandıkça ve Linux popülerleştikçe, Bash hızla ksh'yi gölgede bıraktı.

## Bash'ın Yaygınlığı

Bash, bildiğimiz her Linux dağıtımında varsayılan kullanıcı shell'idir (birkaç yüz Linux dağıtımı olduğu için bazıları farklı varsayılan shell'lere sahip olabilir). 
Ayrıca Mac OS X'de de bulunmaktadır. BSD Unix ve Solaris gibi diğer Unix işletim sistemlerinde de mevcuttur. 
Bash'ın işletim sistemiyle birlikte gelmediği nadir durumlarda bile kolayca yüklenebilir. Windows için de (Cygwin aracılığıyla) mevcuttur.

## Kullanıcı Arayüzü ve Programlama Dili

Bash, güçlü bir programlama dili ve iyi bir kullanıcı arayüzüdür; karmaşık programlama özelliklerinden ödün vermeden klavye kısayollarını kullanmanıza olanak tanır. 

## Bash Öğrenmenin Avantajları

Bash öğrenmekte asla yanlış yapamazsınız. En yaygın varsayılan shell'ler eski Bourne shell ve çoğunlukla Bourne shell ile uyumlu olan Bash'tır. 
Bu shell'lerden biri modern, büyük Unix veya Unix benzeri işletim sistemlerinde kesinlikle mevcuttur. Eğer Bash yoksa, her zaman yükleyebilirsiniz.

## Diğer Shell'ler

Bununla birlikte başka shell'ler de bulunmaktadır. Özgür yazılım ruhu gereği, bu shell'lerin yazarları ve bakımcıları fikirlerini paylaşır. 
Bash değişiklik günlüğüne baktığınızda, birçok özelliğin başka bir shell'deki davranışa uyacak şekilde eklendiğini veya değiştirildiğini göreceksiniz. 
Ancak çoğu insan mevcut olanı kullanacaktır ve bu durumdan memnun kalacaktır.

Eğer ilgileniyorsanız, diğer shell'leri keşfetmekten çekinmeyin. 
Birçok iyi alternatif vardır ve belki daha çok hoşunuza gidecek birini bulabilirsiniz; ancak muhtemelen Bash kadar yaygın olmayacaklardır.

## Shell Programlama ve Scripting

Bash, tekrarlayan veya karmaşık işlemleri otomatikleştirmek için shell programlama veya shell scripting adı verilen bir yöntem sunar. 
Bu, kullanım kolaylığı, güvenilirlik ve tekrarlanabilirlik açısından büyük avantajlar sağlar. 

## Bash ile Tanışma

Eğer bash ile yeni tanışıyorsanız, bazı temel bilgileri öğrenmek iyi bir başlangıç olacaktır. 
Unix veya Linux kullanıyorsanız, muhtemelen bash ile daha önce karşılaştınız ama bunun farkında olmayabilirsiniz. 
Bash, aslında komutları çalıştırmak için bir dildir; dolayısıyla şimdiye kadar yazdığınız komutlar (örneğin, ls, cd, grep, cat) aslında bash komutlarıdır. 
Bazı komutlar bash’in kendisine entegre edilmiştir; diğerleri ise ayrı programlardır. Şu aşamada hangisinin hangisi olduğunun önemi yoktur.

# Komut Satırı İstemcisi: Anlamı ve Yapısı

## Giriş

Komut satırı istemcisi, kullanıcıların işletim sistemi ile etkileşimde bulunmasını sağlayan bir araçtır.
Bu kısımda, ekranınızdaki tüm işaretlerin ne anlama geldiğini anlamanıza yardımcı olacağız.

## İstemci Nedir?

Tüm komut satırı shell'leri, kullanıcıya girdi alabileceğini bildiren bir istemciye sahiptir. 
İstemcinin görünümü, işletim sistemi türü, versiyonu, shell türü ve versiyonu, dağıtım ve yapılandırma gibi birçok faktöre bağlıdır.

# İstemci Sembolleri

## Kullanıcı ve Root Hesabı

Bourne ailesi shell'lerinde, istemcinin sonunda bulunan ```$``` işareti, normal bir kullanıcı olarak oturum açtığınızı gösterirken, 
```#``` işareti root (yönetici) hesabında olduğunuzu belirtir. 
Root hesabı, sistemin yöneticisidir ve genellikle Windows'taki Sistem hesabına veya Netware'deki Supervisor hesabına eşdeğerdir. 
Root, Unix veya Linux sistemlerinde her şeye müdahale edebilir.

![Resim](https://i.ibb.co/3s8CLnt/Sembols-Bash.png)

## Mevcut Dizin Bilgisi

Varsayılan istemciler, bulunduğunuz dizinin yolunu da gösterebilir; genellikle bu yol kısaltılarak gösterilir. 
Örneğin, ```~``` sembolü, home dizininizde olduğunuzu belirtir.

# Örnek İstemciler

## Kullanıcı İstemcisi 

Aşağıda, kali adlı bir kullanıcının kali adlı bir makinede home dizininde oturum açtığı tipik bir Linux istemcisi örneği verilmiştir:

Resim :

![Resim](https://i.ibb.co/TMRYGDj/Home-Bash.png)

## Dizin Değişimi

/tmp dizinine geçtikten sonraki istemci:

![Resim](https://i.ibb.co/m4rx386/Directory-Bash.png)

Burada ~, aslında /home/kali anlamına gelirken, /tmp dizinine geçildiğinde bu değişmiştir.

## Tartışma

Shell'in istemcisi, komut satırında çalışırken en sık göreceğiniz şeydir ve daha fazla özelleştirme yapmanın birçok yolu vardır. 
Ancak şimdilik, bu istemcinin nasıl yorumlanacağını bilmek yeterlidir. Varsayılan istemciniz farklı olabilir, ancak temel bilgileri anlamanız yeterli olacaktır.

## Root Yetkileri

Bazı Unix veya Linux sistemlerinde root yetkileri paylaşılabilir; bu da ```su``` ve ```sudo``` gibi komutlar kullanılarak yapılır. 
Ayrıca, bazı sistemlerde root yetkileri sınırlı olabilir; örneğin NSA'nın SELinux gibi zorunlu erişim kontrol (MAC) sistemleri çalıştırılıyorsa.
