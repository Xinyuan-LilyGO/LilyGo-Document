
## B站视频教程

1. [arduino安装esp32视频教程](https://www.bilibili.com/video/BV1QK411L7Yx/)
2. [如何使用LilyGo T-Watch Library视频教程](https://www.bilibili.com/video/BV1Fe41147aH/)
3. [如何使用LilyGo 相机系列视频教程](https://www.bilibili.com/video/BV1Sk4y197Nm/)
4. [如何使用LilyGo 墨水屏系列视频教程](https://www.bilibili.com/video/BV1V7411m7b9/)
5. [如何使用LilyGo T-DISPLAY](https://www.bilibili.com/video/BV13f4y1S7ER/)
6. [LilyGo K210 上手入门视频](https://www.bilibili.com/video/BV1LV411d7hj/)

## LilyGo 示例代码
1. [T-Wristband examples(手环示例代码)](https://github.com/Xinyuan-LilyGO/LilyGo-T-Wristband)
2. [T-Call(SIM800L) examples](https://github.com/Xinyuan-LilyGO/LilyGo-T-Call-SIM800L)
3. [T-Display examples](https://github.com/Xinyuan-LilyGO/TTGO-T-Display)
4. [T-Watch/2020 Arduino Library](https://github.com/Xinyuan-LilyGO/TTGO_TWatch_Library)
5. [MicroPython + T-Watch](https://github.com/Xinyuan-LilyGO/MicroPython_ESP32_psRAM_LoBo)
6. [T-Camera Arduino examples](https://github.com/Xinyuan-LilyGO/LilyGo-Camera-Series)
7. [T-Camera Plus + ESP-IDF](https://github.com/Xinyuan-LilyGO/esp32-camera-screen)
8. [T-Camera Plus + BIGIOT](https://github.com/Xinyuan-LilyGO/esp32-camera-plus-bigiot)
9. [T4 & T10 Series examples](https://github.com/Xinyuan-LilyGO/LilyGo_Txx)
10. [T13 + ESP-IDF examples](https://github.com/Xinyuan-LilyGO/Ka-Radio32)
11. [T-Beam examples](https://github.com/Xinyuan-LilyGO/LilyGO-T-Beam)
12. [T-SIM(SIM7000G) examples ](https://github.com/Xinyuan-LilyGO/LilyGO-T-SIM7000G)
13. [T-SIM(SIM7000G) Cayenne ](https://github.com/Xinyuan-LilyGO/LilyGO-SIM7000-Cayenne)
14. [Elink Series(墨水屏系列) 1 examples](https://github.com/Xinyuan-LilyGO/LilyGo-T5-ink-series)
15. [Elink Series(墨水屏系列) 2 examples](https://github.com/Xinyuan-LilyGO/T5-Ink-Screen-Series)
16. [T5 V24(墨水屏) examples](https://github.com/Xinyuan-LilyGO/LilyGO_T5_V24)
17. [T-Motion examples](https://github.com/Xinyuan-LilyGO/LilyGO-T-Motion)
18. [T-HiGrow(土壤) LoRaWLAN ](https://github.com/Xinyuan-LilyGO/LilyGO-T-HiGrow-LoRaWLAN)
19. [T-HiGrow(土壤) Cayenne Dashboard](https://github.com/Xinyuan-LilyGO/T-HiGrow-Dashboard)
20. [[T-HiGrow(土壤) BASE Dashboard](https://github.com/Xinyuan-LilyGO/TTGO-HiGrow)
21. [T-Display GD32 examples](https://github.com/Xinyuan-LilyGO/LilyGO-T-DisplayGD32)
22. [T-solar IAR examples](https://github.com/Xinyuan-LilyGO/T-solar)
23. [LoRa Series examples](https://github.com/Xinyuan-LilyGO/TTGO-LoRa-Series)
24. [BBQ Keyboard Driver](https://github.com/Xinyuan-LilyGO/bbq10kbd_i2c_sw)
25. [T-Wristband-NRF52](https://github.com/lewisxhe/LilyGo-T-Wristband-NRF52)

## 图形编程
[图形编程百度云地址](https://pan.baidu.com/s/1VAbl8_A8FZ1fasJG4GrmiQ)(提取码：exjz)

## 文档
[T-Watch esp32 Version 入门篇及文档](https://t-watch.readthedocs.io/zh_CN/latest/)


## FAQ
1. 板子拿到手该怎么安装Arduino ? 
    - 看这里[arduino安装esp32视频教程](https://www.bilibili.com/video/BV1QK411L7Yx/)
2. 如何安装驱动?
    -  一般Win10会自动安装,如果使用了别的系统那么[点击这里下载](https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers)
4. 安装了驱动,如何查看驱动是否安装成功?
    - 在 我的电脑右键选择设备管理器,查看端口列表中是否有多一个设备,不清楚的话先把板子先拔下，然后再插入,看看设备管理器中是否有变化,如果有变化那么就安装好驱动了.
    - 如果安装了还是没端口,那么请换台电脑试试,如果还是不行,请联系客服
5. 当Arduino中没有我购买板子的名称时候我要选择哪个板子 ? 
    - 选择`ESP32 Dev Moudule`
6. 有没有蓝牙通讯或者WiFi通讯的示例,或者更多的示例?
    - 安装ESP32 板子到Arduino中后,自带全部功能的示例程序,你可以在`Arduino` -> `File` -> `Examples`中查看到
    ![](img/1.jpg)
7. 驱动,Arduino都装好了,如何使用?
   - 查看上面的所有示例代码与你购买板子对应的名称,点击跳转查看跳转仓库下方的README,按照上面的要求设置,如果看不明白,请看看最上面的B站视频,随便看一个都行,步骤都差不多
8. xxx款板子,待机如何 功耗如何 ?
    - 只能提供一个参考的深度睡眠的消耗电流,至于工作电流,根据应用程序而定.
9.  我能否使用3.7V的锂电池 或者 18650 的电池给板子供电 ?
    - 只要板子上有电池接口都可以,如果板子没有电池接口,那么可以查看板子有没Vin或者5V的标志,如果有那么也可以接那里,这个一般都为USB电压输入,所以当这样接的时候 请不要插USB电源,如果还是不了解,请联系客服
10. 我能否使用外接电源供电?
    - 查看板子有没Vin或者5V的标志,如果有那么也可以接那里,这个一般都为USB电压输入,所以当这样接的时候 请不要插USB电源,如果还是不了解,请联系客服
11. 我需要原理图,去哪儿找?
    - 一般原理图都和程序放在一个仓库,请查看上面的示例代码列表,如果没有,请联系客服添加
12. 有没有Micropython或者别的语言的示例程序?
    - 没有,我们只提供Arduino的示例测试代码
13. 在哪儿可以购买你们的板子 ?
    - 在淘宝网中搜索LilyGo,看到LilyGo品牌店就是我们的淘宝店铺