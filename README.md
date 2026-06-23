# בשי יעקב — אתר פורטפוליו | Bashy Yacob — Portfolio

אתר פורטפוליו דו-לשוני (עברית RTL / אנגלית LTR) למפתחת אתרים — מושך לקוחות פרילנס ומציג פרויקטים למעסיקים.

**🌐 אתר חי:** https://bashy-yacob.github.io/portfolio/

A bilingual (Hebrew RTL / English LTR) developer portfolio — single self-contained `index.html`, no build step.

---

## איך זה בנוי

- **קובץ אחד:** כל האתר נמצא ב-`index.html` (HTML + CSS + JavaScript inline). אין build, אין npm.
- **דו-לשוני:** כפתור החלפת שפה (he/en) עם החלפת כיוון RTL/LTR ושמירת בחירה ב-`localStorage`.
- **רספונסיבי:** מותאם מובייל ודסקטופ, ללא תלות חיצונית.

## עריכת תוכן

כל הטקסטים נמצאים באובייקט `I18N` בתוך תגית ה-`<script>` שבסוף `index.html` —
מפתח לכל מחרוזת, עם גרסת עברית (`he`) ואנגלית (`en`). פשוט עורכים שם.

מחירי חבילות השירותים, תיאורי הפרויקטים, הניסיון וההשכלה מסומנים כ"לדוגמה — ניתן לעריכה".

## טופס יצירת קשר

הטופס נופל אוטומטית ל-`mailto` (פותח את תוכנת המייל). כדי שישלח מייל אוטומטית:
מוציאים מפתח חינמי ב-[web3forms.com](https://web3forms.com) ומדביקים אותו במשתנה
`WEB3FORMS_KEY` שב-`index.html`.

## הפעלת GitHub Pages

Settings → Pages → Source: *Deploy from a branch* → Branch: `main` → `/(root)` → Save.
