# cobaltstrikebrute\ cobaltstrikebruter
批量爆破Cobalt Strike团队服务器

对于，
单个ip爆破：

https://github.com/ryanohoro/csbruter

例如
python3 csbruter.py -p 50050  ip wordlist.txt
//可指定密码字典，可以检测得比较全面


针对多个CS服务端进行批量弱口令爆破:

ip.txt放置需要爆破的资产，格式ip:50050

python3 cobaltstrikebrute.py
//在脚本中指定密码进行批量爆破

python3 cobaltstrikebruter.py
//调用同目录下的wordlist.txt进行批量爆破
