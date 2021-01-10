# plz-download
Github 离线下载
> aria2 下载 + rclone 上传

# 使用？ How to use
1. Fork这个项目, 点击项目workflow并启用（以下坚果云为例）
2. settings->Secrets 设置 rclone_conf
    ```
    [NutStore]
    type = webdav
    url = https://dav.jianguoyun.com/dav/XXXX
    vendor = other
    user = 你的用户名
    pass = 应用授权码，账户信息->安全选项->第三方应用管理
    ```
3. 新建wiki页面nutstore
4. 每次要下载时编辑Wiki的nutstore页面写上下载地址并保存页面(可多行)

> 要添加其他网盘的请参照[rclone文档](https://rclone.org/docs/) <br>
> Linux 复制~/.conf/rclone.conf的内容<br>
> Windows `Win+R` 输入 `notepad %USERPROFILE%\.config\rclone\rclone.conf`<br>
> wiki页名称要和配置文件里中括号内容对应<br>

# Licence
本项目基于 GLWTPL (Good Luck With That Public License) 许可证开源。
This project under the [Good Luck With That Public License](https://github.com/me-shaon/GLWTPL)
