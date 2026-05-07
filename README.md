# רדיו מיקי טבריה — תיעוד אתר

> אתר אינטרנט רשמי של רדיו מיקי טבריה — מרכז התקנות אביזרי רכב יוקרה ומתקין מורשה מובילאיי.
> **כתובת:** https://www.radio-micky.co.il

---

## תוכן עניינים

1. [פרטי העסק](#פרטי-העסק)
2. [מבנה הקבצים](#מבנה-הקבצים)
3. [דפי האתר](#דפי-האתר)
4. [שירותים ומוצרים](#שירותים-ומוצרים)
5. [תכונות טכניות](#תכונות-טכניות)
6. [SEO ומטא-תגיות](#seo-ומטא-תגיות)
7. [אינטגרציות חיצוניות](#אינטגרציות-חיצוניות)
8. [עיצוב ו-CSS](#עיצוב-ו-css)
9. [JavaScript — פונקציות עיקריות](#javascript--פונקציות-עיקריות)
10. [פריסה ו-Hosting](#פריסה-ו-hosting)
11. [לוג תיקונים ושינויים](#לוג-תיקונים-ושינויים)

---

## פרטי העסק

| שדה | פרטים |
|-----|--------|
| **שם העסק** | רדיו מיקי טבריה |
| **בעלים** | מיקי אוחנה |
| **כתובת** | שוק העירוני, רחוב 407, טבריה 1410101 |
| **טלפון** | 04-6717333 |
| **WhatsApp** | +972-46717333 |
| **אימייל** | micky.ohana@gmail.com |
| **שנת הקמה** | 1996 |
| **שעות פתיחה** | ראשון–חמישי: 09:00–13:00 |
| **דירוג גוגל** | 4.7 ⭐ (47 ביקורות) |
| **Facebook** | https://www.facebook.com/Radio.Micky.Tiberias10/ |
| **Instagram** | https://www.instagram.com/radio.micky.tiberias/ |

---

## מבנה הקבצים

```
radio-micky/
├── index.html          # דף הבית הראשי
├── mobileye.html       # דף נחיתה ייעודי למובילאיי
├── proof.html          # דף נחיתה ייעודי למצלמות PROOF Z-4K
├── robots.txt          # הנחיות לסורקי אינטרנט
├── sitemap.xml         # מפת אתר ל-SEO
├── netlify.toml        # הגדרות פריסה ב-Netlify
├── takana-151.pdf      # תקנה 151 של משרד התחבורה
└── images/
    ├── logo.png                # לוגו האתר
    ├── mobileye-logo.jpg       # לוגו Mobileye
    ├── proof-logo.jpg          # לוגו PROOF
    ├── proof-product.jpg       # תמונת מוצר PROOF Z-4K
    ├── skylock-logo.jpg        # לוגו סקיילוק
    ├── cobra-logo.jpg          # לוגו COBRA
    ├── nippon-logo.jpg         # לוגו Nippon
    ├── alpine-logo.jpg         # לוגו Alpine
    ├── mobileye-logo.jpg       # לוגו Mobileye
    └── IMG_xxxx.jpeg           # גלריית תמונות התקנות (9 תמונות)
```

---

## דפי האתר

### 1. דף הבית — `index.html`
**URL:** https://www.radio-micky.co.il/  
**גודל:** ~1,038 שורות / 71.2 KB

**מבנה הדף (סדר סעיפים):**

| סעיף | תיאור | ID/Class |
|------|--------|----------|
| Nav | ניווט ראשי sticky עם לוגו, קישורים ותפריט המבורגר | `#navbar` |
| Hero | באנר ראשי אדום עם כותרת, כפתורי קשר וסטטיסטיקות | `#hero` |
| Mobileye Strip | פס כחול עם לוגו מובילאיי וכפתור בדיקת זכאות | `.mby-strip` |
| Brands Bar | לוגואים של המותגים (Mobileye, PROOF, Skylock, COBRA, Nippon, Alpine) | `.brands-bar` |
| Eligibility | טופס בדיקת זכאות מובילאיי לפי מספר רישוי | `#eligibility` |
| PROOF Video | סעיף חשוך עם תיאור PROOF Z-4K ווידאו YouTube | `.proof-sec` |
| About | אודות העסק, תכונות ופרטי מנהל | `#about` |
| Services | 6 כרטיסי שירות (מובילאיי, PROOF, סקיילוק, COBRA, Nippon, Alpine) | `#services` |
| Gallery | גלריית 9 תמונות התקנות עם lightbox | ללא ID |
| Reviews | 4 ביקורות לקוחות | `#reviews` |
| CTA Banner | בנר קריאה לפעולה אדום | `.cta-ban` |
| Contact | פרטי קשר + טופס שליחת הודעה | `#contact` |
| Footer | לוגו, זכויות יוצרים, רשתות חברתיות | `footer` |

---

### 2. דף מובילאיי — `mobileye.html`
**URL:** https://www.radio-micky.co.il/mobileye  
**גודל:** ~785 שורות / 49.8 KB

**מבנה הדף:**

| סעיף | תיאור |
|------|--------|
| Hero | באנר כחול (צבע מובילאיי) עם 3 כפתורי פעולה |
| Eligibility | טופס בדיקת זכאות מרכזי |
| How It Works | 4 שלבים של תהליך ההתקנה |
| Product | מובילאיי 8 — תכונות ומפרט |
| Info | מידע מקצועי, תקנה 151, אזורי שירות |
| FAQ | 6 שאלות נפוצות |
| CTA | 3 כפתורי קשר |

---

### 3. דף PROOF — `proof.html`
**URL:** https://www.radio-micky.co.il/proof.html

**מבנה הדף:**

| סעיף | תיאור |
|------|--------|
| Hero | באנר שחור עם 3 כפתורי פעולה + וידאו |
| Stats | 4 מפרטים: 4K / 24/7 / 64GB / 2TB |
| Features | 6 יתרונות עיקריים |
| Models | 3 דגמים: Z-4K / FR-400 / PRO |
| Info | מידע מקצועי ומפרט טכני |
| Process | 3 שלבי התקנה |
| FAQ | 5 שאלות נפוצות |
| CTA | טופס פנייה + כפתורי קשר |

---

## שירותים ומוצרים

### מובילאיי (Mobileye)
- **דגם:** Mobileye 8
- **מתקין:** מורשה ממשרד התחבורה
- **החזר:** 1,500 ₪ לרכבים שנרשמו 1.1.2000–30.4.2017 (תקנה 151)
- **זמן התקנה:** 60–120 דקות
- **כיסוי:** כל צפון ישראל

**יכולות המערכת:**
- אזהרה מהתנגשות קדמית
- זיהוי סטייה מנתיב
- זיהוי מרחק בטיחות
- אזהרה להולכי רגל ורוכבי אופניים
- זיהוי שלטי מהירות

---

### מצלמות PROOF Z-4K
- **רזולוציה:** 4K קדמית + Full HD אחורית
- **קישוריות:** SIM סלולרי מובנה + WiFi
- **GPS:** מובנה עם אנטנה חיצונית
- **אחסון:** 64GB (תמיכה עד 2TB)
- **חשמל:** 12V / 24V
- **אפליקציה:** iOS + Android, בעברית

**3 דגמים:**
| דגם | מתאים ל | תכונה מרכזית |
|-----|----------|--------------|
| Z-4K | רכב פרטי | 4K + SIM מובנה |
| FR-400 | כל רכב | Full HD, דיסקרטי |
| PRO | ציי רכב | ניהול מרוכז |

---

### מיגון ואיתור
- **סקיילוק (Skylock / רב בריח):** חסימת הנעה, GPS, שליטה מרחוק
- **COBRA:** אזעקה חכמה, חסימת הנעה, SMS, GPS

### מולטימדיה ושמע
- **Nippon:** מסך מגע, GPS, Apple CarPlay, Android Auto, Bluetooth
- **Alpine:** רמקולים, מגברים, מערכות שמע יוקרתיות

---

## תכונות טכניות

### בדיקת זכאות מובילאיי (Live API)
- **API:** data.gov.il (מאגר ממשלתי פתוח)
- **Resource ID:** `83bfb278-7be1-4dab-ae2d-40125a923da1`
- **URL:** `https://data.gov.il/api/3/action/datastore_search?resource_id=...&q={plate}`
- **תהליך:** הזנת מספר רישוי → בדיקה מיידית → הצגת תוצאה → טופס ליד

### טופס ליד (Lead Form)
- מוצג לאחר תוצאת בדיקת הזכאות
- שדות: שם, טלפון, מספר רישוי (אוטומטי)
- שליחה דרך EmailJS → micky.ohana@gmail.com
- EmailJS Service: `Radio-Micky`
- EmailJS Template (ליד): `template_6tk6oi7`

### טופס יצירת קשר (Contact Form)
- שדות: שם, טלפון, אימייל, סוג רכב, שנת ייצור, נושא, הודעה
- שליחה דרך EmailJS → micky.ohana@gmail.com
- EmailJS Template (צור קשר): `template_8ewwmn5`
- EmailJS Public Key: `fTjbYldj3Zug1Hm_M`

### גלריה + Lightbox
- 9 תמונות התקנות
- Lightbox מובנה ב-Vanilla JS
- ניווט עם מקלדת (חצים + Escape)

### וידאו PROOF
- YouTube embed מתעכב (lazy load)
- מזהה וידאו: `TxaUQuvNp5U`
- לחיצה על תמונה → iframe YouTube עם autoplay

### ניווט
- Sticky nav עם blur backdrop
- תפריט המבורגר למובייל (עד 900px)
- Smooth scroll לעוגנים

### אנימציות
- Reveal animation ב-IntersectionObserver
- Pulse animation ללחצן מובילאיי בניווט
- Flash animation ללחצן בדיקת זכאות

---

## SEO ומטא-תגיות

### index.html
- **Title:** רדיו מיקי טבריה | אביזרי רכב יוקרה ומובילאיי — מתקין מורשה
- **Canonical:** https://www.radio-micky.co.il/
- **Schema Type:** AutoPartsStore
- **Coordinates:** 32.7940, 35.5310

### mobileye.html
- **Title:** התקנת מובילאיי בטבריה | מתקין מורשה — החזר 1,500 ₪
- **Canonical:** https://www.radio-micky.co.il/mobileye
- **Schema Type:** Service

### proof.html
- **Title:** מצלמת דרך PROOF Z-4K בטבריה | התקנה מקצועית
- **Canonical:** https://www.radio-micky.co.il/proof.html

### Schema.org (index.html)
```json
{
  "@type": "AutoPartsStore",
  "foundingDate": "1996",
  "telephone": "+97246717333",
  "aggregateRating": { "ratingValue": "4.7", "reviewCount": "47" },
  "openingHours": "ראשון-חמישי 09:00-13:00"
}
```

---

## אינטגרציות חיצוניות

| שירות | שימוש | פרטים |
|-------|--------|--------|
| **EmailJS** | שליחת טפסים | Service: `Radio-Micky` |
| **data.gov.il** | API בדיקת זכאות | מאגר רישיונות רכב |
| **Google Fonts** | פונט Heebo | משקלים: 400/500/700/900 |
| **YouTube** | וידאו PROOF | ID: `TxaUQuvNp5U` |
| **WhatsApp** | כפתורי קשר | `https://wa.me/97246717333` |
| **Waze** | ניווט לעסק | קישור לחנות |
| **Facebook** | רשת חברתית | Radio.Micky.Tiberias10 |
| **Instagram** | רשת חברתית | radio.micky.tiberias |
| **Google Reviews** | ביקורות | קישור שיתוף |

---

## עיצוב ו-CSS

### פלטת צבעים (CSS Variables)
| משתנה | צבע | שימוש |
|-------|-----|--------|
| `--red` | `#c62828` | צבע ראשי, כפתורים, לינקים |
| `--red-dark` | `#8e0000` | hover |
| `--gold` | `#f9a825` | הדגשות, כפתור זכאות |
| `--mby` | `#003087` | צבע מובילאיי |
| `--green` | `#2e7d32` | הודעות הצלחה |
| `--text` | `#1a1a1a` | טקסט ראשי |
| `--bg` | `#fff` | רקע |
| `--bg-soft` | `#f7f7f7` | רקע משני |

### פונט
- **Heebo** (Google Fonts) — כל המשקלים
- Fallback: Arial Hebrew, Arial, sans-serif
- כיוון: RTL

### Breakpoints
| נקודה | תיאור |
|-------|--------|
| 900px | תפריט מובייל (המבורגר) |
| 768px | גריד דו-עמודי → עמודה אחת |
| 680px | פס מובילאיי — עמודה אחת |
| 600px | Footer — עמודה אחת |
| 520px | טופס זכאות — עמודה אחת |

### תכונות נגישות (Accessibility)
- Skip link לתוכן הראשי
- `aria-label` על כל אלמנט אינטראקטיבי
- `role` attributes (navigation, banner, main, contentinfo)
- `aria-live` על תוצאות בדיקת זכאות
- Focus visible styles
- prefers-reduced-motion support

---

## JavaScript — פונקציות עיקריות

### index.html

| פונקציה | תיאור |
|---------|--------|
| `runCheck()` | בדיקת זכאות מובילאיי מול API ממשלתי |
| `submitLead()` | שליחת טופס ליד דרך EmailJS |
| `submitCF()` | שליחת טופס צור קשר דרך EmailJS |
| `openLightbox(idx)` | פתיחת גלריה מוגדלת |
| `closeLightbox()` | סגירת גלריה |
| `changeImage(dir)` | ניווט בין תמונות בגלריה |
| `playProofVideo()` | הפעלת וידאו YouTube של PROOF |
| `closeProofVideo()` | סגירת וידאו |
| `showToast(msg, dur)` | הצגת הודעת toast |
| `onPlateInput(el)` | validation לשדה מספר רישוי |
| `clearPlate()` | ניקוי שדה מספר רישוי |
| `resetElig()` | איפוס תצוגת תוצאות בדיקה |

### mobileye.html
- `runCheck()` — גרסה ייעודית לדף מובילאיי
- `submitLead()` — שליחת ליד
- `toggleFaq(el)` — פתיחה/סגירה של שאלות נפוצות

---

## פריסה ו-Hosting

- **Hosting:** Netlify (מחובר לגיטהאב אוטומטית)
- **Repository:** https://github.com/OhanaMichael/radio-micky
- **Branch:** main
- **Deploy:** אוטומטי עם כל push ל-main
- **Domain:** https://www.radio-micky.co.il

---

## לוג תיקונים ושינויים

| תאריך | Commit | שינוי |
|-------|--------|-------|
| 07/05/2025 | `abac8fb` | **fix:** הוספת `pointer-events:none` ל-`.hero::before` בmobileye.html — תיקון חסימת לחצני WhatsApp, טלפון ובדיקת זכאות |
| השבוע | `de860ac` | SEO: שדרוג מלא — Schema, mobileye page, robots, sitemap, keywords, NAP |
| השבוע | — | feat: עמוד נחיתה PROOF Z-4K |
| השבוע | — | fix: בתפריט ובסקציה proof קישורים לעמוד + לוגו |
| השבוע | — | שינוי שמות קבצי לוגו לאנגלית |
| לפני שבועיים | — | Initial commit — Radio Micky with Analytics and SEO |

---

## הערות מפתח

- כל ה-CSS וה-JS הם **inline** בתוך קבצי ה-HTML (אין קבצים חיצוניים)
- אין framework — Vanilla HTML/CSS/JS בלבד
- האתר תומך ב-RTL (עברית) בכל הדפים
- תמונות נטענות עם `loading="lazy"` (חוץ מתמונות hero שנטענות eager)
- EmailJS מאותחל ב-`window.load` (defer)
- ה-`.hero::before` ב-mobileye.html הוא תמונת SVG רקע דקורטיבית — חייב `pointer-events:none` כדי לא לחסום לחצנים
