# 🎓 Kurs Takip Sistemi

Kişisel gelişim kursları için devam ve ödeme takip uygulaması.  
**Tek HTML dosyası** — kurulum gerektirmez, internet bağlantısı gerekmez.

## 🚀 GitHub Pages'te Yayınlama (Adım Adım)

### 1. GitHub Hesabı Aç
- [github.com](https://github.com) → **Sign up** (zaten varsa giriş yap)

### 2. Yeni Repository Oluştur
1. Sağ üstte **＋** → **New repository**
2. Repository name: `kurs-takip` (ya da istediğin isim)
3. **Public** seç ✓
4. **Create repository** tıkla

### 3. Dosyaları Yükle
1. Repository sayfasında **uploading an existing file** linkine tıkla
2. `index.html` dosyasını sürükle-bırak
3. **Commit changes** tıkla

### 4. GitHub Pages'i Aç
1. Repository → **Settings** sekmesi
2. Sol menüde **Pages**
3. Source: **Deploy from a branch**
4. Branch: **main** → **/ (root)**
5. **Save** tıkla

### 5. Sitenin Açılmasını Bekle
⏳ 1-2 dakika sonra adresin hazır olur:
```
https://KULLANICI_ADIN.github.io/kurs-takip/
```

---

## 📱 Kullanım

| Özellik | Açıklama |
|---------|----------|
| **＋ Kurs Ekle** | Yeni kurs ekle, renk ve kişi seç |
| **＋ Ders Ekle** | Kursa yeni ders satırı ekle |
| **📅 Tarih** | Ders tarihini kendin yaz |
| **✅ Devam butonu** | Yeşil = gidildi |
| **💳 Ödeme butonu** | Turuncu = ödendi |
| **⬇️ CSV** | Tüm verileri Excel'e aktarılabilir CSV olarak indir |
| **✏️** | Kursu düzenle |
| **🗑** | Kursu sil |

## 💾 Veriler Nerede Saklanır?

Veriler **tarayıcının LocalStorage** hafızasında saklanır.  
Yani:
- ✅ İnternet bağlantısı gerekmez
- ✅ Sunucu gerekmez — tamamen ücretsiz
- ⚠️ Tarayıcı geçmişini/önbelleği temizlersen veriler silinir
- ⚠️ Farklı cihazlar arasında otomatik senkronize olmaz

**Önemli:** Düzenli olarak **⬇️ CSV** ile yedek al!

## 🔄 Güncelleme

Yeni bir `index.html` üretip GitHub'a yükleyince site otomatik güncellenir.

---

*Tek dosya · Sıfır kurulum · Ücretsiz hosting*
