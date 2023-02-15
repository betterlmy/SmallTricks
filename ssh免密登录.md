# ssh免密登录

```bash
cd ~/.ssh # 进入到家目录下的.ssh文件夹

rm -r * # 删除掉原生成的密钥,酌情!!

ssh-keygen # 本地生成公私钥,一路回车即可

ssh-copy-id -i ~/.ssh/id_rsa.pub -p xxx xxx@192.168.xxx.xxx # 将公钥复制到远程服务器 x自己填写

ssh xxx@192.168.xxx.xxx # 验证免密登录
```
