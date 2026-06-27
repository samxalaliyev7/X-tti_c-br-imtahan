# GitHub Pages aktivləşdirmə təlimatı

GitHub repository-də:

1. `Add file -> Upload files` seç və bu paketin içindəki faylları yüklə.
2. `Commit changes` düyməsinə bas.
3. `Settings` bölməsinə keç.
4. Sol menyuda `Pages` seç.
5. `Build and deployment` hissəsində:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
6. `Save` et.
7. 2-10 dəqiqə gözlə.

Sayt linki belə olacaq:

`https://SENIN_GITHUB_USERNAME.github.io/REPOSITORY_ADI/`

Nümunə:

`https://samxalaliyev7.github.io/xetti-cebr-imtahan/`

Əgər köhnə versiya açılırsa, linkin sonuna bunu əlavə et:

`?v=xetti-cebr-249-readable-v3`

Vacib: `.github/workflows/blank.yml` yaratma. Bu statik sayt üçün lazım deyil və lazımsız "failed check" xətası verə bilər.
