# 🦅 ALBATROS - Kişisel Verimlilik ve Oyunlaştırma Sistemi

**ALBATROS**, günlük görevlerinizi, alışkanlıklarınızı ve odaklanma sürelerinizi oyunlaştırma elementleriyle birleştiren modern bir üretkenlik uygulamasıdır. Seviye atlayın, rütbe kazanın ve hayatınızı bir RPG oyununa dönüştürerek yönetin!

---

## 🚀 Başlangıç

### Kurulum
Program, kuruluma ihtiyaç duymadan doğrudan çalıştırılabilir (Portable). İndirdiğiniz klasör içerisindeki `ALBATROS.exe`  dosyasını çalıştırmanız yeterlidir.

### İlk Giriş ve Kayıt
Uygulamayı ilk açtığınızda **Giriş (Login)** ekranı sizi karşılar.
1. Eğer hesabınız yoksa **"Kayıt Ol"** sekmesine geçin.
2. Bir kullanıcı adı ve şifre belirleyerek **Kayıt Ol** butonuna tıklayın.
3. Kayıt işlemi tamamlandıktan sonra oluşturduğunuz bilgilerle giriş yapabilirsiniz.

> **Not:** Verileriniz tamamen yerel olarak bilgisayarınızda (`albatros.db`) saklanır.

---

## 🖥️ Arayüz Tanıtımı

Uygulama modern ve karanlık temalı bir arayüze sahiptir. Sol tarafta **Navigasyon Menüsü**, sağ tarafta ise seçili modülün içeriği bulunur.

*   **Panel (Dashboard)**: Genel durumunuz, seviyeniz, XP ve HP barlarınızın bulunduğu özet ekran.
*   **Görevler**: Yapılacaklar listenizi yönettiğiniz alan.
*   **Odak**: Pomodoro tekniği ile çalışabileceğiniz zamanlayıcı.
*   **Alışkanlıklar**: Günlük rutinlerinizi takip ettiğiniz bölüm.
*   **Raporlar**: Uzun vadeli istatistikleriniz (Geliştirme aşamasında).
*   **Ayarlar**: Profil ve uygulama ayarları.

---

## ✅ Görev Yönetimi (Tasks)

Görevlerinizi tamamlayarak **XP (Tecrübe Puanı)** kazanırsınız.

### ➕ Yeni Görev Ekleme
1. Görevler sayfasındaki **"+ YENİ GÖREV"** butonuna tıklayın.
2. Açılan pencerede:
    *   **Başlık**: Görevin adı.
    *   **Kategori**: "Pro" (İş/Okul) veya "Kişisel".
    *   **Zorluk**: Kolay, Orta, Zor (Zorluk arttıkça kazanılan XP artar).
    *   **Seçenekler**:
        *   *Günlük Tekrar*: Her gün sıfırlanır (XP vermez, rutin takibi içindir).
        *   *Kritik Görev (!)*: Yapılmazsa veya silinirse **Can (HP)** düşürebilir.
3. **KAYDET** butonuna basın.

### Görev İşlemleri
*   **Tamamlama**: Görevin solundaki kutucuğu işaretleyin. Anında XP kazanırsınız ve seviye ilerlemeniz artar.
*   **Silme**: Göreve sağ tıklayın ve "Sil" seçeneğini seçin.

---

## 🍅 Odak Modu (Focus)

Dikkatiniz dağılmadan çalışmak için Odak Modu'nu kullanın.

### Kullanım
1. **Program Seçimi**: Üst kısımdan bir ön ayar seçin (Örn: 25 Dk Odak / 5 Dk Mola).
2. **Görev Bağlama (Opsiyonel)**: Alt kısımdan, üzerinde çalıştığınız görevi seçerek o göreve odak süresi ekleyebilirsiniz.
3. **Başlat**: **ODAKLAN** butonuna basın. Sayaç geriye doğru saymaya başlayacaktır.

### Özellikler
*   **Zen Modu**: Arayüzü sadeleştirerek sadece sayacı gösterir.
*   **Ambiyans**: Sağ alt köşeden yağmur, ateş, kafe sesi gibi arka plan sesleri açabilirsiniz.
*   **Mini Mod (⧉)**: Pencereyi küçülterek ekranın köşesine sabitler.
*   **Beyin Dökümü (Not Ekle)**: Çalışırken aklınıza gelen ilgisiz fikirleri not alarak odağınızı bozmadan devam etmenizi sağlar.

> ⚠️ **Uyarı:** "Zor" zorluk seviyesindeyseniz, odak oturumunu iptal etmek **-10 HP** kaybetmenize neden olur!

---

## 📅 Alışkanlıklar (Habits)

Her gün düzenli yapmak istediğiniz (Kitap okumak, Su içmek vb.) eylemleri buradan takip edin.

*   **Ekleme**: Sağ üstteki **"+ YENİ"** butonu ile ekleyin.
*   **İşaretleme**: O gün yaptıysanız **"YAP"** butonuna tıklayın.
*   **Zincir (Streak)**: Her gün üst üste yaptığınızda "Streak" sayınız (🔥) artar. Bir gün atlarsanız zincir kırılabilir!

---

## 🎮 Oyunlaştırma Sistemi (Gamification)

Hayatınızı bir RPG karakteri gibi geliştirin.

### 🛡️ İstatistikler ve Barlar
*   **XP (Mavi Bar)**: Görev tamamladıkça artar. Bar dolduğunda **Seviye Atlarsınız (Level Up)**.
*   **HP (Kırmızı Bar)**: Can puanınızdır. Başlangıçta 100'dür.
*   **Nitelikler**: Odak, Disiplin, Hız ve İstikrar puanlarınız aktivitelerinize göre otomatik hesaplanır.

### 💀 Riskler ve Ölüm
*   **Kritik Görevler**: Zamanında yapılmayan veya silinen kritik görevler HP düşürür.
*   **Odak İptali**: Zor modda odak bozulursa HP düşer.
*   **ÖLÜM**: HP 0'a düşerse karakteriniz **ölür**. Seviye düşersiniz (Level Down) ve bazı istatistikleriniz sıfırlanır. Dikkatli olun!

### 🏆 Rütbeler
Seviyeniz arttıkça rütbeniz değişir (Örn: Çaylak -> Avcı -> Usta...). Yeni rütbeler Dashboard'da rozet olarak görünür.

---

## ⚙️ Ayarlar

Uygulamayı kendinize göre özelleştirin.

### 1. Hesap
*   Kullanıcı adınızı değiştirebilirsiniz.

### 2. Genel & Sistem
*   **Başlangıç**: Bilgisayar açıldığında otomatik başlatma.
*   **Kapanış**: "X"e basınca programı kapatmak yerine tepsiye (saat yanına) küçültme.
*   **Her Zaman Üstte**: Albatros penceresini diğer pencerelerin üzerinde tutma.
*   **Verileri Sıfırla**: Tüm ilerlemenizi siler ve başa döner.

### 3. Görünüm
*   **Tema**: Koyu (Dark) veya Açık (Light) mod seçimi.
*   **Renk**: Uygulama vurgu rengini (Mavi, Kırmızı, Yeşil vb.) değiştirme.
*   **Ölçeklendirme**: Yazı ve pencere boyutunu büyütüp/küçültme (%80 - %150).

### 4. Odak & Zaman
*   **Otomatik Mola**: Odak süresi bitince otomatik olarak mola sayacını başlatır.
*   **Tik Sesi**: Sayaç çalışırken klasik saat sesi çıkarır.
*   **Günlük Hedef**: Günde kaç saat odaklanmak istediğinizi belirleyin.

### 5. Ses
*   Genel ses seviyesi ve ambiyans ses seviyesini ayrı ayrı ayarlayabilirsiniz.

### 6. Oyunlaştırma (Zorluk)
*   **Zen Modu**: Sadece verimlilik, ceza yok.
*   **Normal**: Dengeli deneyim.
*   **Spartan (Zor)**: Hata affetmez! Odak bozmak HP götürür.

---

## ⌨️ Klavye Kısayolları

Hızlı işlem yapmak için bu kısayolları kullanabilirsiniz:

| Kısayol | İşlev |
| :--- | :--- |
| **F5** | Odak Modu Zamanlayıcısını Başlat/Durdur |
| **F12** | Patron Modu (Uygulamayı gizle) |
| **Ctrl + N** | Hızlı Görev Ekleme Penceresi |

---

*ALBATROS 2026 - Atakan Köymen tarafından geliştirilmiştir.*
