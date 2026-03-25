# 👋 CSharp_MERHABADUNYA1

## Türkçe

### Açıklama
Bu depo, tek bir düğmeye tıklayınca `Merhaba Dünya :)` mesaj kutusu gösteren basit bir Windows Forms uygulamasıdır. Amaç WinForms giriş noktasını (Program.cs), form tasarımını (Form1.Designer.cs) ve olay tabanlı buton kullanımı örneğini göstermektir.

### Özellikler
- .NET Framework 4.7.2 hedefleyen Windows Forms uygulaması
- Tek düğmeli arayüz, merkezde açılan pencere
- `Merhaba Dünya :)` içerikli mesaj kutusu (başlık: `Selam`)

### Gereksinimler
- Windows işletim sistemi
- .NET Framework 4.7.2 Developer Pack veya Windows üzerinde .NET SDK
- Tercihen Visual Studio (Windows Desktop development workload yüklü)

### Kurulum ve Çalıştırma
1. Depoyu klonlayın:
   git clone https://github.com/mhilmicicek07/CSharp_MERHABADUNYA1.git
2. Proje dizinine girin:
   cd CSharp_MERHABADUNYA1
3. Visual Studio ile çalıştırma:
   - MERHABADUNYA1.sln dosyasını açın.
   - F5 veya “Start” ile uygulamayı başlatın.
4. Komut satırı ile (Windows):
   - dotnet build MERHABADUNYA1/MERHABADUNYA1.csproj
   - bin/Debug/MERHABADUNYA1.exe dosyasını çalıştırın.

Beklenen davranış: Pencere açılır, “Lütfen Tıklayın” butonuna bastığınızda “Merhaba Dünya :)” mesaj kutusu görünür.

### Proje Dosya Yapısı
CSharp_MERHABADUNYA1
├── MERHABADUNYA1.sln
├── MERHABADUNYA1/
│   ├── App.config
│   ├── Form1.cs
│   ├── Form1.Designer.cs
│   ├── Form1.resx
│   ├── Program.cs
│   └── MERHABADUNYA1.csproj
└── README.md

### Örnek Kod
```csharp
private void button1_Click(object sender, EventArgs e)
{
    MessageBox.Show("Merhaba Dünya :)", "Selam");
}
```

### Yazar
Mehmet Hilmi Çiçek — Full Stack Web Developer  
Konum: Geislingen an der Steige

### Katkıda Bulunma
Katkılarınız memnuniyetle karşılanır. Lütfen değişiklik önerileri için issue açın veya pull request gönderin.

### Lisans
Bu proje açık kaynaklıdır. (Lütfen kullanılacak lisansı belirtin, örn. MIT, Apache-2.0 vb.)

---

## English

### Description
This repository is a minimal Windows Forms app: clicking the single button shows a `Merhaba Dünya :)` message box. It demonstrates the WinForms entry point (Program.cs), form design file (Form1.Designer.cs), and a simple button click handler.

### Features
- Windows Forms app targeting .NET Framework 4.7.2
- Single-button UI, centered window
- Message box text `Merhaba Dünya :)` with caption `Selam`

### Requirements
- Windows OS
- .NET Framework 4.7.2 Developer Pack or .NET SDK on Windows
- Preferably Visual Studio with the Windows Desktop workload

### Setup & Run
1. Clone the repository:
   git clone https://github.com/mhilmicicek07/CSharp_MERHABADUNYA1.git
2. Change directory:
   cd CSharp_MERHABADUNYA1
3. Run with Visual Studio:
   - Open MERHABADUNYA1.sln
   - Press F5 / Start
4. Run from CLI on Windows:
   - dotnet build MERHABADUNYA1/MERHABADUNYA1.csproj
   - Launch bin/Debug/MERHABADUNYA1.exe

Expected behavior: a window opens; clicking “Lütfen Tıklayın” shows the “Merhaba Dünya :)” message box.

### Project Structure
CSharp_MERHABADUNYA1
├── MERHABADUNYA1.sln
├── MERHABADUNYA1/
│   ├── App.config
│   ├── Form1.cs
│   ├── Form1.Designer.cs
│   ├── Form1.resx
│   ├── Program.cs
│   └── MERHABADUNYA1.csproj
└── README.md

### Sample Code
```csharp
private void button1_Click(object sender, EventArgs e)
{
    MessageBox.Show("Merhaba Dünya :)", "Selam");
}
```

### Author
Mehmet Hilmi Çiçek — Full Stack Web Developer  
Location: Geislingen an der Steige

### Contributing
Contributions are welcome — please open an issue or submit a pull request.

### License
This project is open source. (Please specify a license such as MIT or Apache-2.0.)

---

## Deutsch

### Beschreibung
Dieses Repository zeigt eine minimalistische Windows-Forms-App: Beim Klick auf den einzigen Button erscheint eine `Merhaba Dünya :)`-Meldung. Es demonstriert den WinForms-Einstiegspunkt (Program.cs), die Form-Designer-Datei (Form1.Designer.cs) und einen einfachen Button-Click-Handler.

### Merkmale
- Windows-Forms-Anwendung für .NET Framework 4.7.2
- Ein Button, zentriertes Fenster
- Meldungsfenstertext `Merhaba Dünya :)` mit Titel `Selam`

### Voraussetzungen
- Windows-Betriebssystem
- .NET Framework 4.7.2 Developer Pack oder .NET SDK unter Windows
- Empfehlenswert: Visual Studio mit Windows Desktop workload

### Installation & Ausführung
1. Repository klonen:
   git clone https://github.com/mhilmicicek07/CSharp_MERHABADUNYA1.git
2. In das Verzeichnis wechseln:
   cd CSharp_MERHABADUNYA1
3. Aus Visual Studio starten:
   - MERHABADUNYA1.sln öffnen
   - F5 / Start drücken
4. Über die Kommandozeile (Windows):
   - dotnet build MERHABADUNYA1/MERHABADUNYA1.csproj
   - bin/Debug/MERHABADUNYA1.exe ausführen

Erwartetes Verhalten: Ein Fenster öffnet sich; beim Klick auf „Lütfen Tıklayın“ erscheint die Meldung „Merhaba Dünya :)“.

### Projektstruktur
CSharp_MERHABADUNYA1
├── MERHABADUNYA1.sln
├── MERHABADUNYA1/
│   ├── App.config
│   ├── Form1.cs
│   ├── Form1.Designer.cs
│   ├── Form1.resx
│   ├── Program.cs
│   └── MERHABADUNYA1.csproj
└── README.md

### Beispielcode
```csharp
private void button1_Click(object sender, EventArgs e)
{
    MessageBox.Show("Merhaba Dünya :)", "Selam");
}
```

### Autor
Mehmet Hilmi Çiçek — Full Stack Web Developer  
Ort: Geislingen an der Steige

### Mitwirken
Beiträge sind willkommen — bitte öffnen Sie ein Issue oder senden Sie einen Pull Request.

### Lizenz
Dieses Projekt ist Open Source. (Bitte geben Sie eine Lizenz an, z. B. MIT oder Apache-2.0.)
