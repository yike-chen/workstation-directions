## 自主机器人与视觉智能团队工作站使用说明

关于Caffe、Cuda、Matlab在ubuntu下的安装使用说明，可以参考我[这篇简书](https://www.jianshu.com/p/9a49ac119509)。

关于Ubuntu下的基本命令使用说明，可以参考我[这篇简书](https://www.jianshu.com/p/9a49ac119509)。

1. 在校外使用，需先连学校VPN。
2. 为了避免各自环境变量之前的冲突，建议只是用自己的账号通过MobaXterm等支持SSH协议的软件登录工作站，MobaXterm已经上传至此仓库。

**MobaXterm使用方法**：通过建立新会话，在Remote host处输入IP，登录后输入用户名和密码进行连接即可。

![1542534415120](README.assets/1542534415120.png){:width="100px" height="100px"}

![1542534497857](README.assets/1542534497857.png)

1. 传输文件尽量传输到/media/hdd，可以通过MobaXterm或者[Filezilla](https://filezilla-project.org/)等支持sftp协议的软件进行传输。
2. 由于学校IP无法固定，IP可能被不定期更新，可以在群里咨询。
3. 尽量不要更新系统和系统中的软件。
4. 请不要更改系统中的环境变量，环境变量都设置在自己的目录下。安装目录如/home/**your_name**/.bashrc(~/.bashrc)
5. 有需要安装软件的时候尽量使用源码安装方式在自己的工作空间中，安装目录如/home/**your_name**/local_install
6. 由于系统盘SSD仅有256GB，而HDD有2T。如有大文件等（如几G的数据集）需要存储，请放在/media/hdd目录下，此目录已挂载HDD。
7. 如有对以上问题不清楚或者有更好的使用建议，可以随时联系我。