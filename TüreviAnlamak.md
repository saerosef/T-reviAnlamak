# Türev ve İntegrali Gerçekten Anlamak: Türev Nedir? İntegral Nedir?

  Türev ve integral, matematiğin en önemli konseptlerinden ikisidir. Günümüzde okullarda (liselerde) bu ikili çok yüzeysel bir şekilde ve çoğunlukla tamamen ezbere dayalı olarak anlatılmaktadır. Özellikle de bu kavramların ne anlama geldiği öğrenciye anlatılmadan, sadece nasıl çözüleceği üzerinden anlatım yapılmaktadır. Örneğin türev için "sayının üssünü katsayı olarak önüne al ve üssü 1 azalt" denmekte, integrali anlatmak içinse "üssü 1 arttırıp, aynı sayıyı payda olarak sayının altına yaz" gibi kalıp halinde ve algılamanın imkansız olduğu bir biçimde anlatılmaktadır. 

  İyi, bu işlemleri yapalım da... Neden? Ne işe yarıyor? Ya da öğrencilerin daha sık sorduğu şekliyle: Gerçek hayatta ne işimize yarayacak?

  En başından şu kadarını söyleyeyelim: 21. yüzyıl itibariyle gördüğünüz teknolojilerin neredeyse istisnasız olarak her biri, türev ve integrale dayalıdır! Dolayısıyla gelin bu iki kavramın gerçekten ne olduğunu, basit bir şekilde anlayalım:
 
 --------------
  
  ## Türev ve İntegrali Basit Bir Örnekle Anlamak
  
 - Türev, bir şeyin bir diğer şeye göre değişim miktardır. Yani türev, "değişim"i ölçmek için kullanılır. Genellikle türevi bir şeyin zaman geçtikçe ne kadar değiştiğini hesaplamak veya ifade etmek için kullanırız. Bunu az sonra örneklendireceğiz.
- İntegral ise, belli bir aralıktaki toplam değişimi, ya da "biriken değişim miktarını" ifade etmek için kullanılır.

Türev ve integrali anlamak için, integrali çözme yöntemleri bir kenara bırakılarak, hayattan örneklere bakılabilir.

Örneğin tavanınız akıtıyorsa ve etrafı su götürmemesi için akıtan noktanın hizasına büyük bir kova koyduysanız, kova içerisindeki su damla damla birikecektir. Birim zamanda (örneğin saatte 1 veya günde 1) kovadaki suyun hacmindeki değişim miktarı türev ile hesaplanır. Çok basit tabiriyle, hacim miktarındaki değişimin, zamandaki değişime oranı türevdir! Zamanı saatle ölçersiniz, dersiniz ki 8 saat geçmiş, buna 8 birim zaman diyelim. Kovaya bakarsınız, boşken 8 litre dolmuş. Kovadaki bu hacim değişiminin, zamandaki değişime oranı türevdir!

Tabii ki bu hesabın bu şekilde kolayca anlaşılabilmesi için, tavanın düzenli olarak akıttığı varsayılmalıdır. Eğer ki tavan bir hızlı, bir yavaş (ya da genel olarak, değişen hızlarda) akıtıyorsa, o zaman çeşitli yöntemlerle bu akıtma davranışı matematiksel olarak tanımlanmalı ve ondan sonra belirli bir zamandaki değişim hesaplanmalıdır. Fakat sonuç değişmez: Eğer değişen şey her neyse, onun değişim biçimini ifade eden matematiksel bir formülünüz varsa, bunun zamana göre türevi, o şeyin zaman içinde nasıl değiştiğini ifade eder. Bu kadar basit!

şte tavanın akıtma hızını matematiksel olarak ifade eden formül her neyse, o formülün zamana göre "türevini almak", birim zamandaki değişim miktarını bulmanızı sağlar. Eğer ki tavan her saniye 1 damla akıtıyorsa, bu davranış V=tV=tV=t formülüyle temsil edilebilir. Neden? Çünkü t, yani zaman her 1 birim (örneğin 1 saniye) arttığında, hacim de 1 birim (örneğin 1 damla) artacaktır. 10 saniye sonra, kovada 10 damla su bulunacaktır. 

Peki ya değişim? Türevini alalım: y=ty=ty=t formülünün t'ye göre türevi 1'dir. Bu işlemin nasıl yapıldığına dair de birçok anlatım yapılabilir; ancak lisede öğrendiğiniz düz mantıkla, bir formülün türevinin nasıl alındığını bildiğinizi varsayıyoruz. Yani y=ty=ty=t formülünde, y'nin t'ye göre türevi, t'nin herhangi bir üssü olmadığı için, doğrudan önündeki katsayıya eşittir. Bu da 1'dir.

Bir formülün türevinin nasıl alındığını şimdilik boşverin. Sonuca odaklanın. Her saniye 1 damla akıyorsa, değişimin miktarının (türevin sonucunun) 1 olması mantıklı, öyle değil mi? Çünkü her saniye hacmin 1 damla arttığını zaten söylemiştik. Dolayısıyla türevin "1 damla" sonucunu vermesi çok normal. Çünkü türev, değişimdir!

Peki, diyelim ki kovamızın başına sandalyemizi çektik ve bir gözlem yaptık. Bu gözlem sonucunda şu verileri topladık:

````
- İlk başta kovada su yok.
- 1. saniye sonunda kovada 2 damla su birikti. Artış 2 damla.
- 2. saniye sonunda kovada 8 damla su birikti. Artış 6 damla.
- 3. saniye sonunda kovada 18 damla su birikti. Artış 10 damla.
- 4. saniye sonunda kovada 32 damla su birikti. Artış 14 damla.
- Ve böyle devam ediyor...
````
İşte bu hacim değişiminin formüle dönüştürmek isterseniz, karşınıza V=2t^2

  çıkacaktır. Örneğin 4. saniyede toplam hacmi bulmak için, t'yi 4 alırsanız, V, yani hacim 32 damla olacaktır. Gerçekten de, her saniyede damlayan miktarı birbirine ekleyecek olursanız 2+6+10+14=322+6+10+14 = 322+6+10+14=32'dir! Devam etmeden önce o tavanı tıkasanız iyi olacak, yoksa çok kısa bir süre içinde her yeri su götürecek!
  
  
