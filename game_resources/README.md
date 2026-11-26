# Game Resources (Split ZIP Staging)

Dito ilagay o i-upload ang mga pinaghati-hating `.zip` files ng iyong game resources bago i-push sa GitHub (halimbawa: `assets.part1.zip`, `assets.part2.zip`, o `assets.zip.001`, `assets.zip.002`).

## Mga Paalala
- **GitHub File Size Limit:** Siguraduhing bawat split file ay mas maliit sa **100 MB** (kung sa GitHub website ka mag-uupload, mas mainam kung **25 MB** pababa bawat file).
- **Safe sa Android Build:** Ang folder na ito ay nasa root ng project kaya hindi ito makakasira sa Android resource compilation at hindi lalaki ang APK habang naka-archive pa ang files.
- **Para magamit sa App:** Kapag handa na ang mga extracted files, puwede na nating ilipat ang mga ito sa `app/src/main/assets/`, `app/src/main/res/drawable/`, o `app/src/main/res/raw/`.
