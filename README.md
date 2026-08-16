# 📍 Tooltif Change Locasyon

[![Language](https://img.shields.io/badge/Language-C%23-239120?logo=csharp&logoColor=white)](https://learn.microsoft.com/dotnet/csharp/)
[![UI](https://img.shields.io/badge/UI-Windows%20Forms-0078D4?logo=windows&logoColor=white)](https://learn.microsoft.com/dotnet/desktop/winforms/)
[![IDE](https://img.shields.io/badge/IDE-Visual%20Studio-5C2D91?logo=visualstudio&logoColor=white)](https://visualstudio.microsoft.com/)
[![License](https://img.shields.io/badge/License-See%20LICENSE-green.svg)](LICENSE)

**Tooltif-Change-Locasyon**, C# Windows Forms tabanlı bir proje iskeletidir. Repository adı, tooltip ve lokasyon değişimiyle ilgili bir çalışma fikrine işaret etse de mevcut kaynak kodunda bu davranışın uygulanmış bir iş mantığı bulunmamaktadır.

Bu nedenle README, projede gerçekten bulunan kodu temel alır ve uygulanmamış özellikleri mevcut özellik gibi göstermemektedir.

## 🎯 Proje Amacı

Windows Forms üzerinde bir kullanıcı arayüzü oluşturmak ve ileride tooltip/konumla ilişkili davranışların geliştirilebileceği bir temel sunmak.

## 📌 Mevcut Durum

Mevcut kaynak kodunda:

- `Program.cs` uygulamanın giriş noktasını oluşturur.
- `Form1.cs` temel Windows Forms form sınıfını içerir.
- Form başlatılırken `InitializeComponent()` çağrılır.
- Repository'de ayrı bir `LICENSE` dosyası bulunur.

> Tooltip konum değiştirme, ekran koordinatı yönetimi veya başka bir lokasyon algoritması mevcut kodda doğrulanmadığı için dokümantasyonda uygulanmış özellik olarak belirtilmemiştir.

## 🧰 Teknoloji Kartları

| Teknoloji | Kullanım |
|---|---|
| ![C#](https://img.shields.io/badge/C%23-239120?logo=csharp&logoColor=white) | Uygulama dili |
| ![WinForms](https://img.shields.io/badge/Windows%20Forms-0078D4?logo=windows&logoColor=white) | Masaüstü arayüz |
| ![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91?logo=visualstudio&logoColor=white) | Geliştirme ortamı |

## 📂 Proje Yapısı

```text
Tooltif-Change-Locasyon/
├── TooltifChangeLocasyon.sln
├── TooltifChangeLocasyon/
│   ├── Program.cs
│   ├── Form1.cs
│   ├── Form1.Designer.cs
│   ├── Form1.resx
│   └── Properties/
├── LICENSE
└── README.md
```

## 🚀 Kurulum

```bash
git clone https://github.com/ebubekirbastama/Tooltif-Change-Locasyon.git
cd Tooltif-Change-Locasyon
```

`TooltifChangeLocasyon.sln` dosyasını Visual Studio ile açın ve projeyi **Build → Build Solution** ile derleyin.

## ▶️ Kullanım

Mevcut sürüm temel bir Windows Forms başlangıç uygulamasıdır. Projeyi çalıştırdığınızda `Form1` açılır.

## 🛣️ Geliştirme Yol Haritası

- [ ] Tooltip oluşturma ve özelleştirme
- [ ] Tooltip konumunu fare koordinatlarına göre değiştirme
- [ ] Ekran sınırlarını algılama
- [ ] Çoklu monitör desteği
- [ ] Sağ/sol/yukarı/aşağı konum seçenekleri
- [ ] DPI ölçeklendirme desteği
- [ ] Örnek demo ekranı

## 🤝 Katkıda Bulunma

1. Repository'yi fork edin.
2. Yeni bir branch oluşturun.
3. Değişikliğinizi yapın.
4. Test edin.
5. Pull Request gönderin.

## 📄 Lisans

Lisans koşulları için [`LICENSE`](LICENSE) dosyasına bakın.

## 👨‍💻 Geliştirici

**Ebubekir Bastama**

GitHub: https://github.com/ebubekirbastama
