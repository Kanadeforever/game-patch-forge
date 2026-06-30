# game-patch-forge

面向游戏逆向、Mod 制作、民间补丁、汉化与现代体验优化的提示词框架。

A prompt framework for game reverse engineering, modding, fan patches, localization, and modern-experience improvements.


目前非常初级，这玩意是我做007血石汉化和各种hack修复MOD的时候的一系列经验总结

目标是让AI不要在逆向工程进行的过程中反复横跳浪费token。

目前只能做到有限的推进，还有非常多的不完善，欢迎一起完善它。

目前觉得问题最大的是rounds统计和记忆维持，一旦开始调用x64dbg扫内存或者调用ghidra，大概率会丢记忆，这是非常麻烦的一件事。

而且rounds的机制也不是那么完善，有好的建议欢迎移步issues讨论。
