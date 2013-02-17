What is ar-espeak?
=================

English: 
----------
Opensource/free  Arabic text to speach solution built on top of eSpeak project.


Arabic:
---------
مشروع جديد يهدف إلى إعداد الملفات الضرورية لعمل آلة النطق مفتوحة المصدر إسبيك، وجعلها تنطق بالعربية.

        **note:** Short Arabic documentation can be found `here <http://tahadz.wordpress.com/2013/02/17/572/>`_ for the time being.

:Authors: `Authors.rst <https://github.com/Alfanous-team/alfanous/blob/master/AUTHORS.rst>`_
:Version: 0.1.##
:License: `GPL (it includes files with their own licenses)`
:Mailinglist: `arabictools@googlegroups.com <http://groups.google.com/group/arabictools/>`_
:Announcement: `on the developer blog <http://tahadz.wordpress.com>`_
:Accounts: `@Twitter <https://twitter.com/linuxscout>`_ `@Facebook <https://www.facebook.com/linuxscout>`_ 
        | `@Sourceforge <http://sourceforge.net/projects/arabic-espeak/>`_

--------------
 How To use? 
--------------

Linux
-----
- Test if espeak is installed on your system, you can download it from  http://espeak.sf.net

- Verify the path for espeak-data

        under Fedora espeak-data path is /usr/share/espeak-data

- Unzip the Arf-espeak

- Copy the espeak-data files into your specified path ( e.g. /usr/share/espeak-data)

- Test if espak use arabic voices

        espeak --voices=ar

  it sould give an output like this:

        espeak --voices=ar

        Pty     Language        Age/Gender      VoiceName         File        Other Langs

        1       ar              M               arabic-mbrola-1   mb/mb-ar1   

        2       ar              M               arabic-mbrola-2   mb/mb-ar2   

        5       ar              M               arabic            ar   


6- Test sound by using vocalized texts:

	espeak 'السلام عليكم' -v ar


Windows
-------
# TODO