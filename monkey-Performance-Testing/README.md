# -*- coding: utf-8 -*-
# monkey-Performance-Testing
* python3 
* Statistical performance cpu,men,fps,battery,flow(wifi,gprs)
* Statistics crash info.
* muilt android
 


## monkey.ini setting

``` 

cmd=monkey -p com.opera.olist --throttle 500 --ignore-timeouts --ignore-crashes   --monitor-native-crashes -v -v -v 500 >
package_name=com.opera.olist
activity = com.olist.main.ui.MainActivity
net = wifi  
```

- throttle Each event waits for 500 milliseconds
- net gprs or wifi


![monkey���](img/analysis.jpg  "monkey���")

![monkey���](img/monitor.png  "monkey���")

![monkey���](img/crash.PNG  "monkey���")

# other
* [Chinese](Chinese.md)







