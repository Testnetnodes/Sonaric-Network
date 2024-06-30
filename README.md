<h1 align="center"> Sonaric AI Node </h1>

> Sonaric Network'un kuruluş amacı, dağıtılmış hesaplama kaynaklarını optimize ederek, Web3 altyapısı ve merkezi olmayan bulut sistemleri için güçlü ve otonom bir ağ oluşturmaktır. Bu ağ, kullanılmayan hesaplama kaynaklarını (CPU, GPU, depolama) bir havuzda toplayarak bunları en yüksek ödüllerle 
 ilişkilendirir. Sonaric, katılımcıların blok zinciri düğümlerini kolayca çalıştırmasını ve yönetmesini sağlayarak teknik bariyerleri ortadan kaldırmayı hedefler.
 Ağ, Sonaric AI düğümleri ve Sonaric Oracle ile çalışır. Sonaric AI düğümleri, kaynakları en iyi şekilde tahsis etmek için kullanıcıların donanım kaynaklarıyla iletişim kurar ve ödülleri optimize eder. Sonaric Oracle ise, pazar verilerini toplayarak düğümleri en karlı ağlarla eşleştirir ve 
 gerektiğinde dinamik olarak değiştirir

![image](https://github.com/Testnetnodes/Sonaric-Network/assets/115115403/a4bc9a2d-d57b-4053-bcd9-351d1bf3390c)

 * [Topluluk kanalımız](https://t.me/testnetnodesgenel)<br>
 * [Topluluk Twitter](https://twitter.com/testnetnodes)<br>
 * [Sonaric Website](https://tracker.sonaric.xyz/)<br>
 * [Discord](https://discord.gg/MZ247hw47z)<br>
 * [Twitter](https://x.com/SonaricNetwork)<br>

 ## 💻 Sistem Gereksinimleri

| Bileşenler | Minimum Gereksinimler | 
| ------------ | ------------ |
| CPU |	2+|
| RAM	| 4+ GB |
| Storage	| 20 GB SSD |
| Ubuntu 22 |


 ## ✅ Sistem güncellemeyle başlayalım
```shell
sudo apt update && sudo apt upgrade -y
sudo apt install curl git jq build-essential gcc unzip wget lz4 -y
```

 ## ✅ Gerekli dosyaları yüklemek için izin verelim
```shell
wget https://raw.githubusercontent.com/Testnetnodes/Sonaric-Network/main/sonaric.sh && chmod +x sonaric.sh && ./sonaric.sh
```

 ## ✅ 22 numaralı portumuzu açalım
```shell
ufw allow 22
ufw allow ssh
```
![image](https://github.com/Testnetnodes/Sonaric-Network/assets/115115403/04055994-1d8f-4478-94e6-d138e3885706)

 
 ## ✅ Nodemizin başarıyla kurulup kurulmadığını kontrol edelim
```shell
sonaric node-info
```
![image](https://github.com/Testnetnodes/Sonaric-Network/assets/115115403/de1581a4-bba6-490e-aba0-2392a5caece2)

 ## ✅ Sıra geldi GUI'yi çalıştırmaya
🔎 Aşağıda yazacağımız kodda bulunan "user@your-vps-ip" kısmını kendi IP bilgilerimize göre düzenleyeceğiz. 
🔎 ÖRN : Diyelim ki sunucumuzun IP adresi 187.23.17.369 olsun.Belirttiğim yeri bu şekilde düzenleyeceğiz.   📌    root@187.23.17.369 
```shell
ssh -L 127.0.0.1:44003:127.0.0.1:44003 -L 127.0.0.1:44004:127.0.0.1:44004 -L 127.0.0.1:44005:127.0.0.1:44005 -L 127.0.0.1:44006:127.0.0.1:44006 user@your-vps-ip
```

Örnek Kod :
```
| ssh -L 127.0.0.1:44003:127.0.0.1:44003 -L 127.0.0.1:44004:127.0.0.1:44004 -L 127.0.0.1:44005:127.0.0.1:44005 -L 127.0.0.1:44006:127.0.0.1:44006 root@187.23.17.369 |
```
Kodu girdikten sonra ## Yes Diyoruz ve devam ediyoruz..


 

 

 
 
