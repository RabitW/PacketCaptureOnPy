# PacketCaptureOnPy
packet capture with Python on Windows, analyse

ProjectJournal
---
#### data struct of the decoded pcap info
1. time	datetime
2. ip	string
3. srcip string
4. dstip string
5. trans_layer_type string
6. ttl int 			;�������ݰ���������������ɾ�����·����                
7. len int
8. src_mac string
9. dst_mac string
10.pcap_id

****
2016-10-06

#### ���ݷ���ά��
1. ʱ�䣺���������ĸ�������һ���ʮ��Сʱ�ϵķֲ�����һ��ʱ���ϵķֲ�
2. �ռ䣺ip ��ַ����
3. ���ݣ��ı���ͼƬ����վ��������


#### database in mysql
> CREATE DATABASE pcap DEFAULT CHARACTER SET utf8 COLLATE utf8_general_ci;

"�����ŵ����ݿ������ˣ��ټ�������ȥ�ˡ�"
****