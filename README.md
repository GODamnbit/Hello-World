���л�����python 3.7

����������װ��
������л�����ĿĿ¼��ִ��pip install -r requirements.txt

��Ŀִ�У�
�����ִ��python app.py

�ӿڲ��ԣ�
��Ŀ���к�ʹ��postman���ԣ�
1. ��¼���ԣ�POST  127.0.0.1��5000/login
	header��json����ֵ��phone��password
	��ex��phone��123��password��123��

2. ע����ԣ�POST  127.0.0.1:5000/add
	header��json����ֵ��phone��user_name��(email)��password��(sex)
	��ex��phone��126��user_name��lala��password��w123��sex���У�
	ps�������ڲ�����Ϊ�գ�sex����/Ů

3. �������ԣ�POST  127.0.0.1��5000/station
	header��json����ֵ��station_id
	��ex��station_id��101��