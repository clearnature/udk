# trirv 开发分支（TernixOS 引导固件线）

上游：hust-open-atom-club/udk（main 跟随）。本分支承载 TriRV/TernixOS
方向的三值引导适配（ubios 子项目为主战场）：

- ubios：替代 BIOS/UEFI 的三进制引导固件（TernixOS 的启动面）
- udkfw：固件开发套件
- odc：配套工具

TernixOS 主仓以子模块引用本分支（boot/udk）。上游同步：merge main。
