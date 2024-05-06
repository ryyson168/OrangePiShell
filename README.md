<img alt="GitHub License" src="https://img.shields.io/github/license/wukongdaily/diy-nas-onescript?labelColor=%23FF4500&color=black"> 

### 通过ssh 连接到zero3,举例
`ssh orangepi@192.168.66.106`
- 默认用户名:`orangepi`
- 默认密码:`orangepi` <br>



### zero3 在Ubuntu系统下如何连接wifi?

`sudo orangepi-config`

### 一键命令如下(Ubuntu)
> 系统带sudo
```bash
wget -qO pi.sh https://cafe.cpolar.cn/wkdaily/zero3/raw/branch/main/zero3/pi.sh && chmod +x pi.sh
./pi.sh proxy

```
### Debian的准备
> debian系统最好先切到root身份再运行上述脚本


```bash
su -
```
```bash
wget -qO pi.sh https://cafe.cpolar.cn/wkdaily/zero3/raw/branch/main/zero3/pi.sh && chmod +x pi.sh
./pi.sh proxy

```


<img src="https://github.com/wukongdaily/OrangePiShell/assets/143675923/67baea9e-9222-4409-8aae-b6e9242c721d" width="40%" />

***

<img src="https://github.com/wukongdaily/OrangePiShell/assets/143675923/56898b74-ea47-44aa-8de3-e14e12873a25" width="40%" />


### 网盘
- docker 离线包：https://wwl.lanzouq.com/s/zero3  密码:3c60
- 免费内网穿透工具:https://i.cpolar.com/m/5Ij6
- docker全部离线包：https://drive.google.com/drive/folders/1lN14zlHeLu0zckHNftpW8kPlqGZHolL8?usp=sharing
- zero3开发版 Ubuntu Server(需要解压后再写入TF卡):https://pan.baidu.com/s/1EKlmccM6STFDb_01rv-qQQ?pwd=2gc7
- TF卡写盘工具：https://etcher.balena.io/
- 教学视频：https://www.bilibili.com/video/BV1ND421T7nB/
- 教学视频2:https://youtu.be/Ym4d7uCo9eg
- 镜像仓库:https://cafe.cpolar.cn/wkdaily/zero3
# 兼容的系统
| 设备 \| 架构   | 是否支持 |
| :----- | :--: | 
| x86-64 \| amd64   |  ✅  |
| arm64 \| arm64v8 |  ✅  | 
| armhf \| armv7 |  ✅  | 

| 系统名称   | 是否支持 |
| :----- | :--: | 
| Ubuntu   |  ✅  |
| Debian |  ✅  | 
| Deepin |  ✅  | 

