# cobaltstrikebrute
cobalt strike服务端批量爆破

单个ip爆破：

 
https://github.com/ryanohoro/csbruter

例如
python3 csbruter.py -p 50050  ip wordlist.txt
//可指定密码字典，可以检测得比较全面


针对多个CS服务端进行批量弱口令爆破:

ip.txt放置需要爆破的资产

python3 cobaltstrikebrute.py
//主要是修改了批量爆破的功能
