# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

-Git, Açık Kaynak Dağıtılmış Sürüm Kontrol Sistemi(Open Source Distributed Version Control System)'dir.

2. Git ile GitHub arasında ne fark var?                                                                                                                                                                    

-Git yereldeki versiyon kontrolünü sağlarken, GitHub projelerinizi uzak sunucuda saklamamıza ve işbirliği yapmamıza yardımcı olur.

3. Neden bir branch oluşturuyoruz?

-GitHub'da branch oluşturmak, geliştirme sürecini üzenlemek, işbirliği yapmak, sürüm yönetimini sağlamak ve kod kalitesini artırmak gibi birçok avantajı kullanmak için oluştururuz.

4. Pull Request'in amacı nedir?

-Açık kaynaklı bir projede katkıda bulunmak isteyen bir kullanıcının, projenin sahibine değişikliklerini inceletmek üzere yaptığı bir taleptir.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

- git checkout main

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

-'git fetch' yapılan değişiklikleri locale alır ancak uygulamaz.
 'git merge' farklı branchlerin değişikliklerini birleştirir.
 'git pull' git fetch ve ardından git merge işlemini otomatik olarak gerçekleştirerek değişiklikleri localde uygular.

7. Merge conflict nedir?

-kısaca çakışma olarak adlandırabiliriz. farklı dallardaki veya versiyonlardaki değişikliklerin aynı satırları veya dosyaları etkilediği durumdur.

8. Merge conflict'i nasıl çözeriz?

-conflicti git pull veya git merge komutlarıyla belirleriz. Çakışma bölgelerini düzenler 'git add' ile işaretleriz. Ardından commit ile kaydeder, daha sonrasında gerekirse çakışmanın çözdüldüğünü 
doğrularız ve 'git push' ile göndeririz.
