# Steam Oyun Verisi Analizi

SteamSpy API'sinden en popüler 100 oyunun verisini çekip, pandas ile temizleyip,
SQLite'a yazıp SQL sorgularıyla analiz ettiğim, seaborn ile görselleştirdiğim bir
pekiştirme projesi.

## Kullanılan araçlar
- Python (requests, pandas, sqlite3, seaborn, matplotlib)
- SteamSpy API (steamspy.com/api.php)

## Yapılan analizler
- Fiyat ile inceleme oranı ilişkisi (korelasyon: 0.18)
- Tür bazında oyun sayısı ve ortalama fiyat
- Fiyat dağılımı

## Nasıl çalıştırılır
1. `pip install -r requirements.txt`
2. `steam_data_analysis.ipynb` dosyasını Jupyter'da aç ve hücreleri sırayla çalıştır.