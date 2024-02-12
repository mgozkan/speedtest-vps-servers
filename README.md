# speedtest-vps-servers
Telefonlarımızda ve bilgisayarlarımızda kullandığımız en popüler hız testi uygulaması olan Speedtest by Ookla ile sunucumuzun gerçek hızını öğreneceğiz. Sunucumuzu kiralarken söylenen 1 Gbit/s - 10 Gbit/s gibi rakamlar gerçekten doğrumuymuş görebileceğiz.

Terminalimizi açıp aşağıdaki kodları teker teker yapıştırıyoruz:
```
sudo apt-get install curl
curl -s https://packagecloud.io/install/repositories/ookla/speedtest-cli/script.deb.sh | sudo bash
sudo apt-get install speedtest
```
![image](https://github.com/mgozkan/speedtest-vps-servers/assets/7867728/dfc2ef90-895e-4be1-8814-c86cecb164a1)

Kurulum tamamlandıktan sonra uygulamayı çalıştırıyoruz.

```
speedtest
```

Lisans sözleşmesini yes yazarak onaylıyoruz. 

![image](https://github.com/mgozkan/speedtest-vps-servers/assets/7867728/c276bc7f-2c8b-4f21-a944-2881e7da1d89)

Aynı telefon ve bilgisayarımızdaki gibi uygun bir bağlantı noktası bulup test işlemine başlıyor. 

Test işlemi bittikten sonra bir link oluşturuyor:
![image](https://github.com/mgozkan/speedtest-vps-servers/assets/7867728/6a5cea43-51c5-4dfb-a5ae-11ae401120be)

Bu linki kopyalayıp browserinize yapıştırıp açtığınızda detaylı hız raporunu görüntüleyebiliyorsunuz.

![image](https://github.com/mgozkan/speedtest-vps-servers/assets/7867728/8e01e539-9b57-448f-96b9-1393871e4e2b)

Böylece VPS'imizin gerçek internet hızını Download (indirme), Upload (Yükleme) hızını görmüş olduk.


Hepsi bu kadar.
