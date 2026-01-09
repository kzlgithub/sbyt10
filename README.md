
RealiTLScanner下载地址：https://github.com/XTLS/RealiTLScanner/releases
<br><br>
扫描命令：
```
RealiTLScanner-windows-64.exe -addr 服务器的IP地址 -port 443 -thread 100 -timeout 5 -out file.csv
```
<br><br>
更新以及安装解压工具：
```
apt update && apt install -y unzip
```
reality协议目标检测工具:
```
wget https://github.com/V2RaySSR/RealityChecker/releases/latest/download/reality-checker-linux-amd64.zip
```
解压zip文件并添加执行权限：
```
unzip reality-checker-linux-amd64.zip && chmod +x reality-checker
```
执行检查：
```
./reality-checker csv file.csv
```
<br><br>
安装s-ui：
```
bash <(curl -Ls https://raw.githubusercontent.com/alireza0/s-ui/master/install.sh)
```
