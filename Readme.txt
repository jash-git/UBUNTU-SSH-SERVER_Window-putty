UBUNTU SSH SERVER 安裝 與 WINDOWS putty 連線 使用教學

資料來源: https://www.ewdna.com/2012/06/ubuntu-ssh-server.html
https://oranwind.org/post-post-10/
https://www.ubuntu-tw.org/modules/newbb/viewtopic.php?viewmode=flat&type=&topic_id=12251&forum=22
http://r97846001.blog.ntu.edu.tw/2013/10/21/utf/



△安裝SSH SERVER[01.html]

要安裝 ssh server, 以下兩行指令都可以
# apt-get install ssh
# apt-get install openssh-server

安裝後可以修改一些 ssh 的設定, 如port, 密碼認證, root登入等
# vim /etc/ssh/sshd_config
Port 22
PasswordAuthentication yes
PermitRootLogin yes -> 是否開放 root 登入

更改完存檔後記得重啟服務
# /etc/init.d/ssh restart


△WINDOWS putty 連線[02.html~04.html]

02.html 基本連線 
03.html ssh 登出 ~ exit
04.html 亂碼解決 ~ 設定語系

