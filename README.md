# Aligned-Layer

## 💥 Aligned Layer 'da proof oluşturduktan sonra tweet atmayı ve discordda bulunan Testnet odasına attığınız tweeti göndermeyi unutmayın ( Ödüllü Olabilir )

# Herhangi bi sunucuda işlemleri yapabilirsiniz.

```console
sudo apt update -y && sudo apt upgrade -y

curl -L https://raw.githubusercontent.com/yetanotherco/aligned_layer/main/batcher/aligned/install_aligned.sh | bash
source /root/.bashrc

curl -L https://raw.githubusercontent.com/yetanotherco/aligned_layer/main/batcher/aligned/get_proof_test_files.sh | bash
```
#

```console
# Alttaki bloğu toplu girin.
rm -rf ~/aligned_verification_data/ &&
aligned submit \
--proving_system SP1 \
--proof ~/.aligned/test_files/sp1_fibonacci.proof \
--vm_program ~/.aligned/test_files/sp1_fibonacci-elf \
--aligned_verification_data_path ~/aligned_verification_data \
--conn wss://batcher.alignedlayer.com
```
> Akabinde altta ki gibi bir çıktı alın, linke tıklayın Verified olmasını bekleyin.

> Son olarakta bu ekran görüntüsünü ailgned'i etiketleyerek - TX HASH İLE BİRLİKTE tweetleyin.

> Tweet'i [discorda](https://discord.gg/b8jKaYBK) testnet kanalında paylaşın.

<img width="1095" alt="Ekran Resmi 2024-06-18 12 33 32" src="https://github.com/ruesandora/Aligned-Layer/assets/101149671/6edfb6e2-7ef1-40b7-9501-c9745e6b139f">
