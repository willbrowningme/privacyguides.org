---
title: "אנדרואיד"
icon: 'simple/android'
---

![לוגו אנדרואיד](assets/img/android/android.svg){ align=right }

**פרויקט הקוד הפתוח של אנדרואיד** היא מערכת הפעלה ניידת בקוד פתוח בהובלת גוגל, המניעה את רוב המכשירים הניידים בעולם. רוב הטלפונים הנמכרים עם אנדרואיד שונו כך שיכללו אינטגרציות פולשניות ואפליקציות כגון שירותי Google Play, כך שתוכל לשפר משמעותית את הפרטיות שלך במכשיר הנייד שלך על ידי החלפת התקנת ברירת המחדל של הטלפון שלך בגרסת אנדרואיד ללא תכונות פולשניות אלו.

[:octicons-home-16:](https://source.android.com/){ .card-link title=דף הבית }
[:octicons-info-16:](https://source.android.com/docs){ .card-link title=תיעוד}
[:octicons-code-16:](https://cs.android.com/android/platform/superproject/){ .card-link title="קוד מקור" }

אלו הן מערכות ההפעלה, המכשירים והאפליקציות של אנדרואיד שאנו ממליצים על מנת למקסם את האבטחה והפרטיות של המכשיר הנייד שלך. למידע נוסף על אנדרואיד:

- [סקירה כללית של אנדרואיד :material-arrow-right-drop-circle:](os/android-overview.md)
- [מדוע אנו ממליצים על GrapheneOS על פני CalyxOS :material-arrow-right-drop-circle:](https://blog.privacyguides.org/2022/04/21/grapheneos-or-calyxos/)

## נגזרות AOSP

אנו ממליצים להתקין במכשיר שלך אחת ממערכות ההפעלה המותאמות אישית של אנדרואיד, המפורטות לפי סדר העדפה, בהתאם לתאימות המכשיר שלך למערכות הפעלה אלו.

!!! note "הערה"

    למכשירי סוף החיים (כגון מכשירי "תמיכה מורחבת" של GrapheneOS או CalyxOS) אין תיקוני אבטחה מלאים (עדכוני קושחה) עקב הפסקת התמיכה של OEM. מכישירים אלה אינם יכולים להיחשב מאובטחים לחלוטין ללא קשר לתוכנה המותקנת.

### GrapheneOS

!!! recommendation

    ![לוגו GrapheneOS](assets/img/android/grapheneos.svg#only-light){ align=right }
    ![לוגו GrapheneOS](assets/img/android/grapheneos-dark.svg#only-dark){ align=right }
    
    **GrapheneOS** היא הבחירה הטובה ביותר בכל הנוגע לפרטיות ואבטחה.
    
    GrapheneOS מספק [התקשות אבטחה](https://en.wikipedia.org/wiki/Hardening_(computing))ושיפורים בפרטיות. יש לו [מקצה זיכרון מוקשה](https://github.com/GrapheneOS/hardened_malloc), הרשאות רשת וחיישן, ועוד [תכונות אבטחה] שונים (https://grapheneos.org/features). GrapheneOS מגיע גם עם עדכוני קושחה מלאים וחתום בונה, כך אתחול מאומת נתמך במלואו.
    
    [:octicons-home-16: דף הבית](https://grapheneos.org/){ .md-button .md-button--primary }
    [:octicons-eye-16:](https://grapheneos.org/faq#privacy-policy){ .card-link title="מדיניות פרטיות" }
    [:octicons-info-16:](https://grapheneos.org/faq){ .card-link title=תיעוד}
    [:octicons-code-16:](https://grapheneos.org/source){ .card-link title="קוד מקור" }
    [:octicons-heart-16:](https://grapheneos.org/donate){ .card-link title=תרומה }

GrapheneOS תומך ב-[Sandboxed Google Play](https://grapheneos.org/usage#sandboxed-google-play), המריץ את [שירותי ](https://en.wikipedia.org/wiki/Google_Play_Services)Google Play בארגז חול מלא כמו כל אפליקציה רגילה אחרת. המשמעות היא שאתה יכול לנצל את רוב שירותי Google Play, כגון [הודעות דחיפה](https://firebase.google.com/docs/cloud-messaging/), תוך מתן שליטה מלאה על ההרשאות והגישה שלהם, ובזמן שהם מכילים אותם ל[פרופיל עבודה](os/android-overview.md#work-profile) או [פרופיל משתמש](os/android-overview.md#user-profiles) לבחירתך.

טלפונים של Google Pixel הם המכשירים היחידים שעומדים כעת ב[דרישות אבטחת החומרה](https://grapheneos.org/faq#device-support) של GrapheneOS.

### DivestOS

!!! recommendation

    ![לוגו של DivestOS](assets/img/android/divestos.svg){ align=right }
    
    **DivestOS** הוא נגזרת של [LineageOS](https://lineageos.org/).
    DivestOS יורשת [מכשירים נתמכים] רבים (https://divestos.org/index.php?page=devices&base=LineageOS) מ - LineageOS. יש לו builds חתומים, מה שמאפשר לקבל [אתחול מאומת](https://source.android.com/security/verifiedboot) בחלק מהמכשירים שאינם Pixel.
    
    [:octicons-home-16: דף הבית](https://divestos.org){ .md-button .md-button--primary }
    [:simple-torbrowser:](http://divestoseb5nncsydt7zzf5hrfg44md4bxqjs5ifcv4t7gt7u6ohjyyd.onion){ .card-link title="שירות בצל" }
    [:octicons-eye-16:](https://divestos.org/index.php?page=privacy_policy){ .card-link title="מדיניות הפרטיות" }
    [:octicons-info-16:](https://divestos.org/index.php?page=faq){ .card-link title=תיעוד}
    [:octicons-code-16:](https://github.com/divested-mobile){ .card-link title="Source Code" }
    [:octicons-heart-16:](https://divested.dev/index.php?page=donate){ .card-link title=לתרומה }

ל - DivestOS יש פגיעות ליבה ([CVE](https://en.wikipedia.org/wiki/Common_Vulnerabilities_and_Exposures)) [שמתוקן](https://gitlab.com/divested-mobile/cve_checker) אוטומטית, פחות בועות קנייניות, וקובץ [מארחים](https://divested.dev/index.php?page=dnsbl) מותאם. זה מקשיח WebView, [Mulch](https://gitlab.com/divested-mobile/mulch), מאפשר [CFI](https://en.wikipedia.org/wiki/Control-flow_integrity) לכל הארכיטקטורות ו [חלוקת מצב רשת למחיצות](https://developer.mozilla.org/en-US/docs/Web/Privacy/State_Partitioning), ומקבל עדכונים "מחוץ-ללהקה". DivestOS כולל גם תיקוני ליבה מ - GrapheneOS ומאפשר את כל תכונות אבטחת הליבה הזמינות באמצעות התקשות [defconfig](https://github.com/Divested-Mobile/DivestOS-Build/blob/master/Scripts/Common/Functions.sh#L758). כל הגרעינים החדשים יותר מגרסה 3.4 כוללים עמוד מלא [חיטוי](https://lwn.net/Articles/334747/) וכל ~22 הגרעינים המורכבים מ - Clang מופעלים [`- flatrivial - auto - var - init =0`](https://reviews.llvm.org/D54604?id=174471).

DivestOS מיישמת כמה תיקוני התקשות מערכת שפותחו במקור עבור GrapheneOS. DivestOS 16.0 ומעלה מיישמת את מתג ההרשאה ל[`אינטרנט`](https://developer.android.com/training/basics/network-ops/connecting) וחיישנים של GrapheneOS, [מקצה זיכרון מוקשה](https://github.com/GrapheneOS/hardened_malloc), [exec-spawning](https://blog.privacyguides.org/2022/04/21/grapheneos-or-calyxos/#additional-hardening), [JNI](https://en.wikipedia.org/wiki/Java_Native_Interface) [constification](https://en.wikipedia.org/wiki/Const_(computer_programming)), ו partial [bionic](https://en.wikipedia.org/wiki/Bionic_(software)) תיקוני הקשחה. 17.1 תכונות גבוהות יותר GrapheneOS של רשת מלאה [MAC הקצאה אקראית](https://en.wikipedia.org/wiki/MAC_address#Randomization) אפשרות, [`ptrace_scope`](https://www.kernel.org/doc/html/latest/admin-guide/LSM/Yama.html) שליטה, ואתחול מחדש אוטומטי/Wi - Fi/Bluetooth [אפשרויות פסק זמן](https://grapheneos.org/features).

DivestOS משתמשת ב-F-Droid כחנות האפליקציות המוגדרת כברירת מחדל. בדרך כלל, אנו ממליצים להימנע מ-F-Droid עקב [בעיות האבטחה](#f-droid) הרבות שלו. עם זאת, לעשות זאת ב-DivestOS לא כדאי; המפתחים מעדכנים את האפליקציות שלהם באמצעות מאגרי F-Droid משלהם ([DivestOS Official](https://divestos.org/fdroid/official/?fingerprint=E4BE8D6ABFA4D9D4FEEF03CDDA7FF62A73FD64B75566F6DD4E5E577550BE8467) ו- [DivestOS WebView](https://divestos.org/fdroid/webview/?fingerprint=FB426DA1750A53D7724C8A582B4D34174E64A84B38940E5D5A802E1DFF9A40D2)). אנו ממליצים להשבית את אפליקציית F-Droid הרשמית ולהשתמש ב[Neo Store](https://github.com/NeoApplications/Neo-Store/) כאשר מאגרי DivestOS מופעלים כדי לשמור על רכיבים אלה מעודכנים. לגבי אפליקציות אחרות, השיטות המומלצות שלנו להשגתן עדיין חלות.

!!! warning "אזהרה"

    עדכון קושחה של DivestOS [status](https://gitlab.com/divested-mobile/firmware-empty/-/blob/master/STATUS) ובקרת איכות משתנים בין המכשירים שבהם הוא תומך. אנו עדיין ממליצים על GrapheneOS בהתאם לתאימות המכשיר שלך. עבור מכשירים אחרים, DivestOS היא אלטרנטיבה טובה.
    
    לא לכל המכשירים הנתמכים יש אתחול מאומת, וחלקם מבצעים אותו טוב יותר מאחרים.

## מכשירי אנדרואיד

בעת רכישת מכשיר, אנו ממליצים לקבל אחד חדש ככל האפשר. התוכנה והקושחה של מכשירים ניידים נתמכים רק לזמן מוגבל, ולכן רכישת חדש מאריך את תוחלת החיים ככל האפשר.

הימנע מקניית טלפונים ממפעילי רשתות סלולריות. אלה לעתים קרובות יש **נעול bootloader** ואינו תומך [OEM ביטול נעילה](https://source.android.com/devices/bootloader/locking_unlocking). גרסאות טלפון אלה ימנעו ממך להתקין כל סוג של הפצת אנדרואידחלופית.

היה מאוד **זהיר** בקניית טלפונים יד שנייה משוק מקוון. בדוק תמיד את המוניטין של המוכר. אם המכשיר נגנב, קיימת אפשרות ל[רשימה שחורה של IMEI](https://www.gsma.com/security/resources/imei-blacklisting/). קיים גם סיכון שכרוך בהיותך קשור לפעילות של הבעלים הקודם.

עוד כמה טיפים לגבי מכשירי אנדרואיד ותאימות מערכות הפעלה:

- אל תקנו מכשירים שהגיעו או קרובים לסוף החיים שלהם, עדכוני קושחה נוספים חייבים להיות מסופקים על ידי היצרן.
- אל תקנו טלפונים טעונים מראש של LineageOS או /e/ OS או כל טלפון אנדרואיד ללא תמיכה מתאימה של [אתחול מאומת](https://source.android.com/security/verifiedboot) ועדכוני קושחה. גם למכשירים האלה אין דרך לבדוק אם התעסקו בהם.
- בקיצור, אם לא מופיעה כאן הפצת מכשיר או אנדרואיד, כנראה שיש סיבה טובה. עיין ב[פורום](https://discuss.privacyguides.net/) שלנו כדי למצוא פרטים!

### גוגל פיקסל

טלפונים של גוגל פיקסל הם המכשירים ה**היחידים** שאנו ממליצים לרכישה. לטלפונים של Pixel יש אבטחת חומרה חזקה יותר מכל מכשירי אנדרואיד אחרים הקיימים כיום בשוק, בשל תמיכת AVB נאותה עבור מערכות הפעלה של צד שלישי ושבבי אבטחה [Titan](https://security.googleblog.com/2021/10/pixel-6-setting-new-standard-for-mobile.html) הפועלים כאלמנט המאובטח.

!!! recommendation

    ![Google Pixel 6](assets/img/android/google-pixel.png){ align=right }
    
    מכשירי **גוגל פיקסל** ידועים כבעלי אבטחה טובה ותומכים כראוי ב[אתחול מאומת](https://source.android.com/security/verifiedboot), גם בעת התקנת מערכות הפעלה מותאמות אישית.
    
    החל מ-**Pixel 6** ו-**6 Pro**, מכשירי Pixel מקבלים לפחות 5 שנים של עדכוני אבטחה מובטחים, מה שמבטיח תוחלת חיים ארוכה בהרבה בהשוואה ל-2-4 שנים שמציעות יצרניות OEM מתחרות בדרך כלל.
    
    [:material-shopping: Store:](https://store.google.com/category/phones){ .md-button .md-button--primary }

רכיבים מאובטחים כמו Titan M2 מוגבלים יותר מסביבת הביצוע המהימנה של המעבד המשמשת את רוב הטלפונים האחרים מכיוון שהם משמשים רק לאחסון סודות, אישור חומרה והגבלת קצב, לא להפעלת תוכניות "מהימנות". טלפונים ללא Secure Element חייבים להשתמש ב-TEE עבור *כל* הפונקציות הללו, וכתוצאה מכך משטח התקפה גדול יותר.

טלפונים של Google Pixel משתמשים במערכת הפעלה TEE בשם Trusty שהיא [קוד פתוח](https://source.android.com/security/trusty#whyTrusty), בניגוד לטלפונים רבים אחרים.

ההתקנה של GrapheneOS בטלפון Pixel קלה עם [מתקין האינטרנט](https://grapheneos.org/install/web) שלהם. אם אתה לא מרגיש בנוח לעשות את זה בעצמך ומוכן להוציא קצת כסף נוסף, בדוק את[NitroPhone](https://shop.nitrokey.com/shop)שהם מגיעים טעונים מראש עם GrapheneOS מחברת [Nitrokey](https://www.nitrokey.com/about) המכובדת.

עוד כמה טיפים לרכישת Google Pixel:

- אם אתה מחפש מציאה על מכשיר פיקסל, אנו מציעים לקנות דגם "**a**", מיד לאחר יציאת ספינת הדגל הבאה. הנחות זמינות בדרך כלל מכיוון שגוגל תנסה לסלק את המלאי שלה.
- שקול מחיר מכה אפשרויות ומבצעים המוצעים בחנויות לבנים וטיט.
- באפשרותך לעיין באתרי המציאה המקוונים של הקהילה במדינה שלך. אלה יכולים להתריע על מכירות טובות.
- Google מספקת רשימה המציגה את [מחזור התמיכה](https://support.google.com/nexus/answer/4457705) עבור כל אחד מהמכשירים שלהם. המחיר ליום עבור מכשיר יכול להיות מחושב כך: $\text{לוּת} \over \text {תאריך סוף החיים}-\text{דייט נוכחי}$, כלומר, ככל שהשימוש במכשיר ארוך יותר, העלות ליום נמוכה יותר.

## אפליקציות כלליות

אנו ממליצים על מגוון רחב של אפליקציות אנדרואיד ברחבי אתר זה. האפליקציות המפורטות כאן הן בלעדיות ל - אנדרואיד ובפרט משפרות או מחליפות פונקציונליות של מערכת מפתח.

### Shelter

!!! recommendation

    ![לוגו Shelter](assets/img/android/shelter.svg){ align=right }
    
    **Shelter** היא אפליקציה שעוזרת לך למנף את הפונקציונליות של פרופיל העבודה של אנדרואיד כדי לבודד או לשכפל אפליקציות במכשיר שלך.
    
    Shelter תומך בחסימת פרופילים חוצי חיפוש אנשי קשר ושיתוף קבצים בין פרופילים באמצעות מנהל הקבצים המוגדר כברירת מחדל ([DocumentsUI](https://source.android.com/devices/architecture/modular-system/documentsui)).
    
    [:octicons-repo-16: מאגר](https://gitea.angry.im/PeterCxy/Shelter#shelter){ .md-button .md-button--primary }
    [:octicons-code-16:](https://gitea.angry.im/PeterCxy/Shelter){ .card-link title="קוד מקור" }
    [:octicons-heart-16:](https://www.patreon.com/PeterCxy){ .card-link title=לתרומה }
    
    ??? downloads "הורדות"
    
        - [simple-googleplay: Google Play:]( https://play.google.com/store/apps/details?id=net.typeblog.shelter)

!!! warning "אזהרה"

    Shelter מומלץ על פני [Insular](https://secure-system.gitlab.io/Insular/) וגם [Island](https://github.com/oasisfeng/island) כפי שהוא תומך [contact search blocking](https://secure-system.gitlab.io/Insular/faq.html).
    
    כאשר אתה משתמש ב - Shelter, אתה נותן אמון מלא במפתח שלה, מאחר שה - Shelter פועל כמנהל [מכשיר]( https://developer.android.com/guide/topics/admin/device-admin) ליצירת פרופיל העבודה, ויש לו גישה נרחבת לנתונים המאוחסנים בתוך פרופיל העבודה.

### Auditor

!!! recommendation

    ![Auditor לוגו](assets/img/android/auditor.svg#only-light){ align=right }
    ![Auditor לוגו](assets/img/android/auditor-dark.svg#only-dark){ align=right }
    
    **Auditor** היא אפליקציה אשר ממנפת תכונות אבטחה בחומרה כדי לספק ניטור תקינות מכשירים עבור [התקנים נתמכים ]( https://attestation.app/about#device-support). כיום, הוא עובד רק עם GrapheneOS ומערכת ההפעלה של המכשיר.
    
    [:octicons-home-16: Homepage](https://attestation.app){ .md-button .md-button--primary }
    [:octicons-eye-16:](https://attestation.app/privacy-policy){ .card-link title="Privacy Policy" }
    [:octicons-info-16:](https://attestation.app/about){ .card-link title=Documentation}
    [:octicons-code-16:](https://attestation.app/source){ .card-link title="Source Code" }
    [:octicons-heart-16:](https://attestation.app/donate){ .card-link title=Contribute } ??? downloads "הורדות"
        - [:simple-googleplay: Google Play](https://play.google.com/store/apps/details?id=app.attestation.auditor)
        - [:simple-github: GitHub](https://github.com/GrapheneOS/Auditor/releases)
        - [:material-cube-outline: GrapheneOS App Store](https://github.com/GrapheneOS/Apps/releases)

Auditor מבצע אימות וזיהוי חדירה על ידי:

- שימוש ב [אמון בשימוש הראשון (TOFU)](https://en.wikipedia.org/wiki/Trust_on_first_use) מודל between an *auditor* and *auditee*, השניים מקימים מפתח פרטי ב[מאגר מפתחות מגובה חומרה](https://source.android.com/security/keystore/) של ה *Auditor*.
- המבקר ** יכול להיות מקרה אחר של אפליקציית המבקר או [שירות ההצהרה מרחוק](https://attestation.app).
- מבקר **מתעד את המצב והתצורה הנוכחיים של מבקר**.
- במקרה של חבלה במערכת ההפעלה של ה*נבדק* לאחר השלמת החיבור, המבקר יהיה מודע לשינוי במצב ההתקן ובתצורות.
- אתה תקבל התראה על השינוי.

לא נשלח מידע אישי הניתן לזיהוי לשירות ההצהרה. אנו ממליצים להירשם באמצעות חשבון אנונימי ולהפעיל הצהרה מרחוק למעקב רציף.

אם [מודל האיום](basics/threat-modeling.md) שלכם דורש פרטיות, תוכלו לשקול להשתמש ב [Orbot](tor.md#orbot) או ב-VPN כדי להסתיר את כתובת ה-IP שלכם משירות האישור. כדי לוודא שחומרתך ומערכת ההפעלה שלך אמינה, בצע [הצהרה מקומית](https://grapheneos.org/install/web#verifying-installation) מיד לאחר התקנת המכשיר ולפני כל חיבור לאינטרנט.

### מצלמה מאובטחת

!!! recommendation

    ![Secure camera לוגו](assets/img/android/secure_camera.svg#only-light){ align=right }
    ![Secure camera לוגו](assets/img/android/secure_camera-dark.svg#only-dark){ align=right }
    
    **Secure Camera** היא אפליקציית מצלמה המתמקדת בפרטיות ובאבטחה שיכולה ללכוד תמונות, סרטונים וקודי QR. הרחבות ספק CameraX (דיוקן, HDR, ראיית לילה, ריטוש פנים ואוטומטי) נתמכות גם במכשירים זמינים.
    
    [:octicons-repo-16: Repository](https://github.com/GrapheneOS/Camera){ .md-button .md-button--primary }
    [:octicons-info-16:](https://grapheneos.org/usage#camera){ .card-link title=Documentation}
    [:octicons-code-16:](https://github.com/GrapheneOS/Camera){ .card-link title="Source Code" }
    [:octicons-heart-16:](https://grapheneos.org/donate){ .card-link title=Contribute }
    
    ??? downloads "הורדות"
    
        - [:simple-googleplay: Google Play](https://play.google.com/store/apps/details?id=app.grapheneos.camera.play)
        - [:simple-github: GitHub](https://github.com/GrapheneOS/Camera/releases)
        - [:material-cube-outline: GrapheneOS App Store](https://github.com/GrapheneOS/Apps/releases)

תכונות הפרטיות העיקריות כוללות:

- הסרה אוטומטית של מטא נתונים מסוג [Exif](https://en.wikipedia.org/wiki/Exif) (מופעלת כברירת מחדל)
- השימוש ב [Media](https://developer.android.com/training/data-storage/shared/media) API החדש, לכן [הרשאות אחסון](https://developer.android.com/training/data-storage) אינם נדרשים
- הרשאת מיקרופון אינה נדרשת אלא אם כן ברצונך להקליט קול

!!! note "הערה"

    מטא - נתונים אינם נמחקים כרגע מקובצי וידאו, אך הם מתוכננים.
    
    המטא נתונים של כיוון התמונה אינם נמחקים. אם תפעיל מיקום (בSecure Camera) זה גם **לא** יימחק. אם ברצונך למחוק זאת מאוחר יותר, יהיה עליך להשתמש באפליקציה חיצונית כגון [ExifEraser](data-redaction.md#exiferaser).

### מציג PDF מאובטח

!!! recommendation

    ![Secure PDF Viewer לוגו](assets/img/android/secure_pdf_viewer.svg#only-light){ align=right }
    ![Secure PDF Viewer לוגו](assets/img/android/secure_pdf_viewer-dark.svg#only-dark){ align=right }
    
    *Secure PDF Viewer** הוא מציג PDF המבוסס על [pdf.js](https://en.wikipedia.org/wiki/PDF.js) שאינו דורש הרשאות כלשהן. PDF מוזן לתוך [sandboxed](https://en.wikipedia.org/wiki/Sandbox_ (software_development)) [webview](https://developer.android.com/guide/webapps/webview). המשמעות היא שאין צורך באישור כדי לגשת ישירות לתוכן או לקבצים.
    
    [Content-Security-Policy](https://en.wikipedia.org/wiki/Content_Security_Policy) משמש כדי לאכוף שמאפייני JavaScript והעיצוב בתוך WebView הם תוכן סטטי לחלוטין.
    
    [:octicons-repo-16: Repository](https://github.com/GrapheneOS/PdfViewer){ .md-button .md-button--primary }
    [:octicons-code-16:](https://github.com/GrapheneOS/PdfViewer){ .card-link title="Source Code" }
    [:octicons-heart-16:](https://grapheneos.org/donate){ .card-link title=Contribute }
    
    ??? downloads "הורדות"
    
        - [:simple-googleplay: Google Play](https://play.google.com/store/apps/details?id=app.grapheneos.pdfviewer.play)
        - [:simple-github: GitHub](https://github.com/GrapheneOS/PdfViewer/releases)
        - [:material-cube-outline: GrapheneOS App Store](https://github.com/GrapheneOS/Apps/releases)

## קבלת בקשות

### GrapheneOS App Store

חנות האפליקציות של GrapheneOS זמינה ב - [GitHub](https://github.com/GrapheneOS/Apps/releases). הוא תומך אנדרואיד 12 ומעלה והוא מסוגל לעדכן את עצמו. חנות האפליקציות יש יישומים עצמאיים שנבנו על ידי פרויקט GrapheneOS כגון [מבקר](https://attestation.app/), [מצלמה](https://github.com/GrapheneOS/Camera), ו [PDF Viewer](https://github.com/GrapheneOS/PdfViewer). אם אתם מחפשים יישומים אלה, אנו ממליצים בחום כי אתה מקבל אותם מחנות האפליקציות של GrapheneOS במקום בחנות Play, כמו היישומים בחנות שלהם חתומים על ידי חתימת הפרויקט של GrapheneOS כי גוגל אין גישה.

### Aurora Store

'חנות Google Play' דורשת מחשבון Google להתחבר לחשבון שאינו מתאים לפרטיות. אתה יכול לעקוף את זה על ידי שימוש בקליינט חלופי, כגון חנות אורורה.

!!! recommendation

    ![לוגו של חנות אורורה](assets/img/android/aurora-store.webp){ align=right }
    
    **חנות אורורה** היא לקוחה של חנות Google Play שאינה דורשת חשבון Google, שירותי Google Play או microG כדי להוריד יישומים.
    
    [:octicons-home-16: Homepage](https://auroraoss.com/){ .md-button .md-button--primary }
    [:octicons-code-16:](https://gitlab.com/AuroraOSS/AuroraStore){ .card-link title="Source Code" }
    
    ??? downloads "הורדות"
    
        - [:simple-gitlab: GitLab](https://gitlab.com/AuroraOSS/AuroraStore/-/releases)

Aurora Store אינה מאפשרת לך להוריד אפליקציות בתשלום עם תכונת החשבון האנונימי שלהם. אתה יכול להיכנס עם חשבון Google שלך עם Aurora Store כדי להוריד אפליקציות שרכשת, מה שכן נותן גישה לרשימת האפליקציות שהתקנת ב-Google, אולם אתה עדיין נהנה מכך שאינך זקוק ללקוח Google Play המלא ולשירותי Google Play או microG במכשיר שלך.

### התראות RSS באופן ידני

עבור אפליקציות שמשוחררות בפלטפורמות כמו GitHub ו - GitLab, ייתכן שתוכל להוסיף הזנת RSS ל - [צובר החדשות שלך](/news-aggregators) שיעזור לך לעקוב אחר מהדורות חדשות.

![RSS APK](./assets/img/android/rss-apk-light.png#only-light) ![RSS APK](./assets/img/android/rss-apk-dark.png#only-dark) ![שינויים ב - APK](./assets/img/android/rss-changes-light.png#only-light) ![שינויים ב - APK](./assets/img/android/rss-changes-dark.png#only-dark)

#### Github

ב GitHub, באמצעות [מצלמה מאובטחת](#secure-camera) כדוגמה, היית לנווט לדף [מהדורות](https://github.com/GrapheneOS/Camera/releases) ולצרף `.atom` לכתובת האתר:

`https://github.com/GrapheneOS/Camera/releases.atom`

#### GitLab

ב - GitLab, באמצעות [Aurora Store](#aurora-store) כדוגמה, היית מנווט למאגר [הפרויקטים שלה](https://gitlab.com/AuroraOSS/AuroraStore) ומוסיף `/-/ tags?format=atom` לכתובת האתר:

`https://gitlab.com/AuroraOSS/AuroraStore/-/tags?format=atom`

#### אימות טביעות אצבע APK

אם אתה מוריד קבצי APK כדי להתקין באופן ידני, אתה יכול לאמת את החתימה שלהם עם [`apksigner`](https://developer.android.com/studio/command-line/apksigner) כלי, המהווה חלק אנדרואיד [לבנות כלים](https://developer.android.com/studio/releases/build-tools).

1. התקן [Java JDK](https://www.oracle.com/java/technologies/downloads/).

2. הורד את [הכלים של שורת הפקודה של אולפן Android](https://developer. android. com/studio#command-tools).

3. חלץ את הארכיון שהורד:

    ```bash
    unzip commandlinetools-*.zip
    cd cmdline-tools
    ./bin/sdkmanager --sdk_root=./ "build-tools;29.0.3"
    ```

4. הפעל את פקודת אימות החתימה:

    ```bash
    ./build-tools/29.0.3/apksigner verify --print-certs ../Camera-37.apk
    ```

5. לאחר מכן ניתן להשוות את הhashes שנוצר למקור אחר. חלק מהמפתחים כגון Signal [מציגים את טביעות האצבע](https://signal.org/android/apk/) באתר שלהם.

    ```bash
    Signer #1 certificate DN: CN=GrapheneOS
    Signer #1 certificate SHA-256 digest: 6436b155b917c2f9a9ed1d15c4993a5968ffabc94947c13f2aeee14b7b27ed59
    Signer #1 certificate SHA-1 digest: 23e108677a2e1b1d6e6b056f3bb951df7ad5570c
    Signer #1 certificate MD5 digest: dbbcd0cac71bd6fa2102a0297c6e0dd3
    ```

### F-Droid

![לוגו F - Droid](assets/img/android/f-droid.svg){ align=right width=120px }

== כיום אנו **לא** ממליצים על F-Droid כדרך להשגת אפליקציות. F-Droid מומלץ לעיתים קרובות כחלופה ל - Google Play, בעיקר בקהילת הפרטיות. האפשרות להוסיף מאגרים של צד שלישי ולא להיות מוגבל לגינה המוקפת חומה של Google הובילה לפופולריות שלה. F-Droid יש גם [גרסאות לשחזור](https://f-droid.org/en/docs/Reproducible_Builds/) עבור יישומים מסוימים והוא מוקדש תוכנה חופשית קוד פתוח. עם זאת, יש [בעיות בולטות](https://privsec.dev/posts/android/f-droid-security-issues/) עם הלקוח הרשמי F-Droid, בקרת האיכות שלהם, וכיצד הם בונים, לחתום, ולספק חבילות.

בשל תהליך בניית האפליקציות שלהם, אפליקציות במאגר F - Droid הרשמי מפגרות לעתים קרובות אחרי עדכונים. מתחזקיF-Droid גם משתמשים מחדש במזהי חבילות בזמן שהם חותמים על אפליקציות עם המפתחות שלהם, וזה לא אידיאלי כי זה נותן אמון אולטימטיבי לצוות F-Droid.

מאגרי צד שלישי פופולריים אחרים כגון [IzzyOnDroid](https://apt.izzysoft.de/fdroid/) מקלים על כמה חששות אלה. המאגר IzzyOnDroid מושך בונה ישירות מ - GitHub והוא הדבר הטוב הבא למאגרים של המפתחים עצמם. עם זאת, זה לא משהו שאנחנו יכולים להמליץ עליו, מכיוון שאפליקציות [בדרך כלל מוסרות](https://github.com/vfsfitvnm/ViMusic/issues/240#issuecomment-1225564446) ממאגר הנשימה כאשר הן מגיעות למאגר F -droid הראשי. אמנם זה הגיוני (מכיוון שהמטרה של המאגר המסוים הזה היא לארח אפליקציות לפני שהן מתקבלות למאגר F-Droid הראשי), אבל זה יכול להשאיר אותך עם אפליקציות מותקנות שכבר לא מקבלות עדכונים.

עם זאת, מאגרי [F-droid](https://f-droid.org/en/packages/) ו [IzzyOnDroid](https://apt.izzysoft.de/fdroid/) הם ביתם של אינספור אפליקציות, כך שהם יכולים להיות כלי שימושי לחיפוש וגילוי אפליקציות קוד פתוח שתוכל להוריד דרך חנות Play, חנות אורורה, או על ידי קבלת ה- APK ישירות מהמפתח. חשוב לזכור שאפליקציות מסוימות במאגרים אלה לא עודכנו במשך שנים ועשויות להסתמך על ספריות שאינן נתמכות, בין היתר, ומהוות סיכון אבטחה פוטנציאלי. עליך להפעיל את שיקול דעתך הטוב ביותר כאשר אתה מחפש אפליקציות חדשות בשיטה זו.

!!! note "הערה"

    במקרים נדירים, מפתח אפליקציה יפיץ אותה רק באמצעות F-droid ([Gadgetbridge](https://gadgetbridge.org/) הוא דוגמה אחת לכך). אם אתה באמת זקוק לאפליקציה כזו, מומלץ להשתמש ב - [ Neo Store]( https://github.com/NeoApplications/NeoStore/) במקום באפליקציית F -Droid הרשמית כדי להשיג אותה.

## קריטריונים

**שים לב שאיננו קשורים לאף אחד מהפרויקטים שאנו ממליצים עליהם.** בנוסף [לקריטריונים הסטנדרטיים שלנו](about/criteria.md), פיתחנו סט ברור של דרישות כדי לאפשר לנו לספק המלצות אובייקטיביות. אנו מציעים לך להכיר את הרשימה הזו לפני שתבחר להשתמש בפרויקט, ולערוך מחקר משלך כדי להבטיח שזו הבחירה הנכונה עבורך.

!!! example "חלק זה הוא חדש"

    אנו עובדים על קביעת קריטריונים מוגדרים לכל קטע באתר שלנו, והדבר עשוי להשתנות. אם יש לך שאלות לגבי הקריטריונים שלנו, אנא [שאל בפורום שלנו]( https://discuss.privacyguides.net/latest) ואל תניח שלא שקלנו משהו בעת ביצוע ההמלצות שלנו אם זה לא מופיע כאן. ישנם גורמים רבים שנשקלים ונדונים כאשר אנו ממליצים על פרויקט, ותיעוד כל אחד מהם הוא עבודה בתהליך.

### מערכות הפעלה

- חייבת להיות תוכנת קוד פתוח.
- חייב לתמוך נעילת bootloader עם תמיכת מפתח AVB מותאמת אישית.
- יש לקבל עדכונים לאנדרואיד בתוך 0 -1 חודשים מיום השקתו.
- חייב לקבל עדכוני תכונות אנדרואיד (גרסה משנית) בתוך 0 -14 ימים מיום השחרור.
- חייב לקבל תיקוני אבטחה רגילים בתוך 0 -5 ימים מיום השחרור.
- חייב **לא** להיות "מושרש" מחוץ לקופסה.
- חייב **לא** לאפשר שירותי Google Play כברירת מחדל.
- חייב **שלא** ידורש שינוי מערכת כדי לתמוך בשירותי Google Play.

### מכשירים

- חייב לתמוך לפחות באחת ממערכות ההפעלה המותאמות אישית המומלצות שלנו.
- חייב שיהיה מלאי חדש בחנויות.
- חייב לקבל מינימום של 5 שנים של עדכוני אבטחה.
- חייב להיות בעל חומרת אלמנט מאובטחת ייעודית.

### יישומים

- יישומים בדף זה אינם חלים על כל קטגוריית תוכנה אחרת באתר.
- יישומים כלליים צריכים להרחיב או להחליף את הפונקציונליות של מערכת הליבה.
- יישומים צריכים לקבל עדכונים שוטפים ותחזוקה.