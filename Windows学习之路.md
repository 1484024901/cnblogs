# �����Ҽ���ġ����͵���

xp���ڡ�C:\Documents and Settings\Administrator\SendTo���£�win7λ��������ͬ����Ȼ����Щ�ļ��п϶���Ĭ�����صģ�����㿴�������������Ƚ��ļ���ѡ����ʾ�����ļ����ļ��С���ֻ�����ˣ��������ݷ�ʽ��һ��������ɱ֮��

# ���޸�Ȩ�ޣ��޸�hosts��service�ļ�

win7���û�Ȩ�޹���Ƚ��ϸ�Ĭ������������޷�ֱ���޸�hosts��service�������ļ�����ʾ��Ȩ�ޡ������кܶ�̳̣�������λ�ȡ����Ա���ļ�Ȩ�ޣ������ֻ�����޸������������ļ������ö���ô��ĸɸ꣬һ��СС�Ķ������С�����hosts��service�ļ�ϵͳ�ļ���֮��������ط�������༭���޸�-�����棬��paste��ȥ���ǵ�ϵͳͬ���ļ���done.



# Windows/system32Ȩ������

����Ȩ�����⣬�޷��޸����е��ļ��������Ҽ�ȡ�ù���ԱȨ�ޡ�

# Windows 8���ɾ������

���ڵ���å�����Խ��Խ����Լ�ע��Ϊһ�����񡣶�����Щ��å�������Ҫɾ����ص�exe�ļ���ʹ�����������У�����ֱ��������������ʹ�����������ʱ����������������ɾ���İ취��������

1.��sc.exe���Windows�����ʼ--����--cmd.exe,Ȼ������sc�Ϳ��Կ����ˡ�ʹ�ð취�ܼ򵥣�sc delete "������" (����������м��пո񣬾���Ҫǰ�������)���� sc delete KSD2Service

2.ֱ�ӽ���ע���༭(���Ƽ�)����ע���༭�����ҵ�����ļ�ֵ��

    HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services 

һ����������ͬ��������������ʾһ��������ֱ��ɾ����صļ�ֵ��ɡ�

ע��

1.���������ʾ����rundll32.exe,��������ļ���λ��system32Ŀ¼�£���ô�Ͳ���ɾ�����rundll32.exe�ļ�������Windowsϵͳ���ļ�����ʱֻҪ�����صķ���Ϳ�����

2.���һ������ɾ�����������Զ������ˣ�˵����̨�н����ڼ��ӡ���������Ҫ���ڽ��̹�������ɱ����Ӧ�Ľ��̣�����������F8,����ȫģʽ��ɾ����

# ��windows����Դ��������ǰ·����һ��������

��ݼ�Alt+Dѡ�е�ַ����Ȼ��ֱ����cmd

ע���㻹������Դ�������ĵ�ַ�������������򣬱���д�ְ�(notepad)��

���ߣ�Shift���Ҽ���ѡ���ڴ˴��������


# Powershell�������

* ͬʱ�򿪶��powershell���ڣ�Win+R+powershell ��μ���
* �鿴powershell������� help [cmd]��help Remove-Item
* ɾ���ļ��У�Remove-Item path �CRecurse �CForse


# ��θı�PowerShell������Ĭ��Ŀ¼ 

ΪʲôҪ�޸�PowerShellĬ�ϵ�����Ŀ¼, �����ϰ�߲���һЩ����������г���, ���ֲ�ϰ�߰����Ƿ���Ĭ�ϵ�home·����, �޸�Ĭ�ϵ�����λ��, ����������ÿ������Powershell��ʱ����ִ���л�Ŀ¼�Ĳ���.

PowerShell��Ĭ������·����ʵ����ִ��PowerShellʱָ����Ĭ�Ϲ���Ŀ¼. ����Ա༭PowerShell�Ŀ�ݷ�ʽ, ������λ��������һ����ϣ����Ĭ��λ��. ������ִ��PowerShellʱ, ��Ĭ�ϵ�����·�������µ�λ����.

�����������, �㻹����ͨ���޸��ض���profile��ʵ���������, �򵥵���profile�м���cd XXX����.

���˵һ��$home�������, ���� HOMEPATH �� HOMEDRIVE��������������ϳɵ�. ���������������洢��ע�����.  �����������Ҳ��Ƽ��޸�, ��Ϊ��֪���������Щ������...�����������޸���Щ���������޸��û�����Ŀ¼λ��.



# Beyond Compare�Ա�.class�ļ�

ʹ��Beyond Compare��չ�������ֱ�ӶԱȱ����.class�ļ�����������ʾһ������롣

* windows��http://www.scootersoftware.com/download.php?zz=kb_moreformats_win
* linux��http://www.scootersoftware.com/download.php?zz=kb_moreformats_nix

# ���xshell��vim��ʾ�������������

��һ����utf8����������ļ�����vim�У�ִ��

```vimscript
    set encoding=utf-8 termencoding=gbk fileencoding=utf-8���������ʾ���Ŀ���
```

* encoding�����õ����ĵ�ǰ����
* termencoding������vim��Ļ����ʾ���룬����xshellĬ��������ʾ��Ļ�ı�����gbk,���Դ˴�����Ϊgbk��ͬ���������޸���xshell��Ĭ�ϱ���Ϊutf-8����ô�˴���ȻӦ��utf-8
* fileencoding��������ʱ�ı��룬�˱���Ӧ��encoding����һ�£�����ᵯ������

����xshell����file->Properties�����Terminal�ڵ㣬�޸�Terminal TypeΪlinux(����ӳ��ģʽ��Ĭ��Ϊxtrem������ģʽ�¶���vimС�����������ֻ�������ַ���)���޸�EncodingΪuft-8(һ�������linuxϵͳ���ô˱��룬����locale����鿴�Լ�ϵͳ��Ĭ�ϱ��룬�޸�Ϊһ�µľ���)��

ͬ��Ҳ�����޸�xftp�ı���Ϊutf-8��������ʾ���ġ�


# VirtualBox

## Windows 8.1+VirtualBox���°汾�������ʱ����

������Ϣ��
```
    Unable to load R3 module D:\Program Files\Oracle\VirtualBox/VBoxDD.dll
    (VBoxDD):GetLastError=1790
    (VERR_UNRESOLVED_ERROR)
```
����취����Windows/system32�£�

* themeui.dll.old.tweakcube�滻themeui.dll
* uxtheme.dll.old.tweakcube�滻uxtheme.dll

�����Windows 7�������������⣬�ο���
http://jingyan.baidu.com/article/ab69b270bb7b2a2ca6189f6d.html

