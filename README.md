# Introduction

    - smart_tools: Practical small scripts by development of oneself.
    - platform: ubuntu x86_64

# Get smart_tools

    - `git clone -b master https://github.com/SeaflyGithub/smart_tools`

# Install smart_tools

    - `cd smart_tools/ && chmod 755 install.sh && ./install.sh`

# Introduction of tools

## rootfs_backup.sh

- ➜  ~ rootfs_backup.sh执行后：
- ➜  ~ 产生的所有备份文件都存放在/tmp/rootfs_ubuntu目录下
- ➜  ~ 备份完成之后直接把整个rootfs_ubuntu目录拷贝只你的其他目录
- ➜  ~ 恢复文件系统就需要这个文件包
- ➜  ~ 
- ➜  ~ 备份：
- ➜  ~ 修改脚本里面的相关变量###############
- ➜  ~ 直接把该脚本拷贝到如上rootfs_ubuntu/顶层目录下，然后执行：
- ➜  ~ bash  ./rootfs_backup.sh
- ➜  ~
- ➜  ~ 恢复：
- ➜  ~ 修改脚本里面的相关变量###############
- ➜  ~ 直接把该脚本拷贝到如上rootfs_ubuntu/顶层目录下，然后执行：
- ➜  ~ bash rootfs_backup.sh  -d 

## docbackup.sh

    - Tip: rename destinative file with last modified time
    - Tip: example: abc.txt --> abc-20170616061606.txt
    - Use: run `docbackup.sh` for help
    - GIF: 
![./screenshots/docbackup.gif](./screenshots/docbackup.gif)

## gif_record.sh

    - Tip: record window which be choosed and save to ~/Desktop/temp.gif
    - Use: run `gif_record.sh` straightly.
    - GIF: 
![./screenshots/gif_record.gif](./screenshots/gif_record.gif)

## global_sys.sh

    - Tip: save global avairiables for other scripts in this dir
    - Use: program other scripts
    - GIF: 
![./screenshots/global_sys.gif](./screenshots/global_sys.gif)

## smart_kill.sh

    - Tip: kill a process with a simple way
    - Use: run `smart_kill.sh` for help.
    - GIF: 
![./screenshots/smart_kill.gif](./screenshots/smart_kill.gif)

## translate

    - Tip: YouDao dictory for command under network environment
    - Use: run `translate` or `t` for help.
    - GIF: 
![./screenshots/translate.gif](./screenshots/translate.gif)


