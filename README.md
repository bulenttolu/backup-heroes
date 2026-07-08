# 🦸 Backup Heroes — Heroes Start Here

İş ortakları ve müşteriler için **oyunlaştırılmış Veeam eğitim platformu**. Her modül, gerçek Veeam Backup & Replication web arayüzünün birebir HTML simülasyonunda ("lab") adım adım ilerletir; her tıklamanın **nedenini** anlatır, doğru seçimleri puanlar ve süreci animasyonlarla görselleştirir.

## Modüller

| # | Use Case | Durum |
|---|----------|-------|
| 1 | SQL VM Ajansız Yedekleme (Agentless Backup) — New Backup Job sihirbazı + veri akışı animasyonu | ✅ Yayında |
| 2 | Kurtarma: O Veritabanını Geri Getir | 🔜 Yakında |
| 3 | 3-2-1-1-0 Kuralı ve Kopya Görevleri | 🔜 Yakında |
| 4 | Fidye Yazılımına Karşı Değişmez Yedek | 🔜 Yakında |

## Teknik

- Tek dosya: [`index.html`](index.html) — bağımlılık yok, derleme yok, herhangi bir statik hosta atılabilir.
- Arayüz referansı: [Veeam Help Center — VBR 13 Web UI](https://helpcenter.veeam.com/docs/vbr/userguide/backup_job_name_vm_web.html?ver=13)
- GitHub Pages üzerinden yayınlanır; `main` dalına push = otomatik güncelleme.

---
*Bu platform bir eğitim simülasyonudur; resmi Veeam yazılımı değildir.*
