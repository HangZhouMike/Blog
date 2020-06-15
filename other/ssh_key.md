* 检查是否有SSH Key 是否存在
  * 文件目录：`~/.ssh`
* 生成SSH Key
  * `ssh-keygen -t rsa -C "your_email@example.com"`
  * `id_rsa` 私钥文件
  * `id_rsa.pub` 公钥文件
* 公钥内容上传到git 仓库
* 上传登录，git 用户邮箱和密码