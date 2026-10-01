# 📜 更新历史 Changelog
## Alpha v0.0.1
**中文**
初代Alpha预览版本，基础玩家动作重制。
实现自定义跑步、冲刺动画，重构原版玩家移动动画底层。
已知问题：大量高级动画尚未开发，部分场景动画抖动，动画过渡不够顺滑。

**English**
Initial alpha preview release, basic rework of player movement.
Custom running and sprint animations implemented, overhauled the base vanilla player animation system.
Known issues: Many advanced animations missing, animation jitter in certain cases, rough animation transitions.

## Alpha v0.0.2
**中文**
增加自定义待机动画、头部俯仰与偏转动画、完整游泳动画，搭建基础物品交互动画框架。
修复动画混合权重计算错误、冲刺姿态异常、第三人称模型偏移，优化基础动作过渡流畅度。

**English**
Added custom idle animations, head yaw & pitch animations, full swimming animation, and basic framework for item interaction animations.
Fixed animation blending weight bugs, incorrect sprint pose, third-person model offset, optimized smoothness of basic movement transitions.

## Alpha v0.0.3
**中文**
本次为目前最大更新，几乎全部动画逻辑完工，包含盾牌格挡动画。仅Respackopts配置系统还在开发中。
新增栅栏行走动画、方块边缘站立动画、盾牌格挡动画、火把手持动画、灯笼手持动画、受伤受击反应动画、物品栏切换动画、护甲状态动画。
修复PCL2/HCL启动器无法识别资源包、部分场景动画抖动、切换物品动画断裂、JSON控制器解析错误、动画混合时机错误、维度切换动画停止等bug。

**English**
This is our biggest update to date. Nearly all animation logic is finished, including shield blocking animation. Only Respackopts configuration support remains in development.
Added walk-on-fence animation, player edge standing animation, custom shield blocking animation, torch holding animation, lantern holding animation, player hurt/damage reaction animation, equipment & hotbar swap animation, dynamic armor state animations.
Fixed resource pack recognition issue in PCL2 and HCL launchers, abnormal animation jitter, broken animation transitions on item swap, JSON controller parsing errors, wrong animation blend timing, rare animation stop after dimension switching.
