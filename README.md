# algoritma-ve-programlama
Ubuntu'da Python kodu yazarken sürüm çakışmalarını önleyen sistem sanal bir ortamdır . Sanal ortam, projenizin bağımlılıklarını sistem Python ortamından izole etmenize olanak tanıyan kendi kendine yeten bir Python ortamıdır.

1-Virtual Environments (Sanal Ortamlar):
venv: Python 3 ile birlikte gelen venv modülünü kullanarak her proje için izole bir ortam oluşturabiliriz. Projemizde gerekli olan bağımlılıkları yalnızca bu sanal ortamda kurarak, sistem genelindeki Python kurulumuyla çakışmalarını engellemiş oluruz.

2-Virtualenv: Eğer Python 2 ile çalışıyorsak veya daha fazla özellik istiyorsak, virtualenv kullanabiliriz.

3-Paket Yöneticileri:Projelerimizin bağımlılıklarını izole etmek için pip ile birlikte requirements.txt dosyası kullanabiliriz. Bu dosya, projemizde kullanmamız gereken bağımlılıkları ve sürümlerini tanımlar.

4-Docker:Uygulamalarımızı ve bağımlılıklarını konteynerler içinde çalıştırarak, her projenin bağımsız bir ortamda çalışmasını sağlayabiliriz. Docker kullanarak farklı projelerde farklı Python sürümleri kullanabiliriz.

5-Pyenv:Farklı Python sürümlerini yönetmek için pyenv kullanabiliriz. Bu, birden fazla Python sürümünü kolayca yükleyip değiştirmeye olanak tanır.

Bu adımlar, Ubuntu üzerinde kod yazarken karşılaşabileceğiniz arızaları azaltmanıza yardımcı olacaktır.
