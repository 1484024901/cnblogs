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

# ͬʱ�򿪶��powershell����

Win+R+powershell ��μ���


# Beyond Compare�Ա�.class�ļ�

ʹ��Beyond Compare��չ�������ֱ�ӶԱȱ����.class�ļ�����������ʾһ������롣

* windows��http://www.scootersoftware.com/download.php?zz=kb_moreformats_win
* linux��http://www.scootersoftware.com/download.php?zz=kb_moreformats_nix

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

