Elbette discord.js kullanarak javascript ile yazılmıştır

Yazan:
- Corius (Canvas, Nsfw, Roleplay, Search, Bot Info hakkinda herseyi Corius yapmistir.)
- Marcell.xd ( Moderasyon, Eglence, Muzik, Level Dosyalarin hepsi **Marcell.xd** Tarafindan olusturlmustur


# Marcell.xd Not: bu botu corius sayesinde motivasyon alarak yaptigim ilk ve 6 ay boyunca ugrasacagim tek bot olmustur bu botu gece gunduz  ugrasarak yaptik ve hata sifira indi v11 olmasi Corius ekledigi canvas ve nsfw komutlar yuzunden olusan bir seydir son istegim v14 olmasiydi ama kendi fikri buydu. botu birisine ben satiyorum etttim fixledim diyeni gorursem son damlasina kadar sikerim.

# Corius 
Dikkat: Yakın zamanda yeni bir bot başlattım ve bu bot artık büyük güncellemeler almayacak ve artık gerçekten çalışmıyor çünkü bence sıfırdan başlayarak birçok şeyi tekrar geliştirebilir ve buradaki sorunları çözebiliriz
Verileri depolamak için sqlite yerine mySQL kullanacağım (Okuma/yazma için bu şekilde daha iyi data)

-----------------------------------------------------------


Öncelikle tüm dosyaları indirin ve bir klasöre koyun.

https://discordapp.com/developers/applications/me/create adresinde yeni bir uygulama oluşturmanız ve ardından botun adını doldurmanız ve avatarını seçmeniz ve oluşturmanız gerekir. Bunu yaptıktan sonra Bot yazan yeri bulun ve bir bot kullanıcısı oluştur'a tıklayın ve evet, yap'a tıklayın

Şimdi bota geri dönmek istiyorsunuz token'a gidin ve token:'a tıklayın ve bunu gösterin, bu size bot token'ını gösterecektir şimdi varlıklarda "token": "Token'ınız" yazan config.json'u düzenleyin ve bot token'ınızı ekleyin, tamamlandıktan sonra kaydet'e tıklayın.

Şimdi bunu yaptığınıza göre NodeJs'i yüklemeniz gerekecek, bunu https://nodejs.org/en/ adresinden edinebilirsiniz, böylece botu çalıştırmaya başlayabilirsiniz.

Şimdi dosyaları koyduğunuz boş bir alandaki klasöre sağ tıklayın ve ardından komut istemini aç'a tıklayın.

Npm install ile bağlı olduğu tüm paketleri yüklemeniz gerekir.

MySQL'i kurmak için şu kılavuzu izleyin: https://www.digitalocean.com/community/tutorials/how-to-install-mysql-on-ubuntu-18-04

(DbConnection'ı veritabanı bilgilerinize göre düzenlediğinizden emin olun)

Bağımlılıkları indirmeyi ve MySQL'i kurmayı bitirdiğinizde, botu başlatmak için node app.js'yi çalıştırın.

Şimdi botu şu şekilde bir davet kullanarak sunucunuza davet edin https://discordapp.com/oauth2/authorize?client_id={your_bot_id}&permissions=8&scope=bot

your_bot_id'yi botunuzun kimliğiyle değiştirdiğinizden emin olun

Davet edildikten sonra varsayılan önek c!'dir, DM'niz kapalıysa (bot loncalara davet edildiğinde ilk kez bir mesaj gönderir)

c!help size oradan bir komut listesi verecektir, botu kullanmanın tadını çıkarın

Bu botu konsol veya terminal açık değilken çalıştırmak istiyorsanız, nodemon veya pm2 kullanın (örn. pm2 app.js'yi başlatın)

Bunun için bir kılavuz: https://www.digitalocean.com/community/questions/how-do-i-set-up-a-discord-bot
