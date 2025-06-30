# 🏆 Turnuva Master

Modern ve kapsamlı bir turnuva yönetim sistemi. React, TypeScript ve Supabase ile geliştirilmiştir.

## 🚀 Özellikler

- **Turnuva Yönetimi**: Lig, Eleme ve Karma (Grup) sistemi ile turnuva oluşturma
- **Takım & Oyuncu**: Takım ve oyuncu ekleme, düzenleme, istatistik takibi
- **Maç Yönetimi**: Otomatik fikstür oluşturma, skor girişi, gol/asist kayıtları
- **İstatistikler**: Puan durumu, gol krallığı, asist krallığı, performans analizi
- **Instagram Çıktıları**: Sosyal medya paylaşımı için optimize edilmiş görsel çıktılar
- **Kullanıcı Sistemi**: Güvenli giriş/kayıt, profil yönetimi
- **Responsive Tasarım**: Mobil, tablet ve masaüstü uyumlu

## 🎯 Neler Yapabilirsiniz

- Farklı formatlarda turnuva oluşturun
- Takımlarınızı ve oyuncularınızı yönetin
- Otomatik fikstür oluşturun (karma lig grup sistemi)
- Maç sonuçlarını girin ve istatistikleri takip edin
- Detaylı gol/asist kayıtları tutun
- Puan durumunu ve sıralamaları görüntüleyin
- Instagram için optimize edilmiş çıktılar alın
- Herkese açık turnuvaları keşfedin

## 📸 Ekran Görüntüleri

### Ana Sayfa
Modern ve kullanıcı dostu arayüz ile turnuva yönetimine giriş.
![image](https://github.com/user-attachments/assets/29abf2e2-1658-4b81-8bd1-a4211aa14a69)

### Keşfet Sayfası
![image](https://github.com/user-attachments/assets/c7d6a68d-1318-4e1e-9e93-8dd5d3654d99)

### Turnuva Detayları
![image](https://github.com/user-attachments/assets/dc88a4cf-d647-4250-9149-35f26a2f33a3)
![image](https://github.com/user-attachments/assets/f5fbd176-7207-41f4-8b7a-9db96b019255)

### İstatistik Sayfası
![image](https://github.com/user-attachments/assets/820a4833-675f-4b4d-9747-67dc4b39788d)

## 📦 Kurulum

### Ön Gereksinimler
- Node.js 18+
- Supabase hesabı

### 1. Projeyi İndirin
```bash
git clone https://github.com/kullaniciadi/turnuva-yonetim-sistemi.git
cd turnuva-yonetim-sistemi
```

### 2. Bağımlılıkları Yükleyin
```bash
cd Design
npm install
```

### 3. Çevre Değişkenlerini Ayarlayın
`.env` dosyası oluşturun:
```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

### 4. Supabase Veritabanını Kurun
`schema.ts` dosyasındaki SQL komutlarını Supabase SQL editöründe çalıştırın.

### 5. Uygulamayı Başlatın
```bash
npm run dev
```

Uygulama `http://localhost:5173` adresinde çalışacaktır.

---
