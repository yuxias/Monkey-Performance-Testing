# -*- coding: utf-8 -*-
# monkey ѹ������android 
* python3 
* ͳ��������Ϣcpu,men,fps,battery,flow
* ֧��wifi,gprsͳ��
* ͳ��crash��Ϣ
* ֧�ֶల׿�豸
 


## monkey.ini �����ļ�

``` 

cmd=monkey -p com.opera.olist --throttle 500 --ignore-timeouts --ignore-crashes   --monitor-native-crashes -v -v -v 500 >
package_name=com.opera.olist
activity = com.olist.main.ui.MainActivity
net = wifi  
```

- throttle ÿ���¼��ȴ�500����
- net ֧��gprs��wifi


![monkey���](img/analysis.PNG  "monkey���")

![monkey���](img/monitor.png  "monkey���")

![monkey���](img/crash.PNG  "monkey���")







