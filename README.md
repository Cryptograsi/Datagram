# Datagram

Öncelikle Datagram dashboard'e [buradan](https://dashboard.datagram.network?ref=463212633) kayıt olun


## Datagram Klasörü Oluşturun
```
mkdir datagram
cd datagram
```

## Repoyu İndirip Çalışma İzni Verin
```
wget https://github.com/Datagram-Group/datagram-cli-release/releases/latest/download/datagram-cli-x86_64-linux
chmod +x datagram-cli-x86_64-linux
```

## Screen Açın
```
screen -S datagram
```

## Nodu Çalıştırın
```
./datagram-cli-x86_64-linux run -- -key YOUR_API_KEY
```

DİKKAT!!!:  Kodda "YOUR_API_KEY" yazan yeri kendi nodunuzun API Key'i ile değiştirin. API Key almak için ssteki gibi önce Wallet, sonra Licences tıklayıp KEY yazan bölümden alın.

![Ekran görüntüsü 2025-06-12 103840](https://github.com/user-attachments/assets/e4cb5d68-6930-48e6-a480-6622e12496b7)

![Ekran görüntüsü 2025-06-12 104656](https://github.com/user-attachments/assets/f51359f6-f593-4986-a3d3-3e3ed6eea082)

Not: Screenden çıkmak için (CTRL+A+D) tuş takımını kullanın. Yeniden screen'e girmek isterseniz screen -r datagram kodunu kullanın

