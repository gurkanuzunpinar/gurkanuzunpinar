[English](README.md) | **Türkçe**

# Gürkan Uzunpınar

**Yapay Zekâ ve Otomasyon Geliştiricisi** · finans ve operasyon için doğrulanabilir yapay zekâ sistemleri · filolog kökenli

Yanlış bir rakamın paraya mal olduğu işler için yapay zekâ sistemleri geliştiriyorum. Yazılımı kendi kendime öğrendim: Outlier'da RLHF ile dil modellerini eğitmeye başladığım 2024'ten beri yapay zekâyla uygulamalı çalışıyor, 2026'dan beri üretim yazılımı geliştiriyorum. Yapay zekâ destekli çalışıyorum: mimariyi beyin fırtınası oturumlarında yapay zekâyla birlikte tasarlıyor, spesifikasyonları ben yazıyor ve doğrulamayı ben üstleniyorum; kodun çoğunu bu kontrol altında kodlama ajanları yazıyor.

## Öne çıkan

**[Z-Report Pipeline: vaka çalışması](https://github.com/gurkanuzunpinar/z-report-pipeline/blob/main/README.tr.md)**
Muhasebe verisi için üretimde çalışan deterministik ayrıştırma ve doğrulama motoru. Dokuz akaryakıt istasyonunun yazarkasalarından gün sonunda basılan Z raporlarını, ayda ortalama 1.500 adet, vergi beyanına giren doğrulanmış muhasebe kayıtlarına dönüştürüyor. Tasarım kuralı: bir değer ya fişin kendi aritmetiğiyle kanıtlanır ya da bir insanın önüne gelir. Depoda sentetik veriyle çalıştırılabilen bir referans uygulama da var.
`Python` `FastAPI` `SQL Server` `PaddleOCR` `pytest`: 598 commit ve 2.850+ otomatik test.

## Nasıl çalışıyorum

- **Hata asla sessiz geçmemeli.** Makul görünen yanlış bir değer boş hücreden daha tehlikelidir; bu yüzden belirsizlik gizlenmez, gösterilir.
- **Kararı deterministik kurallar verir, okumayı modeller yapar.** Mali veride bir dil modelinin tahmini asla gerçek sayılmaz.
- **Önce ölç, sonra iyileştir.** Yanlış kabul, operatör soruları ve P95 gecikme ayrı KPI'lar olarak izlenir.
- **Ajanlara OCR'a duyulan şüpheyle yaklaşırım.** Ajanın ürettiği şey, bağımsız bir kanıt onaylayana kadar adaydır. Görevler ölçülmüş kanıt ve kabul ölçütü içeren kapalı tanımlardır; iş yalıtılmış worktree'lerde ve veritabanı kopyalarında yapılır, kararı ölçüm verir, bağlam paylaşmayan bir denetçi sonucu kırmaya çalışır. Hiçbir alt ajanın mali veriye yazma yolu yok. ([Yöntemin tamamı](https://github.com/gurkanuzunpinar/z-report-pipeline/blob/main/README.tr.md#nasıl-geliştirildi-yapay-zekâ-destekli-aynı-şüpheyle))

## Geçmiş

İngiliz Dili ve Edebiyatı (Ege Üniversitesi) → öğretmenlik → Türk Hava Yolları → uluslararası seyahat satışı (özel satış ve muhasebe yazılımında ürün sahipliği) → yapay zekâ eğitim verisi (Outlier) → bir akaryakıt perakende grubunda kurum içi yapay zekâ ve otomasyon. Dil, yapı ve belirsizlik hep malzemem oldu. Şimdi onlarla yazılımda çalışıyorum.

📫 [LinkedIn](https://www.linkedin.com/in/gurkanuzunpinar) · Ankara / uzaktan
