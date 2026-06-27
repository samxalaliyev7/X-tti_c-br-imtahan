# Xətti cəbr və riyazi analiz - 249 suallıq imtahan saytı

Bu paket UNEC PDF-də verilmiş **249 sual** əsasında hazırlanmış GitHub Pages üçün statik imtahan saytıdır.

## Xüsusiyyətlər

- 249 sualın hamısı imtahanda verilir.
- Vaxt: 120 dəqiqə.
- Suallar hər girişdə qarışdırılır.
- Cavab variantlarının yerləri hər dəfə qarışdırılır.
- PDF-də düzgün cavablar qarşısında olan tik işarələri saytda görünmür.
- Hər sual tək-tək göstərilir.
- Cavab seçiləndən sonra sistem avtomatik növbəti suala keçir.
- Sağ tərəfdə sual nömrələri görünür.
- Mavi: cavablanmış sual.
- Sarı: baxılıb cavabsız keçilmiş sual.
- İmtahan bitəndən sonra səhv və cavabsız suallar düzgün cavabla birlikdə göstərilir.

## GitHub Pages üçün yükləmə

1. Bu ZIP faylını aç.
2. İçindəki faylları repository-nin əsas hissəsinə yüklə:
   - `index.html`
   - `questions-data.js`
   - `.nojekyll`
   - `README.md`
   - `DEPLOY_GITHUB_PAGES.md`
3. GitHub-da `Commit changes` et.
4. `Settings -> Pages` bölməsinə keç.
5. Source: `Deploy from a branch` seç.
6. Branch: `main`, folder: `/root` seç.
7. `Save` et.
8. Sayt bir neçə dəqiqəyə aktiv olacaq.

## Qeyd

Bu statik GitHub Pages sistemidir. Tələbələrin nəticələri mərkəzi serverə yığılmır, yalnız tələbənin öz brauzerində göstərilir. Mərkəzi scoreboard üçün backend/database lazımdır.
