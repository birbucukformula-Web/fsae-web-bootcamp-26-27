# 🏎️ Birbuçuk Formula Web - Bootcamp 2026-27

Bu repo, **1.5 Adana Formula Student Team** web birimine yeni katılan üyeler için hazırlanan **eğitim ve görev takip** sistemidir.

## 🎯 Amaç

Sıfırdan başlayıp takımdan **full stack geliştirici** olarak mezun olmak. Frontend (HTML, CSS, JavaScript, React), backend (Django) ve mobil (Dart, Flutter) öğrenip, öğrendiklerimizi gerçek projelerde kullanacağız. Burası sadece kod yazmayı değil, **yazdığın kodu anlamayı ve anlatabilmeyi** öğrendiğimiz yerdir.

## 🗺️ Yol Haritası

| Aşama | Konu | Çıktı |
|---|---|---|
| [Task-01](Tasks/Task-01-HTML-CSS) | HTML, CSS (semantik yapı, flexbox, grid, responsive) | Kendi CV siten |
| [Task-02](Tasks/Task-02-JavaScript) | JavaScript (DOM, ES6, fetch, async) | CV sitene etkileşim, bir API'den veri çekme |
| [Task-03](Tasks/Task-03-React) | React + Vite (component, props/state, hooks, router) | Küçük bir React uygulaması |
| [Task-04](Tasks/Task-04-Django) | Python, Django, ORM, REST API, auth, PostgreSQL | Basit bir CRUD API |
| Sonrası | Ana projelerimize katkı: issue al, branch aç, PR, code review | Gerçek ekip akışı |
| [Task-05](Tasks/Task-05-Mini-Proje) | React + Django ile mini full stack proje | Çalışan full stack uygulama |
| [Task-06](Tasks/Task-06-Dart-Flutter) | Dart, Flutter (widget, state, navigation, API bağlantısı) | Django API'ne bağlanan mobil uygulama |

Her aşamanın sonunda kısa bir **demo ve soru-cevap** yapılır: kodunu anlatırsın, birkaç soruyu cevaplarsın.

## 🚀 İleride

Bootcamp ilerledikçe, ana projelere katkı aşamasında takımın kullandığı altyapıyı da öğreneceksin:

- **Vercel:** frontend yayınlama
- **Render:** backend yayınlama
- **Supabase (PostgreSQL):** veritabanı

## 📂 Repo Yapısı

- **Tasks:** Her görevin kendi klasörü var. Görev metni klasörün `README.md` dosyasında, teslimler klasörün içindeki `Tasks` klasörüne yapılır.

## 📏 İsimlendirme Standartları

**Boşluk karakteri yasaktır.** Her kelime **büyük harfle** başlar, kelimeler tire ile ayrılır.

Teslim klasörü: `Submission-[TaskNo]-[GorevAdi]-[Ad]-[Soyad]`

- ✅ `Submission-01-HTML-CSS-Ayse-Yilmaz`
- ❌ `submission-01-html-css-ayse-yilmaz` (küçük harf yasak)
- ❌ `Submission 01 Ayse` (boşluk yasak)

## 📝 Nasıl Ödev Teslim Ederim?

Web arayüzünden "Upload files" kullanmak yasaktır. Git kullanacaksın:

1. Bu repoyu **Fork** et.
2. Fork ettiğin repoyu bilgisayarına indir (`git clone`).
3. İlgili görevin `Tasks` klasörüne git, standarda uygun klasörünü oluştur.
4. Ödevini bu klasöre ekle.
5. `git add`, `git commit`, `git push`.
6. Kendi reponundan ana repoya **Pull Request** aç.

## 🚫 Kurallar

1. **Format hatası = red:** İsimlendirme standardına uymayan PR'lar incelenmeden kapatılır.
2. **Anlamadan yapıştırma yok:** Kodun mantığını anlamadan teslim etmek kabul edilmez. Demo aşamasında kodunu anlatman istenecek.
3. **Yapay zeka serbest, sorumluluk sende:** AI araçlarını kullanabilirsin ama çıktıyı kontrol etmeden ve anlamadan teslim eden sorumlu tutulur.
4. **Profesyonellik:** Commit mesajların açıklayıcı olsun (`feat: CV sitesi eklendi` ✅ | `dosya attim` ❌).

Başarılar! 🏁
