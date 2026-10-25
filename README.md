# trader-bekci

Trader botunun **sunucu dışı bekçisi**. Oracle'daki sunucu tamamen durursa, sunucunun kendi
bildirimleri de onunla birlikte susar. Bu depo GitHub'ın sunucularında saatte bir koşar ve
sunucunun herkese açık "buradayım" nabzını (ntfy) ve tünelini kontrol eder. Nabız 25 dakikadan
eskiyse ya da tünel cevap vermiyorsa iş başarısız olur ve GitHub depo sahibine e-posta gönderir.

Bu depoda kod, anahtar ya da sır yoktur; botun kaynağı ayrı ve gizli depodadır.
