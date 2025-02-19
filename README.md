![Ekran görüntüsü 2025-02-19 195604](https://github.com/user-attachments/assets/933f9245-470e-4687-9dfc-b77acac01cdc)

1️⃣ Gerekli Bağımlılıkları Kurma

Öncelikle Rust'ı yükleyelim:
- curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

---

Yüklemeyi tamamladıktan sonra terminali kapatıp tekrar aç veya aşağıdaki komutu çalıştır:
- source $HOME/.cargo/env
---

Daha sonra riscv32i target'ı ekleyelim:
- rustup target add riscv32i-unknown-none-elf
---

2️⃣ Nexus CLI Kurulumu
Hızlı kurulum için aşağıdaki komutu çalıştır:
- curl https://cli.nexus.xyz/ | sh
---


!!!!! Alternatif olarak, manuel yükleme yapmak istersen önce dosyayı indir, sonra çalıştır:
- wget https://cli.nexus.xyz/ -O nexus_install.sh
- chmod +x nexus_install.sh
- ./nexus_install.sh


---

3️⃣ Nexus CLI İlk Kurulum

Kurulumu tamamladıktan sonra, Nexus CLI'yi çalıştır:
- nexus

Burada:

- Kullanım Şartlarını (Terms of Use) kabul etmen istenecek.

- Anonim veya bağlı kanıt modu (proving mode) seçmen gerekecek.
---

4️⃣ Proving Modunu Seçme
- İki seçeneğin var:

1-)  Nexus hesabına bağlan (Önerilir)

- app.nexus.xyz üzerinden bir hesap oluştur.
- Hesap bağlama talimatlarını takip et.
- NEX Puanları kazanabilir, ilerlemeni takip edebilirsin.

2-) Anonim Proving
- Bağlantısız modda çalışır, ancak katkıların kaydedilmez ve ödül kazanamazsın.
- Ödüller almak için CLI’yi Nexus hesabına bağlaman gerekir!
---
Arkadaşlar, Nexus Testnet için GitHub reposunu oluşturduk! 

🎉 Bana destek olmak için aşağıdaki adımları yapabilirsiniz:

- ⭐ Repo’ya yıldız (Star) vererek destek olabilirsiniz!
- 🍴 Fork yaparak projeyi kendi hesabınıza ekleyebilirsiniz!

                      TWİTTER :  https://x.com/GunahkarCasper 
