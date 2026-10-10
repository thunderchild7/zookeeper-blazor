# Zoo Keeper - Blazor WebAssembly

A cute match-3 puzzle game inspired by the classic Japanese **Zoo Keeper** / Zookeeper game.

## Features
- 8×8 grid of adorable animal tiles (🦁 🦒 🐼 🐘 🦛 🐊 🐒)
- Click to select, click adjacent tile to swap
- Match 3 or more in a row or column to clear them
- Cascading matches, gravity, and new tiles falling from the top
- Score, levels, and move counter
- Clean, colorful UI

## How to Run

1. Make sure you have the [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0) installed.
2. Open a terminal in this folder (`ZooKeeperWasm`).
3. Run:
   ```
   dotnet run
   ```
4. Open the URL shown in the terminal (usually https://localhost:5001 or http://localhost:5000).

## How to Play
- Click an animal, then click an adjacent one to swap.
- Only swaps that create a match of 3+ are allowed.
- Cleared animals give points (more at higher levels).
- Levels increase every 500 points.
- Have fun matching cute animals!

## Project Structure
- `Pages/Home.razor` — Main game component with all logic and UI.
- Built with Blazor WebAssembly (standalone).

Enjoy being the zookeeper!
# zookeeper-blazor
