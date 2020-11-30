# day1 리눅스 명령
 - cd
 - mkdir
 - ls

#### scripts

```
BIT@DESKTOP-MFM72BP MINGW64 ~
$ git --version
git version 2.29.2.windows.2

BIT@DESKTOP-MFM72BP MINGW64 ~
$ pwd
/c/Users/BIT

BIT@DESKTOP-MFM72BP MINGW64 ~
$

BIT@DESKTOP-MFM72BP MINGW64 ~
$ cd Downloads/

BIT@DESKTOP-MFM72BP MINGW64 ~/Downloads
$

BIT@DESKTOP-MFM72BP MINGW64 ~/Downloads
$ cd /c/Users/BIT/Downloads/
(KAIPS)협회 회원사 대표자 등 연락망.xlsx
1-1 머신러닝이란 무엇인가요.html
Git-2.29.2.2-64-bit.exe
LD_공간과가치_주거인구수.txt
LD_공간과가치_지도.zip
ME_한국데이터진흥원_성별_연령별혈당데이터.csv
Python교안1-Python기본.pdf
[66] 근로소득(2010-2011).xls
desktop.ini
git remote 이용.pdf
git이용-2020.pdf

BIT@DESKTOP-MFM72BP MINGW64 ~/Downloads
$ cd /c/Users/BIT/Documents/

BIT@DESKTOP-MFM72BP MINGW64 ~/Documents
$ pwd
/c/Users/BIT/Documents

BIT@DESKTOP-MFM72BP MINGW64 ~/Documents
$

BIT@DESKTOP-MFM72BP MINGW64 ~/Documents
$ cd ~

BIT@DESKTOP-MFM72BP MINGW64 ~
$ cd Downloads/

BIT@DESKTOP-MFM72BP MINGW64 ~/Downloads
$ ls
'(KAIPS)협회 회원사 대표자 등 연락망.xlsx'
'1-1 머신러닝이란 무엇인가요.html'
 Git-2.29.2.2-64-bit.exe*
 LD_공간과가치_주거인구수.txt
 LD_공간과가치_지도.zip
 ME_한국데이터진흥원_성별_연령별혈당데이터.csv
 Python교안1-Python기본.pdf
'[66] 근로소득(2010-2011).xls'
 desktop.ini
'git remote 이용.pdf'
 git이용-2020.pdf
 putty.exe*
 putty.exe.gpg
 python_ipmoon_total_pdf.zip
 query_result.csv
 query_result.xls
 report.txt
'강사소개20 (1).pdf'
 강사소개20.pdf
'경기도_용인시_노인복지시설 현황_20190331.csv'
'김균창자바이용한 맵리듀스 프로그래밍 - 20160712 - edited by AhnSJ.pptx'
'서울특별시 광진구_공동주택시공현황_20190226..csv'
'한국지식재산서비스협회 현황소개_2020.08.hwp'


BIT@DESKTOP-MFM72BP MINGW64 ~/Downloads
$ ls -l
total 88318
-rw-r--r-- 1 BIT 197121    24651 Nov  7 14:05 '(KAIPS)협회 회원사 대표자 등 연락망.xlsx'
-rw-r--r-- 1 BIT 197121   283116 Jun 30 11:29 '1-1 머신러닝이란 무엇인가요.html'
-rwxr-xr-x 1 BIT 197121 48536496 Nov 30 10:46  Git-2.29.2.2-64-bit.exe*
-rw-r--r-- 1 BIT 197121        0 Jun 30 10:32  LD_공간과가치_주거인구수.txt
-rw-r--r-- 1 BIT 197121        0 Jun 30 10:40  LD_공간과가치_지도.zip
-rw-r--r-- 1 BIT 197121        0 Jun 30 10:32  ME_한국데이터진흥원_성별_연령별혈당데이터.csv
-rw-r--r-- 1 BIT 197121  9706376 Nov 30 08:55  Python교안1-Python기본.pdf
-rw-r--r-- 1 BIT 197121     9728 Jun 30 10:51 '[66] 근로소득(2010-2011).xls'
-rw-r--r-- 1 BIT 197121      282 Oct 21 14:28  desktop.ini
-rw-r--r-- 1 BIT 197121  7908780 Nov 30 08:26 'git remote 이용.pdf'
-rw-r--r-- 1 BIT 197121 10316966 Nov 30 08:26  git이용-2020.pdf
-rwxr-xr-x 1 BIT 197121  1179024 Feb 25  2020  putty.exe*
-rw-r--r-- 1 BIT 197121      438 Feb 25  2020  putty.exe.gpg
-rw-r--r-- 1 BIT 197121  8651990 Nov 30 09:50  python_ipmoon_total_pdf.zip
-rw-r--r-- 1 BIT 197121    53589 Feb 25  2020  query_result.csv
-rw-r--r-- 1 BIT 197121    53589 Feb 25  2020  query_result.xls
-rw-r--r-- 1 BIT 197121      828 Jun 30 10:50  report.txt
-rw-r--r-- 1 BIT 197121  1204740 Nov 30 09:02 '강사소개20 (1).pdf'
-rw-r--r-- 1 BIT 197121  1204740 Nov 30 08:55  강사소개20.pdf
-rw-r--r-- 1 BIT 197121    13751 Jun 30 10:51 '경기도_용인시_노인복지시설 현황_20190331.csv'
-rw-r--r-- 1 BIT 197121  1055552 Mar 18  2020 '김균창자바이용한 맵리듀스 프로그래밍 - 20160712 - edited by AhnSJ.pptx'
-rw-r--r-- 1 BIT 197121      602 Jun 30 10:48 '서울특별시 광진구_공동주택시공현황_20190226..csv'
-rw-r--r-- 1 BIT 197121   188416 Nov  7 14:31 '한국지식재산서비스협회 현황소개_2020.08.hwp'


BIT@DESKTOP-MFM72BP MINGW64 ~/Downloads
$ cd

BIT@DESKTOP-MFM72BP MINGW64 ~
$ cd

BIT@DESKTOP-MFM72BP MINGW64 ~
$ ls -l
total 11053
drwxr-xr-x 1 BIT 197121       0 Oct 21 14:28 '3D Objects'/
drwxr-xr-x 1 BIT 197121       0 Jun  5 12:42  AndroidStudioPr
drwxr-xr-x 1 BIT 197121       0 Apr 28  2020  AppData/
lrwxrwxrwx 1 BIT 197121      28 Feb  7  2020 'Application Dat/
drwxr-xr-x 1 BIT 197121       0 Jun 11 10:11  BitHomepage/
drwxr-xr-x 1 BIT 197121       0 Oct 21 14:28  Contacts/
lrwxrwxrwx 1 BIT 197121      56 Feb  7  2020  Cookies -> /c/Uindows/INetCookies/
drwxr-xr-x 1 BIT 197121       0 Oct 31 08:46  Desktop/
drwxr-xr-x 1 BIT 197121       0 Nov 30 11:19  Documents/
drwxr-xr-x 1 BIT 197121       0 Nov 30 10:46  Downloads/
drwxr-xr-x 1 BIT 197121       0 Oct 21 14:28  Favorites/
drwxr-xr-x 1 BIT 197121       0 Jun 15 09:19  IdeaProjects/
drwxr-xr-x 1 BIT 197121       0 Nov 30 08:24  IntelGraphicsPr
drwxr-xr-x 1 BIT 197121       0 Jun 15 17:33  Java_KMH/
drwxr-xr-x 1 BIT 197121       0 Oct 21 14:28  Links/
lrwxrwxrwx 1 BIT 197121      26 Feb  7  2020 'Local Settings'
drwxr-xr-x 1 BIT 197121       0 Feb  7  2020  MicrosoftEdgeBa
drwxr-xr-x 1 BIT 197121       0 Oct 21 14:28  Music/
lrwxrwxrwx 1 BIT 197121      22 Feb  7  2020 'My Documents' -
-rw-r--r-- 1 BIT 197121 6553600 Nov 27 15:42  NTUSER.DAT
-rw-r--r-- 1 BIT 197121   65536 Feb  7  2020  NTUSER.DAT{fd5bTM.blf
-rw-r--r-- 1 BIT 197121  524288 Feb  7  2020  NTUSER.DAT{fd5bTMContainer00000000000000000001.regtrans-ms
-rw-r--r-- 1 BIT 197121  524288 Feb  7  2020  NTUSER.DAT{fd5bTMContainer00000000000000000002.regtrans-ms
lrwxrwxrwx 1 BIT 197121      64 Feb  7  2020  NetHood -> '/c/t/Windows/Network Shortcuts'/
drwxr-xr-x 1 BIT 197121       0 Apr 10  2020  OneDrive/
drwxr-xr-x 1 BIT 197121       0 Oct 21 14:28  Pictures/
lrwxrwxrwx 1 BIT 197121      64 Feb  7  2020  PrintHood -> '/oft/Windows/Printer Shortcuts'/
lrwxrwxrwx 1 BIT 197121      53 Feb  7  2020  Recent -> /c/UsWindows/Recent/
drwxr-xr-x 1 BIT 197121       0 Oct 21 14:28 'Saved Games'/
drwxr-xr-x 1 BIT 197121       0 Oct 21 14:28  Searches/
lrwxrwxrwx 1 BIT 197121      53 Feb  7  2020  SendTo -> /c/UsWindows/SendTo/
lrwxrwxrwx 1 BIT 197121      57 Feb  7  2020 'Start Menu' -> osoft/Windows/Start Menu'/
lrwxrwxrwx 1 BIT 197121      56 Feb  7  2020  Templates -> /cft/Windows/Templates/
drwxr-xr-x 1 BIT 197121       0 Oct 21 14:28  Videos/
drwxr-xr-x 1 BIT 197121       0 Feb 26  2020  eclipse/
drwxr-xr-x 1 BIT 197121       0 Feb 13  2020  eclipse-workspa
-rw-r--r-- 1 BIT 197121   14339 May 22  2020  exam.ipynb
-rw-r--r-- 1 BIT 197121 1675264 Feb  7  2020  ntuser.dat.LOG1
-rw-r--r-- 1 BIT 197121 1867776 Feb  7  2020  ntuser.dat.LOG2
-rw-r--r-- 1 BIT 197121      20 Feb  7  2020  ntuser.ini

BIT@DESKTOP-MFM72BP MINGW64 ~
$

BIT@DESKTOP-MFM72BP MINGW64 ~
$ cd Downloads/

BIT@DESKTOP-MFM72BP MINGW64 ~/Downloads
$ mkdir test

BIT@DESKTOP-MFM72BP MINGW64 ~/Downloads
$

BIT@DESKTOP-MFM72BP MINGW64 ~/Downloads
$

BIT@DESKTOP-MFM72BP MINGW64 ~/Downloads
$ ls -l test/
total 0

BIT@DESKTOP-MFM72BP MINGW64 ~/Downloads
$ ls -al test/
total 40
drwxr-xr-x 1 BIT 197121 0 Nov 30 11:34 ./
drwxr-xr-x 1 BIT 197121 0 Nov 30 11:34 ../

BIT@DESKTOP-MFM72BP MINGW64 ~/Downloads
$ rm
rm: missing operand
Try 'rm --help' for more information.

BIT@DESKTOP-MFM72BP MINGW64 ~/Downloads
$

BIT@DESKTOP-MFM72BP MINGW64 ~/Downloads
$ rm -r test

BIT@DESKTOP-MFM72BP MINGW64 ~/Downloads
$ cd ../Documents/

BIT@DESKTOP-MFM72BP MINGW64 ~/Documents
$ pwd
/c/Users/BIT/Documents

BIT@DESKTOP-MFM72BP MINGW64 ~/Documents
$

```
