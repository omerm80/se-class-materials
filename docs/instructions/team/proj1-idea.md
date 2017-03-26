
<div dir="rtl">
<div>
</div>

חזרה ל[עמוד ראשי](../../..)

# פרויקט 1 – הצעת פרויקט - Software Project Proposal

## כללי (אמ;לק)

### מטרות 
- הכרת הארגונים השותפים וההצעות שלהם
- סקירת הצעה לפרויקט והתאמתה לקורס
- שיתוף הסקר עם כלל הכיתה
- בחירת הצעה

### לוח זמנים
- יום א 26/2 - יריד ארגונים
- עד יום ג 28/2 24:00 - פרסום סקרי הצעות
- עד יום ד 29/2 24:00 - שליחת בקשות שיבוץ לפרויקטים
- עד יום א 5/3 הודעה על הרכב הצוותים ומעבר לשלב אתחול הפרוייקטים

### הרכב הציון
הציון למשימה זו אינו נקבע לפי האם ההצעה שנסקרה עברה לשלב הבא, אלא רק איכותה ופרסומה בזמן. הציון ישוקלל כאחת מהמשימות האישיות בקורס.

### עבודה והגשה
המשימה הנוכחית מתבצעת ביחידים, כל סטודנט סוקר שתי הצעות ולכל אחת כותב ומפרסם דו״ח בטופס שלמטה.

## מבוא

במסגרת הקורס תפתחו מוצר/מערכת תוכנה בעלת ערך ללקוח אמיתי. מטרתכם במשימה זו היא לסקור את הארגון וההצעה שלו לפרויקט ולבחון את מידת ההתאמה לקורס.


### מאגר הרעיונות

השנה אנחנו מפתחים מוצרי תוכנה עובר ארגונים חברתיים בירושלים שנענו לקול קורא. הזמנו את הארגונים ליריד במכללה, זאת כדי ליצור קשר בלתי אמצעי בין הסטודנטים לארגונים. מומלץ לבקר בכמה שיותר ארגונים אך כל סטודנט נדרש לסקור שתי הצעות יותר לעומק. אם יש לכם עוד שאלות לארגונים לאחר היריד, אפשר לפנות לפי פרטי הקשר.

#### [רשימת הרעיונות]

במצגות השיעור הראשון תמצאו קישורים לסקרי [רעיונות מקורס קודמים][prev-ideas] להתרשמות. 

עליכם לבחון האם ההצעה מתאימה לצרכי הקורס בהתאם להנחיות שבהמשך מבחינת גודל ואפשרויות טכניות. מומלץ להתיייעץ עם צוות הקורס, כולל רכזת התכנית. אפשר גם לפנות לאיש הקשר של הארגון המצוין בהצעה בבקשה לבירור פרטים.


## כללי

עליכם לבדוק שהרעיון הוא בעל ערך (לארגון) וישים למימוש בקורס במסגרת המשאבים הזמינים.

א.	הרעיון - לתאר את המערכת המוצעת לפיתוח כך שהאחרים יבינו מהי וישתכנעו שהיא בעלת ערך. מהן הבעיות שהיא באה לפתור? מה יהיו הפונקציות העיקריות שלה?

ב.	תיכון, התכנות ותיכון -  עליכם לתאר תיכון ראשוני (ארכיטקטורה\design) אפשרי למוצר. המטרה היא שיהיה אפשר להעריך באופן ראשוני אם ניתן לבנות את המערכת בעזרת שימוש מיטבי במשאבים: סמסטר אחד, חמישה מהנדסי תוכנה וטכנולוגיה מוצעת (במסגרת התרגיל בקורס נלמד פיתוח אפליקציות רשת - אך ייתכנו פתרונות אחרים). עליכם גם לנתח מספר סיכונים עיקריים ואפשרות מענה (למשל לפי מה שלמדתם בקורס ניהול פרויקט תוכנה, ראו גם למשל עוד על ניתוח סיכונים והערכת עלות-תועלת [כאן][google-blog-risk]),

כמהנדסי תוכנה סביר שתתבקשו לעיתים לבחון רעיונות חדשים וגם להציג ולשכנע בערכם והיתכנותם. עקב אילוצי הקורס ההצגה היא ע״י פרסום במקום משותף ומענה על שאלות דרך פורום הקורס.

משימת השכנוע בערך של רעיון (שלכם או אחרים) היא שלב ראשון לקראת עבודה בצוות לבניית מוצר.

### דרישות המערכת

האילוץ העיקרי הוא שהיא באה לפתור בעיה של ארגון שנענה לקול הקורא שפרסמנו. אך לצרכי הקורס חשוב שזו תהיה מערכת לא טריוויאלית בעלת מספר רכיבי תוכנה.
ביתר פירוט, המערכת צריכה ש:

0. יהיה לה קשר לעולם האמיתי, ז"א היא באה לפתור בעיה אמיתית של מישהו\מישהי אמיתי\ת באמצעות מערכת שעיקרה תוכנה.
0. המערכת תהיה אפליקציית ווב (יישום רשת) בארכיטקטורת לקוח/שרת (ולא אתר או מערכת ניהול תוכן בלבד!). כברירת מחדל, הלקוח יהיה כתוב ב- html/css/js (ומותאם גם ללקוח נייד) והשרת ב- node.js או שפה מונחית עצמים אחרת.
0. השרת צריך לכלול לוגיקה שאינה טריוויאלית (ולא רק בסיס נתונים).
0.	כברירת מחדל הקוד יהיה מאוחסן במאגר פתוח ב- github וגרסה עובדת של השרת תהיה זמינה על גבי תשתית ענן - כך שתהיה למוצר גישה נוחה למפתחים וללקוחות (יילמד בתרגיל).
0. מדובר ברעיון חדש. הוא יכול למשל להיות תוסף (plug-in) לתוכנה קיימת, אך לא העתק מדויק של מוצר קיים או של פרויקט אחר במכללה.
0. המערכת תעשה שימוש משמעותי ולא טריוויאלי ברכיבים ותשתיות קיימים, כגון בסיסי נתונים, רכיבי אימות, [שרותים פתוחים][APIs] ועוד (ולא רק ספריות סטנדרטיות), זאת כדי שהוא יהיה מעניין וגם ישים במגבלות הקורס.
0. יהיה אפשר להדגים את המערכת בזמן ההרצאה וגודלה מתאים להערכתכם לפיתוח במסגרת האילוצים של הקורס (כולל הזמן שייקח ללמוד את הסביבה, התהליך וכדו').
0. רעיונות יוצאי דופן במקוריותם אינם מחויבים לתנאים שלמעלה – בתיאום עם צוות הקורס.

### תכני הסקר

0. שם הסטודנט ושם משתמש בגיטהאב (יש לפתוח חשבון בהקדם - ראו [הדרכה בתרגיל אישי 1] בנושא).
0. שם הארגון
0. מהי המערכת שתפותח? איזו בעיה היא פותרת? מי הם הלקוחות והמשתמשים.
0. מדוע היא כדאית לפיתוח (business case)? מהן החלופות כיום? 
0. שם מוצע לפרויקט ולמוצר (באנגלית)
0. תיכון - תיאור ברמה ראשונית של הרכיבים\מודולים שישמשו במערכת. הוסיפו תרשים אחד לפחות ([דוגמאות][uml-diagrams]). שפות תוכנה וספריות\שירותים מתוכננים לשימוש. 
0. תכנון ראשוני - פרטו בקצרה שלבים שלדעתכם נדרשים כדי לממש את הפרויקט.
0. סיכונים -  מה לדעתכם הסיכונים והבעיות העיקריים שהפרויקט עלול להיתקל בהם? כיצד תנמיכו או תתמודדו איתם. האם אפשר לפתור את הבעיה ללא פיתוח תוכנה? מהם הייתרונות שיכולים להתקבל מהשקעה בפיתוח. 
0. הערות נוספות - עם מי התייעצתם במהלך הסקר, שאלות פתוחות וכדו׳

### הוראות הגשה

- בחירת שתי הצעות לסקירה ע״י רישום שמך ב[טבלת השיבוץ] - (מספיק שם פרטי ואות ראשונה)
- השתתפות ביריד ומילוי [טופס סקר]ֿ. תוכלו להתרשם מ[כלל הסקרים] שמולאו וכך לבחור את הפרויקטים המועדפים על ידיכם.
- שליחה אישית של עדיפויות לפרויקט ב[טופס רישום] 

יש להוסיף בטופס פסקה עם תיאור כללי של הסיבה לבחירה שלכם, במקרה שאתם חלק מצוות מוצע של חמישה סטודנטים יש להוסיף פסקה שבה תשכנעו שהצוות הוא בעל **שונות** (diversity) (ראו גם בהגדרות [משימה קבוצתית 2][project2])

צוות הקורס יעדכן לקראת השבוע הבא על השיבוץ שייעשה בהתאם למידע שתעבירו לעיל.

לו״ז להגשות בתחילת ההנחיות.
להבהרות נוספות פנו בבקשה ל[פורום הקורס].


### הנחיות נוספות
שימו לב לנושאי פרטיות ברשת – חלק גדול מתוצרי העבודה בקורס הם ציבוריים. במידה ואינכם מעוניינים לפרסם פרטים אישיים (כמו שם, ת.ז. ומייל) הקפידו שלא להשתמש בהם במסמכים שמועלים לאתר הקורס (ולכלול אותם רק בטופס ההגשה).


זכרו שמשימה זו היא הבסיס להחלטה על המערכות שנפתח בהמשך הסמסטר. זו גם יכולה להיות הזדמנות לעבוד על רעיון שתמיד חלמתם עליו!

### קישורים נוספים

0.	[מדריך כתיבת SOW]( http://www.rfpsolutions.ca/files/SOW_Writing_Guide2.pdf)
0. [ReadySet תבנית הצעת פרויקט מאתר תבניות](http://readyset.tigris.org/nonav/templates/proposal.html)
0.	Jonathan Rasmusson, [Ten Questions You’d Be Crazy not to Ask at the Start of Your Project](
http://www.pragprog.com/magazines/2010-10/way-of-the-agile-warrior)
0. [תבנית למצגת מבוססת על המאמר הקודם](http://agilewarrior.files.wordpress.com/2011/02/blank-inception-deck1.pptx)
0. [טיפים לפרויקט תוכנה לסטודנטים](http://www.comp.nus.edu.sg/~damithch/guide3e/)
0.	[טיפים לכתיבת מצגת לדוגמא](http://www.slideshare.net/Digitaldarren/top-tips-for-power-point-ignite-style-presentation)

בהנאה ובהצלחה
צוות הקורס

<!-- Links -->
[prev-ideas]:  https://github.com/jce-il/se-class/wiki/PastIdeas
[past-projects]: https://github.com/jce-il/se-class/wiki/PastProjects
[community-ideas]: https://github.com/jce-il/se-class/wiki/community-ideas
[community-pool]: https://docs.google.com/spreadsheets/d/1WS4-7GT-pvlxol_EYN-6Fpd80BRhzqKQ-OMDm9LgNJA/edit#gid=0
[project2]: [[project/project2-team]]
[google-blog-risk]: https://testing.googleblog.com/2016/06/the-inquiry-method-for-test-planning.html
[uml-diagrams]: http://en.wikipedia.org/wiki/Applications_of_UML
[פורום הקורס]: https://gitter.im/jce-il/se17b
[טופס רישום]:  https://docs.google.com/forms/d/e/1FAIpQLScX2G4Ty4tQqXSgYrQdrE5UJP99eSSNo-94kczhgZjd-vLpxw/viewform
[טופס סקר]:https://docs.google.com/forms/d/e/1FAIpQLScmCD1Pfj01_5YuoVklb7bSpSLNe9cVBEsS3MdvPzAqPgp0PA/viewform 
[כלל הסקרים]: https://docs.google.com/spreadsheets/d/1y_sOGkOHcNAArdgfGEl27wuxQ_TnzfLDeO0PTW708ks/edit#gid=603015203
[טבלת השיבוץ]: https://docs.google.com/document/d/1oLp-9rMG0Ol4qlQMQ4oKjlNFgYAHQjzqzNBE0EsZNtU/edit?usp=sharing
[רשימת הרעיונות]: ./organizations.pdf
[הדרכה בתרגיל אישי 1]: https://github.com/jce-il/se-class-materials/blob/master/docs/hw1-deploy-webapp.md#git--github
[APIs]: https://github.com/abhishekbanthia/Public-APIs


</div>
