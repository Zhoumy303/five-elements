# Cycle of Elements (五行)

## 📖 About the Game
*Cycle of Elements* is a first-person adventure puzzle game developed using **Unreal Engine 5 (UE5)**.
<img width="2480" height="1218" alt="Game Cover" src="https://github.com/user-attachments/assets/f2d48145-e279-4338-90df-7f8448aac59c" />

Inspired by traditional Chinese Daoist philosophy, players take on the role of a Taoist who harnesses the power of the **Five Elements** (Metal, Wood, Water, Fire, Earth) combined with the rhythm of **seasonal changes** to purify polluted environments and restore balance to the world.

## ✨ Key Features
*   **Cartoon Traditional Chinese Art:** Blends low-poly aesthetics, traditional landscapes, talismans, and natural elements to immerse players in an Eastern-inspired fantasy world.
*   **Harmony of Daoist Journey:** Combines the Five Elements' generating and controlling cycles with seasonal changes, allowing players to experience Daoist harmony while exploring and solving puzzles.
*   **Element-Based Puzzle Design:** Utilizes the generating (Sheng) and controlling (Ke) mechanics of the Five Elements to solve puzzles, open new paths, and restore balance to a deteriorating world.
<img width="2480" height="1218" alt="Key Features 1" src="https://github.com/user-attachments/assets/ecba107f-ed36-4567-8919-dc592de49e19" />
<img width="2480" height="1218" alt="Key Features 2" src="https://github.com/user-attachments/assets/0f3892e1-059e-4d96-a858-9cc4c06d66fd" />

## 🎮 Game Mechanics

### 1. The Five Elements System
*   **Generating Cycle (Sheng):** Wood generates Fire, Fire generates Earth, Earth generates Metal, Metal generates Water, Water generates Wood.
*   **Controlling Cycle (Ke):** Water controls Fire, Fire controls Metal, Metal controls Wood, Wood controls Earth, Earth controls Water.

### 2. Core Interactions
*   **Element Collection & Absorb Element:** Collect and absorb elemental energy at specific locations on the map.
*   **Element Switching:** Switch between currently equipped elemental abilities via the UI.
*   **Element Crafting:** Combine different elements or seasonal environments to craft items and skills.
*   **Season Change:** Manipulate seasonal cycles to alter environmental states and assist in puzzle-solving.
*   **Exploration Abilities:** Includes **Climbing** and **Flying (Sword Flight)**, greatly enriching the first-person exploration experience.
<img width="2480" height="1218" alt="Mechanics 1" src="https://github.com/user-attachments/assets/2a16cab5-6f6b-4653-8d8f-d20724a9d429" />
<img width="2480" height="1218" alt="Mechanics 2" src="https://github.com/user-attachments/assets/6563f4cb-067e-485f-87e9-0415f34d33cd" />

## 🛠️ Development Iteration

The project went through several technical iterations during development:
1.  **Early Level Design:** Progressed from white-box (Blockout) construction to terrain sculpting, vegetation placement, and final scene art pass.
2.  **Element Collection Implementation:** Initially attempted direct Actor type matching, which frequently caused errors. Switched to using **Tags** for identification, resulting in more reliable and accurate logic.
3.  **Element Switching Implementation:** Initially used the `Released` input event to exit the UI, which conflicted with other inputs. Resolved by using a **FlipFlop node** to toggle states, allowing the UI and gameplay controls to switch reliably.
<img width="2480" height="1218" alt="Iteration 1" src="https://github.com/user-attachments/assets/be8b5aa2-3a36-434a-bed2-24dcc59e0a91" />
<img width="2480" height="1218" alt="Iteration 2" src="https://github.com/user-attachments/assets/7cacb0ea-a37a-4207-b8d4-fece5d29b91b" />
<img width="2480" height="1218" alt="Iteration 3" src="https://github.com/user-attachments/assets/11645683-4bc4-44fb-994a-effe7db2d960" />

## 💡 Inspiration

*   **Gameplay:** Draws inspiration from excellent puzzle games like *COCOON* (Geometric Interactive, 2023).
*   **Cultural Core:** Deeply explores the philosophical definitions and totemic symbolism of the traditional Five Elements (Metal, Wood, Water, Fire, Earth).
*   **Art Reference:** Referenced various stylized assets from the UE Marketplace (such as Stylized Japanese Temple, Wooden Sword, Kyoto Fushimi Inari-taisha temple asset packs) and stylized materials.

## 🚀 Getting Started

### Prerequisites
*   Unreal Engine 5.x (5.3 or higher recommended)
*   Windows 11

### Installation & Running
*(To be added)*
