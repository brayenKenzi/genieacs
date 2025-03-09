# INSTALL GENIEACS OTOMATIS
This is autoinstall GenieACS 

# Usage
```
sudo apt update && sudo apt upgrade
```
```

sudo apt install git curl -y
```
```

sudo git clone https://github.com/brayenKenzi/genieacs
```
```
cd genieacs
```
```
sudo chmod +x install.sh && chmod +x darkmode.sh
```
```
chmod +x install-stb.sh
```
INSTALL GENIEACS DARK MODE v@1.2.13
```
bash darkmode.sh
```
INSTALL STB or RASBERRY v@1.2.13
```
bash install-stb.sh
```
INSTALL GENIEACS THEMA ORIGINAL v@1.2.13
```

sudo bash install.sh
```

Baca terlebih dahulu !!!

#=== Script update GenieACS ====#

Config sebelumnya akan terhapus dan tergantikan oleh config baru

Yang akan diupdate, yaitu:

   • Admin >> Preset <br>
   • Admin >> Provosions <br>
   • Admin >> Virtual Parameter<br>
   • Admin >> Config<br>
   
#===Script/config tersebut akan terganti dengan yang baru ====#

Jika anda memiliki config/script custom buatan anda sendiri,<br> 
silahkan backup terlebih dahulu, kemudian setelah update lakukan config manual lagi sesuai config custom anda.<br>

Device, user, permisions, tidak akan terpengaruh<br>
Bagi yang confignya error, akan ter-repair dengan script ini<br>
Anda masih bisa kembali ke konfigurasi sebelumnya dengan memilih restore<br>
======= CARA RESTORE ========<br>
```
cd
```
```
sudo mongorestore --db=genieacs --drop genieacs-backup/genieacs
```


