## 构建deb包
下载到本地后，执行

```bash
dpkg -b pack_deb/ v2rayN_amd64.deb
```
v2rayN_amd64.deb 成功生成到当前目录

## 更新二进制文件
把从官方下载的二进制文件，解压并替换`v2rayN_deb/usr/local/bin/v2rayN`目录下的所有文件就行

