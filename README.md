linux-proxy-ipv6 centos

Link tai Putty: 
https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html

-----------

nhap ip vao putty

root 

nhap pass 

yum update -y

bash <(curl -s "https://raw.githubusercontent.com/tuanmjnh/linux-proxy-ipv6/main/install-centos9.sh")

bash <(curl -s "https://raw.githubusercontent.com/tuanmjnh/linux-proxy-ipv6/main/install-centos7.sh")

dien sl proxy muon tao -> enter

cop link de tai proxy ve

cop pass giai nen file proxy vua tai ve

ps aux | grep 3proxy
netstat -tuplan | grep 3proxy
