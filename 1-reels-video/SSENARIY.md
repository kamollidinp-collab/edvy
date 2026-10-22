# Edvy — Instagram Reels ssenariysi (50 soniya)

**Kim uchun:** o'quv markaz egalari va direktorlari.
**Maqsad:** egasi o'z muammosini taniydi → Edvy uni hal qilishini 6 ta ekranda ko'radi (`kadrlar/02`–`07`) → profildagi havola orqali bepul namoyishga yozadi.
**Format:** 9:16, 1080 × 1920, ~50 soniya.

Faqat gapiriladigan matn alohida: [`OVOZ-50s.txt`](OVOZ-50s.txt) — ElevenLabs'ga to'g'ridan-to'g'ri qo'yiladi.
Videoda ishlatiladigan kadrlar `kadrlar/` papkasida, sahna tartibida raqamlangan. Boshqa barcha ekranlar rol bo'yicha: [`../2-ilova-ekranlari/`](../2-ilova-ekranlari/).

---

## Sahnalar

| Vaqt | Kadr | Ekrandagi yozuv (yirik) | Ovoz |
|---|---|---|---|
| 0:00–0:03 | To'q ko'k fon `#141B4D`, matn tez kattalashib chiqadi | **Kassa daftar bilan to'g'ri kelmaydimi?** | O'quv markazingizda kassa daftar bilan to'g'ri kelmaydimi? |
| 0:03–0:06 | Xuddi shu fon | **Qarzdorlarni qidirasizmi?** | Qarzdorlarni qidirib yurasizmi? |
| 0:06–0:10 | `kadrlar/01-logo.png` — oq kvadratdagi belgi + **edvy** | **edvy** | Edvy — o'quv markazingiz bitta tizimda. |
| 0:10–0:16 | `kadrlar/02-kassa.png` — vertikal kadrga kesib, to'lovlar ro'yxati bo'ylab sekin suriladi | **Har to'lov — chek bilan** | Har bir to'lov chek bilan qabul qilinadi. Naqd va Click alohida. |
| 0:16–0:21 | `kadrlar/03-qarzdorlar.png` — o'ngdagi qarzdorlar ro'yxatiga zoom | **Qarz — avtomatik · SMS eslatma** | Oylik to'lov o'zi hisoblanadi, qarzdorlarga SMS eslatma ketadi. |
| 0:21–0:25 | `kadrlar/04-oqituvchi-davomat.png` (telefon ramkasida) | **O'qituvchi: davomat telefondan** | O'qituvchi davomatni telefondan qiladi. |
| 0:25–0:31 | `kadrlar/05-ota-ona-davomat.png` | **Ota-ona hammasini ko'radi** | Ota-ona farzandining davomati, bahosi va to'lovini o'z ilovasida ko'radi. |
| 0:31–0:36 | `kadrlar/06-oquvchi-oyin.png` | **O'yin · reyting** | O'quvchilar uchun o'yin va reyting — ular darsdan keyin ham o'qiydi. |
| 0:36–0:41 | `kadrlar/07-direktor-telefon.png` | **Siz — hammasini telefonda** | Siz esa tushum, qarz va yangi mijozlarni telefoningizda ko'rasiz. |
| 0:41–0:46 | To'q fon, yirik raqam sanab chiqadi 0 → 1000+ | **1000+ o'quvchi** · Taraqqiyot Chorsu · DLola filiallari | Taraqqiyot Chorsu va DLola filiallarida ming nafardan ortiq o'quvchi allaqachon Edvy bilan. |
| 0:46–0:50 | `kadrlar/01-logo.png` + tugma ko'rinishidagi yozuv | **Bepul namoyish → profildagi havola** | Bepul namoyish uchun profildagi havola orqali yozing. |

---

## Montaj uchun

- **Birinchi 3 soniya hal qiladi:** savol matni darhol, katta harfda, ovoz bilan bir vaqtda chiqsin. Logo bilan boshlamang.
- **Subtitr shart:** Reels'ni ko'pchilik ovozsiz ko'radi. Ekrandagi yozuv va ovoz bir-birini to'ldiradi.
- **Xavfsiz hudud:** matn va muhim joylar tepadan 250 px va pastdan 420 px ichiga kirmasin, aks holda Instagram tugmalari yopib qo'yadi.
- **Kompyuter ekranlari** 16:9 — ularni butunlay kichraytirmang. Kerakli qismini (kassa ro'yxati, qarzdorlar) vertikal kadrga kesib, sekin suring (Ken Burns).
- **Telefon ekranlari** — telefon ramkasida, fon to'q ko'k `#141B4D`.
- **Kesish ritmi:** har 3–6 soniyada yangi kadr. Musiqa: yengil, 100–110 BPM.
- **Ranglar:** to'q ko'k `#141B4D`, oltin urg'u `#FFD66B`. Logo doim oq fonda.

## ElevenLabs

- **Model:** Eleven v3 — o'zbek tilini qo'llaydi (Multilingual v2 qo'llamaydi).
- **Ovoz:** ishonchli, o'rtacha tezlikda. Avval bitta gapni sinab, o'zbekcha talaffuzi toza ovozni tanlang.
- **Sozlamalar (boshlang'ich):** Stability ≈ 50%, Similarity ≈ 75%, Style ≈ 20%, Speed 1.0–1.05.
- `OVOZ-50s.txt` da so'zlar o'qilishiga moslab yozilgan: "Edvi", "Klik", "es-em-es", "Di-Lola", raqam so'z bilan. Ekrandagi yozuvlarda asl yozilishi qoladi.
- Ovoz ~45–50 soniya chiqadi. Uzun chiqsa, Speed'ni 1.05–1.1 ga ko'taring.

## Tekshirib oling

- **"DLola"** qanday o'qilishi: ovoz faylida "Di-Lola". Boshqacha bo'lsa, faylda shu so'zni almashtiring.
- **"Bepul namoyish"** taklifi va profildagi havola — marketing qarori, kerak bo'lsa oxirgi gapni almashtiring.
