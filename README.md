Bu repoda sadece Fabricdose adlı siteme ait olan görseller ve bilgilendirme metinleri vardır.
# FabricDose: Yapay Zeka Destekli Tekstil Tasarım Stüdyosu

**FabricDose**, tekstil tasarımcıları için geliştirilmiş, yapay zeka tabanlı profesyonel bir SaaS platformudur. Bu proje, modern web teknolojilerini gelişmiş üretken yapay zeka (Generative AI) modelleriyle birleştirerek, desen tasarım süreçlerini otomatize eder ve hızlandırır.

## 📸 Proje Görselleri

| Kontrol Paneli (Dashboard) | Yapay Zeka İle Üretim (Generator) |
|:---:|:---:|
| ![Dashboard](public/screenshots/dashboard.png) | ![Generator](public/screenshots/generator.png) |
| *Kullanıcı dostu arayüz ve hızlı erişim* | *Metinden doku ve desen üretimi* |

| Stil Transferi (Style Transfer) | Katalog ve Analiz |
|:---:|:---:|
| ![Style Transfer](public/screenshots/transfer.png) | ![Catalog](public/screenshots/catalog.png) |
| *Görsel stillerini desenlere uygulama* | *Teknik analiz ve otomatik etiketleme* |

## 🚀 Öne Çıkan Özellikler

Bu proje, bir tekstil tasarımcısının ihtiyaç duyabileceği tüm araçları tek bir çatı altında toplar:

*   **Generative AI Tasarım**: Google Gemini Vision ve özel modeller kullanarak, sadece metin komutları ile sınırsız sayıda, yüksek çözünürlüklü ve tekrarlanabilir (seamless) kumaş desenleri üretir.
*   **Stil Transferi & Manipülasyon**: Mevcut bir fotoğrafın sanatsal tarzını, başka bir kumaşın dokusuna transfer edebilir.
*   **Akıllı Doku Analizi**: Yüklenen kumaş görsellerini analiz eder, örgü tipini (saten, dimi, vb.) tespit eder ve teknik detayları (gramaj, dokuma sıklığı) otomatik olarak raporlar.
*   **Otomatik Kataloglama**: Tasarımlar için saniyeler içinde profesyonel PDF sunum dosyaları ve etiketler oluşturur.
*   **Sanal Giydirme (Mockup)**: Tasarlanan desenleri 3D model kalitesinde gömlek, elbise veya ev tekstili ürünleri üzerinde gerçekçi bir şekilde görselleştirir.

## 🛠 Kullanılan Teknolojiler ve Mimari

Proje, performans ve ölçeklenebilirlik odaklı modern bir mimari üzerine inşa edilmiştir:

*   **Frontend**: React (Vite), TypeScript, Tailwind CSS
    *   *Detay*: Responsive tasarım, Custom Hooks, Context API ile state yönetimi.
*   **Backend & Veritabanı**: Supabase (PostgreSQL)
    *   *Detay*: Authentication, Row Level Security (RLS), Realtime veritabanı güncellemeleri.
*   **Yapay Zeka (AI) Entegrasyonu**: Google Gemini 1.5 Pro & Vision API
    *   *Detay*: Çok modlu (multimodal) veri işleme ve görsel üretim hatları.
*   **Görüntü İşleme**: Canvas API, SVG manipülasyonu.

---
*Bu proje, modern web geliştirme yeteneklerimi ve yapay zeka entegrasyonu konusundaki uzmanlığımı sergilemek amacıyla geliştirilmiştir.*
