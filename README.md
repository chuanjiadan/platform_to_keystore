# 签名脚本

platform-to-keystore 为脚本文件

将.x509.pem 和.pk8导入keystore文件、或者.jks文件
需要openssl工具 、密钥和证书管理工具keytool  ,并配置好环境变量


脚本修改:
导出文件命名  your.jks or your.keystore
out="chris.keystore"
密码配置:
alias="chrisBle"
keystorepass="ble123123"
keypass="ble123123"

执行:
./platform-to-keystore



