# Rezerviz — SaaS Randevu ve İşletme Yönetim Platformu

**Portföy / Proje Tanıtımı · 2026 · 2 kişilik ekip projesi**

Rezerviz, randevuyla çalışan küçük hizmet işletmelerinin rezervasyon, çalışan, hizmet ve günlük operasyon süreçlerini tek bir dijital ortamda yönetmesini hedefleyen bir SaaS uygulaması prototipidir.

> **Durum:** İlk geliştirme sürümü tamamlandı; ticari kullanıma açılmadı. Canlı uygulama ve demo sunucusu şu anda aktif değildir. Bu depo yalnızca portföy amaçlıdır; uygulamanın kaynak kodunu içermez.

## Problem ve çözüm

Randevuların manuel takibi; müsaitlik kontrolü, çalışan planlaması ve randevu çakışmalarının önlenmesini zorlaştırabilir. Rezerviz, işletme yönetim paneli ve müşteriye dönük rezervasyon akışıyla bu süreçleri dijitalleştirmeyi amaçlar.

## Geliştirilen başlıca işlevler

- İşletme, çalışan ve hizmet yönetimi
- Çalışma saatleri ve uygun zaman dilimlerinin kontrolü
- Çevrim içi rezervasyon talebi, oluşturma ve onay akışları
- Randevu çakışmalarını önlemeye yönelik kontroller
- Kullanıcı kayıt, giriş ve yetkilendirme akışları
- İşletme yönetim paneli ve randevu takibi
- Stok ve bildirim işlemlerine yönelik uygulama uç noktaları

## Teknoloji ve mimari

| Katman | Kullanılan teknolojiler |
| --- | --- |
| Uygulama ve arayüz | Next.js (App Router), React, TypeScript, Tailwind CSS |
| API | Next.js Route Handlers, REST tarzı HTTP uç noktaları |
| Veri ve kimlik doğrulama | PostgreSQL, Supabase, Supabase Auth |
| Sürüm kontrolü | Git, GitHub |
| Yayın / altyapı çalışmaları | Vercel, Cloudflare |

**Yüksek seviyeli akış:** Müşteri rezervasyon ekranı / işletme paneli → Next.js uygulaması ve API uç noktaları → Supabase kimlik doğrulama ve PostgreSQL veri katmanı.

## Projedeki katkım

İki kişilik ekipte ürünün farklı geliştirme aşamalarında görev aldım. Özellikle:

- İlişkisel veri tabanı tasarımı ve işletme, çalışan, hizmet, randevu verilerinin modellenmesi
- Supabase ve PostgreSQL üzerinde veri erişimi, kullanıcı yetkilendirme ve güvenlik yapılandırmaları
- Veri işlemleri ve uygulama–veri tabanı entegrasyonlarının geliştirilmesi
- Rezervasyon akışlarının ve müsaitlik / çakışma kontrollerinin uygulanmasına katkı
- Uygulamanın test edilmesi ve yayın altyapısının hazırlanması

## Ürün geliştirme açısından kazanımlar

- İşletme ihtiyacını dijital ürün işlevlerine dönüştürme
- Veri modeli ile kullanıcı akışları arasındaki ilişkiyi kurma
- Yetkilendirme, veri güvenliği ve operasyonel kuralları birlikte değerlendirme
- Küçük ekipte uçtan uca ürün geliştirme ve koordinasyon

## Ekran görüntüleri

Güvenli ve kişisel veri içermeyen ürün ekran görüntüleri hazırlandığında bu bölüme eklenecektir. Bu depo canlı demo veya çalıştırılabilir uygulama sunmaz.

## Kaynak kodu ve güvenlik

Uygulamanın kaynak kodu ayrı bir **özel (private)** depoda tutulur. Bu portföy deposunda API anahtarları, ortam değişkenleri, müşteri verileri, veritabanı dökümleri veya gizli altyapı ayrıntıları paylaşılmaz.

---

**CV için kısa açıklama:** Rezerviz — küçük hizmet işletmelerinin randevu ve operasyon süreçlerini dijitalleştiren SaaS prototipi. İki kişilik ekipte özellikle PostgreSQL/Supabase veri modeli, kimlik doğrulama, erişim yetkilendirmesi ve veri güvenliği alanlarında çalıştım.
