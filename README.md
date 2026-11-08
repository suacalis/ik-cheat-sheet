# İK için Python Kopya Kâğıtları

Plotly, pandas, Seaborn, matplotlib ve düzenli ifadeler (RegEx) kopya kâğıtlarındaki komutların **insan kaynakları verisiyle** yeniden yazılmış, aranabilir ve **tarayıcıda çalışan** etkileşimli sürümleri. Kodlar [Pyodide](https://pyodide.org) (WebAssembly Python) ile sayfanın içinde çalışır; kurulum gerekmez.

**Site:** https://suacalis.github.io/ik-cheat-sheet/

| Sayfa | Kaynak | İçerik |
|---|---|---|
| [Plotly Express](https://suacalis.github.io/ik-cheat-sheet/plotly.html) | DataCamp | Etkileşimli grafikler ve `update_traces` ile özelleştirme |
| [pandas](https://suacalis.github.io/ik-cheat-sheet/pandas.html) | Dataquest | 70 komut: okuma/yazma, temizlik, filtreleme, groupby, birleştirme, istatistik |
| [Seaborn](https://suacalis.github.io/ik-cheat-sheet/seaborn.html) | DataCamp | 54 komut: kategorik, dağılım, regresyon, matris grafikleri, ızgaralar, estetik |
| [matplotlib](https://suacalis.github.io/ik-cheat-sheet/matplotlib.html) | Dataquest | 64 komut: temel grafikler, özelleştirme, alt grafikler, pandas/seaborn ile çizim |
| [RegEx](https://suacalis.github.io/ik-cheat-sheet/regex.html) | Dataquest | 62 komut + canlı test aracı: İK metinlerinde desen eşleme ve veri temizliği |

## Özellikler
- Her komut için düzenlenebilir, çalıştırılabilir Python hücresi (Ctrl+Enter)
- Türkçe karakterlere duyarsız arama; Türkçe kavram → komut eşlemesi
- Giriş sayfasında beş sayfanın tüm komutlarında ortak arama
- Grafikleri PNG, dışa aktarılan dosyaları (`indir("dosya.xlsx")`) bilgisayara indirme
- Güncelliğini yitirmiş komutlar (`df.append`, `distplot`, `factorplot` vb.) için güncel karşılıklar ve uyarılar

## Yerelde açmak
Dosyalar tek başına çalışır: indirip Chrome, Edge veya Firefox ile açın. İlk açılışta Python paketleri internetten yüklenir.

Veriler sentetiktir ve öğretim amaçlıdır.
