# Linux Ubuntu container using proot with XFCE desktop when you can't use sudo / root / admin priveleges on hopefully any server

1. Install dependencies (proot)
```
wget https://github.com/dw5/proot-ubuntu-xfce-nosudo/raw/main/proot
wget https://github.com/dw5/proot-ubuntu-xfce-nosudo/raw/main/libtalloc.so.2
chmod a+rx proot
chmod a+rx libtalloc.so.2
```
note: proot and libtalloc is from debian 10 (buster)  
2. Based on androinix ubuntu 20.04 (there was 22.04 but only arm64) typically used for termux
```
echo make sure you have
wget curl proot tar
wget https://github.com/dw5/proot-ubuntu-xfce-nosudo/raw/main/ubuntu20-xfce.sh -O ubuntu20-xfce.sh && chmod +x ubuntu20-xfce.sh && bash ubuntu20-xfce.sh 
```
3. Let's see if it works
