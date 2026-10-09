# Bhakti_RaaS — Android Starter Project

## यह क्या है?
यह एक Android WebView starter app है, जिसमें Bhakti_RaaS का शुरुआती Hindi UI है और GitHub Actions workflow APK compile करने के लिए सेट है।

## मोबाइल से APK बनाने का तरीका
1. GitHub में नया **public या private repository** बनाएं, उदाहरण: `Bhakti_RaaS`.
2. इस ZIP को फोन में extract करें। सभी files/folders (including `.github`) repository में upload करें; files को एक अतिरिक्त nested folder के अंदर न रखें।
3. GitHub repo में **Actions** tab खोलें।
4. `Build Bhakti_RaaS APK` workflow चुनें और **Run workflow** दबाएँ। Push के बाद workflow अपने-आप भी चल सकता है।
5. Green/successful run खोलें → नीचे **Artifacts** में `Bhakti_RaaS-debug-apk` डाउनलोड करें।
6. ZIP artifact extract करें; उसमें `app-debug.apk` मिलेगा। Android security prompt आने पर ही install अनुमति दें।

## महत्वपूर्ण सीमा
यह पहला UI/build starter है, पूरा production app नहीं। अभी वास्तविक Mobile OTP/Email auth, live Panchang, verified news feed, server/admin, real notifications, poster image export, wallpaper setter और ringtone setting backend/native permissions के साथ implement करने बाकी हैं। UI में जिन sections पर tap करेंगे, वे फिलहाल demo information दिखाते हैं।

`Bhakti_RaaS_2063` branding UI में शामिल है; production-grade watermark enforcement और owner-only remote branding के लिए backend/API चाहिए।

Copyrighted songs/books को बिना permission bundle न करें; official links या licensed/public-domain content इस्तेमाल करें।
