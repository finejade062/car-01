# 虚拟机Ubuntu环境搭建记录

# 

# &#x20;1. Ubuntu虚拟机安装

# 参考CSDN教程：https://blog.csdn.net/weixin\_74195551/article/details/127288338

# > 教程较老，需要上网搜索密钥

# &#x20;踩坑：下载成 Ubuntu26.04，版本不合适，需要删除重装

# ✅ 推荐系统：Ubuntu 22.04 LTS（Server/桌面版） 在Ubuntu主页选择LTS说明-22.04LTS-server

# 

# &#x20;2. ROS (OSDV)

# 参考教程：https://blog.csdn.net/m0\_59161987/article/details/128557068?ops\_request\_misc=elastic\_search\_misc\&request\_id=e81edee9e76fff10697e14f365ff9cc8\&biz\_id=0\&utm\_medium=distribute.pc\_search\_result.none-task-blog-2\~all\~top\_positive\~default-2-128557068-null-null.142^v102^pc\_search\_result\_base2\&utm\_term=ubuntu22.04%E5%AE%89%E8%A3%85ros\&spm=1018.2226.3001.4187

# 问题清单：

# \- 公钥签名异常

# \- 缺少数字签名

# \- 软件源被禁用

# \- 无法定位软件包

# 解决步骤：询问ai →配置镜像签名 → 更新源 → 下载安装

# 

# \## 3. Python

# 使用 conda 管理Python环境

# 教程：https://blog.csdn.net/iceymuxue/article/details/134198563?ops\_request\_misc=\&request\_id=\&biz\_id=102\&utm\_term=ubuntu22.04%E5%AE%89%E8%A3%85python\&utm\_medium=distribute.pc\_search\_result.none-task-blog-2\~all\~sobaiduweb\~default-1-134198563.142^v102^pc\_search\_result\_base2\&spm=1018.2226.3001.4187

# 

# 4\. C++ (CPP)  5. VSCode

# 参考教程：https://blog.csdn.net/icacxygh001/article/details/120981354?spm=1001.2014.3001.5501

# 遇到报错：

# 1\. 图片相关报错

# 2\. 命令行安装提示：没有文件或目录

# 解决：询问ai解决

# 

# 6.git

# 步骤：

# 1.在linux下载科学上网软件方便登录github

# 2.在git 官网选择linux下载教程

# 3.打开终端，复制：# add-apt-repository ppa:git-core/ppa

# \# apt update; apt install git

# 4.检验下载成功 git  --version

# 5\. 设置用户名（git config --global user.name "你的名字"

# &#x20;   设置邮箱git config --global user.email "xxx@shturl."

# 6.查看结果 git config --global  --list

