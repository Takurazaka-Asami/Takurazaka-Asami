# 张馨月 | Unity 游戏客户端开发

> 专注 Unity Gameplay、战斗系统与数据驱动的游戏客户端开发。

目前就读于中国传媒大学数据科学与大数据技术专业，求职方向为 **Unity 游戏客户端开发工程师**。参与过商业 Unity 放置 RPG 手游客户端研发，并独立完成 3D RPG + Roguelike 游戏项目。

## 技术关键词

`C#` `Unity` `UGUI` `TextMeshPro` `ScriptableObject` `Gameplay` `FSM` `NavMesh` `对象池` `AssetBundle` `JSON` `Git`

## Featured Project

### Elemental Echo - 3D RPG + Roguelike

独立开发的 Unity 3D PVE 游戏。围绕战斗、技能、局内成长、任务奖励和地图解锁，构建完整的核心玩法闭环。

| 模块 | 实现内容 |
| --- | --- |
| 战斗流程 | 角色、敌人、波次刷怪、Boss、暂停、胜负结算 |
| 技能系统 | 以 `SkillData` 与 `DamageEntity` 构建通用数据和伤害模型，支持多发、环绕、近战、冲刺、DOT、击退、眩晕、吸血等效果 |
| 伤害结算 | 基础伤害、攻击倍率、暴击、元素修正、防御减伤、护盾、最小伤害与状态效果 |
| Roguelike 成长 | 经验拾取、三选一词条、技能升级、属性成长、技能进化 |
| 长线系统 | 任务、战令、商店、货币、地图解锁与奖励数据流 |
| 数据与工程 | ScriptableObject 配置、本地存档、TMP 中文显示与运行时问题定位 |

**试玩与演示**

- 演示视频：

<video src="media/elemental-echo-demo.mp4" controls width="960">
  您的 Markdown 查看器不支持 video 标签，可直接打开 media/elemental-echo-demo.mp4。
</video>

- Windows 试玩包：准备中
- 在线试玩：准备导出 WebGL 并发布到 Unity Play

## 其他项目经验

### LineMatch 消消乐手游

基于 Hybrid ECS 架构的连线消除游戏。负责 8 方向连线与回退、六类 Booster 及队列式链式爆炸、NativeArray 棋盘数据、IJob / EntityCommandBuffer 模块通信、重力填充与对象池，并使用 Unity Editor API 制作可视化关卡编辑工具。

### Tanks - 3D 坦克战斗

独立完成坦克移动、炮弹发射、碰撞与受击、玩家与 AI 控制、战斗交互，以及启动、菜单、战斗、结算的多场景流程。

## 实习经历

**Unity 游戏开发工程师实习生 | 北京阿萨伊科技有限公司 | 2026.05 - 2026.08**

参与商业 Unity 放置 RPG 手游客户端研发，涉及角色、战斗、成长、任务、挑战玩法、UGUI 界面、存档、资源加载和问题定位；接触 C#、UGUI、Spine、AssetBundle、JSON 等技术。

---

欢迎通过 GitHub 与我交流 Unity 客户端与 Gameplay 开发。
