# 简介
本脚本为验证GeoServer 远程代码执行漏洞(CVE-2024-36401)
## 使用方法
在1.py中找到dnslog_domain,填入你控制的域名，在1.txt中导入目标，执行`python 1.py`
对照日志和execution_times.txt中的时间确认目标是否存在漏洞
