# 1.�޲z�s�զ@�θ�ƪ��v���]�p:
* �إ߸s�զW�٬��G mygroup, nogroup
![](https://i.imgur.com/WtiVbbh.png)
* �إ߱b���W�٬��G myuser1, myuser2, myuser3 �A�q�q�[�J mygroup�A�B�K�X�� MyPassWord
* �إ߱b���W�٬��G nouser1, nouser2, nouser3 �A�q�q�[�J nogroup�A�B�K�X�� MyPassWord
![](https://i.imgur.com/krsLKWB.png)
![](https://i.imgur.com/jNcXgYL.png)
�]���W�����O�����ɭP�S���\�[�J�s��,�ҥH�o�̥�usermod�B�z
![](https://i.imgur.com/iMJnfiZ.png)
* �إߤ@�ӦW�� /srv/myproject ���ؿ��A�o�ӥؿ��i�H�� mygroup �s�դ����ϥΪ̧���ϥΡA�B�i�s�ت��ɮ׾֦��s�աj�� mygroup �C���L��L�H���঳�����v��
![](https://i.imgur.com/IIJLDLp.png)
* �Ȯɤ������� myuser1 �������A�ëe�� /srv/myproject �ؿ��A���իإߤ@�ӦW�� myuser1.data ���ɮסA����n�X myuser1�C
![](https://i.imgur.com/vKZiWRS.png)
* �_��/usr/bin/ls��/usr/local/bin/myls
![](https://i.imgur.com/nx6gVMu.png)
![](https://i.imgur.com/V5zIz41.png)
# 2.�ϥε{���[����O�A�f�t grep ������r�d�ߥ\��A�N��쪺 rsyslog �������{�Ǫ� PID, PRI, NI, COMMAND ����T��s�� /root/pr![](https://i.imgur.com/HgjDUTu.png)
�Ϥ��i��� rsyslog��PID,PRI,NI,COMMAND
# 3.�ϥ� find ��X /usr/bin �� /usr/sbin ��ӥؿ����A�t�� SUID ���S���ɮ��ɦW�A�èϥ� ls -l �h�C�X��쪺�ɮת������v����A�N�ù������s�� /root/findsuidsgid.txt �ɮפ��C(�ۦ�d��find���O�Ϊk�A�H�Ψϳz�L���ɦV�Ÿ�>��X�ɮ�)
* �ϥ� find ��X /usr/bin �� /usr/sbin ��ӥؿ����A�t�� SUID ���S���ɮ��ɦW
![](https://i.imgur.com/5nVsMjG.png)
* �ϥ� ls -l �h�C�X��쪺�ɮת������v����A�N�ù������s�� /root/findsuidsgid.txt �ɮפ�
![](https://i.imgur.com/w417wYd.png)