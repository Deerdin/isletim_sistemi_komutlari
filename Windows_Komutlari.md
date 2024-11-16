# ${{\color{purple}W}}\{{\color{green}i}}\{{\color{pink}n}}\{{\color{yellow}d}}\{{\color{red}o}}\{{\color{orange}w}}\{{\color{brown}s}}\ \ \{{\color{blue}Komutları}}$
## ${{\color{purple} 1. }}\{{\color{cyan}Komut}}$ ---> `hostname` Komutu bilgisayarın adını gösterir.
```shell
hostname 
```
## ${{\color{purple} 2. }}\{{\color{cyan}Komut}}$  ---> `dir` Komutu dizinin yolunu gösterir.
```shell
dir  
```
## ${{\color{purple} 3. }}\{{\color{cyan}Komut}}$  ---> `cd` Komutu belirtilen dizine geçer.
```shell
cd C:\Users
```
```shell
cd C:\Users\erdin
```
```shell
cd C:\Users\erdin\Desktop
```
## ${{\color{purple} 4. }}\{{\color{cyan}Komut}}$  ---> `mkdir` Komutu yeni bir klasör oluşturur.
```shell
mkdir yeni_klasor  
```

## ${{\color{purple} 5. }}\{{\color{cyan}Komut}}$  ---> `del` Komutu bir dosya siler.
```shell
del yeni_klasor
```

## ${{\color{purple} 6. }}\{{\color{cyan}Komut}}$  ---> `tree` Komutu dizin yapısını ağaç şeklinde gösterir.
```shell
tree
```

## ${{\color{purple} 7. }}\{{\color{cyan}Komut}}$  ---> `ren` Komutu bir dizinin adını değiştirir.
```shell
ren eski_isim yeni_isim
```

## ${{\color{purple} 8. }}\{{\color{cyan}Komut}}$  ---> `type` Komutu metin belgesinin içeriğini görüntüler.
```shell
type yeni.txt
```

## ${{\color{purple} 9. }}\{{\color{cyan}Komut}}$  ---> `exit` Komutu terminali kapatır.
```shell
exit
```

## ${{\color{purple} 10. }}\{{\color{cyan}Komut}}$  ---> `resmon` Komutu kaynak izleyicisinin penceresini açar.
```shell
resmon
```

## ${{\color{purple} 11. }}\{{\color{cyan}Komut}}$  ---> `msinfo32` Komutu sistem bilgilerini gösterir. 
```shell
msinfo32
```

## ${{\color{purple} 12. }}\{{\color{cyan}Komut}}$  ---> `winver` Komutu  bir pencere açarak Windows sürüm bilgilerini gösterir.
```shell
winver
```

## ${{\color{purple} 13. }}\{{\color{cyan}Komut}}$  ---> `move` Komutu dosyaları taşımada kullanılır.
```shell
move beni_tasi buraya_tasi
```

## ${{\color{purple} 14. }}\{{\color{cyan}Komut}}$  ---> `whoami` Komutu geçerli kullanıcıyı gösterir.
```shell
whoami  
```

## ${{\color{purple} 15. }}\{{\color{cyan}Komut}}$  ---> `date` Komutu sistem saatini gösterir.
```shell
date 
```

## ${{\color{purple} 16. }}\{{\color{cyan}Komut}}$  ---> `ping` Komutu ağ bağlantılarının doğruluğunu ve ağ cihazlarının erişilebilirliğini test etmek için kullanılır.
```shell
ping google.com 
```

## ${{\color{purple} 17. }}\{{\color{cyan}Komut}}$  ---> `echo` Komutu terminale yazdırmak istenileni yazdırır.
```shell
echo `Merhaba Dünya`
```

## ${{\color{purple} 18. }}\{{\color{cyan}Komut}}$  ---> `cls` Komutu terminali temizler.
```shell
cls
```

## ${{\color{purple} 19. }}\{{\color{cyan}Komut}}$  ---> `history` Komutu terminalde yazdırdığınız komutların geçmişini sunar (sonuna yazılan sayı kaçıncı sırada olduğunu gösterir).
```shell
history 5
```

## ${{\color{purple} 20. }}\{{\color{cyan}Komut}}$  ---> `copy` Komutu dosyaları belirtilen dizine kopyalar.
```shell
copy beni_kopyala buraya_kopyala 
```

## ${{\color{purple} 21. }}\{{\color{cyan}Komut}}$  ---> `shutdown` Komutu 30 saniye sonra bilgisayarı kapatır.
```shell
shutdown /s /t 30
```

## ${{\color{purple} extra }}\{{\color{cyan}Komut}}$  ---> `powershell` üzerinden çalıştırılabilen bir pencere açmamıza yarayan güzel bir kod.
```shell
$isim=read-host -prompt "Lütfen adınızı giriniz"
$mesaj="Sen ne iyi bir insansın "+$isim
$wshell = New-Object -ComObject Wscript.Shell
$wshell.Popup($Mesaj,0,"Günün Mesaji",0x1)
```

## ${{\color{purple} extra }}\{{\color{cyan}Komut}}$  ---> `curl parrot.live` cmd'yi yönetici olarak çalıştırıp komutu yazdığımda güzel renkli bir papağanın giff görüntüsünü sağlayan kod.
```shell
curl parrot.live
```
