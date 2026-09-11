# Cornix Curved V2

这是一款 48 键分体键盘，每侧采用 4×6 矩阵，基于 Cornix 布局并根据我的手型调整。

A 48-key split keyboard with a 4×6 matrix per half, based on the Cornix layout and adjusted to fit my hands.


所有生产文件和设计源文件均已包含在本仓库中。视频提供了简要介绍和组装演示[介绍视频](https://www.bilibili.com/video/BV1qfbV63EKA/)。

All manufacturing and design source files are included in this repository. This [video (in Chinese)](https://www.bilibili.com/video/BV1qfbV63EKA/) provides a brief introduction and assembly walkthrough.

配套主控见 [splitfun_qmk_ctrl](https://github.com/AnyuSHAN2004/splitfun_qmk_ctrl)。

The matching controller is available at [splitfun_qmk_ctrl](https://github.com/AnyuSHAN2004/splitfun_qmk_ctrl).

定位板需要攻丝，推荐使用金属材质。如需使用左右手识别引脚，请焊接 FPC 连接器旁对应的分压电阻。使用配套主控时，该引脚为 GPIO10。

The switch plates require tapped holes, so metal is recommended. To use the handedness detection pin, solder the corresponding voltage-divider resistors next to the FPC connector. With the matching controller, this pin is GPIO10.

热熔螺母均为 M2.5×4×3.5（螺纹规格 × 总长 × 外径，单位：mm）。另需一根 30 针、0.5 mm 间距、长度至少 6 cm 的同侧触点 FPC 排线。

All heat-set inserts are M2.5×4×3.5 (thread size × overall length × outer diameter, in mm). You will also need a 30-pin, 0.5 mm-pitch FPC cable at least 6 cm long, with contacts on the same side at both ends.
