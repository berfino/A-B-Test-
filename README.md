# A/B Test
### Hipotez:

H0: "gate_30" ve "gate_40" versiyonları arasında toplam oyun oynama süreleri açısından anlamlı bir fark yoktur.

H1: "gate_30" ve "gate_40" versiyonları arasında toplam oyun oynama süreleri açısından anlamlı bir fark vardır.

### Columns:

userid : Her bir kullanıcıya özel bir numara.

version: Kullanıcının hangi versiyonu denediğini belirten sütun.

sum_gamerounds: Kullanıcıların oyunu ne kadar süreyle oynadığını ifade eder.

retention_1: Kullanıcının oyunu oynadıktan sonraki ilk gün içinde devam edip etmediğini gösteren sütun.

retention_7: Kullanıcının oyunu oynadıktan sonraki yedinci gün içinde devam edip etmediğini gösteren sütun. 

## Gerekli Kütüphaneler
1. Pandas
2. Plotly Express
3. Scipy.stats anderson, mannwhitneyu

