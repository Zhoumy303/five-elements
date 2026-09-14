# 五行 Cycle of Elements

## 📖 游戏简介
《五行 (Cycle of Elements)》是一款采用 **Unreal Engine 5 (UE5)** 开发的第一人称冒险解谜游戏。
<img width="2480" height="1218" alt="image" src="https://github.com/user-attachments/assets/f2d48145-e279-4338-90df-7f8448aac59c" />

游戏灵感源自中国传统道家哲学。玩家将扮演一位道士，运用金、木、水、火、土**五行元素**的力量，结合**季节更迭**的规律，净化被污染的环境，恢复世界的自然平衡。

## ✨ 核心特色 (Key Features)
*   **卡通传统中国风 (Cartoon Traditional Chinese Art):** 融合低多边形风格、传统山水、符箓与自然元素，营造出沉浸式的东方奇幻世界。
*   **道家和谐之旅 (Harmony of Daoist Journey):** 将五行生克与季节变化相结合，让玩家在解谜与探索中感受道法自然的和谐理念。
*   **基于元素的谜题设计 (Element-Based Puzzle Design):** 利用五行相生相克（Sheng & Ke）的机制解开谜题，开辟新道路，拯救不断恶化的世界。
<img width="2480" height="1218" alt="image" src="https://github.com/user-attachments/assets/ecba107f-ed36-4567-8919-dc592de49e19" />
<img width="2480" height="1218" alt="image" src="https://github.com/user-attachments/assets/0f3892e1-059e-4d96-a858-9cc4c06d66fd" />

## 🎮 核心玩法与机制 (Game Mechanics)

### 1. 五行生克系统
*   **相生 (Generating Cycle - Sheng):** 木生火、火生土、土生金、金生水、水生木。
*   **相克 (Controlling Cycle - Ke):** 水克火、火克金、金克木、木克土、土克水。

### 2. 基础交互机制
*   **元素收集 (Element Collection) & 吸收 (Absorb Element):** 在地图特定地点获取并吸收元素能量。
*   **元素切换 (Element Switching):** 在 UI 中切换当前使用的元素能力。
*   **元素合成 (Element Crafting):** 结合不同元素或季节环境进行道具与技能的合成。
*   **季节变换 (Season Change):** 利用季节规律改变环境状态，辅助解谜。
*   **探索能力:** 包含**攀爬 (Climbing)** 与**御剑飞行 (Flying)**，极大地丰富了第一人称视角下的探索体验。
<img width="2480" height="1218" alt="image" src="https://github.com/user-attachments/assets/2a16cab5-6f6b-4653-8d8f-d20724a9d429" />
<img width="2480" height="1218" alt="image" src="https://github.com/user-attachments/assets/6563f4cb-067e-485f-87e9-0415f34d33cd" />

## 🛠️ 开发迭代历程 (Iteration)

本项目在开发过程中经历了多次技术迭代：
1.  **早期关卡设计 (Early Level Design):** 经历了从白模（Blockout）搭建，到地形雕刻、植被与场景美术铺设的完整过程。
2.  **元素收集实现 (Element Collection):** 最初尝试直接匹配 Actor 类型，但频繁报错。后改用 **Tags (标签)** 进行识别，逻辑更可靠、准确。
3.  **元素切换实现 (Element Switching):** 最初使用 `Released` 输入事件退出 UI 导致输入冲突。后利用 **FlipFlop 节点** 切换状态，使 UI 和游戏控制能够稳定切换，解决了输入失效的问题。
<img width="2480" height="1218" alt="image" src="https://github.com/user-attachments/assets/be8b5aa2-3a36-434a-bed2-24dcc59e0a91" />
<img width="2480" height="1218" alt="image" src="https://github.com/user-attachments/assets/7cacb0ea-a37a-4207-b8d4-fece5d29b91b" />
<img width="2480" height="1218" alt="image" src="https://github.com/user-attachments/assets/11645683-4bc4-44fb-994a-effe7db2d960" />


## 💡 灵感来源 (Inspiration)

*   **游戏玩法:** 借鉴了《COCOON》(Geometric Interactive, 2023) 等优秀解谜游戏的关卡设计理念。
*   **文化内核:** 深入挖掘了传统五行（金木水火土）的哲学定义与图腾象征。
*   **美术参考:** 参考了 UE 商城中的各类风格化素材（如 Stylized Japanese Temple, Wooden Sword, Kyoto Fushimi Inari-taisha temple 等资源包）及风格化材质。


### 环境要求
*   Unreal Engine 5.x (推荐 5.3 或更高版本)
*   Windows 11

## 🚀 如何运行 (Getting Started)
//todo
