# kali_repo
Fix kali Reop not work in iran | youtube 

## replace this code with /etc/apt/sources.list all line code delete and paste this code :

```
# See https://www.kali.org/docs/general-use/kali-linux-sources-list-repositories/
#deb http://http.kali.org/kali kali-rolling main contrib non-free
#deb http://http.kali.org/kali kali-experimental main contrib non-free

# Additional line for source packages
# deb-src http://http.kali.org/kali kali-rolling main contrib non-free
# deb-src http://http.kali.org/kali kali-rolling main contrib non-free

deb http://ftp.halifax.rwth-aachen.de/kali/ kali-rolling main contrib non-free
deb http://ftp.halifax.rwth-aachen.de/kali/ kali-experimental main contrib non-free
deb-src http://ftp.halifax.rwth-aachen.de/kali/ kali-experimental main contrib non-free
deb-src http://ftp.halifax.rwth-aachen.de/kali/ kali-rolling main contrib non-free
deb http://ftp.halifax.rwth-aachen.de/kali/ kali-bleeding-edge main contrib non-free


```


اکمیدوارم مشکلتون حل شده باشه 
اگه سرور سریع تری برای ایران پیدا کردین ممنون میشم همینجا بزاریدش
