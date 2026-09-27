> 🇬🇧 [Click here for English](README.md)
# 8-Bit Custom Computer
Bu proje, [Ben Eater'ın efsanevi 8-bit breadboard bilgisayar serisinin](https://www.youtube.com/playlist?list=PLowKtXNTBypGqImE405J2565dvjafglHU) kalıcı ve modüler devre kartlarına (PCB) aktarılmış donanım revizyonudur. Orijinal proje breadboard üzerinde geliştirilmişken, bu depoda devrelerin profesyonel PCB tasarım araçlarıyla FR4 kartlara aktarılmış, güç ve sinyal hatları stabilize edilmiş üretim dosyaları yer almaktadır.

## Modüller
### 1. Clock Module (`/Clock-Module`)
Sistemin kalbini oluşturan saat modülü. 
* **Özellikler:** Ayarlanabilir saat frekansı, manuel adımlama (single-step) ve Halt (durdurma) sinyali desteği.
* **Tasarım:** NE555 zamanlayıcılar ve 74LS serisi mantık kapıları kullanılarak, sinyal bütünlüğü için uygun dekuplaj topolojisiyle ev yapımı (tek katmanlı) üretime uygun tasarlanmıştır.
> [!NOTE]
> **Proje Durumu:** Kalan modüllerin (ALU, Register, RAM vb.) PCB tasarımları henüz tamamlanmamıştır. Modüller arası haberleşmeyi sağlayacak olan veri yolu (bus) mimarisi ve PCB konnektör pin dizilimleri şu an nihai seviyede değildir ve ilerleyen aşamalarda değişikliğe uğrayabilir.
