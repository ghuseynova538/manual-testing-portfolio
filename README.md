# Manual-Testing-Portfolio
Bu depoda manual test layihələrim və test ssenarilərim yer alır.
# 📋 Manual Testing Portfoliom

Bu depoda proqram təminatının sınaqdan keçirilməsi (QA) üzrə öyrəndiyim metodologiyaları və tətbiq etdiyim real test ssenarilərini paylaşıram.

## 🚀 Layihə 1: Login Funksionallığının Testi
Bu layihə çərçivəsində bir veb saytın giriş panelini müxtəlif ssenarilərlə yoxlamışam.

### ✅ Test Case-lər (Ssenarilər)
| ID | Test Addımı | Gözlənilən Nəticə | Status |
|:---|:---|:---|:---|
| TC-01 | Düzgün email və şifrə ilə giriş | İstifadəçi panelinə keçid edilməli | Keçdi ✅ |
| TC-02 | Səhv şifrə daxil etmək | "Şifrə yanlışdır" mesajı görünməli | Keçdi ✅ |
| TC-03 | Boş sahələrlə düyməni sıxmaq | "Sahə doldurulmalıdır" xəbərdarlığı | Keçdi ✅ |
| TC-04 | Sərhəd yoxlanışı: 7 simvoldan ibarət şifrə | "Şifrə ən az 8 simvol olmalıdır" xətası | Keçdi ✅ |
| TC-05 | Sərhəd yoxlanışı: 17 simvoldan ibarət şifrə | "Şifrə ən çox 16 simvol olmalıdır" xətası | Keçdi ✅ |
## 🐞 Tapılan Xətalar (Bug Reports)

### Bug ID: BUG-001
* **Başlıq:** Axtarış düyməsi boş buraxıldıqda səhifə yenilənmir və xəbərdarlıq çıxmır.
* **Ciddilik (Severity):** Medium (Orta).
* **Prioritet (Priority):** Low (Aşağı).
* **Mühit (Environment):** Google Chrome (Versiya 120.0), Windows 11.

**Reproduce Steps (Xətanı təkrarlamaq üçün addımlar):**
1. Saytın ana səhifəsinə daxil ol.
2. Axtarış xanasını tamamilə boş saxla.
3. "Axtar" (Search) düyməsini sıx.

**Gözlənilən Nəticə (Expected Result):**
Səhifədə "Lütfən axtarış sözü daxil edin" mesajı görünməli idi.

**Faktiki Nəticə (Actual Result):**
Səhifədə heç bir dəyişiklik baş vermir, düymə reaksiya vermir.

## 🛠 İstifadə etdiyim alətlər
- **Test İdarəetmə:** Google Sheets / Excel
- **Bug İzləmə:** GitHub Issues
- **Texnologiya:** Manual (Əl ilə) Testing
