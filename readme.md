# picom
安装过程依据picom进行安装。这里只是picom的配置，需要将该配置置于.config/picom文件夹下。
## 与dwm配合
需要在scripts/autostart.sh中添加
```shell
picom --experimental-backends --config ~/.config/picom/picom.conf
```
启用该配置。
