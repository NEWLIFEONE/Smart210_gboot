# Smart210_gboot

1.����������뻷��
	Step1:Linux Ŀ¼�е� arm-linux-gcc-4.5.1-v6-vfp-20101103.tgz ���Ƶ�linuxϵͳ��Ŀ¼���磬Ȼ����뵽��Ŀ¼/home/Smart210��ִ�н�ѹ����:
	#cd /home/Smart210
	#tar zxvpf arm-linux-gcc-4.5.1-v6-vfp-20120301.tgz -C /
	ע�⣺ C �����и��ո񣬲��� C �Ǵ�д�ģ�����Ӣ�ĵ��ʡ� Change���ĵ�һ����ĸ���ڴ��Ǹı�Ŀ¼����˼��
	ִ�и�������� arm-linux-gcc ��װ��/opt/FriendlyARM/toolschain/4.5.1 Ŀ¼��
	Step2:�ѱ�����·������ϵͳ������������������
	#gedit /root/.bashrc
	�༭ /root/.bashrc �ļ��� ע�⡰bashrc��ǰ����һ����.�����޸����һ��Ϊ
	export PATH=$PATH:/opt/FriendlyARM/toolschain/4.5.1/bin�� ע��·��һ��Ҫд�ԣ����򽫲�����Ч��

	



















	


