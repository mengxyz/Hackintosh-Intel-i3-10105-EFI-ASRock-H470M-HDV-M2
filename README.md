# 1 电脑参数
cpu 10105  
主板 Asrock H470M hdv/m2  
硬盘 凯侠240G sata硬盘  
内存 酷兽 夜枭ddr4 3000 8g*2 
  
# 2 更新历史  
### 2021.08.26  
### opencore引导 版本 0.7.2  
已知功能，其他未测试  
1.核显uhd 630驱动成功  
2.显示器HDMI音频正常使用  
3.USB接口没有定制，没有勾选xhciportlimit  

# 配置文件网上搜集，摸索，不解决其他问题，只驱动核显和hdmi音频。

# 其他  
核显驱动原链接 https://github.com/DucAnhVuiVe/Hackintosh-Asus-Z490-G-Gaming-Wifi-i3-10100 音频在open core 0.7.2 上无法使用  

HDMI 音频驱动原链接 https://github.com/Fu-Yuxuan-hub/ASUS-TUF-GAMING-B460M-PLUS-HACKINTOSH 更改 layout-id=7 hda-gfx=onboard-1 （这个参数经测试需要加，不加音频无法使用）device-id 709D0000  

其他功能未知
