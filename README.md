
#كيف تضيف ملفات العربية إلى espeak إسبيك (الدليل العربي)
#How to add Arabic files to espeak (English manual, look below):
[Arabic]
على نظام وندوز
=================
1- نزّل برنامج إسبيك من http://espeak.sf.net
2- عند تثبيت البرنامج، يرجى إدخال قائمة أسماء اللغات التلقائية الآتية:
"ar"و "mb-ar1" و "mb-ar2" 
3- فك ضغط ملف ar-espeak
4- بعد انتهاء التثبيت، انسخ ما في مجلد "espeak-data" إلى
 "C:\Program Files\eSpeak\espeak-data\"


لينكس
=======
1- تحقق أن إسبيك مثبت، يمكن تحميله من 
http://espeak.sf.net
2- تحقق من مسار مجلد espeak-data
	على نظام فيدورا، يوجد في المسار /usr/share/espeak-data
3- فك ضغط ملف ar-speak
4- نسخ ما في مجلد "espeak-data" إلى
/usr/share/espeak-data
5- تحقق أنّ إسبيك تعرف إلى ملفات العربية بالأمر
	espeak --voices=ar
فيعطيك نتيجة مثل:
	espeak --voices=ar
	Pty Language Age/Gender VoiceName       File        Other Langs
	 1  ar             M  arabic-mbrola-1   mb/mb-ar1   
	 2  ar             M  arabic-mbrola-2   mb/mb-ar2   
	 5  ar             M  arabic            ar   

6- جرّب النطق بالأمر:
	espeak 'السلام عليكم' -v ar

 الاستعمال
=====================
البرنامج فيه ثلاث ملفات نطق عربية هي ar, mb-ar1, mb-ar2
يمكن استعمالها أحدها على منوال:
	espeak 'السلام عليكم' -v ar
	espeak 'السلام عليكم' -v mb-ar1
	espeak 'السلام عليكم' -v mb-ar2
يمكن توليد الكلام من ملف مثل
	espeak -f sample.txt -v ar

ملاحظة
======
للحصول على نتائج أفضل، يرجى استعمال نصوص مشكولة.
يمكن تشكيل النصوص ببرنامج مشكال لتشكيل النصوص الذي يمكن تحميله من 
http://mishkal.sourceforge.net
واستعماله على الوب من
http://tahadz.com/mishkal

========================================================================================
[english]

Windows
=============
1. Download eSpeak from espeak.sf.net
2. While you are installing eSpeak on your computer, type "ar", "mb-ar1" and "mb-ar2" as the language name.
3- Unzip the Ar-espeak
4. After finishing the wizard, copy "espeak-data" files in to "C:\Program Files\eSpeak\espeak-data\"

Linux
=============
1. Test if espeak is installed on your system, you can download it from  http://espeak.sf.net
2. Verify the path for espeak-data
	under Fedora espeak-data path is /usr/share/espeak-data
3- Unzip the Arf-espeak
4- Copy the espeak-data files into your specified path ( e.g. /usr/share/espeak-data)
5- Test if espak use arabic voices
	espeak --voices=ar
it gives an output like this:
	espeak --voices=ar
	Pty Language Age/Gender VoiceName       File        Other Langs
	 1  ar             M  arabic-mbrola-1   mb/mb-ar1   
	 2  ar             M  arabic-mbrola-2   mb/mb-ar2   
	 5  ar             M  arabic            ar   

6- Test sound by using an vocalized texts
	espeak 'السلام عليكم' -v ar

USAGE
=======
Ar-speak contains three voice files, named ar, mb-ar1, mb-ar2. You can call espeak by one of them like this:
	espeak 'السلام عليكم' -v ar
	espeak 'السلام عليكم' -v mb-ar1
	espeak 'السلام عليكم' -v mb-ar2
You can also use files 
	espeak -f sample.txt -v ar
Note:
====
To have a better result, please use a vocalized texts.
You can vocalize your arabic texts by Mishkal Arabic text vocalization system.
You can download Mishkal from http://mishkal.sourceforge.net
or use it online http://tahadz.com/mishkal
