�������Ŀ¼�������п�ִ���ļ���Ҳִ����chmod ����
ȴ��ʾ�Ҳ����ļ�����No such file or directory��
��������Ϊ����32λ�ĳ�����64λ��Ubuntu��������Ҫ��ǰ��װ32λ�Ŀ⡣

�������i32�ܹ���Ȼ����¾���Դ���ٰ�װ�Ϳ����ˣ�ָ�����£�

`sudo dpkg --add-architecture i386`

`sudo apt-get update`

`sudo apt-get install libc6:i386 libncurses5:i386 libstdc++6:i386 -y`

`sudo apt install lib32z1 -y`
