# Linux�����������

## ��ݼ�

��ӿ�ݼ���ϵͳ������ѡ������̿�ݼ�

### Shell ��ݼ�
```
    <Ctrl k>��ɾ���ӹ�굽��β�Ĳ��� 
    <Ctrl u>��ɾ���ӹ�굽���׵Ĳ���
    <Alt d>��ɾ���ӹ�굽��ǰ���ʽ�β�Ĳ��� 
    <Ctrl w>��ɾ���ӹ�굽��ǰ���ʿ�ͷ�Ĳ��� 
    <Ctrl a>��������Ƶ����� 
    <Ctrl e>��������Ƶ���β 
    <Alt a>��������Ƶ���ǰ����ͷ�� 
    <Alt e>��������Ƶ���ǰ����β�� 
    <Ctrl y>���������ɾ���ĵ���         
    <Ctrl a>����������
    <Ctrl b>������һ���ַ�
    <Ctrl c>����ֹ�ն˽���
    <Ctrl d>���ӹ�괦����ɾ��
    <Ctrl e>��������β
    <Ctrl f>������һ���ַ�
    <Ctrl k>���ӹ�괦ɾ������β
    <Ctrl l>������������ clear ����
    <Ctrl r>��������ʷ����
    <Ctrl z>��Suspend/ Stop the command  �� ��ͣ�����ִ��
    <Ctrl h>��ɾ����ǰ�ַ�
    <Ctrl w>��ɾ���������ĵ���
    <!$>���ظ�ǰһ���������Ĳ�����
    <SHIFT PageUp/PageDown>���ն����·�ҳ
```

### ���ÿ�ݼ�
```
    <Alt+Tab>���л�����(win)
    <Win+Tab>������3DЧ�����л�
    <Ctrl+Alt+Backspace>���൱��ǿ��ע��
    <Ctrl+Alt+Del>�������ػ��˵�
    <Ctrl+Alt+l>����������
    <Ctrl+Alt+d>����С��gnome���д���
    <Ctrl+Alt+f2>��linux�ն��û���Alt + f7����xwindows��Alt+ <- ��-> �����ն��л���
    <Ctrl+Alt+ <- ��-> >���л�����
    <Alt + F1>�������˵�
    <Alt + F2����>��������x���ڣ�r ������reboot �ػ���hAlt��
    <Ctrl + Alt + d>����ʾ����
    <Alt + F9>����С����ǰ����
    <Alt + F10>����󻯵�ǰ����
    <Alt + F4>���رյ�ǰ����
    Print Screen��ȡȫ��
    Alt + Print Screen��ȡ����
    <Ctrl+Alt+���¼�ͷ>���л�������(Fedora)
    <Alt+F10>���������ڵ�Ĭ�ϴ�С(Fedora)
```

## linux�޸�Ĭ�ϴ��ļ��ĳ���

linux ��ȫ�ֵ��ļ������Ĺ�����ͨ��`/usr/share/applications/defaults.list`�ļ������ã����ļ������˸����ļ������Ĺ����Ĵ򿪷�ʽ����װ��nero֮���ļ�iso���ļ�Ĭ��ʹ��archive manager�򿪣���`~/.local/share/applications/mimeapps.list`���һ�У�

    `application/x-cd-image=nerolinux.desktop;`

��`/usr/share/applications/defaults.list`�����һ�У�

    `application/x-cd-image=nerolinux.desktop;`

ͼ�ν�����˫��iso�ļ���ʹ��nero���ˡ�



##��������

12.10�Լ�֮ǰ�İ汾�ܺ�ʹ������13.04֮�󣬲���У԰�����ǵ��ߣ������������panel������˵�����ѡ�����wifi���ص���

* �Ǽ������ʵ䰲װĿ¼: /usr/share/stardict/dic 
* ����Ŀ¼: home/user/.font/

##�رո���ʱ�����

��ϵͳ����/��Դ��

##�л���Ubuntu gnome ��������

ע��unity���滷����Ȼ��ѡ���¼����Ϊ���������桱���ɽ��롣

# Linux��װϵͳָ��(Ubuntu)

* ��������(ubuntu��ʱ�ر�wifi)
* ��װchrome��ͬ����ǩ
* ��װvim�����������ļ�
* �޸����ļ����ļ���
* ��װ��ɽwps�������������
``` 
     fedora:/opt/kingsoft/wps-office/office6/wps: error while loading shared libraries: libstdc++.so.6: cannot open shared object file: No such file or directory
     yum install libstdc++-devel.i686
``` 
* ��װSynaptic�����������
* ж��libreoffice/firefox/thunderbird/youker-assistant/amazon
* �������������
* ��װGLX-Dock����������
* �������뷨����ݼ��ȣ������µ�¼
* ��װclementine/osd-lyrics���������ã�����������⣬��װ������
* ��װbluefish��geany
* ��װ���̣���������̺�ubuntu one
* ��װfilezilla/okular/meld
* ж��Rhythmbox/empathy/account-plugin-*
* ��װfont-manager

# Linux��װϵͳָ��(Fedora)

* ��װgnome-tweak-tool���ù���
* sudo yum install gnome-tweak-tool
* ��װ�������Ͻǡ����������ҵ����Ż����ߡ�ͼ��򿪽�������
* ��װ������Դ�����sudo yum install yum-plugin-fastestmirror
* ��װ���ؼ��ٲ����sudo yum install yum-presto -y
* ��װ����Ҽ������ն��д򿪡���sudo yum install nautilus-open-terminal
* ����RPM Fusion
* ж��������: firefox
* ��װ������:gcc/Yumex/Compiz(ccsm)/Cariodock
* �����Զ������ļ�ϵͳfstab
* ����ϵͳyum update
* ��װvim
* ɾ�����ں�

    1. �鿴��ǰϵͳ���Ѱ�װ���ں���ذ���# rpm -qa | grep kernel
    2. �鿴��ǰʹ�õ��ںˣ�# uname -r
    3. ȷ��Ҫɾ�����ںˣ�
    4. ɾ���ںˣ�# yum remove kernel-...���ں˰汾���ƣ�ʹ�� yum remove ����ɾ�������Զ��Ƴ���/boot/grub/menu.lst �е����������


# ���Դ��������

## ubuntu��������

���¹������ڼ���������ʱ����������������

�޷����� cdrom://Ubuntu 8.10 _Intrepid Ibex_ - Release i386 (20081029.5)/dists/intrepid/main/binary-i386/Packages  ��ʹ�� apt-cdrom��ͨ�����Ϳ����� APT ��ʶ��ù��̡�apt-get upgdate ���ܱ����������µĹ��̡�

�޷����� cdrom://Ubuntu 8.10 _Intrepid Ibex_ - Release i386 (20081029.5)/dists/intrepid/restricted/binary-i386/Packages  ��ʹ�� apt-cdrom��ͨ�����Ϳ����� APT ��ʶ��ù��̡�apt-get upgdate ���ܱ����������µĹ��̡�

�޷����� http://cn.archive.ubuntu.com/ubuntu/dists/intrepid-backports/main/binary-i386/Packages.bz2  Hash У��Ͳ���

��һЩ�����ļ��������أ����ǿ��ܱ������ˣ�Ҳ����ת��ʹ���˾ɵ������ļ���

�������

�� /etc/apt/sources.list������cdrom�ļ���ɾ������������������Ļ������°������������Դ���е�cdromȥ����

## Ubuntu���°�װԴ  

1.sudo cp /etc/apt/sources.list /etc/apt/sources.list.bk

sudo gedit /etc/apt/sources.list

�༭���Դ�б���ԭ��������ȫ��ɾ������������б������ʺ����Դ��ע�ⲻҪȫ����ӣ���ѡ��һ���������ļ��ɣ����Ƶ�����б��У�Ȼ�󱣴��б�

2.sudo apt-get update ����Դ�б���Ϣ

���������С�sudo apt-get update ��ʱ�鿴һ�´�����Ϣ���Ѳ������ӵ�Դɾ�����������С�sudo apt-get update ����

3.sudo apt-get upgrade ����������ubuntu�Դ��ĸ��¹���������Ҳ�ɡ�

���� Ubuntu 10.10 Դ���ٶȺܿ죩

����:

deb http://mirrors.163.com/ubuntu/ maverick main restricted universe multiverse

deb http://mirrors.163.com/ubuntu/ maverick-security main restricted universe multiverse

deb http://mirrors.163.com/ubuntu/ maverick-updates main restricted universe multiverse

deb http://mirrors.163.com/ubuntu/ maverick-proposed main restricted universe multiverse

deb http://mirrors.163.com/ubuntu/ maverick-backports main restricted universe multiverse

deb-src http://mirrors.163.com/ubuntu/ maverick main restricted universe multiverse

deb-src http://mirrors.163.com/ubuntu/ maverick-security main restricted universe multiverse

deb-src http://mirrors.163.com/ubuntu/ maverick-updates main restricted universe multiverse

deb-src http://mirrors.163.com/ubuntu/ maverick-proposed main restricted universe multiverse

deb-src http://mirrors.163.com/ubuntu/ maverick-backports main restricted universe multiverse

����ǿ���Ƽ���163���ٶȼ��죬�����Ǹ�������Ժ�ǧ�������apt-get updateһ��ߺ��

deb http://tw.archive.ubuntu.com/ubuntu/ karmic main universe restricted multiverse

deb http://tw.archive.ubuntu.com/ubuntu/ karmic-security universe main multiverse restricted

deb http://tw.archive.ubuntu.com/ubuntu/ karmic-updates universe main multiverse restricted

deb http://tw.archive.ubuntu.com/ubuntu/ karmic-proposed universe main multiverse restricted

deb http://tw.archive.ubuntu.com/ubuntu/ karmic-backports universe main multiverse restricted

## RPM FusionԴ

Fedora��װPackage�����Ŀǰ�Ѿ���ԭ�ȵĵ���RPM����ʽ��������Ϊyum��ʽ��, �����ԭ��ʽ����,���Ǽ򵥵İ�װĳ��RPM��, ���ǱȽ����ܻ����ҵ����Ӧ������ϵ,�����Ҫװ��ĳ����,��������������������Ҳ���Ա���װ,���ԭ�ȵķ�ʽ�����൱��Ľ���. ��Fedora�Դ�������ⲻ�Ǻܷḻ,���RPM fusion�Ͳ�����,����ҪĿ����ΪFedora/RedHat��Linux���а��ṩ�����֧��,��ϲ��� Dribble/ Freshrpms��rpm.livna.org����������ֿ�,�ܶ�ԭ�Ȳ�֧�ֵ������,���Ƕ�����ͨ��RPM Fusion�����׵��ҵ�,����Fedora 10�µ�mplayer�ȵ�.     RPM Fusion�Ĺٷ�վ��: http://rpmfusion.org/ 

RPM Fusion�İ�װ����: 

1. ���ȴ�RPM Fusion��վ������Ӧ��RPM Fusion��,���ߴӱ�������.
2. 
ԭ��վ:    

http://download1.rpmfusion.org/free/fedora/rpmfusion-free-release-stable.noarch.rpm        http://download1.rpmfusion.org/nonfree/fedora/rpmfusion-nonfree-release-stable.noarch.rpm         ��������:

rpmfusion-free-release-stable.noarch.rpm

rpmfusion-nonfree-release-stable.noarch.rpm

2. �л�Ϊroot�û�

3. ��װrpm fusion

rpm -ivh rpmfusion-free-release-stable.noarch.rpm

rpm -ivh rpmfusion-nonfree-release-stable.noarch.rpm

4. ��ʱ����yumʱ,���Ѿ��������õ�rpm fusion����Ӧ���������.  
5. 


## ATrpmsԴ

��Ϊrpmfusion��������ATrpms�����,��˽���ִ������Ĳ�������ATrpmsԴ.

ATrpms�ٷ���վ:http://atrpms.net/

��װ�������ٷ���վ��

# FTP��Դ

Linux���                                                

ftp://ftp.tsinghua.edu.cn   ���־���Linux���                
ftp://mirror.pku.edu.cn/pub/linux/                                    
ftp://219.238.157.219/pub/                                            
ftp://eelinux.3322.org                                                
ftp://166.111.72.5/Linux                                        
ftp://166.111.121.3/Linux/                               
ftp://166.111.68.183/pub/Linux/                                 

Debian��������

ftp://debian.ustc.edu.cn/          ����Ƚ�ȫ            
ftp://ftp.tsinghua.edu.cn/mirror/debian 
ftp://ftp.sjtu.edu.cn/mirror/sites/ftp.debian.org/
ftp://mirror.dlut.edu.cn/ 
ftp://debian.nctu.edu.tw/ 

http://debian.cn99.com/   

http://debian.okey.net/   

ftp://deb.distro.cn       

Gentoo��������                      

ftp://ftp.sjtu.edu.cn/mirror/sites/gentoo 

ftp://ftp.tsinghua.edu.cn/mirror/gentoo   

ftp://166.111.172.55/pub/mirror/gentoo   

rsync://gentoo.net9.org/gentoo-portage  

Fedora:apt-rpm

ftp://ftp.tsinghua.edu.cn/mirror/ayo.freshrpms.net/pub/freshrpms/ayo/fedora/linux/2/i386/ 

rpm ftp://ftp.sjtu.edu.cn apt/fedora/2/i386 os updates freshrpms 

ftp://ftp.ctex.org/?

ftp://ftp.kernel.org/pub/

ftp://ftp.gnu.org

# ���뼰��������

##����

�����룺

ascii

�й��ƶ��ı��룺��gb������ұ�׼������gbk���ǹ��ұ�׼���������gb2312.������������ַ���

gb2312

gbk

gb18030

����ͳһ���룺

utf

linuxϵͳ���ļ�������Ϊurf8����

windowsϵͳ���ļ���Ĭ��Ϊgbk����

�����ĵ�ʹ��gbk���룬ϵͳ����utf8����

##���������뷨���µ�����

1��ibus���뷨

Ubuntu ϵͳ��װ���Ѿ��Դ���ibus���뷨����Ӣ�ﻷ����Ĭ�ϲ�������

����ibus�Զ�����������ubuntuϵͳ�˵���ѡ��System --- Preferences --- Startup Applications���ڸô���������һ������

Name: ibus-daemon

Command: ibus-daemon -d -x -r

ibusĬ���ṩ���������뷨�Ƚ����ǣ���Ҫ���ⰲװibus-pinyin���������£�

sudo apt-get install ibus-pinyin

�� ʱ������Ҫ��ibus-pinyin���뷨��������ubuntuϵͳ�˵���ѡ��System --- Preferences --- IBus Preferences����Input Methodҳ�еġ�Select an input method����������ѡ������Chinese �C Pinyin������ͼ�����и�һ�����ġ�ƴ���ֵ���һ����Ȼ����Add��ť�����ͨ��Up��ť�������뷨�ƶ��������档

ϵͳ������ͨ��Ctrl + �ո񼴿ɵ���ibus���뷨��

ibus���뷨������˵�����������ҵĻ����·����޷��ڲ���Java�����е�����������Netbeans��OpenProj��

2��fcitx���뷨

����ibus��ȱ�ݣ������ҳ�����fcitx��ʹ������Ҳ�ǳ��������ҿ�����Java����������ʹ�ã�ֻ������������¹�������Щ���⣬��������ͣ ������Ļ���¶ˣ����ǿ��Խ��ܣ�����ibus����ʹ��Ҫ�ö��ˡ�

��װfcitx��

sudo apt-get install fcitx

����fcitx��

im-switch -s fcitx

ע�������µ�¼��fcitx�ͻ���Ч��

�����Ҫ�л���ibus����������im-switch -s ibus��Ȼ��ע�������µ�¼��

fcitxͬ������ͨ��Ctrl + �ո��������ʱ�ᷢ��fcitx��ʾ�������Ƿ��������Ҫ�޸�fcitx�����á�Fcitx�������ļ���~/.fcitx/config�����ļ�Ϊ GBK���룬��Ubuntu����ʾ������������ͨ�����·�ʽ������

cd ~/.fcitx

iconv -f gbk -t utf8 config > config.tmp

�༭config.tmp�ļ���

��ʾ����(��)=WenQuanYi Micro Hei

��ʾ�����С=10

ʹ�ô���=0

�����˳���Ȼ���������

iconv -f utf8 -t gbk config.tmp > config

ע�������µ�¼��fcitx��ʾ������

�����ѹ������ѡ���������⣬������

sudo apt-get install fcitx-module-kimpanel

Ȼ��ע������������һ��Ϳ�����



## utf8 �� UTF-8 ��ʲô����

��UTF-8���Ǳ�׼д������windows�±�Ӣ�Ĳ����ִ�Сд������Ҳ����д�ɡ�utf-8������UTF-8��Ҳ���԰��м�ġ�-��ʡ�ԣ�д�ɡ�UTF8����һ�������ʶ�𣬵�Ҳ�����⣨�����ģ���Ϊ���ϸ�һ�㣬����ñ�׼�Ĵ�д��UTF-8����

��MySQL���ݿ���ֻ��ʹ�á�utf8��

������MySQL������ģʽ��ֻ��ʹ�á�utf8��������ʹ�á�utf-8����Ҳ����˵��PHP������ֻ��ʹ�á�set names utf8(����С���)�����������ˡ�-���������������Ч��������PHP��headerʱȴҪ���ϡ�-������ΪIE����ʶû�ܵġ�utf8����ԭ�� �����ġ�

��IE�������ֻ��ʹ�á�utf-8��

����IE�����ʹ���ˡ�utf8����ҳ����ܻ� �հ� �� ��ʾΪ���롣

�������������������ȴ�������ģ�ԭ������Ϊ�����������Ĭ��ʹ�õ���UTF-8�ı��룬����޷�ʶ��ҳ��ı���ͻ���Ĭ�ϵ�UTF-8�����룬�� ��IE��Ĭ�ϱ�����GB2312������Ĭ�ϵĻ��͡��������������������ָ��FireFox������Chrome������Opera����

�ܽᡡ��

������ֻ����MySQL�п���ʹ�á�utf-8���ı�����utf8���������������ط�һ��ʹ�ô�д��UTF-8������

��������Ϊ��

�������������mysql_query(set names utf8)����һ���ô�д��UTF-8����



##��ҳ��Flash�е�������ʾΪ����Ľ���취

�༭/etc/fonts/conf.d/49-sansserif.conf�ļ����������޸ģ�

<edit name="family" mode="append_last">

<string>WenQuanYi Micro Hei</string>

</edit>

## Java���򲿷�������ʾΪ����Ľ���취

��$JAVA_HOME/jre /lib/fontsĿ¼�½���fallbackĿ¼�������������ļ����ƣ���link����fallbackĿ¼��

sudo mkdir $JAVA_HOME/jre/lib/fonts/fallback

sudo ln /usr/share/fonts/truetype/wqy/wqy-microhei.ttc $JAVA_HOME/jre/lib/fonts/fallback/

## ��GBK���롱���ο�

������������ƣ�  

��??�� ����??��3?��???1,��2��??�� ����??��3?��???1 

��������� 

ʹ��convmv 

�������ļ����ļ�������һ����Ŀ¼�����У���������Ҳ���£��� 

����: 

convmv -r -f utf8 -t iso88591 --notest --nosmart * && convmv -r -f gbk -t utf8 --notest --nosmart *       

## ��ascii���롱�ο� 

������������ƣ� 

%E5%8C%BB%E4%BF%9D 

��������� 

1.ʹ��uni2ascii ����: 

echo ����ԭ�� | ascii2uni -a J 

2.��װnautilus-filename-repairer0.06���ٷ���Դ�룬�����������⣬�һ�û��װ�ɹ�����0.05�������ڵ�nautilus�е�СС�ĺ����ϰ���ֻ�ܿ����ܸ���) 

3.��chromeplus-1.3.3.1���أ���Ϊ����������Ҫ����ff��Ĭ��utf8������qqȺ����ļ�֮���������chromeplus(Ĭ��GBK)�¾�û�����ˣ�      

���⣬�����ļ��������ݵ����������������enca.

##���Rhythmox�������⣺ 

��װRhythmox��sudo apt-get install rhythmbox 

��װmid3iconv��sudo apt-get install python-mutagen 

mid3iconv -h 



## Clementine��������

��װmid3iconv��sudo apt-get install python-mutagen 

mid3iconv -h

Clementine��֧��utf8����Ҫ�����е�mp3����ת��Ϊgbk��ʽ��wma������ת�Ϳ���

mid3iconv -e gbk *.mp3(���ڲ��ܴ�-r����������Ҫ���ν���ÿ���ļ���)

����clementine����gstreamer��Ϊ��ˣ���Ҫ��װgstreamer�����

1 �����֧��mp3����Ҫ��װgstreamer-0.10-plugins-bad��gstreamer-0.10-plugins-ugly

2 �����֧��wma����Ҫ��װgstreamer-0.10-ffmpeg

3 �����֧��mms��ý�壬��Ҫ��װgstreamer plugins for mms

����Clementine����Amarok������֧��Amarok�Ĳ��һ�㶼֧��Clementine������osdlyrics��

##ת���ļ����ݱ���: 

    file -i <file name> ����ļ�����
    iconv --help 

##ת���ļ�������

    sudo apt-get install convmv 
    convmv --help 
    convmv -f gbk -t utf8 -r --notest files 
    convmv -r -f utf8 -t iso88591 * --notest --nosmart && convmv -r -f gbk -t utf8 * --notest --nosmart 

##���gedit�������⣺ 

    gsettings set org.gnome.gedit.preferences.encodings auto-detected "['GB18030', 'GB2312', 'GBK', 'UTF-8', 'BIG5', 'CURRENT', 'UTF-16']" 
    gsettings set org.gnome.gedit.preferences.encodings shown-in-menu "['GB18030', 'GB2312', 'GBK', 'UTF-8', 'BIG5', 'CURRENT', 'UTF-16']" 

##���PDF�������룺 

��װpoppler-data������� sudo apt-get install poppler-data 

##���rar�ļ�����

ʹ��rar 

##��ѹzip�ļ�����

�������������⣬��������һȦ������ʲôunzip -O��һ���ö�û�У���Щ���ǹ�����ֱ�Ӹ��ƣ��ö�û�ù����������˸��ռ���������python�Ľű�����ѹ�������£�������ã���������Ϊpython�ű��Ĵ��룬�½��ļ�jieya.py��д�����´��룺

```python
    #!/usr/bin/env python
    # -*- coding: utf-8 -*-

    import os
    import sys
    import zipfile

    print "Processing File " + sys.argv[1]
    file=zipfile.ZipFile(sys.argv[1],"r");
    for name in file.namelist():
        utf8name=name.decode('gbk')
        print "Extracting " + utf8name
        pathname = os.path.dirname(utf8name)
        if not os.path.exists(pathname) and pathname!= "":
            os.makedirs(pathname)
        data = file.read(name)
        if not os.path.exists(utf8name):
            fo = open(utf8name, "w")
            fo.write(data)
            fo.close
    file.close()
```

Ȼ��zip�ļ���jieya.py����ͬһ��Ŀ¼����������python  jieya.py file.zip��Ŷ�ˣ�

## smplayer ������Ļ���������� 

1����ѡ�����ѡ�֣�ѡ����Ļѡ��� 

2���ҵ���Ĭ���ַ����롱ѡ�����������ѡ�񡰼������ģ�cp936���� 

3���ٴ򿪡����塱ҳ�����ϱߣ���ѡ��ϵͳ���塱������ѡ����ѡ��һ�ּ����������壬�� Weu Quanyi Zen Hei �ȡ� 

�����������ã�smplayer�Ѿ�����������ʾ������Ļ�ˣ��㻹�����ڸղŵ�λ����һ����չ���ã��硰�ı���ɫ������ʾλ�á��ģ�������߰��Լ�ϲ��ȥ���ա�

## VLC��������ʾ�ļ�������

��ѡ�����޸�һ��֧�����ĵ�����



# ��������������������

pdf�Ķ���:okular evince

�ı��༭����vim��emacs��gedit

���ֲ��������clementine

rhythmbox�����ʾ���ߣ�osd-lyrics

�����������ߣ�compiz

��Ƶ��������KMPlayer

eD2k����:aMule

��̹���:bluefish

pdf�ϲ����ߡ���pdftk

���뷨��ibus+fcitx  ��������Xwindow��ɣ��� Ctrl + �ո���������뷨���������л����뷨ʱ���Ѽ���-ƴ�����뷨����������

΢���������sudo apt-get install msttcorefonts 

���������:font manager 

�ʼ����:Ϊ֪�ʼǣ�ֱ����tar.gz��

����:��ŵ����(�˵����в��ֱ��Ӣ��,����ʹ��,�����滻Ϊ�����) /Dropbox

���������:������(Synaptic) 

���̹�������LVM/GParted 

�������Chrome 

�ʵ䣺goldendict 

3D��ģ���ߣ�blender 

ͼƬ�����ߣ�GIMP 

Dock:GLX-Dock 

��Ƶ�༭�COpenshot

BT���أ�Transimssion

ftp�ͻ���Filezilla

�ʼ��ͻ��ˣ�thunderbird 

������������Furius ISO Mount

�ļ��Ա������meld

��ͼ�����xmind

Զ�̿��ƣ�vncview

���ݴ��������octave�����ּ���matlab��

��¼������Ͳ����ն˻Ự���: ttyrec �� ttyplay

�������������BleachBit

Audio CD Extractor����ƵCD��ȡ����

����������ե֭��������Sound Juicer����

�ܰ�CDת��flac��ogg��mp3�ȸ�ʽ��

�ٷ���ҳ��http://www.burtonini.com/blog/computers/sound-juicer 

Sound Converter������ת������

֧��flac��ogg��mp3��wav��m4a�ȸ�ʽ��������ת��

�ٷ���ҳ��http://soundconverter.berlios.de 

curl������URL�﷨�������з�ʽ�¹������ļ����乤�ߡ�

����ͼ��UML����ͼ����

IHMC CmapTools:http://cmap.ihmc.us/

yED Grahp Editor:http://www.yworks.com/en/index.html

##�ѹ����뷨��װָ��

���� Ubuntu 12.04 LTS �Դ��� Fcitx �汾�Ͼɣ���Ҫ��ͨ�� PPA ���������ܰ�װ���ص� deb �������

1. ������Ͻǵ�ͼ���Dash������update-manager��������¹�������
2. �ڸ��¹������У�ѡ��˵����༭->���Դ��������...��ť���ڵ����Ĵ���������ppa:fcitx-team/nightly�� ������Դ��
3. Ȼ�����������롣
4. ��Ubuntu������ģ�������������fcitx�������ѳ�fcitx��Ȼ����һ�������װ���谲װ�������������
5. ˫�����ص� deb �������װ�ѹ����뷨��

##�����ɽwps��������

�������ѹ��~/.fontsĿ¼��Ȼ������wps���ɡ�

˵������Щ�ļ�Ϊ΢���Ȩ���У�ʹ����Щ����������ȷ��ӵ����Щ�����ʹ����Ȩ������˵��ĳ�汾windows��Ȩ���ɣ�

�����һ�����û���ӳ�����ϵͳ��װ��xfonts-mathml���ܵ��·����޷���ʾ��

������֤����������Ϊxfonts-mathml��Ҳ����һ�������Symbol���µġ�

�����װ����������Դ������������볢���Ƴ�xfonts-mathml����

## libreoffice��PPT����������

Tools �� Options... �� LibreOffice �� View �� Graphics output (ȡ����ѡUse hardware acceleration)  

##С������뷨ͻȻ�޷�ʹ��

�鿴һ���Ƿ�װ��ibus������ϵͳ�����е�����֧�������°����뷨��Ϊibus



# ���ļ�����������ļ��иĳ�Ӣ���ļ���

���նˣ����ն����������

 

export LANG=en_US

xdg-user-dirs-gtk-update

 

���ʱ��ᵯ��һ�����ý��棬��ʾ�Ƿ�����Ŀ¼�л�ΪӢ��Ŀ¼��ѡ�в�����ʾ��ȷ����ϵͳ��ɾ��û�����ݵ�����Ŀ¼���������ݵ�Ŀ¼�ᱣ�֡�������8����Ӧ��Ӣ��Ŀ¼���£���Desktop������Download������Templates������Public������Documents������Music������Pictures������Videos������ʱ�����ڡ�λ�á��￴���ĳ�������Ŀ¼�Ѿ����Ӣ��Ŀ¼��

��ִ�У�

export LANG=zh_CN.UTF-8     

����ʾ����

#�����װʹ������

## Rdseed�İ�װ

1������: 

http://www.iris.edu/pub/programs/rdseedv5.2.tar.gz

2����ѹ: tar -xzvf rdseedv5.2.tar.gz

3�����룺

1����makefile���ҵ��⼸��

CC = cc 

# for cygwin add the -D_CYGwin flag, for users of windows pcs

CFLAGS     = -O -m32 -g -D_CYGwin



# to compile rdseed as a 32-bit application

#CFLAGS     = -O -m32 -g 



2����CYGwin��ע�͵���ȡ��������һ�е�ע�ͣ�

CC = cc 

# for cygwin add the -D_CYGwin flag, for users of windows pcs

#CFLAGS     = -O -m32 -g -D_CYGwin



# to compile rdseed as a 32-bit application

CFLAGS     = -O -m32 -g 



3������make clean



4������make



4��������õ�rdseed�ļ�������binĿ¼�£�sudo cp rdseed /usr/bin/



5������rdseed���ɽ��롣



ע��64λϵͳ�¿���ֱ��ʹ���ѱ���õ��ļ�:cp -p rdseed.rh6.linux_64 /usr/local/bin/rdseed 

## SAC��װ

1������������������������վ�����룬������д����ƽ̨ѡ��ѡ��Linux 32 λ��64λ���������ȤҲ����ѡ��һ��source code����ע�ⲻҪͼʡ��һ�ΰ����а��������ˣ���������Ա��ר�Ÿ��㷢�ʼ�Ҫ����͵ġ����ʹ��ѧУ������߽���������䣬�����б��ܵĿ��ܡ�����֤ͨ���������������ڼ����յ��ʼ���

������ַ��http://www.iris.edu/forms/sac_request.htm

2����sac �ļ�ѹ����ֱ�ӽ�ѹ�������sac�ļ��У���������˶���ļ��У�

tar xvfz netcdf-3.6.3.tar.gz

for i in *.bz2;do tar jxvf $i;done



3��������sac �ļ��п���ĳĿ¼�£�SAC �Ƽ���װĿ¼Ϊ/usr/local����

sudo cp -r sac /usr/local

4���༭.bashrc ���û�������

gedit ~/.bashrc

��.bashrc ���������������



export SACHOME=/usr/local/sac

export SACAUX=$SACHOME/aux

export PATH=$SACHOME/bin:$PATH



5���ն�����source ~/.bashrc 6���ն�����sac��ע��ҪСд���������汾�ŵ���Ϣ����װ�ɹ���
6��
## SEISMIC UNIX ��װʵ����Fedora Core /Ubuntu ϵͳ ��

ǰ�� ��1 ���� fedora core ϵͳ�ڰ�װ������ �����ݸ��˵�ѡ���ָ����װ������ģ���SU�İ�װ �������������ĳ�װ�޷����У���ܿ�����ĳ����û�б���װ��ϵͳ�ǣ��ر����ڰ�װʱ ��һ��Ҫѡ�� MESA��LibGLU���� MESA��LibGL�� ������ �������� �� �� ��xϵͳ���� "�� �����ҵ� ��

2 ���⣬SU �İ�װ�����л���Ҫ GLUT�� ������Ҫ���������ء����ط��� �� ��GOOGLE�� ���� FREEGLUT �����ɿ���������� �� 

��װ������� ��

1 SU ��װ�����Ľ���֮һ

��Ҫ�����㡣1�����ն� �����룣export CWPROOT����home/yourname/su ˵����·�� ��home/yourname/su Ϊ�Լ�����ָ����·�� ���Ժ�SU�������·���½��а�װ������ ���ҵ�·���� ��home/wh/su.

2 ���ն� �� ���� ��export PATH=$PATH��/home/yourname/su/bin ˵�������ϣ�������·��Ϊ�Լ�����ָ����·����ǰһ����Ҫ������һ�£������������˼�ǽ�/home/yourname/su/bin�е���������LINUXϵͳ������·����

2 SU�ڱ�ϵͳ�а�װ�����Ľ�������װ

��������ݸ���ϵͳ�Ĳ�ͬ����ͬ����������һ�µġ����ｫ�ֲ��ֽ���˵����

��1����CWP��SU��������home/yourname/su��Ȼ�� ��ѹ ��tar zxvf cwp-su.xx,��ѹ�󽫻ῴ��������һ���� Ŀ¼ src,�����Ŀ¼��

��2���Ķ��ļ�readme-to-install,���Կ�����װSU�Ĵ��岽�衣

��3)�Ķ��ļ�makefile.config,���ǳɹ���װSU�Ĺؼ����������ΰ�װSU˵���ĺ���� �����Ľ���������Ĺؼ����㡣

2��1 ִ��make install��׼������

��Ҫ����Ҫ�޸�makefile.config�е����

1���� ENDIANFLAG = -DCWP_LITTLE_ENDIAN �伤�

2���� include $(CWPROOT)/src/Rules/gnumake.rules �伤������ε� #include $(CWPROOT)/src/Rules/oldmake.rules ��,�޸ĺ� ���棬Ȼ������ make install�Ϳ��Գɹ���װ��

2��2 ִ��make xtinstall, ����Ҫ�޸ģ�ֱ������make xtinstall

2��3 ִ��make finstall ��׼������

������Ҫָ��fortran����������fedora core 6ϵͳ�У�GCC�İ汾��4��1��1����˿���ֱ������GCC�еı�����gfortran,����makefile.config�е���ؾ��ΪFC = gfortran,������ϵͳ��Ϊ��Ӧ��fortran���������ɡ�

2��4 ִ��make mglinstall ��׼������

�������Ҫ�����ᵽ��LIBGLU���� GLUT��������ؿ��� ��LIBGLU�ڰ�װFC6ʱ��Ϳ��԰�װ��ϵͳ����Ĭ�ϰ�װ·��Ϊ��usr/lib,�� usr/include. ��GLUT��Ҫ���������ء�ֵ�� ע����ǣ�Ҫ���ؽ��µ�FREEGLUT�����غ��ѹ��װ��FREEGLUT�İ�װΪ���氲װ ��װ�ú���Է����䰲װ·��Ϊ��usr/local/lib,�� usr/local/include, ��ˣ��Ͳ���Ҫ��makefile.config����ز������κθĶ���

���ˣ�SU�����岿�ְ�װ��ϣ���������Ϊ��ѡ�����������ƣ����� makefile.config                                �е���ؾ����ʵ��ĸĶ���

����˵����1 ���Ժ�ÿ������SU��ʱ�򣬶���Ҫ����export��������䡣�������ÿ�ζ����룬�����޸�.bashrc�ļ�(���ҵ�ϵͳ������ļ���/home/wh/.bashrc)��export��������ӽ��뼴�ɡ�

2 ������ձ�����˵�Ĺ��̽��а�װ������������ĳһ�����ִ����Ǻܿ�����ϵͳ�� ��װ�Ĺ�����û�а�װ��Ӧ�Ŀ⣬��ʱ����ϸ���������������Ϳ��Է��ֵ�������Щ��û�а�װ��Ȼ����GOOGLE���ҵ���Ӧ�Ŀ����ذ�װ���ɣ����� YUM�����

����ϴ�һ��SU��DEMO�����ӽ��չʾͼƬ��



$(CWPROOT)/src/Rules/oldmake.rules ��,�޸ĺ� ���棬Ȼ������ make install�Ϳ��Գɹ���װ������˵����1 ���Ժ�ÿ������SU��ʱ�򣬶���Ҫ����export��������䡣�������ÿ�ζ����룬�����޸�.bashrc�ļ�(���ҵ�ϵͳ������ļ���/home/wh/.bashrc)��export��������ӽ��뼴�ɡ�





����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������

1 ��װ��ubuntu��������Ҫ���������úã���ѡ����ʵ����Դ�����ڽ������û����Ƽ��й��ƴ�����Դ����ο�����blog�е����÷�����http://hi.baidu.com/from/blog/item/30db2e734f516e1f8701b0a4.html



2 Ԥװ7��������������ն��������������

sudo apt-get install build-essential

sudo apt-get install libx11-dev

sudo apt-get install libxt-dev

sudo apt-get install libglut3-dev

sudo apt-get install libxmu-dev

sudo apt-get install libxi-dev

sudo apt-get install gfortran



3 su��װ��׼��������һ����3����



1�����룺 export CWPROOT=/home/yourname/su   ע�������/home/yourname/suΪ�����ز���ѹsu���ڵ�Ŀ¼

2�����룺export PATH=$PATH:/home/yourname/su/bin ע��/home/yourname/su ������ͬ�ϣ�binΪ��ѹsu�������ɵ�Ŀ¼��

3������/home/yourname/su/src ���Ŀ¼�����Կ���makefile.config ����ļ���Ҫ�޸����������,�������gedit makefile.config , Ȼ���޸����򿪵��ļ���



1���� ENDIANFLAG = -DCWP_LITTLE_ENDIAN �伤���ȥ��#����

2���� include $(CWPROOT)/src/Rules/gnumake.rules �伤������ε� include$(CWPROOT)/src/Rules/oldmake.rules ��,�޸ĺ� ���档

3, ��FC=g77, FC=f77,FC=ifort ���ε�������FC=gfortran

4����OPTF = -O -static -mcpu=i686 -fno-globals -fno-automatic -fno-second-underscore ���Σ�����OPTF = -O -static -march=i686 -fno-automatic -fno-second-underscore



4 ��ʽ��װ,�ֱ����룺

1��make install

2) make xtinstall

3��make finstall

4) make mglinstall

����su�����Ѿ��ɹ����μ���ͼ��



����˵����1 ���Ժ�ÿ������SU��ʱ�򣬶���Ҫ����export��������䡣�������ÿ�ζ����룬�����޸�.bashrc�ļ�(���ҵ�ϵͳ������ļ���/home/wh/.bashrc)��export��������ӽ��뼴�ɡ�



2   ��2011.11��libglut3-dev�Ѿ���freeglut3-dev�滻����:  sudo apt-get install freeglut3-dev



3  �����°汾su�� ������� OPTF = -O -static -march=i686 -fno-automatic -fno-second-underscore ��makefile.config�ļ��С�

## wine

winetricks ��wineTricks�����wine������

���ࣺ Linuxϵͳѧϰ��¼ 2011-04-26 22:11 4493���Ķ� ����(0) �ղ� �ٱ�

΢��windowsscriptingmfcvbbasic



Linux����������windows����ģ��������WINE�ˡ����ṩ��һ������ģ��WINDOWS�����Ļ���ƽ̨�����������㼸�����������κ��������е�windows����



ʲô���㲻���ţ���Ҫ��������ĳ�������ʱ������ʾȱ��mfc42.dll������



Ĭ�ϵ�wine����ȱ�ٺܶ�winƽ̨�Ŀ⣬������ɺ޵��ǣ�system32Ŀ¼�¾�Ȼû��regedit����



 



������������һ�£���������winE������Ϊ������



��ʾ����linux���а���ubuntu 9.04�� wine�İ汾����1.1.26



 



1.׼����ȷ��ע���༭��



���Ƚ�/home/����û���/.wine/dosdevices/c:/windows�µ�regedit.exe�����Ƶ�system32Ŀ¼�¡�



���



sudo cp /home/����û���/.wine/dosdevices/c:/windows/regedit.exe /home/����û���/.wine/dosdevices/c:/windows/system32/



2.���ز���װwinetricks



wget http://www.kegel.com/wine/winetricks



chmod +x winetricks



sudo mv winetricks /usr/local/bin



3����winetricks��װ�����win֧�ֿ⡣��һ���ܹؼ���



������������winetricks



Ȼ��ѡcolorprofile��corefonts��d3dx9��fontfix��fontsmooth-gray��fontsmooth-rgb��fontsmooth-bgr��gdiplus��mfc40��mfc42��



msxml3��msxml4��msxml6��riched20��riched30��tahoma��urlmon��vb6run��vcrun6��vcrun2003��vcrun2005��vcrun2008��ie6��allfonts



Ȼ��ѡ��װ��



4����������winetricks�󣬹�ѡdotnet11��dotnet20��vjrun20����װ��



����װ����Ժ�����Ȥ�����ѿ��Գ��԰�װһ��powerdesigner�����ܲ����á�������



������Ϣ��μ�http://wiki.winehq.org/winetricks



 



 



wine������һ��������DanKegelд��һ����װwindows�йؿ�������С���򣬷ǳ����ã�



����һ��ʹ�÷�����



1�����նˣ�����

wget



http://www.kegel.com/wine/winetricks



2��������

sudo apt-get install cabextract



3��������

chmod +x winetricks



4�����

./winetricks



�ڴ򿪵Ĵ����У����Կ���������֧�ֵ�һ������б�

����:

art2kmin ΢�� Access 2000 ����ʱ.

colorprofile ��׼ RGB ��ɫ�����ļ�

comctl32 ΢�� common controls 5.80

comctl32.ocx ΢���comctl32.ocx ��comctl.ocx,VB6��comctl32���

corefonts ΢�� Arial, Courier, Times ����

dcom98 ΢�� DCOM, �滻wine���Դ���

dirac0.8 the obsolete Dirac 0.8 directshow filter

directx9 ΢�� DirectX 9

divx divx ��Ƶ����

dotnet11 ΢�� .NET 1.1

dotnet20 ΢�� .NET 2.0

ffdshow ffdshow ��Ƶ����

flash Adobe Flash Player ActiveX �� firefox ���

fontfix Fix bad fonts which cause crash in some apps (e.g. .net).

gdiplus ΢�� gdiplus.dll (�밲װpowerpoint)

gecko HTML ��Ⱦ����(Mozilla)

icodecs Intel ý����� (Indeo)

jet40 ΢�� Jet 4.0 Service Pack 8

liberation Red Hat Liberation ���� (Sans, Serif, Mono)

mdac25 ΢�� MDAC 2.5: ΢�� ODBC ����, etc.

mdac27 ΢�� MDAC 2.7

mdac28 ΢�� MDAC 2.8

mfc40 ΢�� mfc40 (Microsoft Foundation Classes from Visual C++ 4)

mfc42 ΢�� mfc42 (�����������vcrun6)

mono19 mono-1.9.1-gtksharp-2.10.4-win32-2

msi2 ΢�� Installer 2.0

msls31 ΢�� Line Services 3.1 (needed by native riched?)

msxml3 ΢�� XML version 3

msxml4 ΢�� XML version 4

msxml6 ΢�� XML version 6

ogg ogg �������ͱ�����: flac, theora, speex, vorbis,



pdh ΢�� pdh.dll (Performance Data Helper)

quicktime72 ƻ�� Quicktime 7.2

riched20 ΢�� riched20 and riched32

riched30 ΢�� riched30

tahoma ΢�� Tahoma ���� (not part of corefonts)

vb3run ΢�� Visual Basic 3 ����ʱ

vb4run ΢�� Visual Basic 4 ����ʱ

vb5run ΢�� Visual Basic 5 ����ʱ

vb6run ΢�� Visual Basic 6 ����ʱ

vcrun6 ΢�� Visual C++ 6 sp4 ���п� (����mfc42.dll, msvcp60.dll, msvcrt.dll)

vcrun2003 ΢�� Visual C++ 2003 ���п� (����mfc71.dll,msvcp71.dll,msvcr71.dll)

vcrun2005 ΢�� Visual C++ 2005 ���п� (����mfc80.dll,msvcp80.dll,msvcr80.dll)

vcrun2005sp1 ΢�� Visual C++ 2005 sp1 ���п�

vcrun2008 ΢�� Visual C++ 2008 ���п� (����mfc90.dll,msvcp90.dll,msvcr90.dll)

vjrun20 ΢�� Visual J# 2.0 ���п� (��Ҫ��װ dotnet20)

wmp9 ΢�� windows Media Player 9

wmp10 ΢�� windows Media Player 10

wsh51 ΢�� windows Scripting Host 5.1

wsh56 ΢�� windows Scripting Host 5.6

wsh56js ΢�� windows scripting 5.6, ֻ��jscript,û��cscript

wsh56vb ΢�� windows scripting 5.6, ֻ��vbscript,û��cscript

xvid xvid ��Ƶ����



autohotkey Autohotkey (open source gui scripting language)

firefox3 Firefox 3

kde KDE for windows installer

mpc Media Player Classic

vlc VLC media player



allfonts ������������ (corefonts, tahoma, liberation)

allcodecs ��������ý����� (xvid, ffdshow, icodecs)

fakeie6 ��ע�����д��IE6�Ѱ�װ��Ϣ

native_mdac Override odbc32 and odbccp32

nt40 Set windows version to nt40

win98 Set windows version to windows 98

win2k Set windows version to windows 2000

winxp Set windows version to windows XP

vista Set windows version to windows Vista

winver= Set windows version to default (winxp)

volnum Rename drive_c to harddiskvolume0 (needed by some installers)



���У�Ҫ��װQQ2008�Ļ���ֻ�谲װflash gecko msls31 riched20 vcrun6���ɡ�



## GTK

�����ô˷����ɹ���Ubuntu?12.04�°�װGTK 2.24.10  ��¼һ��

1����װgcc/g++/gdb/make �Ȼ�����̹���

sudo apt-get install build-essential

2����װ libgtk2.0-dev libglib2.0-dev �ȿ�����صĿ��ļ�

sudo apt-get install gnome-core-devel

3�������ڱ���GTK����ʱ�Զ��ҳ�ͷ�ļ������ļ�λ��

sudo apt-get install pkg-config

4����װ devhelp GTK�ĵ��鿴����

sudo apt-get install devhelp

5����װ gtk/glib ��API�ο��ֲἰ���������ĵ�

sudo apt-get install libglib2.0-doc libgtk2.0-doc

6����װ����GTK�Ľ���GTK�ǿ���Gnome���ڵ�c/c++����ͼ�ο�

sudo apt-get install glade libglade2-dev

7����װgtk2.0 ���� ��gtk+2.0����������ļ�ͳͨ���ذ�װ���

sudo apt-get install libgtk2.0-dev

�鿴GTK��汾

1.�鿴 2.x �汾

pkg-config --modversion gtk+-2.0

2.�鿴pkg-config�İ汾

pkg-config --version

3.�鿴�Ƿ�װ��gtk

pkg-config --list-all grep gtk

���Գ���

�������£�

//Helloworld.c

#include <gtk/gtk.h>

int main(int argc,char *argv[])

{

    GtkWidget    *window;

    GtkWidget    *label;

    

    gtk_init(&argc,&argv);

    

    /* create the main, top level, window */

    window = gtk_window_new(GTK_winDOW_TOPLEVEL);

    

    /* give it the title */

    gtk_window_set_title(GTK_winDOW(window),"Hello World");

    

    /* connect the destroy signal of the window to gtk_main_quit

    * when the window is about to be destroyed we get a notification and

    * stop the main GTK+ loop

    */

    g_signal_connect(window,"destroy",G_CALLBACK(gtk_main_quit),NULL);

    

    /* create the "Hello, World" label */

    label = gtk_label_new("Hello, World");

    

    /* and insert it into the main window */

    gtk_container_add(GTK_CONTAINER(window),label);

    

    /* make sure that everything, window and label, are visible */

    gtk_widget_show_all(window);

    

    /* start the main loop, and let it rest until the application is closed */

    gtk_main();

    

    return 0;

}

��������

1������

gcc -o Helloworld Helloworld.c `pkg-config --cflags --libs gtk+-2.0`

2������

./Helloworld

## wubi

���ȣ��ճ�һ���̷�����F�̣��������ص�ubuntu-12.04-desktop-i386.iso����������һ�����磨D�̣�����D����ľ����н�ѹ�� wubi.exe������ubuntu-12.04-desktop-i386.iso�� wubi.exe����ͬһ���ļ�������Ӣ����������ubuntu-12.04����Ȼ��˫�� wubi.exe�ᰲװ��������ȥ���ؾ��񣬰�װ����������ѡ���̷�ʱѡ����Ҫ��װ����F�̡�ף����ˣ�



��ֱ�ӽ�ѹ�����ļ���Ȼ��ѽ�ѹ������wubi.exe��ԭ�����غõ�ubuntu-12.04-desktop-i386.iso����ͬһ���ļ����У�˫������wubi��Ȼ������ʾһ������װ���ɡ���Ҫע����ǣ���öϿ������ٰ�װ����Ȼ�Ļ���װ�����п��ܻ���64λ�ģ������������������ı��硣

## pdftk����PDF�ļ�



Pdftk����Sid Stewardд��һ��PDF��ǿ����������Ժϲ�/�ָ�PDF�ĵ����⿪��Ҫ���������롢������ܡ���PDF�ĵ���ˮӡ����PDF�ĵ��н����������PDF�ĵ����һҳ�ȵȣ��ܹ���������PDF�ĵ����������顣 



�ϲ�

pdftk 1.pdf 2.pdf 3.pdf cat output 123.pdf

��

pdftk A=1.pdf B=2.pdf cat A B output 12.pdf

��

pdftk *.pdf cat output combined.pdf





���pdf�г������ҳ�ϳ���pdf

pdftk A=one.pdf B=two.pdf cat A1-7 B1-5 A8 output combined.pdf





128λ���ܣ�����һ��Ȩ��

pdftk mydoc.pdf output mydoc.128.pdf owner_pw foopass





ͬ�ϣ����򿪲�������

pdftk mydoc.pdf output mydoc.128.pdf owner_pw foo user_pw baz





ͬ�ϣ��ɴ�ӡ

pdftk mydoc.pdf output mydoc.128.pdf owner_pw foo user_pw baz allow printing





����

pdftk secured.pdf input_pw foopass output unsecured.pdf





�ϲ�������һ�����ܣ��ϲ����ļ�������

pdftk A=secured.pdf mydoc.pdf input_pw A=foopass cat output combined.pdf





Uncompress PDF Page Streams for Editing the PDF Code in a Text Editor

pdftk mydoc.pdf output mydoc.clear.pdf uncompress





�޸� Repair a PDF's Corrupted XREF Table and Stream Lengths (If Possible)

pdftk broken.pdf output fixed.pdf





Burst a Single PDF Document into Single Pages and Report its Data to doc_data.txt

pdftk mydoc.pdf burst





Report on PDF Document Metadata, Bookmarks and Page Labels

pdftk mydoc.pdf dump_data output report.txt

## Wireshark

Wireshark��һ��ǳ����е�Э������������Ȼ��������ץ��������

 sudo apt-get install wireshark 

���ڰ�ȫ����Ŀ��ǣ���ͨ�û����ܹ��������豸����ץ����wireshark�������û�ͨ��sudo��rootȨ�������У�

wiresharkΪubuntu��Debian���û��ṩ��һ���ڷ�root�µĽ��������

��ϸ���Ϳ��Բο���

/usr/share/doc/wireshark-common/README.Debian  http://nariver.com/usr/share/doc/wireshark-common/README.Debian��

���岽�裺

sudo dpkg-reconfigure wireshark-common

press the right arrow and enter for yes

sudo chmod +x /usr/bin/dumpcap

## Vimium��Vimperator ��������

����������� Vimium �� Vimperator�����źܶ���һ����������������־��Ѿ����뵽�˾���� Vim �༭�� ���� ����һ���������Ϊ�༭���е�����������ȫֻʹ�ü��̲�������Ȼ Vim ������ѧϰ���߱Ƚ϶��ͣ���һ����Ϥ֮���㽫�ᱻ�伫֮��Ч���ޱ�ǿ��ļ��������������۷�������һ�㶼�����ʹ�����ı༭�������෴���õúõĸ�������Ч�ʱ�ʹ��һ��win�µı༭��Ч��Ҫ�ߵöࡣ

Vimium �� Vimperator ��������ο��� Vim ����������ʽ����������������������������㼸��ȫ��ʹ�ü��̿�ݼ������������������Ч�ʡ�����㱾����һλ Vim �û��Ļ����㼸��û��ѧϰ���ż����ܿ�����ҵ�ʹ�� Vim �༭���������������ġ���Ϥ�С��������������֮ǰ��ȫû�нӴ��� Vim����ô�͵���΢�˽�ѧϰһ���ˡ���Ȼ����Ҳ���Խ��俴������ҳ������Ŀ�ݼ����ߣ���סһЩ���ò�����������һ��������������ˮ���ü��̹���ʱ�ĳ�����ˡ�Vimium ��һ�� Chrome ������еĲ������ Vimperator ���� FireFox ���������Ĳ������Ȼ���ֲ�ͬ���������ǵĲ���������û��ʲô�������������Ҿ��Խ��� Vimium Ϊ���ɡ�Vimperator ��ͬѧ������Ϊ�ο�һ��.�� shift+/ ��chrome�������ǽ�������ҳ�棨firefox+chrome���������ҵ�����ϸ�ĵİ������������㻹�����������а������Լ���ϰ���滻��һЩ���������Щ��վ�㲻����ռ����İ����Ļ��������������м������⣬�ȷ�˵�����̨��С���⣺��֪�������̨�Ŀ�ݼ��𣿣�

## glxgears

glxgears��һ���������Linux�Ƿ����˳������2D��3D�Ĳ��������������򵯳�һ�����ڣ�����������ת���ĳ��֣���Ļ����ʾ��ÿ������ת������դ����������һ����������ܲ��ԡ�

�����ǿ������ŵģ�դ�����ټ���̶��������ڴ��ڵĴ�С����������ʾ�����ã����������������Ҳ��ϵúܺã��ǳ��־��ܵ�Խ�졣�������¼��FPS���֣�ÿ���֡�ٶȣ��Լ���3D����Ч����

��ѯOpenGL�Ƿ�򿪣�

#glxinfo | grep rendering

��ʾ��direct rendering: Yes ������������

#�ļ�ϵͳ����̷����������

##��װUbuntu��α���/home�����е�����

windowsϵͳ��������װʱֻ��ʽ��C�̣��Ӷ������������������ݡ� UbuntuϵͳҲ���ԣ�ֻҪ�ڰ�װϵͳʱ�ֳ�һ��/home����������԰�Ubuntu�ġ�/��������Ϊwindows��C�̣���װUbuntuʱֻ��ʽ����/������������ʽ����/home���������Ϳ��Ա�����/home���е�����

## FAT��NTFS���

FAT����32λ���ļ����������Ч�ع���2GB���ϵ�Ӳ�̣�������֧��2TB�Ĵ��������� 

��NTFS�ļ�ϵͳ�У����ڲ�ͬ���õ�Ӳ����ʵ�ʵ��ļ���С��4GB��64GB������NTFS�ļ�ϵͳ�Ŀ����ϴ�ʹ�õ���С����ӦΪ50MB�� 

NTFS�ļ�ϵͳ��FAT�ļ�ϵͳ��������ص��ǰ�ȫ�ԣ�NTFS�ṩ�˷���������վ����İ�ȫ���ϡ���NTFS�����ϣ�֧��������ʿ��ƺ�ӵ��Ȩ���Թ����ļ������۲���FAT����NTFS�ļ�ϵͳ������ָ��Ȩ�ޣ������ܵ����ط��ʻ�Զ�̷��ʵ�Ӱ�� 

��֪����Щ�ˣ������ļ��������ϲ������Ը�NTFS��ʽҲ���й�ϵ�ģ� 



�Ƚϴ�Ĳ�ͬ���Ǵز�һ��,��Ӱ�쵽Ӳ�̵Ŀռ����Ͳ���ϵͳ��֧�ֵ�Ӳ�̷�����С. 

FAT16�Ĵ�Ϊ16K��32K,��֧�ִ���2GB(win9X��)��4GB(win2K��)��Ӳ�̷���. 

FAT32�Ĵ�Ϊ4KB��16K,��֧�ִ���32GB��Ӳ�̷���. 

NTFS�Ĵ�Ϊ0.5K��4K,����֧�ֵ�2TB(2048GB)�ķ���. 

����,NTFS�ķ��������ƶ���ȫ����Ȩ�޺Ͷ��û�ʹ�ÿռ�����. 



˳���ٽ���һ�´���������,�����Ǽ���Ӳ��ʹ�ÿռ����С��λ.��ԽСӲ���ڴ����ļ�ʱ�˷ѵĿռ��ԽС. 

����ĳ���ļ��Ĵ�С��20K,�������16K,�򴢴�����ļ���Ҫ��2����(32K),����Ĳ���32-20=12K,����ļ�Ҳû�취������(�˷ѵ���).���������4K,�򴢴�����ļ�Ҫ5����(20K),�ոպ�,��û���˷ѵĿռ���~ 

��ʵС�ļ�(������windows���±�д�����ִ�����),Ҳ���м�bytes,һ���Ӿ�Ҫ�˷�һ���صĿռ�,�����������,Ӳ�̵�Ȼ�������˷���~  



NTFS�ļ�ϵͳ 



NTFS�ǡ��¼����ļ�ϵͳ������д,��΢��Ϊwindows NT������һ���ļ�ϵͳ��������ǰFAT�ļ�ϵͳ�Ļ���������һ���ĸĽ�����������ܡ����ǽ����ڱ����ļ���Ŀ¼���ݻ����ϣ�ͬʱ��ʡ�洢��Դ�����ٴ���ռ������һ���Ƚ����ļ�ϵͳ��windows XP���õ�NTFS�ļ�ϵͳ������ʹ�û�����������win 9X���������ݵز����͹���������ͬʱҲ�����ܵ�NTFS��������ϵͳ��ȫ�ԡ� NTFS֧�ֻ���NT����ϵͳ�İ�ȫ�Թ�����Ȼ����û����ѵ���ͣ���Ҫ�������ֹ����ʱ�����Ҫ��������Ŀռ䡣һ��������NT����ϵͳ��ʱ����ý�Ӳ�̿ռ��10-15%�ճ����Ա�֤NT����ϵͳ���������С� 



NTFS�ļ�ϵͳ�����¼����ص㣺 



1.NTFS����֧�ֵķ�����С���Դﵽ2TB��2048GB��,��FAT32֧�ַ����Ĵ�С���Ϊ32GB��  



2.NTFS�����˸�С�Ĵ��飬���Ը���Ч�ʵع�����̿ռ䡣NTFS�ļ�ϵͳ���������Ĵ�С��2GB����ʱ���صĴ�С������Ӧ��FAT32��С���������Ĵ�С��2GB����ʱ���صĴ�С��Ϊ4KB����FAT32�ļ�ϵͳ������£�������С��2GB��8GBʱ�صĴ�СΪ4KB��������С��8GB��16GBʱ�صĴ�СΪ8KB��������С��16GB��32GBʱ�صĴ�СΪ16KB����Ƚ϶��ԣ�NTFS���Ը���Ч�ع�����̿ռ䣬����޶ȵر����˴��̿ռ���˷ѡ�  



3.NTFS�����Զ����޸����̴����������ʾ������Ϣ��windows XP��NTFS������д�ļ�ʱ���ᱣ���ļ���һ�ݿ�����Ȼ�������������д���ļ��Ƿ����ڴ��е�һ�¡�������߲�һ�£�windows�Ͱ���Ӧ��������Ϊ������������ʹ����������ӳ�䣩��Ȼ�����ڴ��б������ļ����������������д�ļ�������ڶ��ļ�ʱ���ִ���NTFS�򷵻�һ����������Ϣ������֪��Ӧ��Ӧ�ó��������Ѿ���ʧ�� 



4.NTFS����లȫ���ܷ����ѡ������ڱ����Ϻ�ͨ��Զ�̵ķ��������ļ���Ŀ¼��NTFS��֧�ּ����ļ�ϵͳ��EFS����������ֹû����Ȩ���û������ļ��� 



5.NTFS�ļ�ϵͳ��������һ���ô���֧���ļ�ѹ�����ܣ��û�����ѡ��ѹ�������ļ��������ļ��С��κλ���windows��Ӧ�ó����NTFS�����ϵ�ѹ���ļ����ж�дʱ����Ҫ����������������н�ѹ���������ļ����ж�ȡʱ,�ļ����Զ����н�ѹ�����ļ��رջ򱣴�ʱ���Զ����ļ�����ѹ����  



6.�����޶������ϵͳ����Ա�������������û��Ĵ��̿ռ䣬�Ϸ��û�ֻ�ܷ��������Լ����ļ���windows 2000�еĴ����޶���ǻ����û��;�ġ� 



FAT32�ļ�ϵͳ  



��FAT32�ļ�ϵͳ֮ǰ��PC��ͨ��ʹ�õ��ļ�ϵͳ��FAT16����MS-DOS��winows95��ϵͳ�ɶ�����FAT16�ļ�ϵͳ����win 9Xϵͳ�£�FAT16���֧�ֵķ�����СΪ2GB����FAT16����´رȽϴ󣬴洢Ч��Խ�ͣ�����˴洢�ռ���˷ѡ�����������£��Ƴ�����ǿ���ļ�ϵͳFAT32��FAT32ʹ����32λ�Ŀռ�����ʾÿ������(Sector)�����ļ������Ρ�����FAT32����ʹ�õĵ������������ɴﵽ2TB(2048GB)�����Ҹ��ִ�С�ķ��������õ��ĴصĴ�С��Ҳ��ǡ����֣����������ŵ㣬�����Ӳ��ʹ���ϸ���Ч�ʡ� 



ͬFAT16��ȣ�FAT32��Ҫ���������ص㣺 



1. FAT32����֧�ֵĴ��̴�С�ﵽ2TB��windows XP�¿���֧�ַ������Ϊ32GB����FAT16���ֻ֧��4GB�ķ����� 



2. ���ڲ��õĴظ�С�����FAT32�ļ�ϵͳ���Ը���Ч�ʵؽ�����Ϣ�ı��棬ͨ������¿������15%��  



������β 



���Ǿ������ļ�ϵͳ���������˵����NTFS�����FAT�ļ�ϵͳ����������NTFS������һ���ɻָ��ģ���ȫ��Ч���ļ�ϵͳ��NTFS�����ʱ�����ǵ���֧�ֶ�����������ŷ�ַ������ƺͻ����ض����ܡ���������ʹ�ÿ����ڶ��ļ���������Ի���Ϣʱ�������½����ļ�ϵͳ����ŷ�ַ�������֧���������κ�һ�����ԣ�������֪��ASCII��ֻ��7λ��֧�ֵ���������Ҳ����Ӣ���󣬻��ص��ض����ܿ���ʹNTFSʶ�𻵴أ���������ʹд������ݲ�д����Щ���У���֤�����ݵİ�ȫ�ԡ� 



�����windows XP��ʹ�ô���32GB�ķ�����Ψһ����ѡ�����NTFS��ʽ���������������ǰ�ȫ�����⣬��ע����win 9X�ļ����ԣ���ôFAT32��ʽ����õ�ѡ�����ע�ؼ����ϵͳ�İ�ȫ�ԵĻ��������û�����NTFS��ʽ�����Ҫʹ�ö������ϵͳ����Ҫ��װwin 9X����������ϵͳ�������û����ɶ�����ϵͳ��һ����������FAT32��ʽ������ķ�������NTFS��ʽ�����ҽ�windowds XP��װ��NTFS��ʽ�����£���������ϵͳ��װ��FAT32��ʽ�¡�   �����ʹ�����������ȴû�гɹ������Գ�����rootȨ��ִ�У���Ϊ����ļ�ϵͳ����̷����������һ���ȷ��գ����Կ�����Ҫ�ϸߵ�ִ��Ȩ�ޡ�

##һЩС����

cfdisk -Ps

cfdisk Ҳ��һ���ķ������ߣ�����Щ���а��У��˹����Ѿ���util-linux�����޳���cfdisk �������������ص㡣�鿴���̷������÷�   cfdisk   -Ps �����豸�� ֻ��һ��Ӳ��Ҳ������ cfdisk -Ps



[root@localhost ~]# cfdisk -Ps

Partition Table for /dev/sda



                First         Last

# Type        Sector      Sector       Offset     Length      Filesystem Type         (ID) Flag

-- -------   ----------- -----------    ------   ----------- --------------------      ������----

1 Primary           0     10233404     63      10233405         Linux (83)             Boot

2 Primary    10233405    14313914      0       4080510       Linux swap / So (82)    None

3 Primary    14313915    24547319      0      10233405         Linux (83)             None

4 Primary    24547320    44082359      0      19535040       Extended (05)           None

5 Logical    24547320     34314839     63       9767520        Linux (83)             None

6 Logical    34314840    44082359     63       9767520         Linux (83)             None

   Logical    44082360    78124094      0      34041735         Free Space            None



[root@localhost ~]# cfdisk -Ps /dev/sda

Partition Table for /dev/sda



               First       Last

# Type       Sector      Sector   Offset    Length   Filesystem Type (ID) Flag

-- ------- ----------- ----------- ------ ----------- -------------------- ----

1 Primary           0    10233404     63    10233405 Linux (83)           Boot

2 Primary    10233405    14313914      0     4080510 Linux swap / So (82) None

3 Primary    14313915    24547319      0    10233405 Linux (83)           None

4 Primary    24547320    44082359      0    19535040 Extended (05)        None

5 Logical    24547320    34314839     63     9767520 Linux (83)           None

6 Logical    34314840    44082359     63     9767520 Linux (83)           None

   Logical    44082360    78124094      0    34041735 Free Space           None

sfdisk -l

[root@localhost ~]# sfdisk -l



Disk /dev/sda: 4863 cylinders, 255 heads, 63 sectors/track

Units = cylinders of 8225280 bytes, blocks of 1024 bytes, counting from 0



   Device Boot Start     End   #cyls    #blocks   Id System

/dev/sda1   *      0+    636     637-   5116671   83 Linux

/dev/sda2        637     890     254    2040255   82 Linux swap / Solaris

/dev/sda3        891    1527     637    5116702+ 83 Linux

/dev/sda4       1528    2743    1216    9767520    5 Extended

/dev/sda5       1528+   2135     608-   4883728+ 83 Linux

/dev/sda6       2136+   2743     608-   4883728+ 83 Linux

Testdisk

�̳̲ο���TestDiskʹ�ý̡̳�

##�޸ķ����ľ��

Fat16/Fat32��ʽ:

#��װ 

$ sudo apt-get install mtools 

#�½������ļ� 

$ cp /etc/mtools.conf ~/.mtoolsrc

#�༭�ո��Ƶġ�~/.mtoolsrc���ļ�,������һ�м������������У� 

drive i: file="/dev/sda2"    //����ġ�/devsda2��Ӧ����ʵ���������Ϊ��Ҫ�ĵ��� 

#����������ʾ��·������i:���̣� 

$ mcd i: 

#�鿴��i:����ǰ�ľ�� 

$ sudo mlabel -s i:

#���ġ�i:����ԭʼ���Ϊ��ϲ�����¾������ 

$ sudo mlabel i: newLabelName

NTFS��ʽ 

#��װ 

$ sudo apt-get install ntfsprogs

ע����װ������ 

#�޸� 

$ sudo ntfslabel /dev/sda1 newLabelName //�����"/dev/sda1"Ӧ����ʵ������޸�



ext2/ext3��ʽ

ʹ���������� 

$ sudo e2label /dev/sda1 newLabelName

#Ȩ���˻���������

##������� Ubuntu �е� root �ʺ�

���������а汾��Linux��ͬ��Ubuntu Linux��һ�����ڲ�ͬ���ص㣬�Ǿ��ǳ���ʹ��ʱ�����޷���Ϊroot����¼ϵͳ��Ϊʲô�����������Ҫ��ϵͳ�İ�װ˵�𡣶�������Linuxϵͳ��˵��һ���ڰ�װ���̾��趨root���룬�����û�����������¼root�ʻ���ʹ��su����ת���������û���ݡ���֮�෴��UbuntuĬ�ϰ�װʱ����û�и�root�û����ÿ��Ҳû������root�ʻ���������Ҫ����Ϊroot�û��������������ô���أ�û��ϵ�����ǿ���ʹ��sudo������Ŀ�ġ�sudo��linux�³��õ�������ͨ�û�ʹ�ó����û�Ȩ�޵Ĺ��ߣ�������Ϊ����Ա�ṩ��һ��ϸ�����ȵķ��ʿ��Ʒ�����ͨ�������Ǽȿ�����Ϊ�����û��ֿ�����Ϊ�������͵��û�������ϵͳ���������ĺô��ǣ�����Ա�ܹ��ڲ������û�root�����ǰ���£���������ĳЩ�ض����͵ĳ����û�Ȩ�ޣ����������ϵͳ����Ա����������ġ�

�����б�Ҫ˵�ȼ�һ��sudo��su���������

su�������ڲ��˳���ǰ�û���������л��û��Ĺ��ߣ�ͨ��su�������û�֮���л����������Ȩ���û�root����ͨ�������û��л�����Ҫ���룬����ͨ�û��л��������κ��û�����Ҫ������֤��

sudo��Unix/Linuxƽ̨�ϵ�һ���ǳ����õĹ��ߣ�������ϵͳ����Ա�������ͨ�û�һЩ����ġ�Ȩ������������ִ��һЩֻ�г����û������������û�������ɵ���������һ�����Ͳ���������root�û��ĵ�½�����͹���ʱ�䣬Ҳ�����ϵͳ��ȫ�ԡ�sudo����ߵ���ּ�ǣ����û��������ٵ�Ȩ�޵�������������ǵĹ��������ǿ��Լ򵥵����ɣ�su����ȶ��ĳ����û����������û�Ȩ�ޣ���sudo�����ʱ�Ե������˵ĳ����û�Ȩ�ޣ�һ��ʱ��֮���ʧЧ��

�ã����潲һ�¾�������÷���������һ��

1.Ϊroot����һ��root���룺$ sudo passwd root

֮�����ʾҪ����root�û������룬��������root����

2.ʹ�ã�$ su,��������ʾ����root���룬�Ϳ������ն����л��ɳ�������Ա�û�����ˣ�

## Linux�û����sudoer

ʹ��sudo�������Է�root�û���¼ʱ��ʱ���rootȨ�ޣ���ִ����Ҫ���������ʹ��sudo���û����Խ���sudoer��

���sudoer�ķ������������Ѿ���װsudo����ִ��

# visudo

��

# sudoedit

��ʾ��

��Щ���а��sudo�ṩ��sudoedit���е����ṩ��visudo�������ϻ�����һ���ġ���Ҳ����ʹ�������༭����vi���б༭/etc/sudoers���������ļ���ֻ���ģ���ǿ�Ʊ��棨��w!����ȥ��ֻ�������ٱ��档����

root ALL=(ALL) ALL

���������

%adm ALL=(ALL) ALL

���sudoʱ�����������룬���԰��Ͼ�ĳɣ�

%adm ALL=(ALL) NOPASSWD: ALL

�����ļ���Ȼ��ִ��

#gpasswd -a �û��� adm

Ȼ������û��Ϳ�����sudo�ˡ� 

## linux��rootȨ�ް�װ���

����Щ��˾�ǲ����������ԱrootȨ�޵ģ����ǿ�����Ա��ʱ��Ҳ��ҪװһЩ�����û��rootȨ���Ƿ���Գɹ���װ����أ�����yes�������԰�װnginxΪ��˵������β�����

û��rootȨ��ʱ����Ҳ��û��Ȩ�޲���һЩϵͳĿ¼������bin��usr�ȡ������ڰ�װʱ��Ҫ���ý���װ�ļ�װ�ڵ�ǰ�û���Ȩ�޲�����Ŀ¼��

��װnginx����Ҫ���ذ�װ�ļ�������İ�װ�������£�

1. �����ļ�֮����Ҫ��ѹ���ļ���

tar-zvxf nginx-1.2.3.tar.gz

2. ������װ�ļ�Ŀ¼�����磺

cd ~

mkdir nginx

3. ת����ѹ��װ�ļ��Ĵ��Ŀ¼��Ȼ������

cd xxx

./configure��prefix=/xxx/yy/nginx

4. ����

make

5. ��װ

make install

��������������ͳɹ���װ�ˡ�

����rootȨ�ް�װ����������./configure ��Ҫָ����װ�ļ���Ŀ¼��



#ж��LNMP

killall nginx *//��ֹnginx����

/etc/init.d/mysql stop *//�ر�mysql

killall mysqld *//��ֹmysql����

/usr/local/php/sbin/php-fpm stop *//�ر�php

killall php-cgi *//��ֹphp-cgi����

rm -rf /usr/local/php *//ɾ��php�ļ�

rm -rf /usr/local/nginx *//ɾ��nginx�ļ�

rm -rf /usr/local/mysql *//ɾ��mysql�ļ�

rm -rf /usr/local/zend *//ɾ��zend�ļ�

rm /etc/my.cnf *//ɾ�������ļ�

rm /etc/init.d/mysql *//ɾ��mysql�ļ�

rm /root/vhost.sh *//ɾ���������������ű�

rm /root/lnmp *//ɾ��lnmp�ļ���

���߰�װ�ļ���ִ��.unistall.sh

# Could not get lock /var/lib/apt/lists/lock - open

Could not get lock /var/lib/apt/lists/lock - open(11:Resource temporarily unavailable)

ubuntukilllist�ն˹���

������������ԭ�������������һ�������������У�������Դ���������á���������Դ������ԭ�򣬿������ϴΰ�װʱû������ɣ������³��ִ�״����

���������������������

sudo rm /var/cache/apt/archives/lock

sudo rm /var/lib/dpkg/lock

֮���ٰ�װ��װ�İ������ɽ��

 

 

������ubuntu��ʱ����Ū����Դ��ʱ��ͻȻ�������´���

[1]+ Stopped                 sudo apt-get update

haiquan@haiquan-desktop:~$ sudo apt-get update

E: Could not get lock /var/lib/apt/lists/lock - open (11: Resource temporarily unavailable)

E: Unable to lock the list directory

��ʼ��Ϊ��Ȩ�޲����������� sudo apt-get update,���ֻ��Ǳ�������û�н������������������һ�£������£�

����Ӧ����֮ǰ�Ǹ����±�ǿ��ȡ�������⣬������Ȼ���ڡ����������鿴һ�£�

ps -e | grep apt

��ʾ������£�

6362 ? 00:00:00 apt

6934 ? 00:00:00 apt-get

7368 ? 00:00:00 synaptic

Ȼ���ִ��

sudo killall apt

sudo killall apt-get

sudo killall synaptic

�ٴ����ն���鿴ps -e | grep apt û���κν����

����ִ��sudo apt-get update

 

ԭ�򣺸�װ�õ�Ubantuϵͳ���ڲ�ȱ�ٺܶ����Դ����ʱ��ϵͳ���Զ��������Դ���½��̡�apt-get������������һֱ��������������ʱ����ռ�����Դ����ʱ��ϵͳ�������³ơ�ϵͳ���������������ļ��ڡ�/var/lib/apt/lists/��Ŀ¼�£����������µ�apt-get��������ʱ���ͻ���Ϊ�ò���ϵͳ������������"E: �޷������ /var/lib/apt/lists/lock - open (11: Resource temporarily unavailable)"������ʾ����ˣ�����ֻҪ��ԭ�ȵ�apt-get����ɱ�������¼����µ�apt-get���̣��Ϳ�����������������������������ˣ�



��ʱ������԰�һ�²����������

1���������������ps -aux  > temp.txt��.�ûس�ȷ������ʱ���С�warning�����֣���������ᡣ

2���������������grep -n apt-get temp.txt������س�ȷ�������������������ҵ� apt-get ���̵�PID��

3���������������sudo kill <PID>����

4����ɡ�



or



�����ʾ����:E: Could not get lock /var/lib/dpkg/lock - open (11 Resource temporarily unavailable) 

����

sudo rm /var/lib/apt/lists/lock

����





# Ubuntu Linux�������Դ���ļ���װ���

�����ڸ����˷ḻ���������Щ���һ��ʹ��ͼ�λ����Զ���ʽ������ӣ�ɾ�����������á����������ɰ�װ�����Ƕ�����Щ�ո��������������Ubuntu��Դ�л�δ��¼���У���ʱ���Ǿ���Ҫ�õ�һ�ָ�ͨ�õİ�װ��ʽ��ͨ���ֹ���ʽ��Դ�ļ�����װ��Щ���������ͽ��������ֹ���װ��ʽ����ϸ���衣����

����һ�� ��װ�������

������ΪҪ����Դ���룬���Ե�һ�����ǰ�װ����͹���֮��ĳ���������Ѿ���װ���ˣ����������˲�����Ubuntuϵͳ�зǳ��򵥣�ֻҪִ��������������ˣ�

����$ sudo apt-get install build-essential

����������ִ�к󣬴�Դ�ļ���װ�������Ĺ��ߣ���gcc��make��g++��������������Ͱ�װ���ˡ�

�����������ز����������Դ����

��������������Դ�ļ�ʱ��һ��ҪŪ�������������Ŀ��ļ����������򣬲������Ƚ�����װ�á���Щ��Ϣ��ͨ�������ڸÿ�Դ��Ŀ����ҳ�ϲ��ҵ���������Щ׼�����������ǾͿ��Խ�������Ĺ����ˡ���Ϊ�������Դ����ͨ����ѹ���ļ���ʽ������������Ҫ�����ѹ��ָ��Ŀ¼������������ʾ��

����OwnLinux@ubuntu:~$ tar xvzf

����program.tar.gz

����OwnLinux@ubuntu:~$ cd

����program/

������Linux�´�Դ�ļ���װ����ʱ����һ��ͨ��ģʽ�������ã�./configure���C�� ���루make�� �C�� ��װ��sudo make install�������ǣ���ǰ����û����Ķ�Դ�ļ��и����İ�װ˵������Ϊ����ÿ�������俪���ߵ�ָʾ�������Ȩ���Եġ����򿪷���ͨ������װ˵���������ΪINSTALL��README������������Щ�ļ��أ���������Ŀ��ҳ��Դ������Ŀ¼�ж����ҵ���

����1.����

��������Ӧ�õĵ�һ������ִ��configure�ű�,�ýű�λ�ڳ���Դ�ļ�����Ŀ¼�£�

����OwnLinux@ubuntu:~/program$ ./configure

�����ýű���ɨ��ϵͳ����ȷ��������������п��ļ�ҵ�Ѵ��ڣ��������ļ�·����������������ù����������������Ŀ��ļ�����ȫ�������ýű��ͻ��˳���������������Ҫ��Щ���ļ���������Щ�汾̫����Ҫ���¡�������������������Ū�����иÿ��ļ�����������ǲ����ģ�ͬʱ��Ҫ�ҵ����иÿ��ļ�����ͷ�ļ��Ŀ��������ڣ������İ�һ����-dev��Ϊ�ļ����Ľ�β����װ��������Ҫ�Ŀ��ļ��������������ýű���ֱ��û�д�����ʾΪֹ����˵����Ҫ�Ŀ��ļ��Ѿ�ȫ����װ�׵��˼�������������ϵ��

����2.����

���������ýű��ɹ��˳��󣬽�����Ҫ���ľ��Ǳ�������ˡ��������Ϊ��Դ�ļ�����Ŀ¼������make���

����OwnLinux@ubuntu:~/program$ make

������ʱ�����ῴ��һ�������������Ѹ�ٴ���Ļ�Ϲ�������������Ļ���ϵͳ�᷵�ص���ʾ��״̬��Ȼ���������������г��ִ���Ļ����Ŵ�Ĺ��̿ɾͲ������ò�����ô���ˡ���Ϊ����ͨ��Ҫ�漰��Դ����ĵ��ԣ�����Դ�������﷨���󣬻���������ȵȡ���ô�죿������Ǳ�̸��֣��Ǿ��Լ����԰ɣ����򣬼���������ʼ��б��֧�������������ǲ�����֪��bug������ǾͿ�����������ô����ģ����Ǿ��ύһ��bug����ɣ�Ҳ���þͻ��н���취��

����3.��װ

����������ɹ���������һ�����ǽ����ǰ�װ��ϵͳ�ϡ��󲿷ֳ����makefile�ļ��ж�����һ�����ڰ�װ�ĺ�������Ҫע����ǣ����ʱ�����Ǳ�����Ϊroot�û�����װ������������Ͱ��ļ���װ��/usr������ֻ�г����û�����дȨ�޵�Ŀ¼�С���������Դ�ļ�����Ŀ¼�£�ִ���������

����OwnLinux@ubuntu:~/program$ sudo make install

�������ˣ���������ͻᰲװ�����ļ�������ˡ����⣬��������ʹ�øó���ʱ������ʹ�����������ж�ع��ܣ�һ����򶼻�߱��˹��ܡ��л���Դ�ļ�����Ŀ¼�£�ִ����������ɣ�

����OwnLinux@ubuntu:~/program$ sudo make uninstall

������������£�����������ܵķ�����װ�ĳ��򣬶�λ��/usr/local���档�����ð�װ�ĳ����ļ���UbuntuѲ�ӵ��ļ�ϵͳ���뿪�Ļ�������Ϊ��������������ʾ��

����OwnLinux@ubuntu:~/program$ ./configure �Cprefix=/opt

��������������һ�㶼����Ч�ģ�����Ҳ�����⣬��Щ���������������Щ�����纬���ں�ģ��ĳ��򣬻�������Լ�ȫ���Ž������ļ�ϵͳ��

����������ܵ��ֹ���װ����ķ�����Ȼ�����Ubuntu���������ܵģ����Ǹ���Linuxϵͳ�µĴ�Դ�ļ���װӦ�õķ��������϶���ͬС�졣

#��ѹ�� ѹ������

tar

-c: ����ѹ������

-x����ѹ

-t���鿴����

-r����ѹ���鵵�ļ�ĩβ׷���ļ�

-u������ԭѹ�����е��ļ�



������Ƕ��������ѹ����ѹ��Ҫ�õ�����һ�������Ժͱ���������õ�ֻ��������һ��������Ĳ����Ǹ�����Ҫ��ѹ�����ѹ����ʱ��ѡ�ġ�



-z����gzip���Ե�

-j����bz2���Ե�

-Z����compress���Ե�

-v����ʾ���й���

-O�����ļ��⿪����׼���



����Ĳ���-f�Ǳ����



-f: ʹ�õ������֣��мǣ�������������һ������������ֻ�ܽӵ�������



# tar -cf all.tar *.jpg 

���������ǽ�����.jpg���ļ����һ����Ϊall.tar�İ���-c�Ǳ�ʾ�����µİ���-fָ�������ļ����� 



# tar -rf all.tar *.gif 

���������ǽ�����.gif���ļ����ӵ�all.tar�İ�����ȥ��-r�Ǳ�ʾ�����ļ�����˼�� 



# tar -uf all.tar logo.gif 

���������Ǹ���ԭ��tar��all.tar��logo.gif�ļ���-u�Ǳ�ʾ�����ļ�����˼�� 



# tar -tf all.tar 

�����������г�all.tar���������ļ���-t���г��ļ�����˼ 



# tar -xf all.tar 

���������ǽ��all.tar���������ļ���-x�ǽ⿪����˼ 



ѹ��

tar �Ccvf jpg.tar *.jpg //��Ŀ¼������jpg�ļ������tar.jpg

tar �Cczf jpg.tar.gz *.jpg   //��Ŀ¼������jpg�ļ������jpg.tar�󣬲��ҽ�����gzipѹ��������һ��gzipѹ�����İ�������Ϊjpg.tar.gz

tar �Ccjf jpg.tar.bz2 *.jpg //��Ŀ¼������jpg�ļ������jpg.tar�󣬲��ҽ�����bzip2ѹ��������һ��bzip2ѹ�����İ�������Ϊjpg.tar.bz2

tar �CcZf jpg.tar.Z *.jpg   //��Ŀ¼������jpg�ļ������jpg.tar�󣬲��ҽ�����compressѹ��������һ��umcompressѹ�����İ�������Ϊjpg.tar.Z

rar a jpg.rar *.jpg //rar��ʽ��ѹ������Ҫ������rar for linux

zip jpg.zip *.jpg //zip��ʽ��ѹ������Ҫ������zip for linux



��ѹ

tar �Cxvf file.tar //��ѹ tar��

tar -xzvf file.tar.gz //��ѹtar.gz

tar -xjvf file.tar.bz2   //��ѹ tar.bz2

tar �CxZvf file.tar.Z   //��ѹtar.Z

unrar e file.rar //��ѹrar

unzip file.zip //��ѹzip



�ܽ�

1��*.tar �� tar �Cxvf ��ѹ

2��*.gz �� gzip -d����gunzip ��ѹ

3��*.tar.gz��*.tgz �� tar �Cxzf ��ѹ

4��*.bz2 �� bzip2 -d������bunzip2 ��ѹ

5��*.tar.bz2��tar �Cxjf ��ѹ

6��*.Z �� uncompress ��ѹ

7��*.tar.Z ��tar �CxZf ��ѹ

8��*.rar �� unrar e��ѹ

9��*.zip �� unzip ��ѹ

# Virtual Box���

ע����ǿ�������ش���Documents

ͨ���豸��������������ɷ���

##����USB��ϵͳʧ��

���ubuntu��virtualbox����usb��ϵͳʧ��

http://blog.coltcn.com/2012/03/13/virtualbox-error-failed-to-access-usb-subsystem/

## ubuntu�û�����sudoers�ļ�������

http://blog.csdn.net/killzero/article/details/10298845

##��װCentOS��װ��ǿ����

1.����CentOS����root��ݵ�¼���������滷����

2.ִ���������

#yum upadate

#yum install kernel-devel ��

#yum install gcc

3.����ϵͳ

4.��װ��ǿ����

5.��������

## Cannot register the hard disk�������취

virtualbox�м������е�����Ӳ��ʱ����Cannot register the hard disk����������������ġ�



ERROR: Cannot register the hard disk '/mnt/ee/winxp/xp.vdi' with UUID {395ae4ae-8bf9-42e5-b82a-61af9f95fbf0} because a hard disk '/mnt/ee/winxp/xp.vdi' with UUID {395ae4ae-8bf9-42e5-b82a-61af9f95fbf0} already exists in the media registry ('/home/pzye/.VirtualBox/VirtualBox.xml')

Details: code NS_ERROR_INVALID_ARG (0x80070057), component VirtualBox, interface IVirtualBox, callee nsISupports

Context: "OpenHardDisk(Bstr(szFilenameAbs), AccessMode_ReadWrite, srcDisk.asOutParam())" at line 603 of file VBoxManageDisk.cpp



����������£�

�ر�virtualbox������������������������Ӳ�̣����ܻ������һЩ����Ӳ�̣��뽫��ɾ����Ȼ��Ͳ��������������ˡ�

## VirtualBox�����������������

VirtualBox���ṩ�������������ģʽ�����Ƿֱ��ǣ�

1��NAT    �����ַת��ģʽ(NAT,Network Address Translation)

2��Bridged Adapter    �Ž�ģʽ

3��Internal    �ڲ�����ģʽ

4��Host-only Adapter  ����ģʽ

�������Ƿֱ������������ģʽ���з������ͣ�



��һ�� NATģʽ

���ͣ�

NATģʽ����򵥵�ʵ������������ķ�ʽ�������������⣺Vhost����������������ݶ����������ṩ�ģ�vhost������ʵ�����������У������������е��κλ��������ܲ鿴�ͷ��ʵ�Vhost�Ĵ��ڡ�

�������������ϵ��

ֻ�ܵ�����ʣ����������ͨ��������ʵ������������޷�ͨ��������ʵ��������

����������������������Ĺ�ϵ��

ֻ�ܵ�����ʣ���������Է��ʵ�����������������������������ͨ��������ʵ��������

������������֮��Ĺ�ϵ��

�໥���ܷ��ʣ�������������������ȫ�������໥���޷�ͨ��������ʱ˴ˡ�

IP:10.0.2.15

���أ�10.0.2.2

DNS��10.0.2.3

һ̨������Ķ���������Ա��趨ʹ�� NAT�� ��һ�����������˵�ר���� 10.0.2.0���ڶ����������ӵ�ר������ 10.0.3.0���ȵȡ�Ĭ�ϵõ��Ŀͻ���ip��IP Address����10.0.2.15�����أ�Gateway����10.0.2.2��������������DNS����10.0.2.3�������ֶ��ο���������޸ġ�

NAT������ȱ�㣺

�ʼǱ��Ѳ�����ʱ�� ��������Է�����������������Է��ʻ������������˶˿�ӳ��������˵�������������Է���������ϵķ��������ݿ⣩��

�ʼǱ�û������ʱ�� �����ġ��������ӡ��к��ģ���������Է�������������������Է��ʻ������������˶˿�ӳ����������Է���������ϵķ��������ݿ⣩��



�ڶ��� Bridged Adapterģʽ

���ͣ�

����ģʽ������ϲ�����õ�һ��ģʽ��ͬʱ��ģ���Ҳ���൱�����������������⣬����ͨ������������������һ���ţ�ֱ�����뵽�������ˡ���ˣ���ʹ��������ܱ����䵽һ�������ж�����IP���������繦����ȫ���������е���ʵ����һ����

�������������ϵ��

�����໥���ʣ���Ϊ���������ʵ��������ж���IP�����������������ͬһ������У��˴˿���ͨ������IP�໥���ʡ�

�����������������������ϵ��

�����໥���ʣ�ͬ����Ϊ���������ʵ��������ж���IP�����������������������������ͬһ������У��˴˿���ͨ������IP�໥���ʡ�

��������������ϵ��

�����໥���ʣ�ԭ��ͬ�ϡ�

IP��һ����DHCP����ģ��������ġ��������ӡ���IP ��ͬһ���εġ��������������������ͨ�š�

�ʼǱ��Ѳ�����ʱ��������������DHCP���������������������ͨ��DHCP�ֱ�õ�һ��IP��������IP��ͬһ���Ρ� ���������������pingͨ������������ϻ�������

�ʼǱ�û������ʱ�����������������ͨ�š������ġ��������ӡ��к�棬�Ͳ����ֹ�ָ��IP�������Ҳ����ͨ��DHCP�õ�IP��ַ���ֹ�ָ��IP��Ҳ�޷�������ͨ�ţ���Ϊ������IP��

��ʱ������VirtualBox Host-Only Network ��������ip�ģ�192.168.56.1������������ֹ�ָ����IP 192.168.56.*��Ҳping����������



������ Internalģʽ

���ͣ�

����ģʽ������˼������ڲ�����ģʽ���������������ȫ�Ͽ���ֻʵ��������������֮����ڲ�����ģʽ��

�������������ϵ��

�����໥���ʣ��˴˲�����ͬһ�����磬�޷��໥���ʡ�

�����������������������ϵ��

�����໥���ʣ�����ͬ�ϡ�

��������������ϵ��

�����໥���ʣ�ǰ��������������ʱ����̨���������ͬһ�������ơ���������ͼ�У�����Ϊintnet��

IP: VirtualBox��DHCP��������Ϊ������IP ��һ��õ�����192.168.56.101����Ϊ�Ǵ�101��ֵģ�Ҳ���ֹ�ָ��192.168.56.*��

�ʼǱ��Ѳ�����ʱ�������������������VirtualBox Host-Only Network ����ͨ��

���ַ������������������ӣ��������Ƿ��к���Ӱ�졣



������ Host-only Adapterģʽ

���ͣ�

����ģʽ������һ�ֱȽϸ��ӵ�ģʽ����Ҫ�бȽ���ʵ���������֪ʶ������ת������˵ǰ�漸��ģʽ��ʵ�ֵĹ��ܣ�������ģʽ�£�ͨ������������������ö����Ա�ʵ�֡�

���ǿ������ΪVbox��������ģ���һ��ר�������ʹ�õ�����������������������ӵ��������ϵģ����ǿ���ͨ����������������ʵ�������������ܶ๦�ܣ����磨�������������Žӵȣ���

�������������ϵ

Ĭ�ϲ����໥���ʣ�˫��������ͬһIP�Σ�host-only����Ĭ��IP��Ϊ192.168.56.X ��������Ϊ255.255.255.0�����������������䵽��Ҳ����������Ρ�ͨ���������������Žӵȣ�����ʵ��������������໥���ʡ�

�����������������ϵ

Ĭ�ϲ����໥���ʣ�ԭ��ͬ�ϣ�ͨ�����ã�����ʵ���໥���ʡ�

��������������ϵ

Ĭ�Ͽ����໥���ʣ�����ͬ����һ�����Ρ�

������������� �õ���������VirtualBox Host-Only Network������IP��192.168.56.1  �������������������ӡ����޺�棬��Զͨ��

������������������ǵ������������3��IP�� 192.168.56.101  �������������������ӡ����޺�棬��Զͨ��

��������ʻ��������õ����Լ�������2�� ��ʱ����Ҫ��ͨ�����������ӡ������������������������У�



ͨ�������ϼ�������ģʽ���˽⣬���ǾͿ���������ã�ģ���齨����������Ҫ���κ�һ�����绷���ˡ�

��������ģ�����һ��һ̨���������һ��������������������绷����

�����ҿ�������̨�����vhost1��vhost2����Ȼ���Ӳ��������ͬ������������vhost3��vhost4��

���е�vhost�Ҷ����ó�internat����ģʽ����������Ϊintnal������Ϊ192.168.56.100����˼����ͨ�� 192.168.56.100����������������һ̨vhost1������Ϊ˫������һ��Ϊ����ģʽ��192.168.56.100����һ��Ϊ����ģʽ��192.168.1.101����������������˫������������

�����֮��Ϊ��������������һ̨�����vhost1ͨ�����������������о������е��������ͨ��vhost1��ʵ��������������vhost1�Ϳ��Լ�������������������������ˡ�



NAT ���ö˿�ӳ��

http://huzhangsheng.blog.163.com/blog/static/34787784200802801435931/

���������һ��������ķ��񣨱��� WEB  ���񣩣�ͨ��ʹ�������й��� VboxManage ��������Ҫ֪��������ķ���ʹ���ĸ��˿ڣ�Ȼ�������������ʹ���ĸ��˿ڣ�ͨ������������Ҫʹ�����������ʹ��ͬһ���˿ڣ������������ṩһ��������Ҫʹ��һ���˿ڣ�����ʹ����������û��׼�������ṩ������κζ˿ڡ�һ�����������µ� NAT ���ӣ�������������ӵ�һ�� ssh ����������Ҫ������������

VBoxManage setextradata 'Linux Guest' 'VBoxInternal/Devices/pcnet/0/LUN#0/Config/guestssh/Protocol' TCP

VBoxManage setextradata 'Linux Guest' 'VBoxInternal/Devices/pcnet/0/LUN#0/Config/guestssh/GuestPort' 22

VBoxManage setextradata 'Linux Guest' 'VBoxInternal/Devices/pcnet/0/LUN#0/Config/guestssh/HostPort' 2222

˵����VboxManage ��һ�������г������ѯ��� VirtualBox ��װĿ¼��'Linux Guest' ��������������guestssh ��һ���Զ�������ƣ�������������ã�ͨ����������������������� 22 �˿� ת���������� 2222 �˿ڡ�

�ֱ��磬��������� debian �ϰ�װ�� apache2 ��������ʹ�� 80 �˿ڣ�ӳ�䵽������ 80 �˿ڡ�ʹ����������

'C:\Program Files\innotek VirtualBox\VBoxManage.exe' setextradata 'debian' 'VBoxInternal/Devices/pcnet/0/LUN#0/Config/huzhangsheng/Protocol' TCP

'C:\Program Files\innotek VirtualBox\VBoxManage.exe' setextradata 'debian' 'VBoxInternal/Devices/pcnet/0/LUN#0/Config/huzhangsheng/GuestPort' 80

'C:\Program Files\innotek VirtualBox\VBoxManage.exe' setextradata 'debian' 'VBoxInternal/Devices/pcnet/0/LUN#0/Config/huzhangsheng/HostPort' 80

ע�⣺Ҫʹ������Ч����ص� VirtualBox ��������������Ұ� VirtualBox ��װ�� winxp �ϣ���������а�װ debian 4.02r ����������� debian ������װ�� apache2 php5 mysql-server ������������IE��� http://localhost���ɹ�ת��������� debian �� apache2 web ��������

## virtualbox�����й���CentOSĿ¼

1. ��װvirtualbox��ǿ����

2. ���ù����ļ���

��ɺ���"�豸(Devices)" -> �����ļ���(Shared Folders)�˵������һ�������ļ��У�ѡ��̶�����ʱ��ָ���ļ����Ƿ��ǳ־õġ���������������ȡ����"yongfu"������ʹ��Ӣ�����ƣ���Ҫ�пո�

3. ���ع����ļ���

���������ն������룺

mkdir /mnt/yongfu

mount -t vboxsf yongfu /mnt/yongfu

����"yongfu"��֮ǰ�����Ĺ����ļ��е����֡�������������������Ի����ļ��ˡ�

�粻��ÿ�ζ��ֶ����أ�������/etc/fstab�����һ��

yongfu /mnt/yongfu vboxsf rw,gid=100,uid=1000,auto 0 0

�������ܹ��Զ������ˡ�

4. ж�صĻ�ʹ����������

umount -f /mnt/yongfu

linux����ͶӰ��



# update-Alternativesѧϰ�ʼ�

Linux ��չ�����죬���õ�����Ѿ��ǳ����ˡ�������Ȼ����һЩ����Ĺ��ܴ�������ͬ�����磬ͬ���Ǳ༭�������� nvi��vim��emacs��nano��������˵����Щ��ֻ��һ���֡����������£������Ĺ������Ƶ��������ͬʱ��װ��ϵͳ��ģ����������ǵ�������ִ�С����磬Ҫִ�� vim��ֻҪ���ն������� vim �����س��Ϳ����ˡ���������Щ�����������Ҫ��һ����Թ̶������������Щ�����е�һ�������磬������дһ���ű�����ʱ��ֻҪд�� editor������ϣ��ҪΪ���༭�����ĸ��������ġ�Debian �ṩ��һ�ֻ��������������⣬�� update-Alternatives ��������ʵ�����ֻ��Ƶġ�



1)����Ҫ���ܵĲ����� --display����ʹ���ǿ��Կ���һ����������п�ѡ���ִ�У�

update-Alternatives --display editor

���Կ����ҵĻ����ϵ����п��������� editor ���ӵ����



2)--config�����ѡ��ʹ���ǿ���ѡ������һ�������������Ϊeditor,ִ�У�

update-Alternatives --config editor



���ȣ�update-Alternatives ��һ�����������postinst �� prerm �����İ�װ�ű��Զ����õģ�����һ�� Alternative ��״̬�����֣��Զ����ֶ���ÿ�� Alternative �ĳ�ʼ״̬�����Զ������ϵͳ���ֹ���Ա�ֶ��޸���һ�� Alternative������״̬�ʹ��Զ�������ֶ���������װ�ű��Ͳ���������ˡ������ϣ����һ�� Alternative ����Զ���ֻҪִ�д���:

update-Alternatives --auto editor



general name -- ����ָһϵ�й������Ƶĳ���ġ����á����֣���������·���������� /usr/bin/editor��

link -- ����ָһ�� Alternative �� /etc/Alternative �е����֣����� editor��

Alternative -- ����˼�壬����ָһ����ѡ�ĳ������ڵ�·������������·���������� /usr/bin/vim��



-auto��--display �� --config ���Ķ��� link������Ҫ˵�ĵ��������������ȼ�������Ƚϼ򵥣���Ȼ���ȼ�Խ�ߵĳ���Խ���������һ�����������ʹӵ� Alternative�����뿴���㽫 /usr/bin/editor ���ӵ��� vim�����ǵ���ִ�� man editor ʱ������ȴ�� emacs �� manpage��������θ����أ�������������ʹ� Alternative �ĸ����ˣ����������� Alternative ʱ���ӵ� Alternative Ҳ�ᱻ���¡�



��������ѡ���һ���� --install�����ĸ�ʽ�ǣ�

update-Alternatives --install gen link Alt pri [--slave sgen slink sAlt] ...



gen��link��Alt��pri �ֱ�����������˵���ġ������Ҫ�ӵ� Alternative���������--slave ���ں��档���������һ���Ѿ����ڵ� Alternative ��������µ� Alternatives������������Щ Alternatives ���뵽����Ѿ����ڵ� Alternative ����б��У������µĿ�ѡ������Ϊ�µ�������򣬽��Ὠ��һ���µ��Զ��� Alternative�顣

�غ����Ҽ�����һ������� Alternative���Ҳ���Ҫ��� Alternative �ˡ����������

�£�����ִ����������

update-Alternatives --remove name path

# linuxϵͳ���޷����ʵ���Ӳ��

```
    Error mounting /dev/sda6 at /media/qiaokaiming/20F47472F4744BD2: Command-line 'mount -t "ntfs" -o "uhelper=udisks2,nodev,nosuid,uid=1000,gid=1000,dmask=0077,fmask=0177" "/dev/sda6" "/media/qiaokaiming/20F47472F4744BD2"' exited with non-zero exit status 14: The disk contains an unclean file system (0, 0).
    Metadata kept in windows cache, refused to mount.
    Failed to mount '/dev/sda6': Operation not permitted
    The NTFS partition is in an unsafe state. Please resume and shutdown
    windows fully (no hibernation or fast restarting), or mount the volume
    read-only with the 'ro' mount option.
```

�Ǹ���ʾ���У�Please resume and shutdown windows fully (no hibernation or fast restarting)����win8�ѡ������������ص��ͺ��ˡ�������塷���п������ѡ���Դѡ�ϵͳ���á��رա����ÿ���������

# /etc/profile��/etc/environment(Ubuntu)

�Ƚ�export LANG=zh_CN����/etc/profile ,�˳�ϵͳ���µ�¼����¼��ʾ��ʾӢ�ġ���/etc/profile �е�export LANG=zh_CNɾ������LNAG=zh_CN����/etc/environment���˳�ϵͳ���µ�¼����¼��ʾ��ʾ���ġ�

ԭ����ϵͳ����ִ��/etc/environment����ִ��/etc/profile��/etc/environment����������ϵͳ�Ļ�������/etc/profile�����������û��Ļ�����ǰ�����¼�û��޹أ��������¼�û��йء�ϵͳӦ�ó����ִ�����û������������޹صģ�����ϵͳ��������صģ����Ե����¼ʱ���㿴������ʾ��Ϣ�������ڡ�ʱ����Ϣ����ʾ��ʽ��ϵͳ������LANG����صģ�ȱʡLANG=en_US�����ϵͳ����LANG=zh_CN������ʾ��Ϣ�����ĵģ�������Ӣ�ĵġ���½ϵͳʱshell��ȡ��˳��Ӧ���� ��

/etc/enviroment->/etc/profile-->$HOME/.profile-->$HOME/.env(�������)

���ͬһ���������û�����(/etc/profile)��ϵͳ����(/etc/environment)�в�ͬ��ֵ��Ӧ�������û�����Ϊ׼�ˡ��޸�environment ֮��ִ�� source /etc/environment ����������Ч��

# Configure��������˵��

Linux�����µ������װ��������һ�����׵����飻���ͨ��Դ���������ڰ�װ����Ȼ����͸�Ϊ����һЩ�����ڰ�װ��������Ľ̶̳��ǳ��ձ飻����䲻�����У��Ի���֪ʶ����ʵ���գ���װ��������������ӭ�ж����ˡ�Configure�ű����ù��߾��ǻ���֮һ������autoconf�Ĺ��ߵĻ���Ӧ�á���һЩ������ȣ�Configure�Եû���һЩ����Ȼʹ�ú�ѧϰ�������Եÿ��﷦ζһЩ����ȻҪ��Ϊ���֣��Ի�������Ϥ���ܺ���Ŷ��Ϊ����ת����һƪ����Configureѡ�����õ���ϸ���ܡ�����Ҳο�

'configure'�ű��д�����������ѡ��Բ�ͬ���������˵����Щѡ����ܻ��б仯��������������ѡ���ǲ���ı�ġ�����'--help'ѡ��ִ��'configure'�ű����Կ������õ�����ѡ��������ѡ���Ǻ����õ��ģ����ǵ���Ϊ������������configureһ����ʱ��֪�����ǵĴ����Ǻ����洦�ġ������ÿһ��ѡ����м��ԵĽ��ܣ�

--cache-file=FILE 'configure'�������ϵͳ�ϲ��Դ��ڵ�����(����bug!)��Ϊ�˼��������е����ã����ԵĽ����洢��һ��cache file���configureһ��ÿ�������ﶼ��'configure'�ű��ĸ��ӵ�Դ����ʱ��һ���ܺõ�cache file�Ĵ��ڻ��кܴ������
--help ���������Ϣ����ʹ���о�����û�Ҳż����Ҫʹ��ʹ��'--help'ѡ���Ϊһ�����ӵ���Ŀ��������ӵ�ѡ����磬GCC�����'configure'�ű��Ͱ���������������Ƿ����ɺ���GCC��ʹ��GNU�������ѡ�
--no-create 'configure'�е�һ����Ҫ��������������ļ�����ѡ����ֹ'configure'��������ļ����������Ϊ����һ����ϰ(dry run)�����ܻ���(cache)��Ȼ����д�ˡ�
--quiet

--silent

��'configure'�������Ĳ���ʱ���������Ҫ����Ϣ�������û�������ʲô������������Ϊ'configure'���ܻ�Ƚ�����û����������Ļ��û����ᱻ����һ���ɻ����ڷ���ʲô��ʹ��������ѡ���е��κ�һ����������ӵ�һ�ԡ�(��ע�������仰�Ƚ�����˼��ԭ���������ģ�If there was no such output, the user would be left wondering what is happening. By using this option, you too can be left wondering!)



--version

��ӡ��������'configure'�ű���Autoconf�İ汾�š�



--prefix=PEWFIX

'--prefix'����õ�ѡ���������'Makefile'��鿴���ѡ��ݵĲ�������һ�����ڰ�װʱ���Գ��׵����°������Ľṹ�������֡���һ�����ӣ�����װһ����������˵Emacs������������ʹEmacs Lisp file����װ��"/opt/gnu/share"��

$ ./configure --prefix=/opt/gnu



--exec-prefix=EPREFIX

��'--prefix'ѡ�����ƣ����������������ýṹ�������ļ��İ�װλ�ã�����õ�'emacs'�������ļ���������һ���ʼ������û���������ѡ��Ļ���Ĭ��ʹ�õ�ѡ��ֵ������Ϊ��'--prefix'ѡ��ֵһ����



--bindir=DIR

ָ���������ļ��İ�װλ�ã�����Ķ������ļ�����Ϊ���Ա��û�ֱ��ִ�еĳ���



--sbindir=DIR

ָ�������������ļ��İ�װλ�á�����һЩͨ��ֻ���ɳ����û�ִ�еĳ���



--libexecdir=DIR

ָ����ִ��֧���ļ��İ�װλ�á���������ļ��෴����Щ�ļ�������ֱ�����û�ִ�У����ǿ��Ա������ᵽ�Ķ������ļ���ִ�С�



--datadir=DIR

ָ��ͨ�������ļ��İ�װλ�á�



--sysconfdir=DIR

ָ���ڵ���������ʹ�õ�ֻ�����ݵİ�װλ�á�





--sharedstatedir=DIR



ָ�������ڶ�������Ϲ���Ŀ�д���ݵİ�װλ�á�





--localstatedir=DIR



ָ��ֻ�ܵ���ʹ�õĿ�д���ݵİ�װλ�á�



--libdir=DIR



ָ�����ļ��İ�װλ�á�





--includedir=DIR



ָ��Cͷ�ļ��İ�װλ�á�����������C++��ͷ�ļ�Ҳ����ʹ�ô�ѡ�





--oldincludedir=DIR



ָ��Ϊ��GCC���������װ��Cͷ�ļ��İ�װλ�á�





--infodir=DIR



ָ��Info��ʽ�ĵ��İ�װλ��.Info�Ǳ�GNU������ʹ�õ��ĵ���ʽ��





--mandir=DIR



ָ���ֲ�ҳ�İ�װλ�á�





--srcdir=DIR



���ѡ��԰�װû�����ã��������'configure'Դ���λ�á�һ����˵����ָ����ѡ���Ϊ'configure'�ű�һ���Դ���ļ���ͬһ��Ŀ¼�¡�





--program-prefix=PREFIX



ָ�������ӵ�����װ����������ϵ�ǰ׺�����磬ʹ��'--program-prefix=g'��configureһ����Ϊ'tar'�ĳ��򽫻�ʹ��װ�ĳ�������Ϊ'gtar'�����������İ�װѡ��һ��ʹ��ʱ�����ѡ��ֻ�е�����`Makefile.in'�ļ�ʹ��ʱ�ŻṤ����





--program-suffix=SUFFIX



ָ�������ӵ�����װ����������ϵĺ�׺��





--program-transform-name=PROGRAM



�����PROGRAM��һ��sed�ű�����һ�����򱻰�װʱ���������ֽ�����`sed -e PROGRAM'��������װ�����֡�





--build=BUILD



ָ���������װ��ϵͳƽ̨�����û��ָ����Ĭ��ֵ����'--host'ѡ���ֵ��





--host=HOST



ָ��������е�ϵͳƽ̨�����û��ָ������������`config.guess'����⡣





--target=GARGET



ָ���������(target to)��ϵͳƽ̨������Ҫ�ڳ������Թ�����������ͻ�����������������á����û��ָ����Ĭ�Ͻ�ʹ��'--host'ѡ���ֵ��





--disable-FEATURE



һЩ���������ѡ�����ѡ�����ṩΪ����ѡ��ı���ʱ���ã�����ʹ��Kerberos��֤ϵͳ����һ��ʵ���Եı������������á����Ĭ�����ṩ��Щ���ԣ�����ʹ��'--disable-FEATURE'��������������'FEATURE'�����Ե����֣����磺



$ ./configure --disable-gui





-enable-FEATURE[=ARG]



�෴�ģ�һЩ����������ṩ��һЩĬ�ϱ���ֹ������,����ʹ��'--enable-FEATURE'��������������'FEATURE'�����Ե����֡�һ�����Կ��ܻ����һ����ѡ�Ĳ��������磺



$ ./configure --enable-buffers=128



`--enable-FEATURE=no'�������ᵽ��'--disable-FEATURE'��ͬ��ġ�





--with-PACKAGE[=ARG]



����������������ʹ������������Ϳ�����㴫ͳ������'configure'������һ��Դ����ʱ�������ṩ�����Ѿ���װ�����������Ϣ�����磬������Tcl��Tk��BLT�������߰���Ҫ����BLT��������Ҫ��'configure'�ṩһЩ�������ǰ�Tcl��Tkװ�ĺδ�����Ϣ��



$ ./configure --with-tcl=/usr/local --with-tk=/usr/local



'--with-PACKAGE=no'�����潫�ᵽ��'--without-PACKAGE'��ͬ��ġ�





--without-PACKAGE



��ʱ������ܲ���������������ϵͳ���е���������������磬����ܲ���������±�����ʹ��GNU ld��ͨ��ʹ�����ѡ�����������һ�㣺



$ ./configure --without-gnu-ld





--x-includes=DIR



���ѡ����'--with-PACKAGE'ѡ���һ����������Autoconf�������������ʱ������ʹ��'configure'����ΪImake��һ����ͨ����������������X�������'--x-includes'ѡ���ṩ����'configure'�ű�ָ������X11ͷ�ļ���Ŀ¼�ķ�����





--x-libraries=DIR



���Ƶģ�'--x-libraries'ѡ���ṩ����'configure'�ű�ָ������X11���Ŀ¼�ķ�����





��Դ����������'configure'�ǲ���Ҫ��ͬʱҲ�ǲ��õġ�һ����'configure'���������õ�'Makefile'���Թ���Դ��������һ���������������һ��������Դ������й����������ļ��ĺô��Ǻ����Եģ��������ļ�����Ŀ���ļ��������ҵ�ɢ����Դ��������Ҳʹ����һ����ͬ��ϵͳ���ò�ͬ������ѡ���ͬ����Ŀ���ļ��ǳ����ѡ�����ʹ����������һ��Դ����(source tree)��һ�ù�����(build tree)��һ�ð�װ��(install tree)��������һ���ܽӽ������ӣ���ʹ�����ַ���������GNU malloc����



$ gtar zxf mmalloc-1.0.tar.gz



$ mkdir build && cd build



$ ../mmalloc-1.0/configure



creating cache ./config.cache



checking for gcc... gcc



checking whether the C compiler (gcc ) works... yes



checking whether the C compiler (gcc ) is a cross-compiler... no



checking whether we are using GNU C... yes



checking whether gcc accepts -g... yes



checking for a BSD compatible install... /usr/bin/install -c



checking host system type... i586-pc-linux-gnu



checking build system type... i586-pc-linux-gnu



checking for ar... ar



checking for ranlib... ranlib



checking how to run the C preprocessor... gcc -E



checking for unistd.h... yes



checking for getpagesize... yes



checking for working mmap... yes



checking for limits.h... yes



checking for stddef.h... yes



updating cache ../config.cache



creating ./config.status



������ù������ͱ������ˣ�������Լ��������Ͱ�װ�������Ĭ�ϵ�λ��'/usr/local'��



$ make all && make install

# fedora�����yum������õ������

yum history [undo|redo|info|...]: yum���������ʾ��yum����ʷ��¼�����ҿ��Գ���ָ���ļ�¼(undo)������ָ����¼(redo)�ȵȣ�����Ĺ��ܿ�man yum

yum-plugin-remove-with-leaves��ж�������ʱ����˲�����Ҷ��һ��ж�ص����õ�ʱ����-yѡ����������ȷ�ϣ���Щ�ǳ���������������Ҫ��ϵͳ���ж�ص��������÷���װ��ò���Ժ󿴰���:yum --help�����yum���Ӧ�þ���������������ģ�������ס�����ã�����ܴ�yum history��鵽��¼�Ļ���������yum history undo�������Ƚϰ�ȫ��

yum-plugin-show-leaves�� ִ�а�װ/ж���Ժ���ʾ�˴β�����������Ҷ�ӣ��Զ����У�����Ҫ������

rpmreaper: ����ncurses��ĳ���ͨ�������ı���gui������ʾϵͳ�е�rpm���������ṩ���ֲ���������Ŀ�man��



#�����Ubuntu������һ����վ

��/etc/hosts�ļ��������������

127.0.0.1 domain.com

����domain.comΪ��Ҫ���ε���վ��������˱༭����󣬱�����ļ����˳���

#���ű��е���Ϣ������ļ���

Linux�У��ű����Ի����У�������make xxx������һЩ��ͨlinux�������ls��find�ȣ���ͬ�����֣�����ͬ�ĺ��壺 

0�����׼����

1�����׼���

2����������

��ϵͳĬ�ϵ�stdin�Ǽ��̣�stdout��stderr������Ļ�����Ե���ִ���������make�����������Ϣ�����ǿ�������Ļ�Ͽ����ġ�������Ҫ����Ӧ��Ϣ�����ĳ���ļ��У����ö�Ӧ�����ּ����ض������'>'��ʵ�ֽ���Щ��Ϣ���¶��򵽶�Ӧ���ļ��м��ɡ�������make����Ϊ����˵������ΰѶ�Ӧ����Ϣ���������Ӧ���ļ��У�

1.��Ҫ��make�����ȫ����Ϣ�������ĳ���ļ��У�����İ취���ǣ�
2.
3.make xxx > build_output.txt
4.
5.��ʱĬ�������û�иı�2=stderr�������ʽ��������Ļ�����ԣ�����д�����Ϣ�����ǿ�������Ļ�Ͽ����ġ�
6.
7.2.ֻ��Ҫ��make����еĴ��󣨼����棩��Ϣ������ļ���ing�������ã�
8.
9.make xxx 2> build_output.txt
10.
11.��Ӧ�أ�����1=stdoutû�б䣬������Ļ�����ԣ���Щ����ִ��ʱ�������������Ϣ�����ǻ��������Ļ�ϣ��㻹�ǿ�������Ļ�Ͽ����ġ�
12.
13.3.ֻ��Ҫ��make����е��������Ǵ��󣬷Ǿ��棩����Ϣ������ļ��У������ã�
14.
15.make xxx 1> build_output.txt
16.
17.��Ӧ�أ�����2=stderrû�б䣬������Ļ�����ԣ���Щ����ִ��ʱ������Ĵ�����Ϣ�����ǻ��������Ļ�ϣ��㻹�ǿ�������Ļ�Ͽ����ġ�
18.
19.4.��Ҫ�����������Ϣ�ʹ�����Ϣ������ֱ���ļ��У������ã�
20.
21.make xxx 1> build_output_normal.txt 2>build_output_error.txt
22.
23.������ʹ����1��2��������Ϣ�ʹ�����Ϣ�����������Ӧ�ļ����ˡ�
24.
25.5. ���е���Ϣ�������ͬһ���ļ��У�
26.
27.make xxx > build_output_all.txt 2>&1
28.
29.���е�2>&1��ʾ������Ϣ�����&1�У���&1��ָ����ǰ����Ǹ��ļ���build_output_all.txt ��
30.
31.ע�⣺�������е�1,2�����֣���������Ŵ��ں�'>' ���м䲻���пո�
32.
6.make xxx > build_output_all.txt 2>&1
7.
Ҳ����д�ɣ�

make xxx 2>&1 | tee build_output_all.txt

Ψһ��������ǣ�stdout��stderr�������ļ���ͬʱ�������Կ�����Ļ�����

#��������

## ps �Cfu $USER | grep java

## find . �Cname ��*.log�� | xargs grep ��

��ʾ��ǰ�û��������߳�

## ack

http://beyondgrep.com/

## Glances

top ������ Linux �µ�һ��ʵʱ����������� ͬʱҲ�������� GNU/Linux ���а���Ѱ��ϵͳ���ܷ����ƿ��������������������ȷ�����ĳ���ϵͳ���ӹ��ߡ� ������һ����Ϊ���Ľ��棬���Դ������Ŀ��԰������ǿ����˽�ϵͳ���ܵ�ʵ��ѡ����ǣ���Щʱ����Ҫͨ����Ѱ��һ��ռ��ϵͳ��Դ�Ƚϴ��Ӧ�û���̿��ܻ�Ƚ����ѡ� ��Ϊ top ���������������Ǹ�����Щ��̫�� CPU���ڴ棬����������Դ�ĳ���Ϊ�˴ﵽ���Ŀ�꣬�������ǽ�����һ�ţ�Ƶ�ϵͳ���ӳ��� ���� Glances�� �������Զ������������ϵͳ��Դ�ĳ��򣬲�Ϊ Linux/Unix �������ṩ�����ܶ����Ϣ��

https://github.com/nicolargo/glances/



##��ȡĳ���������·����

��������Linux����ps aux ����������һ������ʱ��

root     19463  0.0  0.0   1508   272 pts/0    S    16:43   0:00 ./server-a

��Ϊϵͳ����Ա���㣬��λ�ó���server-a���ڵ�����·���أ��ڴ˸��ߴ��һ���򵥵Ľ���취��������ps ������п��Կ���19463��server-a��PID�ţ���ô�����������cat /proc/19463/environ ,������£�

PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/gamesGNOME_KEYRING_PID=2269USER=jiangxinLANGUAGE=zh_CN:XDG_SEAT=seat0TEXTDOMAIN=im-configCOMPIZ_CONFIG_PROFILE=ubuntuHOME=/home/jiangxinQT4_IM_MODULE=fcitxDESKTOP_SESSION=ubuntuXDG_SEAT_PATH=/org/freedesktop/DisplayManager/Seat0GTK_MODULES=overlay-scrollbar:unity-gtk-moduleGNOME_KEYRING_CONTROL=/run/user/1000/keyring-wrFl7VQT_QPA_PLATFORMTHEME=appmenu-qt5MANDATORY_PATH=/usr/share/gconf/ubuntu.mandatory.pathIM_CONFIG_PHASE=1SESSIONTYPE=gnome-sessionLOGNAME=jiangxinGTK_IM_MODULE=fcitxDEFAULTS_PATH=/usr/share/gconf/ubuntu.default.pathXDG_SESSION_ID=c3GDM_LANG=zh_CNXDG_SESSION_PATH=/org/freedesktop/DisplayManager/Session0XDG_RUNTIME_DIR=/run/user/1000DISPLAY=:0XDG_CURRENT_DESKTOP=UnityLANG=zh_CN.UTF-8XAUTHORITY=/home/jiangxin/.XauthorityXMODIFIERS=@im=fcitxXDG_GREETER_DATA_DIR=/var/lib/lightdm-data/jiangxinSHELL=/bin/bashGDMSESSION=ubuntuTEXTDOMAINDIR=/usr/share/locale/XDG_VTNR=7QT_IM_MODULE=ximPWD=/home/jiangxinXDG_CONFIG_DIRS=/etc/xdg/xdg-ubuntu:/usr/share/upstart/xdg:/etc/xdgXDG_DATA_DIRS=/usr/share/ubuntu:/usr/share/gnome:/usr/local/share/:/usr/share/CLUTTER_IM_MODULE=ximSELINUX_INIT=YESUBUNTU_MENUPROXY=1DBUS_SESSION_BUS_ADDRESS=unix:abstract=/tmp/dbus-BqwNaGt8wESSH_AUTH_SOCK=/run/user/1000/keyring-wrFl7V/sshSSH_AGENT_PID=2383SSH_AGENT_LAUNCHER=upstartGNOME_DESKTOP_SESSION_ID=this-is-deprecatedJOB=gnome-sessionINSTANCE=UnityUPSTART_EVENTS=started startingUPSTART_JOB=unity-settings-daemonUPSTART_INSTANCE=UPSTART_SESSION=unix:abstract=/com/ubuntu/upstart-session/1000/2299GPG_AGENT_INFO=/run/user/1000/keyring-wrFl7V/gpg:0:1

ע������еģ�PWD=/data1/1230

�ɴ˿����жϳ�����server-a�������·��Ϊ�� /data1/1230/server-a

������֤һ�°ɣ�

bash-3.2# ls -l /data1/1230/server-a

-rwxr-xr-x 1 root root 5842 Feb 25 16:42 /data1/1230/server-a

��Ȼ��ˣ�

##ʱ��У׼:rdate

rdate(receive date)

����˵������ʾ����������������ʱ�䡣

�﷨��rdate [-ps][�������ƻ�IP��ַ...]

����˵����ִ��rdateָ�����������ѯ��ϵͳʱ�䲢��ʾ������

������

  -p ����ʾԶ��������������ʱ�䡣 

  -s ���Ѵ�Զ�������յ������ں�ʱ�䣬�ش浽����������ϵͳʱ�䡣

##��ӡĳһ�ļ����µ������ļ�����������

����ֱ�Ҫ���ǵ����ļ����л�û�����ļ��е��������shellʵ�ִ�ӡĳһ�ļ����µ������ļ�����������ļ����µ��ļ�����Ҫ��ӡ���Ŀ¼�������ļ��������嵥���б�����������

filename1 100��

file/filename2 200��

.......



find -name "*" | xargs wc -l



�� -type f ���������˵���Ŀ¼��wc

find -name "*" -type f | xargs wc -l



��Ҫ�õ�ָ���ĸ�ʽ�������ܵ�awk��

find -name "*" -type f| xargs wc -l | awk '{print $2" "$1"��"}'



find ����ɼ�ָ��Ŀ¼����"/etc/"

find "/etc/" -name "*" -type f| xargs wc -l | awk '{print $2" "$1"��"}'

##�鿴cpu�Ƿ�֧��64λ

�鿴cpuinfo���Ƿ���lm�������lm��ʾ֧��64λ��lm����˼��long mode�������������£�

cat /proc/cpuinfo | grep flags �����������Ƿ��� lm �ַ� �� cat /proc/cpuinfo | grep flags | grep lm | wc -l ���������� 0 ��ʾ֧��64λ

 

�鿴�����м���cpu���Ƿ�֧��64λ

1. �鿴����CPU�ĸ���

#cat /proc/cpuinfo |grep "physical id"|sort |uniq|wc -l

 

2. �鿴�߼�CPU�ĸ���

#cat /proc/cpuinfo |grep "processor"|wc -l

 

3. �鿴CPU�Ǽ���

#cat /proc/cpuinfo |grep "cores"|uniq

 

4. �鿴CPU����Ƶ

#cat /proc/cpuinfo |grep MHz|uniq

 

# uname -a

Linux euis1 2.6.9-55.ELsmp #1 SMP Fri Apr 20 17:03:35 EDT 2007 i686 i686 i386 GNU/Linux

(�鿴��ǰ����ϵͳ�ں���Ϣ)



# cat /etc/issue | grep Linux

Red Hat Enterprise Linux AS release 4 (Nahant Update 5)

(�鿴��ǰ����ϵͳ���а���Ϣ)



# cat /proc/cpuinfo | grep name | cut -f2 -d: | uniq -c

      8  Intel(R) Xeon(R) CPU            E5410   @ 2.33GHz

(������8���߼�CPU, Ҳ֪����CPU�ͺ�)



# cat /proc/cpuinfo | grep physical | uniq -c

      4 physical id      : 0

      4 physical id      : 1

(˵��ʵ����������4�˵�CPU)



# getconf LONG_BIT

32

(˵����ǰCPU������32bitģʽ��, ��������CPU��֧��64bit)



# cat /proc/cpuinfo | grep flags | grep ' lm ' | wc -l

8

(�������0, ˵��֧��64bit����. lmָlong mode, ֧��lm����64bit)

## apt-cache

apt 0.9.7.7ubuntu4������ i386 ���ܣ������� Apr 12 2013 23:49:20

Usage: apt-cache [options] command

       apt-cache [options] showpkg pkg1 [pkg2 ...]

       apt-cache [options] showsrc pkg1 [pkg2 ...]



apt-cache is a low-level tool used to query information

from APT's binary cache files



Commands:

   gencaches - Build both the package and source cache

   showpkg - Show some general information for a single package

   showsrc - Show source records

   stats - Show some basic statistics

   dump - Show the entire file in a terse form

   dumpavail - Print an available file to stdout

   unmet - Show unmet dependencies

   search - Search the package list for a regex pattern	���Ұ������ֹؼ��ֵ������

   show - Show a readable record for the package	��ȡ���������Ϣ����˵������С���汾��

   depends - Show raw dependency information for a package	�˽�ʹ������

   rdepends - Show reverse dependency information for a package	�˽�ĳ�����������

   pkgnames - List the names of all packages in the system

   dotty - Generate package graphs for GraphViz

   xvcg - Generate package graphs for xvcg

   policy - Show policy settings



Options:

  -h   This help text.

  -p=? The package cache.

  -s=? The source cache.

  -q   Disable progress indicator.

  -i   Show only important deps for the unmet command.

  -c=? Read this configuration file

  -o=? Set an arbitrary configuration option, eg -o dir::cache=/tmp

See the apt-cache(8) and apt.conf(5) manual pages for more information.



## apt-file

��һ����������ҹ��ߣ����Բ鵽������������ļ��Ͱ�װ��λ�á�

apt-file [options] action [pattern]

apt-file [options] -f action <file>

apt-file [options] -D action <debfile>



Configuration options:

    --architecture		-a  <arch>       Use specific architecture

    --cache			-c  <dir>        Cache directory

    --cdrom-mount		-d  <cdrom>      Use specific cdrom mountpoint

    --dummy			-y               run in dummy mode (no action)

    --fixed-string		-F               Do not expand pattern

    --from-deb		-D               Use file list of .deb package(s) as

                                        patterns; implies -F

    --from-file			-f               Read patterns from file(s), one per line

                                        (use '-' for stdin)

    --ignore-case		-i               Ignore case distinctions

    --non-interactive	-N               Skip schemes requiring user input

                                        (useful in cron jobs)

    --package-only     -l               Only display packages name

    --regexp          -x               pattern is a regular expression

    --sources-list     	-s  <file>       sources.list location

    --verbose         -v               run in verbose mode

    --help            -h               Show this help.

                     --               End of options (neccessary if pattern

                                        starts with a '-')



Action:

update                              Fetch Contents files from apt-sources.

������������ļ��⣬��һ��ʹ�û�apt-get update��������һ�Ρ�

search|find        <pattern>        Search files in packages

���Ҹ��ļ���������Щ������С�



list|show          <pattern>        List files in packages

��ʾ����������ļ�

    purge                               Remove cache files

## apt-get

apt 0.9.7.7ubuntu4������ i386 ���ܣ������� Apr 12 2013 23:49:24

Usage: apt-get [options] command

       apt-get [options] install|remove pkg1 [pkg2 ...]

       apt-get [options] source pkg1 [pkg2 ...]



apt-get is a simple command line interface for downloading and

installing packages. The most frequently used commands are update

and install.



Commands:

   update - Retrieve new lists of packages	����Դ����ö��ڸ���һ��ʹ���Լ�������������ݺͷ�����(/etc/apt/sources.list�г�)�������Ϣ����һ��,�ڰ�װ���֮ǰ��������һ��������֤�ɹ��ԡ�

   upgrade - Perform an upgrade	�����Ѱ�װ�İ����������-uѡ���г���Ҫ��������������ܻ���ʾ��Щ���������������Ϊ���ܻ��ƻ�������ϵ�����õķ���������apt-get dist-upgrade

�� ����ͨ��cd�������Դ��ַ�����£���������cd����������������apt-cdrom��cd�е������ӵ�/etc/apt/sourcesԴ�У�Ȼ�� ����apt-get dist-upgrade��������������Ϊapt-get����ʹ�����°汾�����cd�еĲ������µİ汾����ôҲ�����õ�cd��

   install - Install new packages (pkg is libc6 not libc6.deb)	

   remove - Remove packages		ɾ����

   autoremove - Remove automatically all unused packages	ɾ���������ð�

   purge - Remove packages and config files	ɾ������������������������ļ���

   source - Download source archives	���ظð���Դ����

   build-dep - Configure build-dependencies for source packages	��װ��صı��뻷��

   dist-upgrade - Distribution upgrade, see apt-get(8)	����ϵͳ��������װ�����ǰ��apt-get -u upgrade�����˵�Ҳ�ᰲװ�ˣ����������Ȼ���ܰ�װ�����磺�����ᵼ����Ҫж��һЩ����ж����Щ���ᵼ���������������ã����ԾͲ������ˡ�

   dselect-upgrade - Follow dselect selections	ʹ�� dselect ����

   clean - Erase downloaded archive files	���������ļ��Ĵ浵

   autoclean - Erase old downloaded archive files	ֻ�����ʱ�İ�

   check - Verify that there are no broken dependencies	����Ƿ����𻵵�����

   changelog - Download and display the changelog for the given package

   download - Download the binary package into the current directory



Options:

  -h  This help text.

  -q  Loggable output - no progress indicator

  -qq No output except for errors

  -d  Download only - do NOT install or unpack archives

  -s  No-act. Perform ordering simulation

  -y  Assume Yes to all queries and do not prompt

  -f  Attempt to correct a system with broken dependencies in place

  -m  Attempt to continue if archives are unlocatable

  -u  Show a list of upgraded packages as well

  -b  Build the source package after fetching it

  -V  Show verbose version numbers

  -c=? Read this configuration file

  -o=? Set an arbitrary configuration option, eg -o dir::cache=/tmp

See the apt-get(8), sources.list(5) and apt.conf(5) manual

pages for more information and options.

                       This APT has win Cow Powers.

## apt-cdrom

apt-cdrom is a tool to add CDROM's to APT's source list. The

CDROM mount point and device information is taken from apt.conf

and /etc/fstab.



Commands:

   add - Add a CDROM

   ident - Report the identity of a CDROM



Options:

  -h   This help text

  -d   CD-ROM mount point

  -r   Rename a recognized CD-ROM

  -m   No mounting

  -f   Fast mode, don't check package files

  -a   Thorough scan mode

  --auto-detect Auto detect drive and mount point

  -c=? Read this configuration file

  -o=? Set an arbitrary configuration option, eg -o dir::cache=/tmp

See fstab(5)



## apititude

aptitude update ���¿��õİ��б�

aptitude upgrade �������õİ�

aptitude dist-upgrade ��ϵͳ�������µķ��а�

aptitude install pkgname ��װ��

aptitude remove pkgname ɾ����

aptitude purge pkgname ɾ�������������ļ�

aptitude search string ������

aptitude show pkgname ��ʾ������ϸ��Ϣ

aptitude clean ɾ�����صİ��ļ�

aptitude autoclean ��ɾ�����ڵİ��ļ�

## dpkg

dpkg -L  �����  �鿴�����װ��λ��



##��.sh�ļ�

sudo sh *.sh

##��������ִ���ļ���

./***(���û�п�ִ��Ȩ�ޣ���Ҫchmod)

## nautilus����

file explore



## �����п��ٴ򿪸������ļ�

xdg-open (opens a file or URL in the user's preferred application)

���ߣ� mplayer xxx.mp3

## ED�༭����ʹ��

ed �༭���� Linux ����ϵͳ����򵥵��ı��༭������������Ϊ��λ���ļ����б༭�ı༭���������� MS-DOS ϵͳ�µ� edit ��������������Ļ���Ϊ��λ���ļ����б༭�ġ���ˣ�������Ѿ�ϰ����ʹ�� edit ���ַ��ı༭������ô�������Ҫһ��ʱ�����ϰ�� ed �ķ�񡣵����Ⲣ����Ҫ����Ϊ ed �ļ���Կ���ʹ��ܿ����ֵġ� 

ed �༭���ĵ��úܼ򵥣���������½�һ���ļ�����ôֻ��Ҫ�������д��������� ed Ȼ���»س������ɣ� 

[titan@localhost titan]$ ed <- 

�������༭һ���Ѿ����ڵ��ļ�����ô��ֻҪ�� ed �ĺ����һ����Ȼ�������ļ������ɣ� 

[titan@localhost titan]$ ed filename <- 

���� ed ����������� ed �༭����������״̬�������ʹһЩ��ѧ����Щ��ϰ�ߣ��������ʱ���������һЩ���ݣ�ϵͳ�᷵��һ�� ?����ʾ��֪����Ҫִ��ʲô���� 

[titan@localhost titan]$ ed <- 

abcde <- 

? 



��ʱ����Ҫ��ȷ�����༭����������ǣ� 

a - ���ļ���ĩβ��������� 

i - ���ļ������һ��֮ǰ���������� 

o - ���ļ���������һ�У�������ԭ�����ڵĻ��߲���ģ��滻�������� 

. - �˳��༭�ļ�ģʽ����������ģʽ��ע�⣺��ʱ��û���˳� ed �༭���� 

w - �����ļ� 

q - �����˳� ed �༭�� 



�����ҽ����ż����������˵��һ�¡� 

[titan@localhost titan]$ ed <- ���� ed ���� 

a <- ���� ed ��Ҫ�༭���ļ� 

My name is Titan. <- �����һ������ 

And I love Perl very much. <- ����ڶ������� 

. <- ���� ed ��������״̬ 

i <- ���� ed ��Ҫ�����һ��֮ǰ�������� 

I am 24. <- ����I am 24.�����롰My name is Titan.���͡�And I love Perl very much.��֮�� 

. <- ���� ed ��������״̬ 

c <- ���� ed ��Ҫ�滻���һ���������� 

I am 24 years old. <- ����I am 24.���滻�ɡ�I am 24 years old.����ע�⣺�����滻�������������ݣ� 

. <- ���� ed ��������״̬ 

w readme.text <- ���ļ�����Ϊ��readme.text�������棨ע�⣺����Ǳ༭�Ѿ����ڵ��ļ���ֻ��Ҫ���� w ���ɣ�

q <- ��ȫ�˳� ed �༭�� 

[titan@localhost titan]$ ���ص� Linux ϵͳ��������״̬ 

�����ļ��������ǣ� 

[titan@localhost titan]$ cat readme.text <- 

My name is Titan. 

I am 24 years old. 

And I love Perl vrey much. 

[titan@localhost titan]$ 



��Ϊʹ�� ed �༭�ļ�ʱʱ�������ļ����ݵģ����������� MS-DOS �µ� edit ��ô�������ڱ༭�ļ���һ��Ҫ��ϸ�������������Ա�֤����ȷ�ԣ����ⷴ�������ڱ༭״̬��������״̬֮�䣬�������˷Ѵ�����ʱ�䡣

##��shell��ʹ��chrome����

��linux��bash shellΪ��˵�� google-chrome��������ʹ�÷���

linux�д�chrome�����������Ϊ:"google-chrome"(��chromium�����������Ϊ:"chromium-browser",chrome������ǻ��ڿ�Դ��chromium�����������)

��basn�����롰google-chrome�� ִ������󼴿ɵ���chrome������Ĵ���,��ַΪ���õ�Ĭ�ϵ���ַ

��ban������"google-chrome --help"����"google-chrome -h"���ɵ�������google-chrome��������һЩ�÷���Ϣ

��bash������"google-chrome  ��ַ"���ɴ�ָ������ַ

��bash������"google-chrome --app="http://www.baidu.com"" �Ϳ�����Ӧ�ó���ķ�ʽ����ַ

���������ʹ�÷�ʽͬ��



##�鿴����

fc-list :lang=zh-cn

## mkisofs�÷����



����˵��������ISO 9660ӳ���ļ���

�﷨��mkisofs [-adDfhJlLNrRTvz][-print-size][-quiet][-A <Ӧ�ó���ID>][-abstract <ժҪ�ļ�>][-b <����ӳ���ļ�>][-biblio <ISBN�ļ�>][-c <�����ļ�����>][-C <������ţ��������>][-copyright <��Ȩ��Ϣ�ļ�>][-hide <Ŀ¼���ļ���>][-hide-joliet <�ļ���Ŀ¼��>][-log-file <��¼�ļ�>][-m <Ŀ¼���ļ���>][-M <����ӳ���ļ�>][-o <ӳ���ļ�>][-p <���ݴ�����>][-P <���̷�����>][-sysid <ϵͳID >][-V <����ID >][-volset <��ἯID>][-volset-size <��������>][-volset-seqno <������>][-x <Ŀ¼>][Ŀ¼���ļ�]

����˵����mkisofs�ɽ�ָ����Ŀ¼���ļ�����ISO 9660��ʽ��ӳ���ļ����Թ���¼���̡�

������

-a��--all   mkisofsͨ�����������ļ���ʹ�ô˲������԰ѱ����ļ��ӵ�ӳ���ļ��С� 

-A<Ӧ�ó���ID>��-appid<Ӧ�ó���ID>   ָ�����̵�Ӧ�ó���ID�� 

-abstract<ժҪ�ļ�>   ָ��ժҪ�ļ����ļ�����

-b<����ӳ���ļ�>��-eltorito-boot<����ӳ���ļ�>   ָ���������ɿ�������ʱ����Ŀ���ӳ���ļ���

-biblio<ISBN�ļ�>   ָ��ISBN�ļ����ļ�����ISBN�ļ�λ�ڹ��̸�Ŀ¼�£���¼���̵�ISBN��

-c<�����ļ�����>   �����ɿ�������ʱ��mkisofs�Ὣ����ӳ���ļ��е�ȫ-eltorito-catalog<�����ļ�����>ȫ����������һ���ļ���

-C<������ţ��������>   ���������ϳ�һ��ӳ���ļ�ʱ������ʹ�ô˲�����

-copyright<��Ȩ��Ϣ�ļ�>   ָ����Ȩ��Ϣ�ļ����ļ�����

-d��-omit-period   ʡ���ļ���ľ�š�

-D��-disable-deep-relocation   ISO 9660���ֻ�ܴ���8���Ŀ¼������8��Ĳ��֣�RRIP���Զ����������ó�ISO 9660���ݵĸ�ʽ��ʹ��-D�����ɹرմ˹��ܡ�

-f��-follow-links   ���Է������ӡ�

-h   ��ʾ������

-hide<Ŀ¼���ļ���>   ʹָ����Ŀ¼���ļ���ISO 9660��Rock RidgeExtensions��ϵͳ�����ء�

-hide-joliet<Ŀ¼���ļ���>   ʹָ����Ŀ¼���ļ���Jolietϵͳ�����ء�

-J��-joliet   ʹ��Joliet��ʽ��Ŀ¼���ļ����ơ�

-l��-full-iso9660-filenames   ʹ��ISO 9660 32�ַ����ȵ��ļ�����

-L��-allow-leading-dots   �����ļ����ĵ�һ���ַ�Ϊ��š�

-log-file<��¼�ļ�>   ��ִ�й��������д�����Ϣ��Ԥ�����ʾ����Ļ�ϡ�

-m<Ŀ¼���ļ���>��-exclude<Ŀ¼���ļ���>   ָ����Ŀ¼���ļ��������᷿��ӳ���ļ��С�

-M<ӳ���ļ�>��-prev-session<ӳ���ļ�>   ��ָ����ӳ���ļ��ϲ���

-N��-omit-version-number   ʡ��ISO 9660�ļ��еİ汾��Ϣ��

-o<ӳ���ļ�>��-output<ӳ���ļ�>   ָ��ӳ���ļ������ơ�

-p<���ݴ�����>��-preparer<���ݴ�����>   ��¼���̵����ݴ����ˡ�

-print-size   ��ʾԤ�����ļ�ϵͳ��С��

-quiet   ִ��ʱ����ʾ�κ���Ϣ��

-r��-rational-rock   ʹ��Rock Ridge Extensions��������ȫ���ļ��Ķ�ȡȨ�ޡ�

-R��-rock   ʹ��Rock Ridge Extensions��

-sysid<ϵͳID>   ָ�����̵�ϵͳID��

-T��-translation-table   �����ļ�����ת���������ڲ�֧��Rock Ridge Extensions��ϵͳ�ϡ�

-v��-verbose   ִ��ʱ��ʾ��ϸ����Ϣ��

-V<����ID>��-volid<����ID>   ָ�����̵ľ�ἯID��

-volset-size<��������>   ָ����Ἧ�������Ĺ���������

-volset-seqno<������>   ָ������Ƭ�ھ�Ἧ�еı�š�

-x<Ŀ¼>   ָ����Ŀ¼���������ӳ���ļ��С�

-z   ����ͨ͸��ѹ���ļ���SUSP��¼���˼�¼Ŀǰֻ��Alpha�����ϵ�Linux��Ч��

## linux��������iso����

���磺��/dev/cdromĿ¼����Ϊ��������Ϊ/root/rh1.iso

����1��dd if=/dev/cdrom of=/root/rh1.iso

����2��#cat /dev/cdrom >;/root/1.iso

����3��mkisofs -r -o myiso.iso /dev/cdrom

����4��cp -r /home/user name.iso

## lspci��ʹ��  

PCI��PCI Express���Ǽ������ʹ�õ�һ�ָ������ߡ�����ϵͳ�е�PCI/PCI-E�豸�����Լ�����ϵͳ�ںˣ�����Ҫ����PCI��PCI-E���ÿռ䡣PCI/PCI-E�豸���������У��벻��PCI/PCI-E���ÿռ䡣ͨ����дPCI/PCI-E���ÿռ䣬���Ը����豸���в������Ż��豸���С����Ľ����û��ռ���Զ�ȡ���޸ġ�ɨ��PCI/PCIE�豸���û����ʹ�á���Linux�ں��У�ΪPCI��PCI-Eֻ������һ������PCI���ں��ṩ������ϵͳ�����ʷ���PCI-E���ÿռ䣬Ҳ������PCI�豸���ÿռ䡣��ȡPCI-E�豸���ÿռ��������lspci����ϸ�������������ʹ��man lspci���鿴����������ֻ���ܳ��ò���������Ĭ���������ǣ���ǰϵͳ������PCI/PCI-E�豸��

���ò�����

-v ��ʾ�豸����ϸ��Ϣ��

-vv ��ʾ�豸����ϸ����Ϣ��

-vvv ��ʾ�豸���пɽ�������Ϣ��

-x ��16������ʾ���ÿռ��ǰ64�ֽڣ�����CardBus�ŵ�ǰ128�ֽڡ�

-xxx ��16������ʾ����PCI���ÿռ䣨256�ֽڣ���

-xxxx ��16������ʾ����PCI-E���ÿռ䣨4096�ֽڣ���

-s [[[[<domain>]:]<bus>]:][<slot>][.[<func>]]��

## mplayerʹ��ascii�ı����ŵ�Ӱ

���ȣ���Ҫȷ��mplayer�Ѿ�װ�ã���ֻ��ִ�������������

sudo apt-get install mplayer

��������Ϊ�˲��ŵ�Ӱ������Ҫִ�����������ǵð�MovieName.avi�ĳ�����������Ӱ�ļ������֣�

mplayer -vo caca MovieName.avi

��caca����������Ų�ɫ�ı��������棬��Ҳ����ʹ�á�-vo aa���������������������Ϳ��԰Ѳ�ɫ���ı���ɺڰ���ɫ��

##��Ϣ����鿴��ȫ

```
    # uname -a               # �鿴�ں�/����ϵͳ/CPU��Ϣ
    # head -n 1 /etc/issue   # �鿴����ϵͳ�汾
    # cat /proc/cpuinfo      # �鿴CPU��Ϣ
    # hostname               # �鿴�������
    # lspci -tv              # �г�����PCI�豸
    # lsusb -tv              # �г�����USB�豸
    # lsmod                  # �г����ص��ں�ģ��
    # env                    # �鿴����������Դ
    # free -m                # �鿴�ڴ�ʹ�����ͽ�����ʹ����
    # df -h                  # �鿴������ʹ�����
    # du -sh <Ŀ¼��>        # �鿴ָ��Ŀ¼�Ĵ�С
    # grep MemTotal /proc/meminfo   # �鿴�ڴ�����
    # grep MemFree /proc/meminfo    # �鿴�����ڴ���
    # uptime                 # �鿴ϵͳ����ʱ�䡢�û���������
    # cat /proc/loadavg      # �鿴ϵͳ���ش��̺ͷ���
    # mount | column -t      # �鿴�ҽӵķ���״̬
    # fdisk -l               # �鿴���з���
    # swapon -s              # �鿴���н�������
    # hdparm -i /dev/hda     # �鿴���̲���(��������IDE�豸)
    # dmesg | grep IDE       # �鿴����ʱIDE�豸���״������
    # ifconfig               # �鿴��������ӿڵ�����
    # iptables -L            # �鿴����ǽ����
    # route -n               # �鿴·�ɱ�
    # netstat -lntp          # �鿴���м����˿�
    # netstat -antp          # �鿴�����Ѿ�����������
    # netstat -s             # �鿴����ͳ����Ϣ����
    # ps -ef                 # �鿴���н���
    # top                    # ʵʱ��ʾ����״̬�û�
    # w                      # �鿴��û�
    # id <�û���>            # �鿴ָ���û���Ϣ
    # last                   # �鿴�û���¼��־
    # cut -d: -f1 /etc/passwd   # �鿴ϵͳ�����û�
    # cut -d: -f1 /etc/group    # �鿴ϵͳ������
    # crontab -l             # �鿴��ǰ�û��ļƻ��������
    # chkconfig --list       # �г�����ϵͳ����
    # chkconfig --list | grep on    # �г�����������ϵͳ�������
    # rpm -qa                # �鿴���а�װ������� 
```

## Linux�²鿴ĳ���˿������е���ʲô����

netstat -anp | grep xxxx   #xxxxΪ�˿ں�

����

lsof -i :xxxx    #xxxxΪ�˿ں�

## Windows/Linux�ı��ļ���ʽת��

DOS/Windows��Linux/Unix���ı��ļ����и�ʽ��ͬ������ DOS/Windows ���ı��ļ���ÿһ��ĩβ��һ�� CR���س����� LF�����У����� UNIX �ı�ֻ��һ��LF�����У���

DOS/Windows�ı��ļ���ʽת����Linux/Unix�ı��ļ���ʽ

sed -e 's/.$//' mydos.txt > myunix.txt

˵�������������ʽ��һ�е���ĩ�ַ�ƥ�䣬�����ַ�ǡ�þ��ǻس��������ÿ��ַ��滻�����Ӷ����������г���ɾ����

��Linux/Unix �ı��ļ���ʽת���� DOS/Windows�ı��ļ���ʽ

sed -e 's/$/\r/' myunix.txt > mydos.txt

˵����'$' ������ʽ�����е�ĩβƥ�䣬�� '\r' ���� sed ����֮ǰ����һ���س����ڻ���֮ǰ����س���ÿһ�о��� CR/LF ������

���⻹�и�������ʹ������ ��

unix2dos filename

dos2unix filename

## Linux��rename����

��ͬ��Dos�µ�rename���linux�µ�rename����ܷǳ�ǿ�� rename����ĸ�ʽ��

rename [ -v ] [ -n ] [ -f ] perlexpr [ files ]

��һ�����������滻�����ַ���

�ڶ����������滻�ɵ��ַ���

������������ƥ��Ҫ�滻���ļ�ģʽ

����rename  main1.c main.c main1.c  ��main1.c������Ϊmain.c

rename֧��ͨ���

?    ����������ַ�

*    ���������ַ�

[charset]  �����charset���е����ⵥ���ַ�

 

eg���ļ���������Щ�ļ�foo1, ..., foo9, foo10, ..., foo278�����ʹ��

rename foo foo0 foo?

���foo1��foo9���ļ�������Ϊfoo01��foo09�����������ļ�ֻ����4���ַ��������Ƶ��ļ����ļ����е�foo���滻Ϊfoo0�����ʹ��

rename foo foo0 foo??

foo01��foo99�������ļ�����������Ϊfoo001��foo099��ֻ������5���ַ��������Ƶ��ļ����ļ����е�foo���滻Ϊfoo0�����ʹ��

rename foo foo0 foo*

foo001��foo278�������ļ�����������Ϊfoo0001��foo0278��������foo��ͷ���ļ����������������ʹ��

ename foo0 foo foo0[2]*

��foo0200��foo0278�������ļ�����������Ϊfoo200��foo278���ļ����е�foo0���滻Ϊfoo��

rename֧��������ʽ

��ĸ���滻rename "s/AA/aa/" *             //���ļ����е�AA�滻��aa

�޸��ļ��ĺ�׺rename "s/.html/.php/" *     //��.html ��׺�ĸĳ� .php��׺

��������ļ���׺rename "s/$//.txt/" *             //�����е��ļ�������txt��β

����ɾ���ļ���rename "s//.txt//" *               //��������.txt��β���ļ�����.txtɾ��

##ʹ��script��¼Linux�ն˻Ự

���ϵͳ����Ա��֪������һ�����������������øı�Ȼ��־����Ҫ�ԡ���һЩ��֯���ԣ�����������������¡���Լ�������Ǽ��¡��ļ���־�����㹻������һЩ��֯����Ҫ��¼���иı䡣���ն�������и���ճ�����ܷǳ���ζ������ʹ��һ������script����Ϊ��֪�ĳ��������������⣬���Ǵ����Linux��Ʒutil-linux�������һ���֡�script��¼�Ự��һ�����ݣ�����������ݺ��㿴�������ݡ���������¼��ɫ�����������������ʾ�����������а�����ɫ��script����¼����Ҫʹ��script����ִ���������

$ script

Ĭ������£�����ǰĿ¼��typescript�ļ���д�����ݡ�Ȼ���������һ�����ݶ�����¼���Ǹ��ļ��С�Ҫ����һ���ļ��м�¼��־��ֻ��ʹ�����

script /path/to/file

(����script screen.log)

��ɼ�¼������exit�˳����������ر�script�Ự�������ļ������������ʹ��cat�������κγ����������־�ļ����쳣�˳�Ҳû������,��Ȼ��¼log,ֻ������Ҫ���ϲ�����

script -f ido.log

�����һ���ն���ʹ�ã�

mkfifo ido.log;script -f ido.log 

Ȼ������һ���ն˵�¼,�ҵ����ido.log�ļ�,��tail -f �ͻ�����������������ݡ�

2.ʹ��script��ȱ�����ڣ�����¼����������ַ��������������ļ��н����������ַ���ANSIת�����С��������script��ʹ��һ���ǳ��򵥵�shell�����������⣺

SHELL=/bin/bash PS1=��$ �� script

ʹ��scriptʱ����Ҫʹ�ý���ʽ��������ڵĳ�����vior top�����ǻ��ƻ��Ự�������������⣬��־�ļ����¼��ʹ�õ��κ������г���������һ����������ȡ�Ĳ��衣�������Ҫ�ڽű��б༭һ���ļ��������˳�script�Ự��Ȼ����script �Ca�����ھɻỰ������»Ự�����ļ����б༭�������������Ự��

## tee����

tee--  read from standard input and write to standard output and files

���������Զ�ȡ�ն�����������ն˻����ļ��У���ʱ�����������¼make��������ܲ�����������ն˵Ĵ�������������ļ���ȥ���������Է����¼��Щ�������־��

cmd | tee -a file.txt

> make 2>&1 | tee make.log��Ȼ������Ҳ����ֱ���ض���һ���ļ���> make > make.log

PS: 2>&1��Ϊ�˼�¼������־if you want to filter the control symbols, try to use the "col" command like this:

$ cat screenlog.0 | col -b > screenlog

or

$ cat typescript | col -b > scriptlog

 ִ��script -q tty.log��,�Ϳ�ʼ��¼�ն˵����������Ϣ,������ʱ��Ctrl+D���ɵõ��ն˵������ļ�tty.log

## screen����

Screen��һ�������ڶ������֮���·����һ�������ն˵Ĵ��ڹ�����,����ζ�����ܹ�ʹ��һ����һ���ն˴������ж��ն˵�Ӧ�á�Screen���лỰ�ĸ���û�������һ��screen�Ự�д������screen���ڣ���ÿһ��screen�����о������һ����ʵ�� telnet/SSH���Ӵ���������

��װ��

CentOS/Red Hat��yum install screen

Debian/Ubuntu��apt-get install screen

Դ����밲װ:

[root@host1 src]# wget ftp://ftp.gnu.org/pub/gnu/screen/screen-4.0.3.tar.gz

[root@host1 src]# tar -zxvf screen-4.0.3.tar.gz

[root@host1 src]# cd screen-4.0.3

[root@host1 screen-4.0.2]# ./configure

[root@host1 screen-4.0.2]# make

[root@host1 screen-4.0.2]# make install

[root@host1 screen-4.0.2]# install -m 644 etc/etcscreenrc /etc/screenrc

[root@host1 screen-4.0.2]# cp ./screen /bin

ע���һ�����İ�װ����������ͬ������������ָ��һ��Ҫִ�С� 

screen�������ļ���һ���� /etc/screenrc ���� ~/.screenrc���������ļ�����Ĳ����趨��Ҳ����ͨ���������ݻ�����������ָ̬����

�﷨��

screen [-AmRvx -ls -wipe][-d <��ҵ����>][-h <����>][-r <��ҵ����>][-s ][-S <��ҵ����>]

����˵����

screenΪ�����Ӵ�������򡣴˴���ν���Ӵ�����ָһ��ȫ��Ļ������ģʽ���档ͨ��ֻ����ʹ��telnet������������ʹ����ʽ���ն˻�ʱ�����п����õ�screen����

������

-A �������е��Ӵ�������ΪĿǰ�ն˻��Ĵ�С��

-d <��ҵ����> ����ָ����screen��ҵ���ߡ�

-h <����> ��ָ���Ӵ��Ļ�����������

-m ����ʹĿǰ������ҵ�е�screen��ҵ����ǿ�ƽ����µ�screen��ҵ��

-r <��ҵ����> ���ָ����ߵ�screen��ҵ��

-R ������ͼ�ָ����ߵ���ҵ�����Ҳ������ߵ���ҵ���������µ�screen��ҵ��

-s ��ָ���������Ӵ�ʱ����Ҫִ�е�shell��

-S <��ҵ����> ��ָ��screen��ҵ�����ơ�

-v ����ʾ�汾��Ϣ��

-x ���ָ�֮ǰ���ߵ�screen��ҵ��

-ls��--list ����ʾĿǰ���е�screen��ҵ��

-wipe �����Ŀǰ���е�screen��ҵ����ɾ���Ѿ��޷�ʹ�õ�screen��ҵ��

����screen������

screen -S yourname -> �½�һ����yourname��session

screen -ls -> �г���ǰ���е�session

screen -r yourname -> �ص�yourname���session

screen -d yourname -> Զ��detachĳ��session

screen -d -r yourname -> ������ǰsession���ص�yourname���session

��ÿ��screen session �£���������� Ctrl+a(C-a) ��ʼ���˳�screenʹ�� exit

����Ctrl+a,d(��סCtrl��Ȼ��a���ſ�a����d)

C-a ? -> Help����ʾ��˵��

C-a c -> Create�������µ� window

C-a n -> Next���л����¸� window 

C-a p -> Previous��ǰһ�� window 

C-a 0..9 -> �л����� 0..9 ��window

Ctrl+a [Space] -> ��ҕ��0ѭ��Q��ҕ��9

C-a C-a -> ���������ʹ�õ� window ���л� 

C-a x -> ��ס��ǰ�� window�������û��������

C-a d -> detach����ʱ�뿪��ǰsession����Ŀǰ�� screen session (���ܺ��ж�� windows) ������ִ̨�У�����ص���û�� screen ʱ��״̬����ʱ�� screen session ��    ÿ�� window �����е� process (������ǰ̨/��̨)���ڼ���ִ�У���ʹ logout Ҳ��Ӱ�졣 

C-a z -> �ѵ�ǰsession�ŵ���ִ̨�У��� shell �� fg ����t�ɻ�ȥ��

C-a w -> windows���г��ѿ����� windows ����Щ 

C-a t -> Time����ʾ��ǰʱ�䣬��ϵͳ�� load 

C-a K -> kill window��ǿ�йرյ�ǰ�� window

screen����ͬ����ʾ�����Ļ����һ���Ự�����ڸ����˴�����������Ϊ���ã������öԷ�ͬ��������Ĳ�����˫��ͬʱ��½һ̨��������ʾ������  screen -S example���ۿ������� screen -x example������ͬ����ʾ��ʾ�����������

## tree����

��ʱ������Ҫ����Ŀ¼���ṹ:

��ʱ��Ҫ�õ�TREE����:

����TREE�����һЩ����:

�������÷�:

tree -a ��ʾ����

tree -d ����ʾĿ¼

tree -L n n��������..��ʾҪ��ʾ����...

tree -f ��ʾ����·��..

��Ȼtree֧���ض������ļ�...

tree -L 4 >dirce.doc��������UTF8��ʽ���ĵ�..����Ҳ������windows �²鿴..

ע��:���ɵ�TXT�������ļ���win�����ʱҲΪ����...��ʱ����Ҫѡ���ַ�����ΪUTF-8..��Ȼ..UTF-8����linux�µ�Ĭ���ַ����ſ���......

## Linux�´���Ŀ¼���ļ� 

�����ļ��У�

�﷨��mkdir [-p][--help][--version][-m <Ŀ¼����>][Ŀ¼����]

˵����mkdir�ɽ���Ŀ¼��ͬʱ����Ŀ¼��Ȩ�ޡ�

������

  -m<Ŀ¼����>��--mode<Ŀ¼����>   ����Ŀ¼ʱͬʱ����Ŀ¼��Ȩ�ޡ�

  -p��--parents   ����Ҫ����Ŀ¼���ϲ�Ŀ¼Ŀǰ��δ���������һ�������ϲ�Ŀ¼

����

mkdir aaa

mkdir -p aaa

mkdir -m 777 aaa   (����һ������Ϊaaa�Ŀ�д�ɶ��ļ���)

�����ļ���

vi a.php

echo ��abfdsfdsf�� > b.txt

cat > c.txt

���岽��:

1������cat > filename.txt ��س� 

2��¼���ı����ݣ� 

3������س��� 

4���ڼ����ϰ���Ctrl+D (���߼���Control��D)��

## linux����ͶӰ��

����һ��

һ����˵����Ҫ�ʼǱ���ǰʹ�õķֱ��ʺ�ͶӰ�ǵķֱ�����ͬ��������ͶӰ������ʾ�ʼǱ���X����ô������������������ 

$xrandr

�������ҵĵ����ϣ�������£�

$xrandr

 SZ:    Pixels          Physical       Refresh

*0   1280 x 1024   ( 433mm x 346mm )  *50   54

 1   1024 x 768    ( 346mm x 260mm )   51   60   61

 2    800 x 600    ( 270mm x 203mm )   52   65   66   67   68

 3    640 x 480    ( 216mm x 162mm )   53   73   74   75

 4   1280 x 960    ( 433mm x 325mm )   55

 5   1280 x 800    ( 433mm x 270mm )   56

 6   1280 x 768    ( 433mm x 260mm )   57

 7   1152 x 864    ( 390mm x 292mm )   58

 8   1152 x 768    ( 390mm x 260mm )   59

 9    960 x 600    ( 325mm x 203mm )   62

 10   840 x 525    ( 284mm x 177mm )   63

 11   832 x 624    ( 281mm x 211mm )   64

 12   800 x 512    ( 270mm x 173mm )   69

 13   720 x 450    ( 243mm x 152mm )   70

 14   640 x 512    ( 216mm x 173mm )   71   72

 15   640 x 400    ( 216mm x 135mm )   76

 16   640 x 384    ( 216mm x 130mm )   77

 17   576 x 432    ( 195mm x 146mm )   78

 18   576 x 384    ( 195mm x 130mm )   79

 19   512 x 384    ( 173mm x 130mm )   80   81   82

 20   416 x 312    ( 140mm x 105mm )   83

 21   400 x 300    ( 135mm x 101mm )   84   85   86   87

 22   320 x 240    ( 108mm x  81mm )   88   89   90

Current rotation - normal

Current reflection - none

Rotations possible - normal

Reflections possible - none

 

��0������*�ţ�˵�����ǱʼǱ����Ե�ǰʹ�õķֱ��ʡ����ͶӰ�ǵķֱ�����1024x768����ô����Ҫ�ı�ʼǱ����Եķֱ��ʡ���Ϊ������Ľ���У�1024x768��Ӧ��1����������������������ı�ֱ��ʣ�

$xrandr -s 1

�������л��˷ֱ��ʡ��ȴ�ͶӰ�ǵ������ɡ�

���Ƚ���VGA��ִ������(VGA������ʾ����LVDS����ʼǱ�Һ����):

$ xrandr --output VGA --auto

��ǰ����Ḵ�Ƶ�VGA���棬��ʱִ��xrandr�ῴ������VGA-0

�Ͽ�VGA-0:

$ xrandr --output VGA-0 --auto

���յ�ǰ��������չ����:

$xrandr --output VGA-0 --auto --left-of LVDS

�������޸�xorg.conf�����ò�������ִ��xrandr�ܹ��г���ǰ����ʾ�豸��ÿ���豸֧�ֵ�ģʽ��Screen����������ʾ����VGA������ʾ����LVDS����ʼǱ�Һ������

 

Screen 0: minimum 320 x 200, current 1280 x 768, maximum 1280 x 1280 

VGA connected (normal left inverted right x axis y axis)

   1280x1024      75.0 +   69.8     59.9  

   1024x768       75.1     70.1     60.0  

   800x600        72.2     75.0     60.3  

   640x480        75.0     72.8     65.4     60.0  

   720x400        70.1  

LVDS connected 1024x768+0+0 (normal left inverted right x axis y axis) 246mm x 184mm

   1024x768       50.0*+   60.0     40.0  

   800x600        60.3  

   640x480        60.0     59.9 

 

�޸ģ�

 

gksudo gedit /etc/X11/xorg.conf

 

�޸ĺ����£�

 

Section "Screen"

   Identifier "Default Screen"

   Monitor "Configured Monitor"

   Device "Configured Video Device"

   SubSection "Display" 

      Virtual 2304 1024 #������չ˫��,2304=1280+1024,1024=max(1024,768)

   EndSubSection 

EndSection

 

ע�⣺Ubuntu 8.04�е�xorg.conf�Ѿ��ǳ�����Subsection "Display" ����Ҫ�Լ���ӣ������� EndSubSection

 

 

xrandr �����п��Ժܷ�����л�˫�������÷�ʽ���£������Ŀ����Լ�̽����

 

xrandr --output VGA --same-as LVDS --auto

 

         �������ʾ��(��߷ֱ���)����ʼǱ�Һ����Ļ��ʾͬ�����ݣ���¡��

 

xrandr --output VGA --same-as LVDS --mode 1024x768

 

         �������ʾ��(�ֱ���Ϊ1024x768)����ʼǱ�Һ����Ļ��ʾͬ�����ݣ���¡��

 

xrandr --output VGA --right-of LVDS --auto

 

         �������ʾ��(��߷ֱ���)������Ϊ�Ҳ���չ��Ļ

 

xrandr --output VGA --off

 

          �ر������ʾ��

 

xrandr --output VGA --auto --output LVDS --off

 

        �������ʾ����ͬʱ�رձʼǱ�Һ����Ļ��ֻ�������ʾ��������

 

xrandr --output VGA --off --output LVDS --auto

 

        �ر������ʾ����ͬʱ�򿪱ʼǱ�Һ����Ļ (ֻ�ñʼǱ�Һ����)

 

��������

 

��xorg.conf

 

gksudo gedit /etc/X11/xorg.conf

 

�޸�Section ��Device�����£�

 

Section "Device"

 

Identifier "Configured Video Device"

 

Option "TwinView" "True" #��˫��֧��

 

Option "TwinViewOrientation" "Clone" #����ģʽ��RelativeΪ��չģʽ

 

Option "UseEdidFreqs" "True" #��ˢ��Ƶ������

 

Option "Metamodes" "1024x768_60, 1024x768; 1024x768_60,800x600" #ˢ��Ƶ��ģʽ��ָ���������豸�ķֱ��ʣ�����ǰ�ĵ�һ���Ǳ�����ʾ�豸�����ź�ĵڶ������ⲿ�豸���ֺŷָ�������ģʽ�����������׷�������ࡣ

 

EndSection

 

���档���Ӻ�ͶӰ�ǣ���������Xwindows(Ctrl+Alt+Backspace)��OK�ˡ�

#����linux˽���˿����

����Linux˽���˻���ѧϰƪ(������)�������Ŀ����(�����ʵ������)



�������İ��鼮���ϣ�



�������ڣ�2010��7�µ�3��



�鼮ISBN��978-7-115-22626-6



�����磺�����ʵ������







����P10��0.2.2 �ڴ棬��0-2



��DDR DDRII800 64 400 800 6.4GB/s��



Ӧ��Ϊ����DDR DDRII800 64 200 800 6.4GB/s��







P19��0.4.1 ����������������ͼ0-17�����һ��



���������ͼʾ����......������ѽ����������(Ӣ��)д�����ģ���



Ӧ��Ϊ�����������ͼʾ����......������Ѿ����������(Ӣ��)д�����ģ���







P30��1.1.2 Linux֮ǰUNIX����ʷ�����һ��



�����⣬Minux����ϵͳ�Ŀ����߽���̷������ڡ�



Ӧ��Ϊ�������⣬Minix����ϵͳ�Ŀ����߽���̷������ڡ�







P46��1.4 �ص�ع�



��1984����Andrew Tannenbaum������Minix����ϵͳ����



Ӧ��Ϊ����1984����Andrew Tanenbaum������Minix����ϵͳ����







P46��1.4 �ص�ع�



��ĿǰLinux�ں˵Ŀ�����Ϊ���ְ汾......��һ���ǿ����а汾����2.5.x�桱



Ӧ��Ϊ����ĿǰLinux�ں˵Ŀ�����Ϊ���ְ汾......��һ���ǿ����а汾�������棬��2.5.x�桱







P55��2.2.3 X Window��ѧϰ



��Open Office(http://www.latex-project.org/)��



Ӧ��Ϊ����Open Office(http://www.openoffice.org/)��







P160��6.5 ������ϰ�����������Ŀ¼��Ҫ����ʲô���ݣ�



��/etc/��/etc/initd��/boot��/usr/bin��/bin��/usr/sbin��/sbin��/dev��/var/log����



Ӧ��Ϊ��/etc/��/etc/init.d��/boot��/usr/bin��/bin��/usr/sbin��/sbin��/dev��/var/log��������ȥ��ǰ���С����







P200��8.1.3 Linux��Ext2�ļ�ϵͳ(inode)������



�������ļ�����Ϊ��50 x 10000(bytes)= 488.3KB������ʱ�˷ѵ�����Ϊ�� 4046 x 10000(bytes) = 38.6MB��



Ӧ��Ϊ�������ļ�����Ϊ��50 (bytes)x 10000 = 488.3KB������ʱ�˷ѵ�����Ϊ�� 4046 (bytes) x 10000 = 38.6MB��







P203��8.1.3 Linux��Ext2�ļ�ϵͳ(inode)��block bitmap



��ͬ��......����ʱ��block bitmpap�������Ӧ����block����ı�־��Ҫ�޸ġ�



Ӧ��Ϊ����ͬ��......����ʱ��block bitmap�������Ӧ����block����ı�־��Ҫ�޸ġ�







P243��8.6.2 ���̿ռ���˷����⣬�ڶ�����ɫ��



��118  /etc   <==��λ��KB��



Ӧ��Ϊ��118  /etc   <==��λ��MB��







�������ġ�����������Ќ��R�ą^�K������ʹ�� [ctrl]-v �M���}�u/�N��/�h�����О顱



P291��10.5 �ص�عˣ����������



������ʹ��[ctrl]-v���и���/ճ��/ɾ������Ϊ����







P301��11.2.2 ��������ʾ�����ã�������



����������ʾ����ͬ����ķ���������ehco���ܹ���������



Ӧ��Ϊ������������ʾ����ͬ����ķ���������echo���ܹ���������







P316��11.2.8 �������ݵ�ɾ����������滻����һ����ɫ��



��Ȼ�����һ�µȺţ�-�����÷���



Ӧ��Ϊ����Ȼ�����һ�¼��ţ�-�����÷���







P338��11.6.2 ��������������һ��



����ʹ��wc-c���������



Ӧ��Ϊ������ʹ��wc-m���������







P354��12.2.3 ����������ʽ��ϰ��������



��*(�Ǻ�)�������ظ�ǰһ��0�������ε���˼��Ϊ�����̬��



Ӧ��Ϊ����*(�Ǻ�)�������ظ�ǰһ����Ԫ��0�������ε���˼��Ϊ�����̬��







P356��12.2.4 ����������ʽ�ַ�(characters)����12-2��[n1-n2]



��grep -n '[0-9]' regular_express.txt��



Ӧ��Ϊ��grep -n '[A-Z]' regular_express.txt







P379��13.2.2 script��ִ�з�ʽ����ͼ13-2 sh02.sh�ڸ�����������



��sh sh02.sh�ڴ�ִ�С�



Ӧ��Ϊ����source sh02.sh�ڴ�ִ�С�







P430��14.4.2 sudo��visudo��/etc/sudoers



����Ȥ�ɡ�������������ļ�����/etc/sudoerds��



Ӧ��Ϊ����Ȥ�ɡ�������������ļ�����/etc/sudoers��







P449��14.9 ����ϰ�⣬��������ɫ��



��useradd -G youcan -s -m $username��



Ӧ��Ϊ����useradd -G youcan -s /bin/bash -m $username��







P500��16.3.2 ϵͳ�������ļ���/etc/crontab��Tips



��/etc/init.d/crondrestart��



Ӧ��Ϊ����/etc/init.d/crond restart��







P515��17.2.3 �ѻ��������⣬�ڶ�����ɫ��



��[root@www ~]#exit��Ӧ�ڻ�ɫ����



��������ٴε�¼�Ļ�����ʹ��ps -lȥ�鿴��Ľ��̣���



Ӧ��Ϊ����������ٴε�¼�Ļ�����ʹ��pstreeȥ�鿴��Ľ��̣���







P560��18.2.1 Ĭ��ֵ�����ļ�����18-1��per_source



������ֵ��[һ�����ֻ�NULIMITED]��



Ӧ��Ϊ��������ֵ��[һ�����ֻ�UNLIMITED]��







P572��18.4.3 CentOS 5.x Ĭ�������ķ������˵������18-2��xfs



������㲻����X���ڵĻ�����ô������������������



Ӧ��Ϊ��������㲻����X���ڵĻ�����ô���������Բ���������







P572��18.5 �ص�عˣ�����������



���������ķ�ʽ��Ϊ/etc/init.d/xientd restart����



Ӧ��Ϊ�����������ķ�ʽ��Ϊ/etc/init.d/xinetd restart����







P579��19.2.1 ��־�ļ����ݵ�һ���ʽ��������



��ĳ��demonִ�й������ǲ�˳��ʱ����



Ӧ��Ϊ��������ֵ��ĳ��daemonִ�й������ǲ�˳��ʱ����







P627��20.5 �ص�عˣ�������



��init�������ļ�Ϊ/etc/initab����



Ӧ��Ϊ����init�������ļ�Ϊ/etc/inittab����







P652��21.3.2 ����USB�豸���ڶ���



������USB2.0��Linux�϶���Enahnced Host Controller Interface (EHCI)�������ġ���



Ӧ��Ϊ��������USB2.0��Linux�϶���Enhanced Host Controller Interface (EHCI)�������ġ���







P740��25.1.3 ѡ�񱸷��豸���洢�豸�Ŀ���



��Ӳ�̣�/dev/hd[a-d][1-16] (IDE), /dev/sd[a-p][1-16] (SCSI/SATA)��



Ӧ��Ϊ����Ӳ�̣�/dev/hd[a-d][1-63] (IDE), /dev/sd[a-p][1-16] (SCSI/SATA)��



 



                                                                                     2011��9��16�� 
# ssh���

## Agent admitted failure to sign using the key 
ssh-keygen ������ id_rsa, id_rsa.pub, �Ѿ����ŵ���ȷλ��(.ssh), ��������ʱȴ��������ѶϢ:

Agent admitted failure to sign using the key

�ⷨ

���Լ��Ļ�����, ִ�� ssh-add, ���������ѶϢ.

Identity added: /home/user/.ssh/id_rsa (/home/user/.ssh/id_rsa)

## connect to host localhost port 22: Connection refused

����ԭ��

1.sshd δ��װ

2.sshd δ���� 

3.����ǽ

4����������ssh ����



���������

1.ȷ����װsshd: 

$ sudo apt-get install openssh-server 

2.����sshd: 

$ sudo net start sshd 

3.������ǽ����,�رշ���ǽ�� 

$ sudo ufw disable

���鷽����

�������

$ ssh localhost  

���ɹ������ʾ��װ�ɹ���������ͨ����

�����е�ʱ����Ȼ�ɹ��˵��ǻ��ǻ����Connection refused ���⡣

���� ps -e | grep ssh���鿴�Ƿ���sshd���̣�

 

��ʱ����Ȼ���Կ���sshd ���ǻ��ǲ������ӳɹ�

��ʱ���Ҫ�뵽��������һ�£�sudo service ssh restart

Ȼ�������� 
#�鿴linux���̵�ִ���ļ�·�� 
�����������ǣ�

           1���Գ����û���½

           2������/procĿ¼

           3��ps�鿴���з���./cmd�Ľ��̣��ҳ����Ӧ��PID���̺�

           4����ll��� ll ���̺� 

              ������ʾһ��ʾ����

              [root@Cluster1 proc]# ll 22401 (proc�ļ������ж�ӦPID����ļ���,���뼴��)

       total 0

       -r--r--r--    1 zhouys    zhouys     0 Dec 11 11:10 cmdline

       -r--r--r--    1 zhouys    zhouys     0 Dec 11 11:10 cpu

       lrwxrwxrwx    1 zhouys    zhouys     0 Dec 11 11:10 cwd -> /home/zhouys/sbs/bin

       -r--------    1 zhouys    zhouys     0 Dec 11 11:10 environ

       lrwxrwxrwx    1 zhouys    zhouys     0 Dec 11 11:10 exe -> /home/zhouys/sbs/bin/cbs (deleted)

       dr-x------    2 zhouys    zhouys     0 Dec 11 11:10 fd

       -r--------    1 zhouys    zhouys     0 Dec 11 11:10 maps

       -rw-------    1 zhouys    zhouys     0 Dec 11 11:10 mem

       -r--r--r--    1 zhouys    zhouys     0 Dec 11 11:10 mounts

       lrwxrwxrwx    1 zhouys    zhouys     0 Dec 11 11:10 root -> /

       -r--r--r--    1 zhouys    zhouys     0 Dec 11 11:10 stat

       -r--r--r--    1 zhouys    zhouys     0 Dec 11 11:10 statm

       -r--r--r--    1 zhouys    zhouys     0 Dec 11 11:10 status

              /proc�ļ�ϵͳ�µ� ���̺�Ŀ¼ ������ļ������˽��̵ĵ�ǰ������Ϣ��

              ���п��Կ�����

              cwd�������ӵľ��ǽ���22401������Ŀ¼��

              exe�������Ӿ���ִ�г���ľ���·����

              cmdline���ǳ�������ʱ������������������Ϊ��./cbs

              cpu��¼�˽��̿������������ϵ�cpu����ʾ�����cpu��Ϣ

              environ��¼�˽�������ʱ�Ļ�������

              fdĿ¼���ǽ��̴򿪻�ʹ�õ��ļ��ķ�������

              ...

                  

        ͨ��cwdֱ�ӽ����������Ŀ¼��ͨ���鿴�����Ϣ�Ϳ��Զ�λ��Ŀ¼��Ӧ�Ǹ��˿ںţ��Լ�

    ��λ���Ǹ�Ӧ�ò�ʹ�ô˷������       



3. ps -aux ����



����psҲ�ɴ�ӡ��·��,���������ܵ�,��Щ·��ֻ��ʹ���������ַ���ȡ��.

#һЩ��������

12�����Linux�������ն˹���

http://www.vaikan.com/best-terminal-alternatives-for-linux-systems/

Linux�º��������

http://www.cnblogs.com/joeyupdo/articles/2768113.html

������ʾһЩ���õ���Ȥ��Linux����

http://www.vaikan.com/10-funny-liunx-command/

Linux��10�����õ������в�������

http://www.geekfan.net/8169/

Linux�е�10�����Ӳ�����

http://linux.cn/thread/12205/1/1/

7 �������� Linux ����

http://linux.cn/thread/10246/1/1/

��ǽ����Chrome+������GoAgent+SwitchySharp���/���Firefox+AutoProxy��

http://blog.chinaunix.net/uid-24250828-id-3788304.html

ͨ�������в���һ��IP�ĵ���λ����Ϣ

http://www.geekfan.net/7863/

���ն˹�����tmuxʹ�����

http://blog.csdn.net/stelalala/article/details/9025691

Linuxϵͳ����γ��׵������Ļ��

http://www.vaikan.com/how-to-clear-the-terminal-screen-for-real-in-case-of-linux/

�����Linux�Ͻ�HTMLҳ��ת����pngͼƬ

http://linux.cn/article-2708-1.html

SSHԭ�������ã�һ����Զ�̵�¼

http://www.ruanyifeng.com/blog/2011/12/ssh_remote_login.html

SSHԭ�������ã�������Զ�̲�����˿�ת��

http://www.ruanyifeng.com/blog/2011/12/ssh_port_forwarding.html

LNMP��װ���ٵ����������̳̣�

http://lnmp.org/install.html

ubuntuɾ�����ں˺Ͷ��������� 

http://pppboy.blog.163.com/blog/static/3020379620113173147935/

����Linux�汾�ı���root�����ƽⷽ��

http://os.51cto.com/art/200910/159523.htm

apt-get remove, apt-get autoremove��aptitude remove������

http://blog.csdn.net/jiangxinnju/article/details/38341283

# Linux���ѧϰ֮·

# GTK+���

##��Windows��ʹ��GTK+

����GTK+�Ŀ�ƽ̨����, ���ǿ�����Windows��ʹ��DevCpp������ʹ��GTK+ͼ�ο��GUI����.

  ��������:



1. ����DevCPP, Ҳ��Dev-C++, ��ʹ�õİ汾��4.9.9.2, ����װ



2. ����gtk+ for win32���߰�����, ������溬�б�������GTK+������������ж���, ����Ҫһ��һ�������ذ�װ��. ��ַ : http://ftp.gnome.org/pub/gnome/binaries/win32/gtk+/2.14/gtk+-bundle_2.14.4-20081108_win32.zip, ����ʾ��װ, �ҵİ�װĿ¼Ϊ D:/dev/GTK



3. ��D:/dev/GTK/bin���뻷������PATH



4. ����cmd, ���� " pkg-config --cflags --libs gtk+-2.0 > d:/a.txt", ��˼�ǰѱ���GTK+��������Ҫ�Ĳ������ض���D�̵�a.txt�ı��ļ���



5. ��DevCpp, �½�һ������, ע�⹤������Ϊ Windows Application, C����.

   DevCpp���ܻ��������һ��Դ�ļ�, �����Դ�ļ������������滻Ϊһ���򵥵�GTK+����, ������һ������:

#include <gtk/gtk.h>

int  main( int  argc, char  *argv[])

{

    GtkWidget *window;

    gtk_init(&argc,&argv);

    window=gtk_window_new(GTK_WINDOW_TOPLEVEL);

    gtk_window_set_title(GTK_WINDOW(window),g_locale_to_utf8("����" ,-1,NULL,NULL,NULL));

    g_signal_connect(window,  "destroy", G_CALLBACK(gtk_main_quit), &window);

    gtk_widget_show(window);

    gtk_main();

     return  0;

}

6.��� ���� > �������� > "����"ѡ�, ��"������"��������a.txt��ǰ�벿������,�һ�������������:

 -mms-bitfields -ID:/dev/GTK/include/gtk-2.0 -ID:/dev/GTK/lib/gtk-2.0/include -ID:/dev/GTK/include/atk-1.0 -ID:/dev/GTK/include/cairo -ID:/dev/GTK/include/pango-1.0 -ID:/dev/GTK/include/glib-2.0 -ID:/dev/GTK/lib/glib-2.0/include -ID:/dev/GTK/include/libpng13 

  ��"������"��������a.txt�ĺ�벿������, �һ�������������:

 -LD:/dev/GTK/lib -lgtk-win32-2.0 -lgdk-win32-2.0 -latk-1.0 -lgdk_pixbuf-2.0 -lpangowin32-1.0 -lgdi32 -lpangocairo-1.0 -lpango-1.0 -lcairo -lgobject-2.0 -lgmodule-2.0 -lglib-2.0 -lintl

  ע����Щ���ݻ����GTK+��װĿ¼�Ĳ�ͬ���������, ��˵һ��, �һ�������D:/dev/GTK. ��������"ȷ��".



7. ��������.

�������һ���򵥵Ŀհ״���, ��ϲ��ɹ���. [��]

# GTK�е�delete_event��destroy 
delete_event �¼�һ�����û�����˵�û�ͨ�����ڹ�����������������������Ͻǵ��˳���ť�����粻���κ����⴦�����ڹ��������Զ�����destroy�źţ���������� �����˴���delete_event�¼��Ļص��������Ƿ����destroy�źžͺͺ����ķ���ֵ�йأ������FALSE�Ͳ�������֮��û��Ч����

�� ��destroy�����˿�����delete_event�¼�����֮�⣬������ͨ��gtk_widget_destroy�����������źŷ���������ͬ�����������ָ����Ĭ�Ͻ���ǹر���ָ��Ĵ��ڵ������������̡��������ϣ�������ںͽ���һ��رգ�����ʹ��gtk_main_quit()��

# g_signal_connect �� g_signal_connect_swapped

�� 2.0 �棬�ź�ϵͳ�Ѵ� GTK �Ƶ� GLib������ں��������͵�˵������ǰ׺ "g_" ������ "gtk_"�����ǲ�������� GLib 2.0 �ź�ϵͳ��� GTK 1.2 �ź�ϵͳ��չ��ϸ�ڡ�

��������ϸ���� helloworld ����֮ǰ�����ǻ������źźͻص�������GTK ��һ���¼������Ĺ��߰�����ζ��������� gtk_main() ���ֱ����һ���¼��������Űѿ���Ȩ�����ʵ��ĺ�����

����Ȩ�Ĵ�����ʹ�á��źš��İ취����ɵġ�(ע��������źŲ�����ͬ�� Unix ϵͳ����źţ�����Ҳ����������ʵ�ֵģ���Ȼʹ�õ�������һ���ġ�) ��һ���¼�����ʱ���簴һ�������������Ĺ����ᡰ�������ʵ����źš������ GTK �Ĺ������ơ������й������̳е��źţ��� "destroy"���й���ר�е��źţ��翪�� (toggle) ��ť������ "toggled" �źš�

Ҫʹһ����ťִ��һ�������������������źź��źŴ�����֮������ӡ���������ʹ�ú������������ӣ�

gulong g_signal_connect( gpointer *object,const gchar *name,GCallback func,gpointer func_data );

��һ��������Ҫ�����źŵĹ������ڶ�������������Ҫ���ӵ��źŵ����ƣ��������������źű�����ʱ��Ҫ���õĺ��������ĸ����������봫�ݸ�������������ݡ�

����������ָ���ĺ��������ص�������һ��Ϊ�������ʽ��

void callback_func( GtkWidget *widget,gpointer callback_data );

��һ��������һ��ָ�򷢳��źŵĹ�����ָ�룬�ڶ���������һ��ָ�����ݵ�ָ�룬�������� g_signal_connect() ���������һ�����������������ݡ�

ע������ص�����������ֻ��һ�����ʽ����Щ�����������źŻ��ò�ͬ�ĵ��ò�����

��һ���� helloworld ʾ����ʹ�õĵ��ã��ǣ�

gulong g_signal_connect_swapped( gpointer *object,const gchar *name,GCallback func,gpointer *slot_object );

g_signal_connect_swapped() �� g_signal_connect() ��ͬ��ֻ�ǻص�����ֻ��һ��������һ��ָ�� GTK �����ָ�롣���Ե�ʹ��������������ź�ʱ���ص�����Ӧ������������ʽ

void callback_func( GtkObject *object );



�������ͨ����һ��������Ȼ������һ�㲻�ú��� g_signal_connect_swapped() ���ûص������ǳ���������һ��ֻ����һ�������Ĺ������߶�����Ϊ������ GTK ��������ͬ���ǵ� helloworld ʾ����������



ӵ�����������������ź����ӵ�Ŀ��ֻ��Ϊ������ص������в�ͬ��Ŀ�Ĳ�����GTK ������ຯ��������һ�������Ĺ���ָ����Ϊ����������Զ�����Щ������Ҫ�� g_signal_connect_swapped()��Ȼ�������Լ�����ĺ������������Ҫ���ӵ������ṩ����Ļص�������

# CodeBlocks ʹ�þ���̸  

�����µ�CodeBlocks 10.05Ϊ����

һ���Զ����Զ���ȫ

1�����δ� Project -> Properties -> C/C++ parser options ���� Additional search paths;

2����  Add ѡ��ͷ�ļ���·�����ȷ��;

3����Դ�ļ��������Ӧ��ͷ�ļ��󼴿�ʵ���Զ���ȫ��

�����ڵ�2�����ĳɡ������ռ䡱�а�����Ӧ��ͷ�ļ�Ҳ�С�

apt-get install codeblocks-contrib

# ubuntu �޷�ʹ��gnome��,����δ���

gcc: 
gcc -o gnome1 gnome1.c `pkg-config �Clibs �Ccflags libgnome-2.0 libgnomeui-2.0`

codebocks:

`pkg-config libgnome-2.0 libgnomeui-2.0 --cflags`

`pkg-config  libgnome-2.0 libgnomeui-2.0 --libs`

`pkg-config gtk+-2.0 --cflags --libs`

#�̵߳���

-lpthread

#���ú���

herror(3)

# Linux ��C���������ձ�׼������

������Linux������Ƶ�ʱ����Ҫ��ձ�׼���뻺����������ʹ��������Windows��������еķ�����fflush(stdin)�����fflush()�����������Ǳ�׼C�еĺ�����ֻ�Ǳ�׼C����չ��������Linux��ʹ�ø������У��������������£����������ѽ���ʹ��rewind(stdin)�����������ʵ�ǽ�ָ��ָ�����Ŀ�ʼ�������������ļ������е�һ����������������FILE��������Windows����������ǿ�����ձ�׼���뻺�����ģ�������Linux�в��С�

ע�����������м������������The Standart Library��

ͨ�������׼�������е�ʣ���ַ�������������ձ�׼��������ʹ�õĺ�����getchar()���˺����������Ǵӱ�׼���뻺�����ж���һ���ַ����˷�����Linux�п��С������Ҫ���stdin����ͨ������ѭ��ʵ�֣�

char ch;

while((ch=getchar())!='/n'&&ch!=EOF);

������佫���stdin�е��ַ���֪���������з������Ƕ��껺������

# linux���� conio.h�Ľ���취��ԭ����

conio.h����C��׼���е�ͷ�ļ�����ISO��POSIX��׼�о�û�ж��塣conio��Console Input/Output������̨����������ļ�д�����ж�����ͨ������̨���������������������ĺ�������Ҫ��һЩ�û�ͨ�������̲����Ķ�Ӧ����������getch()�����ȵȡ��󲿷�DOS��Windows��Phar Lap��DOSX��OS/2 ��ƽ̨�ϵ�C�������ṩ���ļ���UNIX ��Linuxƽ̨��C����������ͨ����������ͷ�ļ������Ѿ�������ݰ����ɲο���

http://conio.sourceforge.net/

������ƽʱ��Ҫ������conio.h���ͷ�ļ��е�getch()����������ȡ�����ַ����ǲ���ʾ������without echo)�����Ǻ���conio.h�ĳ�����linux�޷�ֱ�ӱ���ͨ������Ϊlinuxû�����ͷ�ļ����������������ļ��ݰ��⻹������linux����ԭ���ķ����ﵽͬ����Ч�����Ǿ�������linuxϵͳ������stty �Cecho����������ʾ�������ݣ�Դ�������¡�

//in windows

#include<stdio.h>

#include<conio.h>

int main(){

char c;

printf("input a char:");

c=getch();

printf("You have inputed:%c \n",c);

return 0;

}

//in linux

#include<stdio.h>

int main(){

char c;

printf("Input a char:");

system("stty -echo");

c=getchar();

system("stty echo");

printf("You have inputed:%c \n",c);

return 0;

}

#�ı�linux�ն���ɫ

�ı��ն˵���ɫ����ʹ�á�ANSI�ǳ����ַ����С������ɣ���ANSI�ǳ����ַ����С����� Esc[ ��Ϊ������Ŀ�ʼ��־�����У�Esc ��ansi��Ϊ 27-ʮ���ƣ�33-�˽��ƣ�������c�У�����ʹ�� \033 ��ʾ��



echo -e "\033[ǰ��;����;���m ME \033[0m"

 

������echo -e "\033[44;37;5m ME \033[0m COOL"

 

�����������ñ�����Ϊ��ɫ��ǰ����ɫ����˸��꣬����ַ���ME����Ȼ������������Ļ��ȱʡ���ã�����ַ� ��COOL������e�������� echo ��һ����ѡ������ڼ��������ַ��Ľ���������\033�������ǳ����ַ����С���m����ζ����������Ȼ������ǳ����ַ����У����������������Ч���ַ��� ��44;37;5�� �͡�0�����޸ġ�44;37;5���������ɲ�ͬ��ɫ����ϣ���ֵ�ͱ����ǰ��˳��û�й�ϵ������ѡ��ı���������ʾ��



ǰ��      ����       ��ɫ

---------------------------------------

30          40          ��ɫ

31          41          ��ɫ

32          42          ��ɫ

33          43          ��ɫ

34          44          ��ɫ

35          45          �Ϻ�ɫ

36          46          ����ɫ

37          47          ��ɫ





\33[0m �ر��������� 

\33[1m ���ô��� 

\33[2m ����һ�����ȣ�ģ���ɫ��ʾ������ɫ�� 

\33[4m �»��� 

\33[5m ��˸ 

\33[7m ���� 

\33[8m ���� 

\33[30m -- \33[37m ����ǰ��ɫ 

\33[38m��ȱʡ��ǰ����ɫ�������»���

\33[39m��ȱʡ��ǰ����ɫ�Ϲر��»��� 

\33[40m -- \33[47m ���ñ���ɫ 

\33[nA �������n�� 

\33[nB �������n�� 

\33[nC �������n�� 

\33[nD �������n�� 

\33[y;xH���ù��λ�� 

\33[2J ���� 

\33[K ����ӹ�굽��β������ 

\33[s ������λ�� 

\33[u �ָ����λ�� 

\33[?25l ���ع�� 

\33[?25h ��ʾ���

\033[0q         ��	�ر����еļ���ָʾ�� 

\033[1q         ��	���á�����������ָʾ�� (Scroll Lock) 

\033[2q         ��	���á���ֵ������ָʾ�� (Num Lock) 

\033[3q         ��	���á���д������ָʾ�� (Caps Lock) 

\033[15:40H     		�ѹر��ƶ�����15�У�40�� 

\007            ����	��������beep

# linux�������c���Ե���shell����

#include <stdlib.h>

int system(const char *string);

������~/myprogram/Ŀ¼����shell�ű�test.sh������Ϊ

����#!bin/bash

����#test.sh

����echo $HOME

�����ڸ�Ŀ¼���½�һ��c�ļ�systemtest.c������Ϊ��

����#include<stdlib.h>

����

����main()

����{

����system("~/myprogram/test.sh");

����}

����ִ�н�����£�

����xiakeyou@ubuntu:~/myprogram$ gcc systemtest.c -o systemtest

����xiakeyou@ubuntu:~/myprogram$ ./systemtest

����/home/d/e/xiakeyou

����xiakeyou@ubuntu:~/myprogram$

����2��popen(char *command,char *type)

����ִ�й��̣�popen()�����fork()�����ӽ��̣�Ȼ����ӽ����е���/bin/sh -c��ִ�в���command��ָ�����type��ʹ�á�r�������ȡ����w������д�롣���մ�typeֵ��popen()�Ὠ���ܵ������ӽ��̵ı�׼����豸���׼�����豸��Ȼ�󷵻�һ���ļ�ָ�롣�����̱�����ô��ļ�ָ������ȡ�ӽ��̵�����豸����д�뵽�ӽ��̵ı�׼�����豸�С����⣬����ʹ���ļ�ָ��(FILE*)�����ĺ���Ҳ������ʹ�ã�����fclose()���⡣

��������ֵ�����ɹ��򷵻��ļ�ָ�룬���򷵻�NULL������ԭ�����errno�С�

����ע�⣺�ڱ�д��SUID/SGIDȨ�޵ĳ���ʱ�뾡������ʹ��popen()��popen()��̳л���������ͨ�������������ܻ����ϵͳ��ȫ�����⡣

��������C����popentest.c�������£�

����#include<stdio.h>

����main()

����{

����FILE * fp;

����charbuffer[80];

����fp=popen(��~/myprogram/test.sh��,��r��);

����fgets(buffer,sizeof(buffer),fp);

����printf(��%s��,buffer);

����pclose(fp);

����}

����ִ�н�����£�

����xiakeyou@ubuntu:~/myprogram$ vim popentest.c

����xiakeyou@ubuntu:~/myprogram$ gcc popentest.c -o popentest

����xiakeyou@ubuntu:~/myprogram$ ./popentest

����/home/d/e/xiakeyou

����xiakeyou@ubuntu:~/myprogram$

����ֻ��ż���������е����ޣ�û��̫������ֱ����system()���ǽű�����ִ�У�ֻ�Ƿ���ֵȴ��һ����Ϳ�����˶��Ҳû���ҵ�ʲô���ɡ������ֿ���һ���������ƪ���ģ��õ�һЩ����������������ʵ�֣�

�����Ƚ��ű��ķ���ֵ���� echo > XXXXX �����һ�������ļ���

��������Ҫ�������ֵ�ǣ�����ͨ��C���Ե��ļ�����������ֱ�Ӵ��ļ��ж�ȡ

��������һ�룬��Ӧ�þ���������POPEN��ʵ�ַ�����

C�������shell�ű��������ַ��� ��system()��popen()��execϵ�к��� system() �������Լ�ȥ�������̣����Ѿ���װ�ˣ�ֱ�Ӽ����Լ�������exec ��Ҫ���Լ� fork ���̣�Ȼ��exec �Լ�������

popen() Ҳ����ʵ��ִ����������system ����С

1��system(shell�����shell�ű�·��);

system()�����fork()���� �����̣���������������/bin/sh-c string������ ����string�ַ����������������������� ����漴����ԭ���õ����̡��ڵ���system()�ڼ�SIGCHLD �źŻᱻ��ʱ���ã�SIGINT��SIGQUIT �ź���ᱻĮ�� ��

����ֵ�����system()�ڵ���/bin/shʱʧ���򷵻�127������ʧ��ԭ�򷵻�-1��������stringΪ��ָ��(NULL)���򷵻ط���ֵ�� ��� system()���óɹ� �����᷵������ shell�����ķ���ֵ�����Ǵ˷���ֵҲ�п���Ϊsystem()����/bin/shʧ�������ص�127���� ��������ٷ�ʡ errno ��ȷ������ �ɹ� ��

system����������� ��Ч�����õõ��ܹܺ㷺 ������ ��������һ������

������~/test/Ŀ¼����shell�ű�test.sh������Ϊ

#!bin/bash

#test.sh

echo hello

��ͬ��Ŀ¼���½�һ��c�ļ�system_test.c������Ϊ��

#include<stdlib.h>

int main()

{

system("~/test/test.sh");

}

���� Ч�� ���£�

[root@localhost test]$gcc system_test.c -o system_test

[root@localhost test]$./system_test

hello

[root@localhost test]$

2��popen(char *command,char *type)

popen()�����fork()���� �����̣�Ȼ����������е���/bin/sh -c������ ����command��ָ�����type��Ӧ�� ��r�������ȡ����w������д�롣��ѭ��typeֵ��popen()�Ὠ�� �ܵ����������̵ı�׼ ����豸 ���׼ �����豸 ��Ȼ�󷵻�һ���ļ�ָ�롣������̱������ ���ļ�ָ������ȡ�����̵�����豸 ����д�뵽�����̵ı�׼ �����豸 �С����⣬����Ӧ�� �� ��ָ��(FILE*)�����ĺ���Ҳ������Ӧ�� ������fclose()���⡣

����ֵ�����ɹ� �򷵻��ļ�ָ�룬���򷵻�NULL����� ԭ�����errno�С�ע�⣺�ڱ�д��SUID/SGIDȨ�޵ĳ���ʱ�뾡������Ӧ�� popen()��popen()��̳л���������ͨ�������������ܻ����ϵͳ��ȫ�����⡣

����C����popentest.c�������£�

#include<stdio.h>

main

{

FILE * fp;

charbuffer[80];

fp=popen(��~/myprogram/test.sh��,��r��);

fgets(buffer,sizeof(buffer),fp);

printf(��%s��,buffer);

pclose(fp);

}

���� Ч�� ���£�

[root@localhost test]$ vim popentest.c

[root@localhost test]$ gcc popentest.c -o popentest

[root@localhost test]$ ./popentest

# ftok()����(linux)

ϵͳ����IPCͨѶ������Ϣ���С������ڴ�ʱ������ָ��һ��IDֵ��ͨ������£���idֵͨ��ftok�����õ���ftokԭ�����£�

key_t ftok( char * fname, int id )

fname��ʱ��ָ�����ļ���(���ļ������Ǵ��ڶ��ҿ��Է��ʵ�)��һ��ʹ�õ�ǰĿ¼���磺key = ftok(".", 1); �������ǽ�fname��Ϊ��ǰĿ¼��id������ţ���ȻΪint������ֻ��8�����ر�ʹ��(0-255)�����ɹ�ִ�е�ʱ��һ��key_tֵ���ᱻ���أ����� -1 �����ء���һ���UNIXʵ���У��ǽ��ļ��������ڵ��ȡ����ǰ���������ŵõ�key_t�ķ���ֵ����ָ���ļ��������ڵ��Ϊ65538�������16����Ϊ 0x010002������ָ����IDֵΪ38�������16����Ϊ0x26��������key_t����ֵΪ0x26010002����ѯ�ļ������ڵ�ŵķ����ǣ�ls -i���ڳɹ���ȡ��key֮�󣬾Ϳ���ʹ�ø�key��Ϊĳ�ַ����Ľ��̼�ͨ�ŵ�keyֵ������shmget�����ڴ�ķ�ʽ��shmget�ĺ���ԭ��Ϊ��int shmget( key_t, size_t, flag)���ڴ����ɹ��󣬾ͷ��ع����ڴ������������shmget��ʹ�õ���key_t����ͨ��ftok�ķ�ʽ���ɵġ�

shmctl(shmid, IPC_RMID, 0)�������Ǵ�ϵͳ��ɾ���ù���洢�Ρ���Ϊÿ������洢����һ�����Ӽ���(shmid_ds�ṹ�е�shm_nattch)�����Գ���ʹ�øöε����һ��������ֹ��ö��ѽӣ����򲻻�ʵ����ɾ���ô洢��

#�����ڴ����ź���

##�����ڴ�

�����ڴ��������������̹���ͬһ���ڴ����򣬲�ͨ�����ڴ�����ʵ�����ݽ����Ľ��̼�ͨ�š���Ȼ�����ڴ��ǽ��̼�ͨ�ŵ�����ٵĻ��ƣ����ǽ��̼��ͬ�����⿿�������Խ�������Ǿ���Ҫ�ź������ƣ��ź����ܺܺõĽ��������Դ��ͬ�����⡣��Щǣ�浽����ϵͳ���֪ʶ��Ҫ�ú��о�һ��ͬ������������ܼ�����

�����ڴ�Ĺ���ģʽһ���ǣ�

������ȡ��һ�鹲���ڴ�

1����ָ�� KEY

// IPC_PRIVATEָ����Ҫ�����ڴ�; 

//SHM_SIZE ָ���ֽڴ�С; 

//SHM_MODE ָ������Ȩ������ 0600��ʾ���û����Զ�д���ڴ�

int shmget(key_t IPC_PRIVATE,size_t SHM_SIZE,int SHM_MODE);

2��ָ��KEY

//���SHM_KEYָ��Ĺ���洢�Ѿ����ڣ��򷵻ع���洢��ID; 

//���򣬴�������洢��������ID

int  shmget(key_t SHM_KEY,size_t SHM_SIZE,int SHM_MODE);

2.	void *shmat(int shmid, const void *shmaddr, int shmflg);

	��shmid��ָ�����ڴ�͵�ǰ��������(attach)

3.	Ҫ������

4.	int shmdt(const void *shmaddr);

	����ǰ��shmat���ӺõĹ����ڴ����(detach)��ǰ�Ľ���

5.	int shmctl(int shmid ,int cmd, struct shmid_ds *buf)

	��cmd���IPC_RMIDɾ�������ڴ漰�����ݽṹ

����˵����

1.     �ھ���fork()���ӽ��̽��̳������ӵĹ����ڴ��ַ

2.     �ھ���exec()�������ӵĹ����ڴ��ַ���Զ�detach

3.     �ڽ������̺������ӵĹ����ڴ��ַ���Զ�detach

##�ź���

�ź�����Ӧ��ĳһ����Դ��ȡһ���Ǹ�������ֵ

�ź���ֵָ���ǵ�ǰ���õĸ���Դ����������������0����ζ��Ŀǰû�п��õ���Դ

�ڸ��ź����µȴ���Դ�Ľ��̵ȴ�����

���ź������е�����ԭ�Ӳ�����P������V��������򵥵��ź�����ֻ��ȡ0 ��1 ����ֵ��������ά�ź���

��̲��裺

�����ź���������ϵͳ�Ѵ��ڵ��ź���

����semget()��������ͬ����ʹ��ͬһ���ź�����ֵ�����ͬһ���ź���

int semget(key_t key, int nsems, int semflg);

�����ź���

ʹ��semctl()������SETVAL��������ʹ�ö�ά�ź���ʱ��ͨ�����ź�����ʼ��Ϊ1����cmd=SETVAL�����ź�����ֵ�� ����cmd=IPC_STAT���semid_ds�ṹ

 int semctl(int semid, int semnum, int cmd, union semun arg);

�����ź�����PV����

����semop()������ʵ�ֽ���֮���ͬ���ͻ���ĺ��Ĳ���

�������Ҫ�ź��������ϵͳ��ɾ����

ʹ��semclt()������IPC_RMID�������ڳ����в�Ӧ�ó��ֶ��ѱ�ɾ�����ź����Ĳ���

һ�����ӳ���sem_shm_1.c������С�Ķ����򵥵ķ������Ϳͻ��˳������������������з����������������ǿͻ��ˡ������������󴴽��ź����͹����ڴ棬���������ڴ������ID��ʾ���������ź���������ID���ڹ����ڴ��У����÷��������ṩ�Ĺ����ڴ�����ID�������ڴ渽�ӵ���ַ��,��ȡ�ź�����ʵ����������֮���ͬ��,֮�����������̾Ϳ����ù����ڴ���н��̼�ͨ��,�ͻ����������Ϣ���ڷ���������ʾ������

# Linux�¿������߽���

## indent

indent ʵ�ó����� Linux ���������һ�����ʵ�ù���. ������߼򵥵�˵��Ϊ��Ĵ���������۵������ĸ�ʽ. indent Ҳ�кܶ�ѡ����ָ����θ�ʽ�����Դ����.��Щѡ��ĸ�����Ϣ�뿴 indent ��ָ��ҳ .indent �����ı�����ʵ������, ��ֻ�Ǹı��������. ʹ����ø��ɶ�, ����Զ��һ������.

indent��һ�������õ�cԴ������빤�ߡ�һ�������Լ�ϲ���ķ�񣬿��Ը�����Ҫ���趨indent�ķ��

indent -kr -cli4 -nut -bl4 -bli0 <filename> 

## cproto

cproto ���� C Դ�����ļ����Զ�Ϊÿ����������ԭ������. �� cproto ������д����ʱΪ���ʡ�����������庯��ԭ�͵�ʱ��.

## gprof

gprof �ǰ�װ����� Linux ϵͳ�� /usr/bin Ŀ¼�µ�һ������. ��ʹ����������ĳ���Ӷ�֪���������һ��������ִ��ʱ���ʱ��.gprof �������������ÿ�����������õĴ�����ÿ������ִ��ʱ��ռʱ��İٷֱ�. ������������ĳ������ܵĻ���Щ��Ϣ�ǳ�����.Ϊ������ĳ�����ʹ�� gprof, ������ڱ������ʱ���� -pg ѡ��. �⽫ʹ������ÿ��ִ��ʱ����һ���� gmon.out ���ļ�. gprof ������ļ�����������Ϣ.������������ĳ��򲢲����� gmon.out �ļ��������������������������Ϣ:

gprof <program_name>

## hexdump

���ò���

	[-bcCdovx] [-e format_string] [-f format_file] [-n length] [-s skip] file ...

	

��������

	-b	���ֽڰ˽�����ʾ��ʮ��������ʾƫ������ÿ����ʾ16���ַ���ÿ�ַ�����λ��ʾ�����㲹�㣬�м��Կո�ָ�

	-c	���ֽ��ַ���ʾ��ʮ��������ʾƫ������ÿ����ʾ16���ַ���ÿ�ַ���λ��ʾ�����㲹�ո��м��Կո�ָ�

	-C	��׼ʮ������+ascii����ʾ��ʮ��������ʾƫ������ÿ��16���ַ���ÿ�ַ���λ��ʾ�����㲹0����β��ʾ��ǰ16λ���ݵ�ascii��ֵ����|��ס

	-d	˫�ֽ�ʮ������ʾ��ʮ��������ʾƫ������ÿ��8�飨16�ֽڣ�ÿ��5λ�����㲹�㣬�м��Կո�ָ������޷���10������ֵ��ʾ

	-e format_string

		��ָ���ĸ�ʽ��ʾ

	-f format_file

		����format file�еĸ�ʽ�������������formatfile�п��м���#��ʼ���л�

	-n length

		ֻ��ʾlength���ֽڵ�����

	-o	˫�ֽڰ˽�����ʾ��ʮ��������ʾƫ������ÿ��8�����ݣ�ÿ����ռ���ֽڣ�6�У����㲹�㣬�Կո�ָ�

	-s offset

		�����ӿ�ʼ��offset���ֽڣ�Ĭ������ʮ���ƣ���0x��0X��ʼ��16���ƴ�����������0��ʼ���˽��ƴ��������b/k/m��β����ԭ��ֵ����512/1024/1048576

	-v	��ʾ�������ݣ������������һѡ�����ͬ��һ����ȫ��ͬ�����ݣ�hexdump����*������ʾ

	-x	��λʮ��������ʾ.ʮ��������ʾƫ������ÿ��8�����ݣ�ÿ����ռ���ֽڣ�4�У����㲹�㣬�Կո�ָ�

	





-e ָ����ʽ�ַ�������ʽ�ַ���������һ�Ե������У���ʽ�ַ������磺

'a/b "format1" "format2"'





ÿ����ʽ�ַ�������������ɣ�ÿ���ɿո�ָ�����һ������a/b��b��ʾ��ÿb�������ֽ�Ӧ��format1��ʽ��a��ʾ��ÿa�������ֽ�Ӧ��format2��ʽ��һ��a>b����bֻ��Ϊ1��2��4������a����ʡ�ԣ�ʡ����a=1��format1��format2�п���ʹ������printf�ĸ�ʽ�ַ������磺

%02d����λʮ����

%03x����λʮ������

%02o����λ�˽���

%c�������ַ���





����һЩ������÷���

%_ad�������һ������ֽڵ���ţ���ʮ���Ʊ�ʾ

%_ax�������һ������ֽڵ���ţ���ʮ�����Ʊ�ʾ



%_ao�������һ������ֽڵ���ţ��ð˽��Ʊ�ʾ



%_p���Բ����Գ����ַ���ʾ����.����

ͬһ�����Ҫ��ʾ�����ʽ�ַ���������Ը����-eѡ��









��1��

���룺

hexdump -e '16/1 "%02X " "  |  "' -e '16/1 "%_p" "\n"' test  



�����

00 01 02 03 04 05 06 07 08 09 0A 0B 0C 0D 0E 0F  |  ................  

10 11 12 13 14 15 16 17 18 19 1A 1B 1C 1D 1E 1F  |  ................  

20 21 22 23 24 25 26 27 28 29 2A 2B 2C 2D 2E 2F  |   !"#$%&'()*+,-./  



00 01 02 03 04 05 06 07 08 09 0A 0B 0C 0D 0E 0F  |  ................

10 11 12 13 14 15 16 17 18 19 1A 1B 1C 1D 1E 1F  |  ................

20 21 22 23 24 25 26 27 28 29 2A 2B 2C 2D 2E 2F  |   !"#$%&'()*+,-./









��2��

���룺

hexdump -e '1/1 "0x%08_ax "' -e '8/1 "%02X " " *  "' -e '8/1 "%_p" "\n"' test  



�����

0x00000000 00 01 02 03 04 05 06 07 *  ........  

0x00000008 08 09 0A 0B 0C 0D 0E 0F *  ........  

0x00000010 10 11 12 13 14 15 16 17 *  ........  

0x00000018 18 19 1A 1B 1C 1D 1E 1F *  ........  

0x00000020 20 21 22 23 24 25 26 27 *   !"#$%&'  

0x00000028 28 29 2A 2B 2C 2D 2E 2F *  ()*+,-./  



0x00000000 00 01 02 03 04 05 06 07 *  ........

0x00000008 08 09 0A 0B 0C 0D 0E 0F *  ........

0x00000010 10 11 12 13 14 15 16 17 *  ........

0x00000018 18 19 1A 1B 1C 1D 1E 1F *  ........

0x00000020 20 21 22 23 24 25 26 27 *   !"#$%&'

0x00000028 28 29 2A 2B 2C 2D 2E 2F *  ()*+,-./







��3��

���룺



hexdump -e '1/1 "%02_ad#    "' -e '/1 "hex = %02X * "' -e '/1 "dec = %03d | "' -e '/1 "oct = %03o"' -e '/1 " \_\n"' -n 20 test  



�����

00#    hex = 00 * dec = 000 | oct = 000 _  

01#    hex = 01 * dec = 001 | oct = 001 _  

02#    hex = 02 * dec = 002 | oct = 002 _  

03#    hex = 03 * dec = 003 | oct = 003 _  

04#    hex = 04 * dec = 004 | oct = 004 _  

05#    hex = 05 * dec = 005 | oct = 005 _  

06#    hex = 06 * dec = 006 | oct = 006 _  

07#    hex = 07 * dec = 007 | oct = 007 _  

08#    hex = 08 * dec = 008 | oct = 010 _  

09#    hex = 09 * dec = 009 | oct = 011 _  

10#    hex = 0A * dec = 010 | oct = 012 _  

11#    hex = 0B * dec = 011 | oct = 013 _  

12#    hex = 0C * dec = 012 | oct = 014 _  

13#    hex = 0D * dec = 013 | oct = 015 _  

14#    hex = 0E * dec = 014 | oct = 016 _  

15#    hex = 0F * dec = 015 | oct = 017 _  

16#    hex = 10 * dec = 016 | oct = 020 _  

17#    hex = 11 * dec = 017 | oct = 021 _  

18#    hex = 12 * dec = 018 | oct = 022 _  

19#    hex = 13 * dec = 019 | oct = 023 _  



00#    hex = 00 * dec = 000 | oct = 000 _

01#    hex = 01 * dec = 001 | oct = 001 _

02#    hex = 02 * dec = 002 | oct = 002 _

03#    hex = 03 * dec = 003 | oct = 003 _

04#    hex = 04 * dec = 004 | oct = 004 _

05#    hex = 05 * dec = 005 | oct = 005 _

06#    hex = 06 * dec = 006 | oct = 006 _

07#    hex = 07 * dec = 007 | oct = 007 _

08#    hex = 08 * dec = 008 | oct = 010 _

09#    hex = 09 * dec = 009 | oct = 011 _

10#    hex = 0A * dec = 010 | oct = 012 _

11#    hex = 0B * dec = 011 | oct = 013 _

12#    hex = 0C * dec = 012 | oct = 014 _

13#    hex = 0D * dec = 013 | oct = 015 _

14#    hex = 0E * dec = 014 | oct = 016 _

15#    hex = 0F * dec = 015 | oct = 017 _

16#    hex = 10 * dec = 016 | oct = 020 _

17#    hex = 11 * dec = 017 | oct = 021 _

18#    hex = 12 * dec = 018 | oct = 022 _

19#    hex = 13 * dec = 019 | oct = 023 _

## GDB�̳�



LINUX��GDB���� 

http://blog.csdn.net/sco_field/article/details/4310987

## objdump������๤�ߣ�

objdump �Ct

���������Դ�ӡ��bomb �ķ��ű����ű������bomb�����к��������ƺʹ洢��ַ�Լ�ȫ�ֱ��������ơ������ͨ���鿴�������õ�һЩ��Ϣ��

objdump �Cd

��������������ǿ��Զ�bomb �еĴ�����з���ࡣͨ���Ķ���������Ը�����bomb ��������еġ���Ȼobjdump �Cd ������ܶ����Ϣ�������������ܸ��������е���Ϣ�����磺һ������sscanf ��������������ʾΪ��8048c36: e8 99 fc ff ff call 80488d4 <_init+0x1a0>���㻹��Ҫgdb ��������ȷ��������ľ��幦�ܡ�

objdump��ӡ���ű�ĸ�ʽ��

shenyan@ubuntu:~/Temp$ objdump -t a.o

a.o:     file format elf32-i386

SYMBOL TABLE:

00000000 l    df *ABS* 00000000 a.c

00000000 l    d  .text 00000000 .text

00000000 l    d  .data 00000000 .data

00000000 l    d  .bss 00000000 .bss

00000000 l    d  .note.GNU-stack 00000000 .note.GNU-stack

00000000 l    d  .comment 00000000 .comment

00000000 g     F .text 00000005 f_test

00000005 g     F .text 00000027 main

00000000         *UND* 00000000 shared

00000000         *UND* 00000000 swap



1.����ƫ��

2.����������

3.�������ͣ�d ??��df Դ�ļ�����F ������

4.�������ڶΣ� *UND*�ⲿ���ӷ��ţ�δ�ڱ�Ŀ���ļ�����

5.���Ŷ�Ӧ�Ķ���ռ�ݵ��ڴ�ռ��С��û��ʵ������СΪ0��δ�����Ϊ0

6. ������

linux��strings����

strings - ��ʾ�ļ��еĿɴ�ӡ�ַ���һ�������鿴���ı��ļ�������.

man strings

# strings /lib/tls/libc.so.6 | grep GLIBC

GLIBC_2.0

GLIBC_2.1

GLIBC_2.1.1

GLIBC_2.1.2

GLIBC_2.1.3

GLIBC_2.2

GLIBC_2.2.1

GLIBC_2.2.2

GLIBC_2.2.3

GLIBC_2.2.4

GLIBC_2.2.6

GLIBC_2.3

GLIBC_2.3.2

GLIBC_2.3.3

GLIBC_2.3.4

GLIBC_PRIVATE



�������ܿ���glibc֧�ֵİ汾��

## DevHelp 
# shell���ѧϰ֮·

3����Shell��̣��ж�һ�ļ��ǲ����ַ��豸�ļ�������ǽ��俽���� /dev Ŀ¼�¡�

�ο�����

#!/bin/sh

FILENAME=

echo ��Input file name����

read FILENAME

if [ -c "$FILENAME" ]

then

cp $FILENAME /dev

fi





7��ĳϵͳ����Ա��ÿ����һ�����ظ��������밴������Ҫ�󣬱���һ����� ���� ��

��1��������4 :50ɾ��/abcĿ¼�µ�ȫ����Ŀ¼��ȫ���ļ���

��2������8:00������6:00ÿСʱ��ȡ/xyzĿ¼��x1�ļ���ÿ�е�һ�����ȫ�����ݼ��뵽/backupĿ¼�µ�bak01.txt�ļ��ڣ�

��3��ÿ������һ����5:50��/dataĿ¼�µ�����Ŀ¼���ļ��鵵��ѹ��Ϊ�ļ���backup.tar.gz��

��4��������5:55��IDE�ӿڵ�CD-ROMж�أ����裺CD-ROM���豸��Ϊhdc����

��5�����糿8:00ǰ������������



�ο���:

���������

��1����vi�����༭һ����Ϊprgx��crontab�ļ���

	prgx�ļ������ݣ�

50 16 * * * rm -r /abc/*



��2����0 8-18/1 * * * cut -f1 /xyz/x1 >;>; /backup/bak01.txt

��3����50 17 * * * tar zcvf backup.tar.gz /data

��4����55 17 * * * umount /dev/hdc

��5�����ɳ����û���¼����crontabִ�� prgx�ļ��е����ݣ�

root@xxx:#crontab prgx����ÿ���糿8:00֮ǰ�����󼴿��Զ�����crontab��

��������������������������������������������������������������������������������������������

8�����һ��shell������ÿ�µ�һ�챸�ݲ�ѹ��/etcĿ¼���������ݣ������/root/bakĿ¼����ļ���Ϊ������ʽyymmdd_etc��yyΪ�꣬mmΪ�£�ddΪ�ա�Shell����fileback�����/usr/binĿ¼�¡�

�ο��𰸣�

��1����дshell����fileback��

#!/bin/sh

DIRNAME=`ls /root | grep bak`

if [ -z "$DIRNAME" ] ; then

mkdir /root/bak

cd /root/bak

fi

YY=`date +%y`

MM=`date +%m`

DD=`date +%d`

BACKETC=$YY$MM$DD_etc.tar.gz

tar zcvf $BACKETC /etc

echo "fileback finished!"

��2����д����ʱ����

echo "0 0 1 * * /bin/sh /usr/bin/fileback" >; /root/etcbakcron

crontab /root/etcbakcron

��ʹ��crontab -e ������Ӷ�ʱ����

0 1 * * * /bin/sh /usr/bin/fileback



9����һ��ͨ�û�����ÿ�����賿�����ֶ��ڱ���/user/backup��/tmpĿ¼�£����û�Ӧ�������

�ο��𰸣���1����һ�ַ�����

�û�Ӧʹ��crontab �Ce �����crontab�ļ�����ʽ���£�

0 0 * * sun cp �Cr /user/backup /tmp

��2���ڶ��ַ�����

�û������Լ�Ŀ¼���½��ļ�file���ļ��������£�

0 * * sun cp �Cr /user/backup /tmp

Ȼ��ִ�� crontab file ʹ��Ч��

#������õ�Linux��ؽű�����



Ϊ����ṩ�������linux��ؽű�(�鿴��������������ϵͳ״����ء���������Ĵ��̿ռ�,��ʹ�ÿռ䳬��90����ͨ����mail�������桢���CPU���ڴ��ʹ�������ȫ��λ�������)������Ҫ�����Ѳ�������Ŷ







1���鿴������������



#!/bin/bash

#network

#Mike.Xu

while : ; do

      time='date +%m"-"%d" "%k":"%M'

      day='date +%m"-"%d'

      rx_before='ifconfig eth0|sed -n "8"p|awk '{print $2}'|cut -c7-'

      tx_before='ifconfig eth0|sed -n "8"p|awk '{print $6}'|cut -c7-'

      sleep 2

      rx_after='ifconfig eth0|sed -n "8"p|awk '{print $2}'|cut -c7-'

      tx_after='ifconfig eth0|sed -n "8"p|awk '{print $6}'|cut -c7-'

      rx_result=$[(rx_after-rx_before)/256]

      tx_result=$[(tx_after-tx_before)/256]

      echo "$time Now_In_Speed: "$rx_result"kbps Now_OUt_Speed: "$tx_result"kbps"

      sleep 2

done

2��ϵͳ״�����



#!/bin/sh

#systemstat.sh

#Mike.Xu

IP=192.168.1.227

top -n 2| grep "Cpu" >>./temp/cpu.txt

free -m | grep "Mem" >> ./temp/mem.txt

df -k | grep "sda1" >> ./temp/drive_sda1.txt

#df -k | grep sda2 >> ./temp/drive_sda2.txt

df -k | grep "/mnt/storage_0" >> ./temp/mnt_storage_0.txt

df -k | grep "/mnt/storage_pic" >> ./temp/mnt_storage_pic.txt

time=`date +%m"."%d" "%k":"%M`

connect=`netstat -na | grep "219.238.148.30:80" | wc -l`

echo "$time  $connect" >> ./temp/connect_count.txt

3����������Ĵ��̿ռ�,��ʹ�ÿռ䳬��90����ͨ����mail��������



#!/bin/bash

#monitor available disk space

SPACE='df | sed -n '/ \ / $ / p' | gawk '{print $5}' | sed  's/%//'

if [ $SPACE -ge 90 ]

then

jbxue123@163.com

fi

4�� ���CPU���ڴ��ʹ�����



#!/bin/bash

#script  to capture system statistics

OUTFILE=/home/xu/capstats.csv

DATE='date +%m/%d/%Y'

TIME='date +%k:%m:%s'

TIMEOUT='uptime'

VMOUT='vmstat 1 2'

 USERS='echo $TIMEOUT | gawk '{print $4}' '

LOAD='echo $TIMEOUT | gawk '{print $9}' | sed "s/,//' '

FREE='echo $VMOUT | sed -n '/[0-9]/p' | sed -n '2p' | gawk '{print $4} ' '

IDLE='echo  $VMOUT | sed -n '/[0-9]/p' | sed -n '2p' |gawk '{print $15}' '

echo "$DATE,$TIME,$USERS,$LOAD,$FREE,$IDLE" >> $OUTFILE

5��ȫ��λ�������



#!/bin/bash

# check_xu.sh

# 0 * * * * /home/check_xu.sh



DAT="`date +%Y%m%d`"

HOUR="`date +%H`"

DIR="/home/oslog/host_${DAT}/${HOUR}"

DELAY=60

COUNT=60

# whether the responsible directory exist

if ! test -d ${DIR}

then

        /bin/mkdir -p ${DIR}

fi

# general check

export TERM=linux

/usr/bin/top -b -d ${DELAY} -n ${COUNT} > ${DIR}/top_${DAT}.log 2>&1 &

# cpu check

/usr/bin/sar -u ${DELAY} ${COUNT} > ${DIR}/cpu_${DAT}.log 2>&1 &

#/usr/bin/mpstat -P 0 ${DELAY} ${COUNT} > ${DIR}/cpu_0_${DAT}.log 2>&1 &

#/usr/bin/mpstat -P 1 ${DELAY} ${COUNT} > ${DIR}/cpu_1_${DAT}.log 2>&1 &

# memory check

/usr/bin/vmstat ${DELAY} ${COUNT} > ${DIR}/vmstat_${DAT}.log 2>&1 &

# I/O check

/usr/bin/iostat ${DELAY} ${COUNT} > ${DIR}/iostat_${DAT}.log 2>&1 &

# network check

/usr/bin/sar -n DEV ${DELAY} ${COUNT} > ${DIR}/net_${DAT}.log 2>&1 &

#/usr/bin/sar -n EDEV ${DELAY} ${COUNT} > ${DIR}/net_edev_${DAT}.log 2>&1 &

����crontab��ÿСʱ�Զ�ִ�У�

0 * * * * /home/check_xu.sh

���������/home/oslog/host_yyyymmdd/hhĿ¼�����ɸ�Сʱcpu���ڴ桢���磬IO��ͳ�����ݡ�

���ĳ��ʱ��β��������ˣ��Ϳ���ȥ����Ӧ����־��Ϣ��������ʱ������������Ρ�

# shell ��syntax error:unexpected end of file��

������дShellʱ������ʱ�����������Ĵ���

git-sync-tree.sh_temp: line 111: syntax error: unexpected end of file

����Google��һ�£����϶���˵��windows�½ű�����Linux�Ͽ��ܻ�������������⣬����ΪWindows��Linux�µ���ĩ�������ǲ�һ���ģ�����д��һƪ���ͣ��س��뻻�е�����    ��Ȼ���ҽ��������Ĳ�������������µġ�

1. ���ȷʵ�������������windows��д����Shell ������linux���ã�

sh -n [filesName]  ����﷨���ǳ�һ������ syntax error:unexpected end of file

ԭ������:

dos�ļ����䵽unixϵͳʱ,����ÿ�еĽ�β��һ��^M,��vi��ʱ��,�������������

vi dos.txt

:set fileformat=unix

:w

�ͻῴ����Щ������ÿ�н�β��^M���ţ�������ǲ���syntax error:unexpected end of file��ԭ��

���������

��vi�°���Щ^M��ɾ���󼴿ɡ�

Ҳ����ʹ��Linux�µĹ��ߣ�dos2unixҲ�����ɽ�һ��windows�µ��ı��ļ�ת��ΪUnix���ݵĸ�ʽ��

2.�������Ĳ�����������windows��Linux�໥�����ļ������µġ�������﷨��������������shell�ű��е�󣬿���һ����Ҳû�������Ǿ仰�﷨�����ˣ����Բ��ò��ö��ַ�������ԭ�򣬲���ע��һЩ���룬Ȼ����sh -n test.sh�����﷨��飬ֱ������ҵ���һ�λ�����һ�д�������Ĵ����ҷ������������д�������ģ����ܿ������е�������^_^

[ -d /home/repo/${SPPATH} ] || { mkdir -p /home/repo/${SPPATH}; cd /home/repo/${SPPATH}; git init >> $GITLOG 2>&1 }

�ţ���ʵ���û�����{}����Ѽ���������������ڵ�ǰshell��ִ�У�Ȼ���ҷ���һ���﷨����������һ�������û�мӷֺţ�;���������и�Ϊ���¼��ɣ����һ�����ķֺţ���

[ -d /home/repo/${SPPATH} ] || { mkdir -p /home/repo/${SPPATH}; cd /home/repo/${SPPATH}; git init >> $GITLOG 2>&1; }

���ڵ�ǰshell��ִ��һ������ر�Ҫע����ǣ��ڡ�{�����ұ� �͡�}������ߣ�����Ҫ���һ�����ϵĿո񣬶���ÿ�����Ҫ�Էֺ�(;)��Ϊ��β��

#��������������ִ��������

��linux shell�ű������һ�����������Ǳ�����һ�������Ҫ��ִ�н���ŵ����������������磺ip='ifconfig eth0'  echo $ip���������Խ�ҳ����ʾ����eth0������״��������ifconfig eth0�Ľ����

ip=`ifconfig eth0`

echo $ip

ʹ�÷����ſ��԰�һ�����������嵽��һ��������ȥ����ͬ���ܵ�д������$()������ͬ` ` Ч����һ���ġ�����ĳЩunixϵͳ��֧��$()����д��������` `���κ�unix��linuxϵͳ�¶�����ʹ�á�

# shell �ж��ַ����Ƿ���ڰ�����ϵ

#! /bin/bash



var1="hello"

var2="he"



#����1

if [ ${var1:0:2} = $var2 ]

then

    echo "1:include"

fi



#����2

echo "$var1" |grep -q "$var2"

if [ $? -eq 0 ]

then

    echo "2:include"

fi



#����3

echo "$var1" |grep -q "$var2" && echo "include" ||echo "not"



#����4

[[ "${var1/$var2/}" != "$var2" ]] && echo "include" || echo "not"



����������



expr��awk��index����

${var#...}                  

${var%...}

${var/.../...}

#�鿴linux����ϵͳ�汾

##�鿴�ں˰汾����

jiangxin@Ubuntu:~$ cat /proc/version

Linux version 3.13.0-30-generic (buildd@allspice) (gcc version 4.8.2 (Ubuntu 4.8.2-19ubuntu1) ) #54-Ubuntu SMP Mon Jun 9 22:45:01 UTC 2014

jiangxin@Ubuntu:~$ uname -r

3.13.0-30-generic

jiangxin@Ubuntu:~$ uname -a

Linux Ubuntu 3.13.0-30-generic #54-Ubuntu SMP Mon Jun 9 22:45:01 UTC 2014 x86_64 x86_64 x86_64 GNU/Linux

##�鿴linux�汾

jiangxin@Ubuntu:~$ lsb_release -a

No LSB modules are available.

Distributor ID:	Ubuntu

Description:	Ubuntu 14.04 LTS

Release:	14.04

Codename:	trusty

jiangxin@Ubuntu:~$ cat /etc/debian_version 

jessie/sid

jiangxin@Ubuntu:~$ cat /etc/issue

Ubuntu 14.04 LTS \n \l

jiangxin@Ubuntu:~$ cat /etc/issue

Ubuntu 14.04 LTS \n \l

jiangxin@Ubuntu:~$ file /bin/bash 

/bin/bash: ELF 64-bit LSB  executable, x86-64, version 1 (SYSV), dynamically linked (uses shared libs), for GNU/Linux 2.6.24, BuildID[sha1]=796da7aa73903b1e5608a8ff8433669b7e00e980, stripped

jiangxin@Ubuntu:~$ file /bin/cat 

/bin/cat: ELF 64-bit LSB  executable, x86-64, version 1 (SYSV), dynamically linked (uses shared libs), for GNU/Linux 2.6.24, BuildID[sha1]=950f866ca2bc042f9ca643e1af0fde0e0c029dc3, stripped

[root@SOR_SYS ~]# cat /etc/redhat-release //Only for Redhat

Red Hat Enterprise Linux AS release 4 (Nahant Update 4)

[root@SOR_SYS ~]# rpm -q redhat-release //Only for Redhat

redhat-release-5Server-5.6.0.3

ע:���ַ�ʽ�¿ɿ���һ����ν��release�ţ������ϱߵ�������5�����release�ź�ʵ�ʵİ汾֮�����һ���Ķ�Ӧ��ϵ�����£�

redhat-release-3AS-1 -> Redhat Enterprise Linux AS 3

redhat-release-3AS-7.4 -> Redhat Enterprise Linux AS 3 Update 4

redhat-release-4AS-2 -> Redhat Enterprise Linux AS 4

redhat-release-4AS-2.4 -> Redhat Enterprise Linux AS 4 Update 1

redhat-release-4AS-3 -> Redhat Enterprise Linux AS 4 Update 2

redhat-release-4AS-4.1 -> Redhat Enterprise Linux AS 4 Update 3

redhat-release-4AS-5.5 -> Redhat Enterprise Linux AS 4 Update 4

jiangxin@Ubuntu:~$ cat /etc/debian_version //Only for Debian

jessie/sid

# C���Ե����ֶ�:���������ʵ�ַ���

����Ŀ���������У������ȷ���ĸ��ļ��µ��ĸ������µ����г���--�����������Ǹö�ð��������¾���Ϊ�˶����ġ��������˽�һ���ļ�Ĭ�ϵ������Ϣ�ĺ����ɣ�



printf("line : %d\n", __LINE__);                   //��ǰ����

printf("filename : %s\n", __FILE__);             //��ǰ�ļ���

printf("function : %s\n", __FUNCTION__);  //��ǰ����

printf("time : %s\n", __TIME__);                  //��ǰʱ��

printf ("date : %s\n",  __DATE__);              //��ǰ����



line : 10

filename : test.c

function : main.c

time : 14:13:51

date : Oct 13 2012



�������㣬�Ǿ������������������ɣ�

һ��Դ�ļ���



erroutput.c

#include <stdio.h>

#include <assert.h>

#define _DEBUG(msg...)    printf("[ %s,%s, %d ]=>",__FILE__, __FUNCTION__, __LINE__);  printf(msg);printf("\r\n")

#define _ERROR(msg...)    printf("[ error: %s, %d]=>", __FILE__,  __LINE__);printf(msg); printf("\r\n")

#define _ASSERT(exp)      \

                        do {\

                                if (!(exp)) {\

                                printf( "[ %s ]  ",#exp);printf("\r\n");\

                                assert(exp);\

                                }\

                        } while (0)

int main(void)

{

        char *p = NULL;

        _DEBUG("DEBUG!");

        _ERROR("ERROR!");

        _ASSERT(NULL != p);

        return 0;

}



���������



[root@localhost for_test]# gcc erroutput.c

[root@localhost for_test]# ./a.out

[ erroutput.c,main, 17 ]=>DEBUG!

[ error: erroutput.c, 18]=>ERROR!

[ NULL != p ]

a.out: erroutput.c:19: main: Assertion `((void *)0) != p' failed.

�ѷ���



TI����

#ifdef DEBUG

    #define DBG(fmt, args...)  printf("Debug " fmt, ##args)// ##��������ڰѲ������ӵ�һ��Ԥ�������ѳ�����##����Ĳ����ϲ���һ�����š�

#else

    #define DBG(fmt, args...)

#endif

#define ERR(fmt, args...)  printf("Error " fmt, ##args)

[root@localhost for_test]# cat debug_err.c

#include <stdio.h>

//#define DEBUG

int main(void)

{

       DBG("xxxx\n");

       ERR("xxxx\n");

       return 0;

}

[root@localhost for_test]# ./a.out

Error xxxx



#ifdef __DEBUG

    #define DBG(fmt, args...) fprintf(stderr,"Encode Debug: " fmt, ## args)

#else

    #define DBG(fmt, args...)

#endif

#define ERR(fmt, args...) fprintf(stderr,"Encode Error: " fmt, ## args)

#���ubuntu���Ҳ���libgtk-x11-2.0.so.0

The following error came up when I tried to run Adobe Acrobat Reader on ubuntu 12.10 

error while loading shared libraries: libgtk-x11-2.0.so.0: cannot open shared object file: No such file or directory

To fix this, simple install the package ia32-libs-gtk

$ sudo apt-get install ia32-libs-gtk

Now run the application again and the error should go away.

���䣺

�����ubuntu 14.04��������ִ�У�

����1��

sudo gedit /etc/apt/sources.list

Ȼ�����������ϣ� deb http://archive.ubuntu.com/ubuntu/ raring main restricted universe multiverse

����2�� 

echo "deb http://archive.ubuntu.com/ubuntu/ raring main restricted universe multiverse"  >>  sudo gedit /etc/apt/sources.list 

�����Դ֮��

sudo apt-get update

sudo apt-get install ia32-libs ia32-libs-gtk

������Ӧ�ÿ����ˡ�

# debian hosts�ļ��е� 127.0.1.1 ������ַ

��ʱ��/etc/hosts�ļ��ῴ��127.0.1.1�����ַ,����ʲô��?

127.0.0.1���loopback��ַ�ܳ��������Ǳ��ؽӿڵĻ�·/�ػ���ַ������ʱ��/etc/hosts�ļ��л������127.0.1.1,������ʲô��ַ�أ���Ҳ�Ǹ����ػ�·/�ػ���ַ��

���������ַ��ԭ������Ϊ��ЩӦ�ó�����Ҫ�淶��ȫ�޶�����FQDN(Fully Qualified Domain Name)��FQDN��ֻ��Ҫ����������Ҫ����������������ʽΪhostname.domainname

������������һ����̬IP��ַ����FQDN���ֽ����������̬��ַ�����������127.0.1.1������ػ�·��ַ������һ������²��ῴ��127.0.1.1�����ַ��

127.0.0.1һ��ֻ��Ӧhostname����Ҳ�Ƕ��ߵ���Ҫ��������

127.0.0.1 hostname

127.0.1.1 hostname.domainname

��Ȼ��һ����Ҫ��127.0.1.1���IP,RFC�涨��127.0.0.0/8���IP���ڵ�����IP�����ԣ�ֻҪû�г�ͻ��debianѡ����127.0.1.1

�鿴������

# hostname

 hostname

�鿴FQDN����

# hostname --fqdn

 hostname.domainname

# Linux�·ָ�ϲ��� 

�и�ϲ��ļ���linux����split��cat�Ϳ�����ɡ������Щʵ������˵����

1.�ļ��и�

�ļ��и�ģʽ��Ϊ���֣��ı��ļ���������ģʽ��

1.1�ı�ģʽ

�ı�ģʽֻ�������ı��ļ���������ģʽ�и���ÿ���ļ����ǿɶ��ġ��ı�ģʽ�ַ�Ϊ���֣�

������ļ���С�и

���ı������и

1.1.1����ļ���С�и�

split -C 5k duanxin split

���ı��ļ�duanxin��ÿ�����5k�Ĵ�С�����и�������С�����ļ�������splitaa, splitab����

split -b 5k duanxin split

ÿ���ֿ飨��Ȼ�����һ������֤����С����5k�����ܻ�����С�

1.1.2 ���ı������и�

split -l 100 duanxin split

ÿ���ֿ�100�У������Ǵ�С����־����ʱӦ�����á�

1.2 ������ģʽ

split -b 5k duanxin split

ÿ���ֿ飨��Ȼ�����һ������֤����С����5k���������ɶ����κ������ļ��������������и�ģʽ��

2.�ļ��ϲ�

cat split* >newduanxin

������ʲô��ʽ�и�ϲ��������䡣

3.����

split������-aѡ��ָ������ļ����ĳ��ȡ���

split -l 100 -a 3 duanxin split

������ļ���������splitaaa,splitaab����ָ��ʱĬ��Ϊ2��

��-b��-Cָ���ֿ��Сʱ�����õĵ�λ�У�b for 512bytes, k for 1Kbytes, m for 1 Megbytes.

split ������

-a, --suffix-length=N   ָ������ļ����ĺ�׺��Ĭ��Ϊ2��

-b, --bytes=SIZE        ָ������ļ����ֽ���

-C, --line-bytes=SIZE  ÿһ������У����е���� byte ��

-d, --numeric-suffixes  ʹ�����ִ�����ĸ����׺

-l, --lines=NUMBER    NUMBER ֵΪÿһ�������������С

# ubuntu���ն�·��ֻ��ʾ��ǰĿ¼

���һֱ�����ն˲�����������������·����ʵ�ڲ�ˬ�� �������ĸĿ���

$: sudo vim ~/.bashrc

����ļ���¼���û��ն�����

�ҵ�

if [ "$color_prompt " = yes ]; then

    PS1 ='{debian_chroot:+(debian_chroot)}

\033[01;32m

\u@\h

\033[00m

:

\033[01;34m

\W 

\033[00m

\$ '

else

    PS1 ='{debian_chroot:+(debian_chroot)}\u@\h:\W \$ '

 ����ɫ��w��Сд�ĳɴ�д�����Ա�ʾֻ��ʾ��ǰĿ¼����.

# ubuntu�ն���ɫ��ʧ������

ubuntukylin 13.10    ls���ն���ʾ������������Ǻڵװ��֣�û�в�ɫ����su��lsȴ�в�ɫ 

echo $PS1  �������Ҳ�в��죬һ�������û�Ŀ¼��.bashrcû�У�  

cp /etc/skel/.bashrc  ~/ 

�������������Ҫ����ɫ���ã������޸�PS1��ֵ�� 

#ͨ��find����Ѱ���ļ���������ָ��Ŀ¼

��������һ��������Ҫ��һ���ַ����������ļ���һ��Ŀ¼��������һ��Ŀ¼�У�����ͨ��ʹ��find�����ԴĿ¼���ҵ������������ļ�Ȼ��ʹ��cp�������Ŀ��Ŀ¼

����һ 

�������£� 

find src_dir -name "access.log.2011102[2-6]*" -exec cp {} dst_dir \; 

�����ļ���Զ�������ϵ�Ŀ��Ŀ¼����� 

find src_dir -name "access.log.2011102[2-6]*" -exec scp {} �û���@����ip:dst_dir \; 

������ 

find src_dir -name "access.log.2011102[2-6]*" |xargs -i cp {} dst_dir 

�� 

find src_dir -name "access.log.2011102[2-6]*" |xargs -I {} cp {} dst_dir 

�����ļ���Զ�������ϵ�Ŀ��Ŀ¼����� 

find src_dir -name "access.log.2011102[2-6]*" |xargs -i scp {} �û���@����ip:dst_dir 

�� 

find src_dir -name "access.log.2011102[2-6]*" |xargs -I {} scp {} �û���@����ip:dst_dir 

src_dir ԴĿ¼ 

dst_dir Ŀ��Ŀ¼ 

access.log.2011102[2-6]* �ļ�����������ʽ����ȡ�ļ������� 

������ 

find������cp�������ĳ��Ŀ¼�������ļ�����һ��Ŀ¼�� 



Ҫ������Ŀ¼��ȫ��������һ��Ŀ¼�����Һ��Ը���Ŀ¼���ű����£� 

find ./ -path '/tmp/mnt/disk1/ignore' -prune -o \( -name '*' ! -name "*.tmp" \) | xargs cp "Ŀ��Ŀ¼" "{}" \;



����������ű��У���ִ�е���| xargs cp��ʱ������������ַ����������£� 

/tmp/mnt/disk1/tt.txt 

/tmp/mnt/disk1/test/dd.txt 



Ҫ��ִ�С�xargs cp������Ӧ���������µ�Ŀ¼�ṹ 

(����ԭ��disk1Ŀ¼�������ļ���������srcĿ¼�£�Ŀ¼�ṹ����)�� 

/tmp/mnt/src/tt.txt 

/tmp/mnt/src/test/dd.txt

# ubuntu��¼�����û���������������ص�¼����

������Ubuntu 14.04��½������������֮�󣬺���һ��������ת����¼���档

ԭ����Ŀ¼�µ�.Xauthority�ļ�ӵ���߱����root���Ӷ����û���½��ʱ���޷���ȡ.Xauthority�ļ���

˵����Xauthority����startx�ű���¼�ļ���Xserver����ʱ�����ļ�~/.Xauthority,�����Ӧ��display�ļ�¼����һ����Ҫ��ʾ�Ŀͻ�������������XOpenDisplay()Ҳ������� ���������ҵ���magic code ���͸�Xserver��

��Xserver��֤���magic code��ȷ�Ժ󣬾�ͬ�����������۲�startx�ű�Ҳ���Կ�����ÿ��startx���У����ڵ���xinit��ǰʹ����xauth��add���������һ���µļ�¼��~/.Xauthority�������������Xʹ����֤

���������������Ҫ��.Xauthority��ӵ���߸�Ϊ��½�û������߸ɴཫ.Xauthorityɾ�����˷�ת�����ϣ�����δ��֤��

�������ڵ�½���水��shift + ctrl + F1����tty�������ն˵�½�����룺 

$ cd ~

$ sudo chown groupname:username .Xauthority

Ȼ���ٴ����룺

ls .Xauthority -l

�ɹ�����ʾ���£�

-rw------- 1 hp hp 80 1�� 27 10:41 .Xauthority

��ʱӵ�����Ѿ���Ϊ�û�������shift + ctrl + F7�л���ͼ�ε�½�����½���ɡ�

# watchdog

Linux �Դ���һ�� watchdog ��ʵ�֣����ڼ���ϵͳ�����У�����һ���ں� watchdog module ��һ���û��ռ�� watchdog �����ں� watchdog ģ��ͨ�� /dev/watchdog ����ַ��豸���û��ռ�ͨ�š��û��ռ����һ���� /dev/watchdog �豸���׳ơ����ŷŹ��������ͻᵼ�����ں�������һ��1���ӵĶ�ʱ����ϵͳĬ��ʱ�䣩���˺��û��ռ������Ҫ��֤��1����֮��������豸д�����ݣ��׳ơ�����ι��������ÿ��д�����ᵼ�������趨��ʱ��������û��ռ������1����֮��û��д��������ʱ�����ڻᵼ��һ��ϵͳ

reboot ����������ҧ���ˡ��Ǻǣ���ͨ�����ֻ��ƣ����ǿ��Ա�֤ϵͳ���Ľ��̴󲿷�ʱ�䶼��������״̬����ʹ�ض������½��̱��������޷�������ʱ��ι������Linuxϵͳ�ڿ��Ź�����������������reboot�������Ľ��������������ˡ�������Ƕ��ʽϵͳ��



�� /dev/watchdog �豸�������ŷŹ�������



int fd_watchdog = open("/dev/watchdog", O_WRONLY);

if(fd_watchdog == -1) {

	int err = errno;

	printf("\n!!! FAILED to open /dev/watchdog, errno: %d, %s\n", err, strerror(err));

	syslog(LOG_WARNING, "FAILED to open /dev/watchdog, errno: %d, %s", err, strerror(err));

}

ÿ��һ��ʱ���� /dev/watchdog �豸д�����ݣ�������ι��������



//feed the watchdog

if(fd_watchdog >= 0) {

	static unsigned char food = 0;

	ssize_t eaten = write(fd_watchdog, &food, 1);

	if(eaten != 1) {

		puts("\n!!! FAILED feeding watchdog");

		syslog(LOG_WARNING, "FAILED feeding watchdog");

	}

}

�ر� /dev/watchdog �豸��ͨ������Ҫ������裺



close(fd_watchdog);

����ͷ�ļ���



#include <unistd.h>

#include <sys/stat.h>

#include <syslog.h>

#include <errno.h>

# tailf

tailf�������ͬ��tail -f���ϸ�˵��Ӧ����tail --follow=name������Щ�����ļ�����֮����Ҳ�ܼ������٣��ر��ʺ�����־�ļ��ĸ��١���tail -f��ͬ���ǣ�����ļ���������������ȥ���ʴ����ļ������������ĺô������û���µ���־��������־�ļ���ʱ���(access time)�Ͳ���ı䡣tailf�ر��ʺ���Щ��Я���ϸ�����־�ļ�����Ϊ����ʡ�磬��Ϊ�����˴��̷����

��ʽ��tailf logfile

��̬������־�ļ�logfile�������ʱ���ӡ�ļ������10�����ݡ�

Ctrl+C ֹͣ

# vimrc��bashrc��rc�ĺ���

rc (���� ".cshrc" �� "/etc/rc" �е� rc ��������ĸ) = "RunCom" 

"rc" ��ȡ�� "runcom", ������ʡ��ѧԺ�� 1965 �귢չ�� CTSSϵͳ�����������������һ�λ�: '���дӵ�����ȡ��һϵ��������ִ�еĹ��ܣ����Ϊ "run commands" �ֳ�Ϊ "runcom"�������ֵ����ֳ�Ϊһ�� runcom (a runcom)��' 

Brian Kernighan �� Dennis Ritchie ���� Vicki Brown ˵: "rc" Ҳ��Plan 9 ��ҵϵͳ shell �����֡�

#.cshrc�ļ��Ǹ�ʲô�õ�?

����Ǹ������ļ�  ������ʹ�õ��û���Ŀ¼�µ�

��csh ���shell(csh)�������ļ������csh�ĸ��Ķ����¼������ļ��У��´���������csh��ʱ����ȡ����ļ���

# There are unfinished transactions remaining

�����ڷ�������yum��װ������ʱ��,���Ǳ�:There are unfinished transactions remaining. You might consider running yum-complete-transaction first to finish them.��˼��:��δ��ɵ�yum����,����������yum-complete-transaction�������.�����¿���,ԭ����ǿ�ƽ���yum��,�ð�,�����������е���΢ǿ��֢������˵,�����������������Щ��Ϣ��.

����취:

��������:

# ��װ yum-complete-transaction������һ���ܷ���δ��ɻ��жϵ�yum����ĳ���

yum -y install yum-utils

# ���yum����

yum clean all

# ���� yum-complete-transaction,����δ�������

yum-complete-transaction --cleanup-only

ps:

yum������ص��������header�洢��cache��,�������Զ�ɾ��.����yum clean headers���header,yum clean packages������ص�rpm��,yum clean allȫ��.

# yum��ʾanother app is currently holding the yum lock;waiting for it to exit

������ϵͳ�Զ������������У�yum������״̬�С�

����ͨ��ǿ�ƹص�yum���̣�

#rm -f /var/run/yum.pid

Ȼ��Ϳ���ʹ��yum�ˡ�

#����

GTK+2.0��̷��������ι�ΰ���䣺

gwsong52@sohu.com

��������⣺

G_CALLBACK()��  GTK_SIGNAL_FUNC()����

# shell��̽���

## ��1��SHELL��ʽ

�涨һ����ʽ��������ͳһ���������ӿɶ��ԡ����ڱ�дSHELL�������޸ļ��ɡ�

��ʽ:

ASSIGN SHELL/ָ����

DESCRIPTION/����˵��

BODY/������

��չ��

1 ASSIGN SHELL/ָ���ǣ������ָ���ǣ�Ĭ��ʹ��Bourne SHELL������ʹ��KSH

#!SHELL·��

1.1	 CSH
1.2	
#!/bin/csh

1.3	 BSH
1.4	
#!/bin/sh

1.5	 KSH
1.6	
#!/bin/ksh



2 DESCRIPTION/����˵��

#PROCEDURE NAME/��������

#PROCEDURE FUNCTION/������˵��

#AUTHOR/����

#DATE/����ʱ��

#INPUT/����

#OUTPUT/���

#CALL/���ú���˵��

#HISTORY/�����ʷ



3 BODY/������

INCLUDE LIBRARY /�������ļ�

VARIABLE DEFINE/��������

FUNCTION DEFINE/��������

MAIN/�������

3.1 INCLUDE LIBRARY /�������ļ�

. LIBRARY FILE/���ļ�����

3.2 FUNCTION DEFINE/��������

#FUNCRION: FUNCTION NAME

#DESC    : FUNCTION DESC

#INPUT   : INPUT DESC

#OUTPUT  : OUTPUT DESC

FUNCTION()

{



}

3.3 MAIN/�������(����Ϊ)

��������˵��

����ִ�в���

�������

exit 0



��ʽ������

#!/bin/ksh

 

#################################################################################

# ������  �� update.sh							        					#

# ���ܼ�飺 ���������********����								#

# ����    :  *********0                                                     #

# ����ʱ�䣺 2002-05-05   												#

#	     															#

# ����˵���� ��������													#

#	        CheckBackupDir()	��鱸��Ŀ¼��������򴴽�					#

#	        CheckDbinstallDir()	���SMP�����ݿⰲװ�ű�Ŀ¼					#

#            CheckIfUpgraded()	����Ƿ��Ѿ�����							#

#	        UpdateSMPDir()		����SMP��Ŀ¼�ṹ							#

#            BackupDb()			�������ݿ�Ľű�������						#

#            BackupFile()		����SMPĿ¼���ļ�							#

#            UpdateDb()			�������ݿ�                         		     #

#            UpdateFile()		�����ļ� 	                	    		 	     #

#																	#

# �޸���ʷ�� First Programming			   								#

# ����    ��															#

# ����	  ��															#

# �޸�˵����															#

#################################################################################



#Ӧ�ÿ⺯����Ҫ��⺯���ļ��뵱ǰSHELLͬһĿ¼

. ./comm_func.sh.rc



#�������

#��������

ProgName="SMP Platform Upgrade"



#����

Title="WINV200R002 D039P2"



#Ŀ¼���ļ�����

WorkDir=`pwd`

LogDir=$WorkDir/log

TempDir=$WorkDir/temp



#��־���־�ļ�

ErrFile=$LogDir/update.err

LogFile=$LogDir/update.log

FlagFile=$LogDir/flag.flg



########################��������####################################



####################################################################

# ������PrintUsage

# Ŀ�ģ������ӡ�÷�������

# ���룺

# �������Ļ

####################################################################

PrintUsage()

{

    echo "***************************************************************"

    echo "      NAME : ${ProgName}                                     "

    echo "   VERSION : ${Title}                                        "

    echo "    SYSTEM : WIN SMP                                         "

    echo "      DESC : SMP platform or service upgrade                 "

    echo "    NOTICE :                                                 "

    echo " COPYRIGHT : 2002, HUAWEI Tech. Co. Ltd.                     "

    echo "***************************************************************"

    echo " 1. Execute backup operation"

    echo " 2. Execute upgrade operation"

    echo " 3. Execute rollback operation"    

    echo " 0. Exit"

    echo "Please input operation choice [0-3]:"

}

��

###########               Main            ##############

��

exit 0

#####################  END OF PROCEDURE  ###############



##��2��SHELL����﷨

Script������Ϊ��λ��������д��Script�ᱻ�ֽ��һ��һ����ִ�С���ÿһ�п��������ע�⡢�������̿���ָ��ȡ����ĳһ����δ��ɣ�����ĩ����"\" �����ʱ����һ�е����ݾͻ�ӵ���һ�е����棬��Ϊͬһ�С�



��Script�г���"#"ʱ�����������ͬһ�����ּ�Ϊע�⣬Shell����䷭�롣 ��Script��Ҫִ��һ������ķ���������������һ���������ǰ̨���ִ̨�У�ִ������ʱҲ����Ҫ�趨һЩ���������� 



Script�����̿��ƺ�һ��߼����Ե����̿���û��ʲ��������Ҳ�͸߼�����һ���и���ʽ����Щʹ��Script�Ĺ��ܸ���ǿ�� 



1 SHELL����������ؼ���

.            	��ǰshell������ͬĿ¼

..            	��ǰshell�������һ��Ŀ¼

break    		�˳�for��while��until��case���

cd          		�ı䵽��ǰĿ¼

continue 		ִ��ѭ������һ��

echo       		������Ϣ����׼���

eval        		��ȡ������ִ�н������

exec       		ִ����������ڵ�ǰshell

exit         	�˳���ǰshell

export    		����������ʹ��ǰshell��������

pwd        		��ʾ��ǰĿ¼

read       		�ӱ�׼�����ȡһ���ı�

readonly 		ʹ����ֻ��

return     		�˳����������з���ֵ

set         		���Ƹ��ֲ�������׼�������ʾ

shift       		�����в�������ƫ��һ��

test         	�����������ʽ

times      		��ʾshell���й��̵��û���ϵͳʱ��

trap       		�������ź�ʱ����ָ������

ulimit    		��ʾ������shell��Դ

umask     		��ʾ������ȱʡ�ļ�����ģʽ

unset  			��shell�ڴ���ɾ����������

wait       		�ȴ�ֱ���ӽ���������ϣ�������ֹ



2����

Shell������ֻ���ִ�����������Ҫʹ����ֵ��������뿿�ⲿ������Ŀ�ġ�����������������м��֣� 

2.1 ��ͨ���� 

�����ʹ�õı��������ǿ����κβ������հ���Ԫ���ִ��������������ơ� �趨����ֵʱ�������з�ʽ�� 

var=string   #������var = string�����Ⱥ����߲����пո����ж���������෴���ж������=���������������߱����пո񣬷���Ϊ��ֵ����

ȡ�ñ���ʱ���ڱ�������ǰ����һ"$" �ţ�����${name}�� 

name=Tom 

echo name

echo $name 

������£�

name

Tom



2.2��������

��ʹ��ͨ�������ƣ�ֻ�������ֱ����Ὣ��ֵ��������ִ�е����Ҫ��һʹ ���߱����趨Ϊϵͳ������ֻҪ���ϣ� 

export var����export var=var_value ����setenv var var_valued

name=Tom

export name



������ʹ����һ����ϵͳ֮������趨�õ�ϵͳ������ 

$HOME ʹ�����Լ���Ŀ¼ 

$PATH ִ������ʱ����Ѱ��Ŀ¼ 

$TZ ʱ�� 

$MAILCHECK ÿ�����������Ƿ����µ��ż� 

$PS1 ��������ʱ����ʾ�� 

$PS2 ��������δ����ʱ��ShellҪ��������ʱ����ʾ�� 

$MANPATH man ָ�����Ѱ·�� 



2.3 ֻ����ʹ���߱��� 

��ʹ���߱������ƣ�ֻ������Щ�������ܱ��ı䡣Ҫ���������ֻ���� ��ֻҪ���ϣ� 

readonly var 



����ֻ��readonly����г�����ֻ���ı�����ksh֧��readonly���csh��֧�֣�������shell�����п���ʹ��readonly����ĳ��������������һ�㣬ϵͳ�����������趨��ֻ���ġ� 

name=Tom 

readonly name

echo $name

name=John

echo $name

(�����ļ�����Ϊaa)

������£�

aaa

aa[4]: name: This variable is read only



2.4 ������� 

��Щ������һ��ʼִ��Scriptʱ�ͻ��趨�����Ҳ��Լ����޸ģ������ǲ�����ֻ����ϵͳ�����������������������Ϊ��Щ������һִ�г�ʽʱ�����ˣ�����ʹ�����޷���һ���ϵͳ�����趨��ֻ���ġ�������һЩ���������

$0 �����ʽ��ִ������ 

$n �����ʽ�ĵ�n������ֵ��n=1..9 

$* �����ʽ�����в��� 

$# �����ʽ�Ĳ������� 

$$ �����ʽ��PID 

$! ִ����һ������ָ���PID 

$? ִ����һ��ָ��ķ���ֵ 



$n��nֻ��Ϊ0-9��ԭ����Bourne Shell��λ�ò�������Ϊ$1~$9, ���ͨ��λ�ñ���$nֻ�ܷ���ǰ9������������ִ�������ʽʱ�Ĳ�����Ŀ����9 ʱ�����ǿ���ʹ��shift ���������ǰ��һ����˼���ʹ�õ�10������Ĳ���������֮�⣬������set ����ı�$n��$*���������£� 

set string 



���$*��ֵ��Ϊstring�����ֽ���������$n�����set��������û�в����� ����г������Ѿ��趨�ı����Լ���ֵ�� 

echo Filename: $0

echo Arguments: $*

echo No. of args.: $# 

echo 2nd arg.: $2 

shift 

echo No. of args.: $#

echo 2nd arg.: $2 

set hello, everyone 

echo Arguments: $* 

echo 2nd arg.: $2 



������£�

Filename: ex1

Arguments: this is a test

No. of args.: 4

2nd arg.: is

No. of args.: 3

2nd arg.: a

Arguments: hello, everyone

2nd arg.: everyone



2.5 ������� ��ksh֧�֣�

name[index]=value

����nameΪ��������,indexΪ�����±꣬��ksh���������֧��1024,��indexΪ0~1023.

����

set �CA name value1 value2��valuen

�����������

${name[index]}

Ӧ�������

${name[*]}    #����

${name[@]}



�磺

set �CA ser pps ppip mvpn

echo ${ser[2]}

echo ${ser[*]}

��ӡΪ��

mvpn

pps ppip mvpn



�磺

set �CA ser pps ppip mvpn

echo $ser[2]

echo $ser[*]

��ӡΪ��

pps[2]

pps[*]



2.6 SHELL���� 

SHELL�����п���ֱ��ʹ��һЩ�����������У�

SECONDS			#ftp�������жϳ�ʱ����ʹ���������

IFS				#��ָ����ȱʡΪ�ո����TAB�����������û�ָ��



3����

ĳЩ�ַ���SHELL�о߱�����ĺ��壺

�磺& * + ^ $ ` " | ? [ ] ; ^ < >

����ʹ��˫���Ż��ߵ����Ż���\ȥ�������ַ��ĺ��壬ʹ��Ϊһ����ͨ�ַ�.

3.1	 ��������ȥ����$, \, ``֮������������ַ��ĺ��塣
3.2	
���磺

>echo *    		#�����ǰĳ��������Ŀ¼���ļ�

>echo ��*��		#���*�ַ�

>echo ��`date`��	#���Ϊdate�����ӡ��ʱ�䡰Tue Sep 17 11:31:58 MDT 2002��

>echo ��$PATH��	#�����ǰ�û�������·��

>echo ��a\na��		#���Ϊ2�У�һ��һ��a����ʱ\Ϊ�����ַ�

3.3	 ���������ſ���ȥ��\ȥ���������ڰ������κ������ַ��ĺ��壬ʹ��Ϊһ����ͨ�ַ�.
3.4	
���磺

>echo ��*��		#���*�ַ�

>echo ��`date`��	#���`date`

>echo ��$PATH��	#���$PATH

>echo ��a\na��		#���Ϊ2�У�һ��һ��a����ʱ\Ϊ�����ַ�



3.5	 \����ȥ��& * + ^ $ ` " | ?�����⺬�壬\��������⺬�������\ȥ��������\\����һ��\������ͨ�ַ�
3.6	
�磺

>echo \*			#���*



4��׼���������

��������shell��ִ�������ʱ��ÿ�����̶��������򿪵��ļ�����ϵ����ʹ���ļ���������������Щ�ļ��������ļ������������׼��䣬 shellͬʱҲ��������Ӧ���ļ��������������Щ�ļ�������������ͨ������Ӧ���ļ�����

�ļ��ļ�������

�����ļ�����׼����0

����ļ�����׼���1

��������ļ�����׼����2

ϵͳ��ʵ������1 2���ļ������������������������ϱ����������ģ� 0��1��2�Ǳ�׼���롢����ʹ���



command > filename �Ѱѱ�׼����ض���һ�����ļ���

command >> filename �Ѱѱ�׼����ض���һ���ļ���(׷��)

command 1 > fielname �Ѱѱ�׼����ض���һ���ļ���

command > filename 2>&1 �Ѱѱ�׼����ͱ�׼����һ���ض���һ���ļ���

command 2 > filename �Ѱѱ�׼�����ض���һ���ļ���

command 2 >> filename �Ѱѱ�׼����ض���һ���ļ���(׷��)

command >> filename 2>&1 �Ѱѱ�׼����ͱ�׼����һ���ض���һ���ļ���(׷��)

command < filename >filename2 ��command������filename�ļ���Ϊ��׼���룬��filename2�ļ���Ϊ��׼���

command < filename ��c o m m a n d������f i l e n a m e�ļ���Ϊ��׼����

command << delimiter �Ѵӱ�׼�����ж��룬ֱ������d e l i m i t e r�ֽ��

command <&m �Ѱ��ļ�������m��Ϊ��׼����

command >&m �Ѱѱ�׼����ض����ļ�������m��

command <&- �ѹرձ�׼����



���糣��dbaccessִ��һ��SQL����

>dbaccess $TELLIN_DBNAME <<EOF >$errorfile 2>&1

delete from basetab_pps where msisdn=��13000000000��

EOF



5���¶���

���붨�򣺿��Դ��ļ����߱�׼�����豸�õ�����

<

�������

>	#���������Ļ��������ļ�

>>  #���������Ļ��������ļ�������Append��ʽ

�ܵ�����

| 	#��һ������������������һ������������ĳЩ���֧��ֱ��|����

�磺��һ��SQL�����dbaccessִ��

>echo ��update basetab_pps set multiserviceflag=��00000000000�� where msisdn=��13501300000��|dbaccess $TELLIN_DBNAME

>ps �Cef |grep ��manager�� |grep �Cv ��grep�� | wc �Cl   #��ιܵ�����



�õ������ֵ�������������

var=`command`

�磺

>echo Time=`date "+%y-%m-%d %H:%M:%S"`		#���Time=02-09-17 18:30:06



6�����������

6.1 ˳��

6.2 �������if-then-fi

if  condition 

then

   ...

fi



���Ǿ���ʹ�õ���д��ʽ��ʹ��;���ţ���һ���а����������������

if  condition  ��then

   ...

fi



6.3 �������if-then-else-fi

If  condition 

then

   ...

else

   ...

fi

        

if condition1

then

   ...

elif condition2

then

   ...

else

   ...

fi

      

6.4 while����ѭ��

while express

do

   ...

done 

#��ѭ�����˳�ʹ�� break��continue����

      

6.5 forѭ��

for var in arg1 arg2 ... argn

do 

  ...

done

#��ѭ�����˳�ʹ�� break��continue����



6.6 untilѭ��

until express

do

...



done

#��ѭ�����˳�ʹ�� break��continue����

      

6.7 caseѡ�����

case var in

var1) 

    ...

    ;;

var2|var3) 

    ...

    ;;

*)

    ;;

esac

             

����������ѡ��˵���������case�����ģ�

while true

do

     #ִ��

     echo ""

     if [ "-${OprChc}" = "-1" ]; then

               Backup   #����

     elif [ "-${OprChc}" = "-2" ]; then

               Upgrade  #����

     elif [ "-${OprChc}" = "-3" ]; then

               Rollback #�ع�       

     elif [ "-${OprChc}" = "-0" ]; then

               Log "Goodbye!"

               Log ""

               break        

     else

               echo "Invalid input , please input again!"

     fi

            

      echo ""

      PrintUsage  

      read OprChc

done  



6.8 selectѡ�����(ksh֧��)

selectѡ�����һ����case�������ʹ�ã��û������û������˵����﷨Ϊ��

select var in value1 value2 value3 �� valuen

do

   ��

done

selectִ��ʱ�����value������һ���б�����ÿһ��֮ǰ��һ����1��ʼ���������֡��û�ѡ��ĳ�����֣��൱��ѡ��value��Ӧ���ֵ��var�������磺

1)	value1
2)	
3)	value2
4)	
5)	value3
6)	
��

n)	valuen
o)	
#?



һ��do done֮��ʹ��case��䡣�﷨��չΪ��

select var in value1 value2 value3 �� valuen

do

   case $var in

      value1)

         ��

         ;;

      value2)

         ��

         ;;

      value3)

         ��

         ;;

      ��

      valuen)

         ��

         ;;

      *)

   esac

done



7 �Ƚϲ���

�Ƚϲ���һ�����������ж��У������﷨ʹ�������ж�Ϊ����

7.1 �ַ����Ƚ�

1���ַ�����ȱȽ�

if [ $str = ��value�� ]; then        #ע��Ⱥ����߱Ƚ��пո񣬷���Ϊ��ֵ����

��

fi



2���ַ����Ƿ�Ϊ��

if [ ��-$str�� = ��-�� ]; then         #-û���κκ��壬ֻ��Ϊ�����ӿɶ���

��

fi



if [ ��X$str�� = ��X�� ]; then         #Xû���κκ��壬ֻ��Ϊ�����ӿɶ���

��

fi



3���ַ�������ȱȽ�

if [ $str != ��value�� ]; then       #ע��Ⱥ����߱Ƚ��пո񣬷���Ϊ��ֵ����

��

fi



if [ ! $str = ��value�� ]; then      #��Ϊnot�ĺ��壬��ȡ��

��

fi



7.2 ���ֱȽ�

1�����ڡ����ڵ���

if [ $str -gt 100 ]; then        #-gt��ʾ����

��

fi



if [ $str -ge 100 ]; then        #-ge��ʾ���ڵ���

��

fi



2��С�ڡ�С�ڵ���

if [ $str -lt 100 ]; then        #-lt��ʾС��

��

fi



if [ $str -le 100 ]; then        #-le��ʾС�ڵ���

��

fi



2�����ڡ�������

if [ $str �Ceq 100 ]; then        #-eq��ʾ����

��

fi



if [ $str -ne 100 ]; then        #-ne��ʾ������

��

fi



if [ ! $str -eq 100 ]; then        #!��ʾȡ��-eq��ʾ����

��

fi



7.3 �ж���������

1����/and����Ҫ����ʽ1����ʽ2ͬʱΪ��

if express1 && express 2 ;           #&&��ʾ��/and���� -a

then

��

fi



if [ str1 = ��aa�� ] && [ str2 = ��bb�� ] ;     

then

��

fi





2����/or����Ҫ����ʽ1���߱��ʽ2֮һΪ��

if express1 || express 2 ;             #||��ʾ��/or���� -o

then

��

fi



if [ str1 = ��aa�� ] || [ str2 = ��bb�� ] ;     

then

��

fi



3��ȡ����

if ! express1 ;                    #����ʾȥ��

then

��

fi



if [ ! $? �Ceq 0 ]; 

then

��

fi





8 SHELL����



���Խ�SHELL����Ҫ�ظ�ִ�еĴ���д�ɺ�������C��̵ĺ���һ�¡�

8.1 ������ʽ

���庯���ĸ�ʽΪ��

����������

{

   ...

}

����

����������{

   ...

}

���߷�ʽ�����С����Ը�⣬���ں�����ǰ���Ϲؼ���function���������ӡ�

function ����������

{

 ...

}



8.2 �����������

�������Դ��������ã����÷�ʽΪ

��������  �����б�



����ȡ�ô���Ĳ�������SHELL�õ����õĲ�����ȫһ�£�

�жϲ���������

$#

ȡ������

$1  $2 ��



8.3	 �������ز���
8.4	
��������ʹ��return ���ص��ò�һ��ֵ�������߿����ڵ��ú�����õ������ķ���ֵ��

$?�õ�,�磺

#���ø�ʽ��aaa  parameter

aaa()

{

   return 1

}



#�����÷�

a=`aaa para`   #�޷��õ�����ֵ1



#��ȷ�÷�

aaa para

ret=$?



���ʹ��exit�����˳�SHELL����



8.5	 �����ú���д�ɿ⺯��
8.6	
Ϊ���ظ����ô��룬���Խ�����д�ɿ⺯���ķ�ʽ��Ȼ����SHELL�а������м���ʹ�ã�

. libraryfile



9���������﷨

9.1 �������ӷ�

and�� 

�����У�command1 && command2   #���command1ִ�гɹ���ִ��commnad2

�磺rm * && echo "File successfully removed"

(���鲻Ҫʹ�������﷨����Ϊ�﷨�����ã��ɶ��Բ�ǿ)

���ʽ��express1 && express2

�磺if [ $1 -eq 1 ] && [ $1 -eq 1 ]

    then

       ...

    fi



or��

�����У�command1 || command2    #����ǰһ������ִ�г���ʱ��ִ�к�һ������

�磺rm * || echo "File removed failed"

(���鲻Ҫʹ�������﷨����Ϊ�﷨�����ã��ɶ��Բ�ǿ)

���ʽ��express1 || express2

�磺if [ $1 -eq 1 ] || [ $1 -eq 1 ]

    then

       ...

    fi



9.2 �����⺯��

#. �ո�֮���ļ���·���� һ����ڳ������ʼ����

. ./comm_func.sh.rc



9.3 �źŴ���

trap "echo ___ $0 interrupted ___; exit 1" 2



9.4 �ָ��

SHELLĬ�ϵķָ��IFSΪ�ո���TAB���������п���ʹ�ö��Ƶķָ��

�磺��dbaccess��������û��ָ��delimiterʱ���ֶηָ�Ϊ��|��

OLD_IFS=$IFS

IFS=��|��

Read col1 col2 col3 < datafile

��

IFS=$OLD_IFS



9.5�ն˵�һЩ֪ʶ

1�� ʹ�ַ���ʾ��ʽ�������߷�ת��ʾ

echo ��\033[m\c��    #������ʾ

echo ��\033[7m\c��   #��ת��ʾ



2������ͼ��ģʽ�����ַ�ģʽ

echo ��\033(B\c��    #�ַ�ģʽ

echo ��\033(0\c��    #ͼ��ģʽ



3�����ն˵õ�һ���ַ�

TTY=`tty`

$1='`dd if=$TTY bs=1 count=1 2>/dev/null`'



4����λ���λ��

echo "\033[$1;$2H\c"   #����$1��ʾ�У�$2��ʾ��



5) �����ն˲���

stty�������������������ն����ԣ��磺�ն�������֮��Ĵ����ʡ��˸��жϵȡ�

echo[-echo]   	�Ƿ����

intr				�����ж��źţ�Ĭ��ʹ��del��������

erase			�˸����������ǰ��һ���ַ�

##��3�����ø������������

1�ļ�

1.1 �ļ����ͣ�ls �Cal �е�һ�еĵ�һ���ַ���

drwxr-xr-x  12 smp20      sms           1024 Aug 13 15:36 .dt

d Ŀ¼��

l ��������(ָ����һ���ļ�)��

s �׽����ļ���

b ���豸�ļ�������informix�����Ĵ洢�ļ�Ϊ���豸

c �ַ��豸�ļ�������/dev/null���豸

p �����ܵ��ļ���������ͨ��ʹ�õ�PIPE�ļ�

- ��ͨ�ļ������߸�׼ȷ��˵�����������ϼ������͵��ļ�



1.2 �ļ�Ȩ�ޣ�ls �Cal �е�һ�еĵ�2-10���ַ�

(2-4�ַ�)	�ļ�������Ȩ��

(5-7�ַ�) 	ͬ���û���Ȩ��

(8-10�ַ�) 	�����û���Ȩ��



1.3 �ı�Ȩ��λ

chmod�����һ���ʽΪ��

chmod [who] operator [permission] filename

who�ĺ����ǣ�

u �ļ�����Ȩ�ޡ�

g ͬ���û�Ȩ�ޡ�

o �����û�Ȩ�ޡ�

a �����û�(�ļ�������ͬ���û��������û�)��

operator�ĺ��壺

+ ����Ȩ�ޡ�

- ȡ��Ȩ�ޡ�

= �趨Ȩ�ޡ�

permission�ĺ��壺

r ��Ȩ�ޡ�

w дȨ�ޡ�

x ִ��Ȩ�ޡ�

s �ļ���������set-ID��

t ճ��λ*��

l ���ļ�������ʹ�����û��޷����ʡ�

���ߣ�

chmod Ȩ��ֵ filename

�ļ�����		ͬ���û�		�����û�

rwx			rwx			rwx

4+2+1 		4+2+1 		4+2+1



1.4 Ŀ¼Ȩ��λ

Ŀ¼�Ķ�Ȩ��λ��ζ�ſ����г����е����ݡ�дȨ��λ��ζ�ſ����ڸ�Ŀ¼�д����ļ��������ϣ�������û������Ŀ¼�д����ļ�������ȡ����Ӧ��дȨ��λ��ִ��Ȩ��λ����ζ�������ͷ��ʸ�Ŀ¼



1.5 �ı��ļ�������

chown�����һ����ʽΪ��

chown -R -h owner file

-	Rѡ����ζ�Ŷ�������Ŀ¼�µ��ļ�Ҳ������ͬ���Ĳ�����- hѡ����ζ���ڸı���������ļ�������ʱ��Ӱ���������ָ���Ŀ���ļ���һ�����ļ�������Ȩ��������һ���û������޷��������ջ���������Ȩ
-	


1.6 umask

umask����ȷ�����㴴���ļ���ȱʡģʽ����һ����ʵ���Ϻ�chmod���������෴

umask��������/etc/profile�ļ������õģ�ÿ���û��ڵ�¼ʱ������������ļ����������ϣ���ı������û���umask�������ڸ��ļ��м�����Ӧ����Ŀ�����ϣ�������Ե������Լ���umaskֵ����ô�Ͱ��������Լ�$HOMEĿ¼�µ�. profile��.bash_profile�ļ��С�

����SMP����SCP�����Ƕ�����.cshrc�У�������½����Ч���磺umask 002�������������ļ���Ȩ��Ϊ777-002=775



1.7 �ж��ļ�ĳЩ����

-r file   #�Ƿ���ڲ��ҿɶ�

-w file   #�Ƿ���ڲ��ҿ�д

-s file   #�Ƿ���ڲ����ļ���С����0

-f file   #�Ƿ���ڲ����ǹ����ļ�

-d file   #�Ƿ���ڲ���ΪĿ¼

-x file   #�Ƿ���ڲ��ҿ���ִ��

-p file   #�Ƿ���ڲ���Ϊ�ܵ��ļ�



1.8 �ļ���¼ѭ������

ʹ��whileѭ����ȡ�ļ���¼���д��������ļ�������� < �������ѭ�����ʽΪread����﷨���£�

while read var1 var2 ��

do

    #�������

done < filename



���У�

1һ�ζ�ȡһ�����ݡ�

2 ���Խ��ļ���һ�������Կո����TAB���񿪵����ֶΣ����ݶ�������������������С�����ֶΣ���������ǰ�沿��һһ��Ӧ�����ʣ������������ݶ������һ�����������磺

�У�AAA BBB CCC

while read var1 var2 

do

done

��var1=��AAA��, var2=��BBB CCC��

2	�����ʹ�������ַ�������ֶΣ��������޸�IFS�õ������磺�޸�Ϊ|
3	
OLD_IFS=$IFS

IFS=|

while read var1 var2..

do 

done



#�ָ�IFSԭ����

IFS=$OLD_IFS





2��ֵ����

����ʹ��:expr����bc���KSH����ʹ��let

ʹ�� expr Ӧ�ó���

2.1	expr
2.2	
n1=3

n2=5

n=`expr $n1 + $n2 `  

ע�⣺+�Ȳ�����2����Ҫʹ�ÿո��



�磺

>expr 10000 + 1111    #���

>expr 10000 \* 1111   #���



ksh �п�ʹ�� let

n1=3

n2=5

let n=n1+n2



2.2 bc

ʹ��bc���Լ������ⳤ�ȵļ��㣬�������

>echo "1000000000000000000000000000000*1111" | bc

111100000000000000000000000000000



2.3 ����ת��

��ʹ��printf����ת��

���磺16 to 10

     ʮ��������ǰ�ӡ�0x"

     test1=`printf "%d" 0x9d83000`



 ���磺10 to 16

     test2=`printf "%x" 83000



3�ϲ���ָ�

���õĺϲ���ָ������У�

? sort

? cut

? split



3.1	 sort����
3.2	
sort -cmur -o ����ļ� �Ct �ָ�� +n �����ļ�

�����Ҫ����һ��s o r t�Ĳ�����

-c �����ļ��Ƿ��Ѿ����ࡣ

-m �ϲ����������ļ���

-u ɾ�����и����С�

-r ��������DESC��Ĭ��Ϊ����ASC



�磺��basetab_pps�ļ�����4���ֶ���������

sort �Ct\| -r +3 basetab_pps.unl > basetab_pps.unl.sort

ע�⣺����ʹ��-t|����Ϊ|��SHELL�����ڹܵ����ţ���Ҫʹ��\|



3.3	 cut�и�
3.4	
cut�����ӱ�׼������ı��ļ��м����л��򡣼����ı����Խ�֮ճ����һ���ı��ļ���

��һ�ڽ�����ճ���÷���

cutһ���ʽΪ��

cut [options] file1 file2

������������ѡ�

-c list ָ�������ַ�����

-f field ָ������������

-d ָ����ո��tab����ͬ����ָ�����

-c����ָ�����з�Χ��������ʾ��

-c1��5-7 ���е�1���ַ���Ȼ���ǵ�5����7���ַ���

-c1-50 ����ǰ50���ַ���

-f ��ʽ��-c��ͬ��

-f1��5 ���е�1�򣬵�5��

-f1��10-12 ���е�1�򣬵�1 0�򵽵�1 2��



�磺���ַ����С�aaabb:aaaaa:bbb������aaaaa���и����

>echo ��aaabb:aaaaa:bbb�� | cut �Cd ��:�� �Cf2



3.5	 split
3.6	
split���������ļ��ָ��С�ļ�����ʱ�ļ�Խ��Խ�󣬴�����Щ�ļ�ʱ�����Ƚ���ָ���ܸ����ס�ʹ��vi��������������sortʱ������ļ����ڹ���������̫��Ҳ�����һЩ���⡣�����ʱû��ѡ����أ����뽫�ļ��ָ��С����Ƭ��

Split����һ���ʽ��

split �Coutput-file-line input-filename output-filename

����output-file-sizeָ�����ı��ļ����ָ��������Split�鿴�ļ�ʱ��output-file-lineѡ��

ָ�����ļ���ÿ�����1000�зָ����и��ļ���2800�У���ô���ָ��3���ļ����ֱ���1000��1000��800�С�ÿ���ļ���ʽΪx[aa]��x[zz]��xΪ�ļ�������ĸ�� [aa]��[zz]Ϊ�ļ���ʣ�ಿ��˳���ַ���ϣ�



4ƥ����߹��˲���

4.1 grep��ʹ��

grep���Դ�������ַ��У�����ĳЩ���߹��˵�ĳ���ض��ַ������

һ��ʹ��Ϊ��

grep �������ַ�����  inputFile

grep �Cv �������ַ�����  inputFile



4.2  awk�����ʹ��

awk�ǿ���ʹ�úܸ��ӣ����������ĳЩ�ض����ܣ����ҳ�ʹ�õ�һ�����ʹ���÷���

awk [�CF �ָ���] ��ģʽ�� inputfile

-F����ָ���������֮��ķָ���������ָ����ʹ��Ĭ�ϵķָ�����ո����TAB����������ڷָ�unload�������ص��ļ��� ����ָ�� �CF |

����ģʽ�е�ʹ�÷ָ���ָ����򣬱��$1��$2 . . . $n��$0��ʶ���е���

Ϊ��ӡһ�����������ʹ��p r i n t����

�����ӡ��ǰĿ¼�������ļ��Ĵ�С����:

>ls �Cal | awk ��{ print $5, $9}��   #��С���ļ�����ʹ�ÿո�񿪣���$5,$9ʹ�ÿո�����

>ls �Cal | awk ��{ print $5��|��$9}��  #��С���ļ�����ʹ��|��,��$5,$9ʹ��|����

ʹ��BEGINģʽ��ӡͷ����Ϣ��

>ls �Cal | awk ��BEGIN {print ��size  filename��} { print $5��\t��$9}��  #�൱�ڴ�ӡ�еı���

ʹ��ENDģʽ��ӡβ����Ϣ��

>ls �Cal | awk ��{print $5��\t��$9} END{print ��finished��}��  #���г��ļ��󣬼���finished�ַ�



awk��ʹ��������ʽ

awk��������ʽƥ������õ����ַ��У�

\ ^ $ . [] | () * + ?

�÷���

awk [-F �ָ��] ��{if (express) ����}��

��ָ��������express���ʽ���У��Ŵ�ӡ����.

���ӡĿ¼�ļ��а���sms���ļ���

>ls �Cal | awk ��{if ( $9~/sms/) print $0}��

���ӡĿ¼�ļ���С����100000�ֽڵ��ļ���

>ls �Cal | awk ��{if ( $5>100000) print $0}��



awk�л��кܶ��÷����ڴ˲��г���



4.3 sed����



5�źŴ���

�źž���ϵͳ��ű������������Ϣ����֪����ĳ���¼��ķ�������Щ�¼�ͨ�����ڴ���󣬷���Ȩ�������ĳ���û���ͼֹͣ��Ľ��̡��ź�ʵ������һЩ���֡��±��г�����õ��źż����ǵĺ����г������źţ�

>kill �Cl

HUP INT QUIT ILL TRAP IOT EMT FPE KILL BUS SEGV SYS PIPE ALRM TERM USR1

USR2 CLD PWR VTALRM PROF IO WINCH STOP TSTP CONT TTIN TTOU



һЩ�źŵĺ��壺

1 SIGHUP 	����򸸽��̱�ɱ��

2 SIGINT 	���Լ��̵��ж��źţ�ͨ����< C T R L - C >

3 SIGQUIT 	�Ӽ����˳�

9 SIGKILL 	��������ֹ

11 SIGSEGV 	�Σ��ڴ棩��ͻ

15 SIGTERM 	�����ֹ��ȱʡɱ�����źţ�



5.1 �����źţ�

kill �C�ź�  ���̺�

ע����kill �C9 ���̺�  ɱ������ʱ������ϵͳֱ�ӽ����̴��ں�����������˳��Ĵ���



5.2 ����źŻ��߲�׽�ź�

��Щ�źſ��Ա�Ӧ�ó����ű����񣬲����ݸ��źŲ�ȡ��Ӧ���ж�������һЩ�źŲ�

�ܱ��������磬���һ�������յ����ź�9�����޷��ٲ�׽�����źš�

���ű���׽��һ���źź������ܻ��ȡ�������ֲ���֮һ��

1) ����ȡ�κ��ж�����ϵͳ�����д���

2) ������źţ�����������

3) ������źţ�����ȡ��Ӧ���ж�



�����Ҫ��׽�źź󣬲����Զ���Ĳ���������ʹ��trap���

trap name signal(s)

���У�name�ǲ�׽���ź��Ժ�����ȡ��һϵ�в�����ʵ�������У� nameһ����һ��ר��������������׽�źŵĺ�����Name��Ҫ��˫���ţ��� ������������Signal���Ǵ���׽���źš�

�±��г���һЩ�����trap�����÷���

trap "" 2 3 			�����ź�2���ź�3���û�������ֹ�ýű�

trap"commands" 2 3 	�����׽���ź�2��3����ִ����Ӧ��commands����

trap 2 3 			��λ�ź�2��3���û�������ֹ�ýű�



�磺�յ�3( SIGQUIT 	�Ӽ����˳�),��ӡһ�С�proc received SIGQUIT and exit��

#!/bin/ksh



trap ��fun_exit�� 3



fun_exit()

{

   echo ��proc received SIGQUIT and exit��

   exit 1

}



echo ��start running��



exit 0



6 eval����

eval��������ִ��֮������������߱���������ֵ���߱��ʽ�����磺

�÷�1��

eval echo ��aaa��

�÷�2��

command=env

eval $env

command=��echo aaa��

eval $command

�÷�3:

value=0

eval [ $? -gt $value ]&&j=1

eval [ $? -gt $value ]&& echo ��successfully��

eval var=$#

eval������ִ�г������й����и�ֵ����ı����ǳ����á�������SHELL���Ƶ��˻����������У�ѡ��ĳ���˵����ִ��û��������ߺ������ű���������Ϊÿ���˵���caseһ�顣



##��4������

4.1 ʹ�ò�ͬ�Ŀ�ִ�������ļ�

1) ���Script�ĵ�һ���ǿհ���Ԫ����"#"��������ʹ��Bourne Shell�� 

2) ���Script�ĵ�һ���ǿհ���Ԫ��"#"ʱ��������"#!"��ͷʱ��������ʹ��C Shell�� 

3) ���Script��"#!"��ͷ����"#!"������д�ľ�����ʹ�õ�Shell������Ҫ������·������ָ���������ｨ��ʹ�õ����ַ�ʽָ��Shell ����ȷ����ִ�еľ�����Ҫ�ġ�Bourne Shell��·������Ϊ/bin/sh ����C Shell ��Ϊ/bin/csh�� ����һ��ʹ��ksh�� ·��Ϊ/bin/ksh



4.2 ʹ�ò�ͬSHELL������

  BSH: 

      ���û�������ʹ��export var=var_value; var=var_valu; export var

  CSH/KSH:

      ���û�������ʹ��setenv var var_value



һЩKSH���е�������

1)KSH��������

HISTSIZE:��ʷ����������Ĭ��Ϊ128,������.chsrc�н�������Ϊ����ֵ

TMOUT   :��ʱ�Զ��˳�������һ��ʱ��û�м������ǿ���˳�    

1)	����
2)	
���Զ����Լ��ı�ʶ����ʶ�����������磺

alias dba dbaccess $TELLIN_DBNAME

3)	֧���������
4)	


4.3 SHELL����ķ���ֵ���ܳ���255�����򷵻�ֵ����ȷ��

  

4.4  read�������Ķ����part�����һ������

>read var1 var2

aa bb cc

>echo $var1

aa

>echo $var2

bb cc



4.5 ����

ʹ��-x

1) ��SHELL����ָ��ִ��Ϊ����ģʽ

#!/bin/sh �Cx



2) ����������ָ������ģʽִ��

ָ��SHELL �Cx �������ƣ��磺

sh �Cx update_iuser214.sh



4.6 ִ��SHELL

ǰִ̨�У�

>sh ��������

>��������

��ִ̨�У�

>sh ��������  &

>��������     &



4.7 ��ֲ��

Ŀǰ����ҵ�񲿵��豸ѡ���У�С�ͻ���IBM/HP/SUN 3����ѡ����Ӧ���ǵ�SHELLһ����Ҫ��AIX,HP-UX,SunOS��Ӧ������һ�¡���SHELL����һ����Ҫ��3�в���ϵͳ�Ͻ�����ֲ��

����ʹ��uname �Csȷ�������Ĳ���ϵͳ�����磺

#��������

OsType=`uname -s`

if [ "-$OsType" = "-SunOS" ]; then

    ��

elif [ "-$OsType" = "-HP-UX" ]; then

    ��

elif [ "-$OsType" = "-AIX" ]; then

    ��

else

   echo "ERROR: system not support this machine type $OsType"

   eixt 1

fi



�󲿷ֳ�����UNIX����������3�в�����һ�µģ�����ĳЩ��������в���(��ftp��ls��HP-UXΪnlist)��������������ϵͳ��صĵط�������Ҫ���ݲ���ϵͳ����Ӧ����





��¼��

һ��SHELL���Ƶ��˻��������棬����ʹ�õ�SHELL�﷨�Ƚ����롣����ܶ������߱���ͬ��������������SHELL�̱������Ѿ��㹻���������ܶ�����������սһ���Լ���

# Linux�´��ѹ��war�ͽ�ѹwar��

�ѵ�ǰĿ¼�µ������ļ������game.war

jar -cvfM0 game.war ./

-c   ����war��

-v   ��ʾ������Ϣ

-f    

-M

-0   ����ǰ��������֣�ֻ�����ѹ������˼





��ѹgame.war����ǰĿ¼

jar -xvf game.war



# Ubuntu����ֱ�ӽ������̨

ֻ��༭�ļ�`/etc/default/grub`���� `GRUB_CMDLINE_LINUX_DEFAULT=��quiet splash��`�ĳ�`GRUB_CMDLINE_LINUX_DEFAULT=��quiet splash text��`��Ȼ��������`sudo update-grub`���ɡ�

�ڿ���̨�������x-window��������root�û������룺`gdm`����`startx`

�޸�UbuntuĬ�����������ı�ģʽ������������ͣ��Checking battery state���⡣û��ϵ��ʵ��ϵͳ�Ѿ����������� ALT+F1 ���ɽ��������û�����¼���ַ���ʾ���档


