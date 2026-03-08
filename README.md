# TrainDrain

TrainDrain is a VR survival game built in Unreal Engine 5.5. The player's objective is simple: keep the train moving for as long as possible while defending it from monsters.

The game revolves around switching between two critical roles:

- **Driver's Cabin** — manage the furnace heat and maintain the train's pipe system
- **Wagon Roof** — fight off monsters attacking the train

If you fail to keep the train operational, the run ends.

## Screenshots

![TrainDrain screenshot 1](media/image1.png)

![TrainDrain screenshot 2](media/image2.png)

![TrainDrain screenshot 3](media/image3.png)

## Core Gameplay Loop

Gameplay is based on constantly alternating between maintenance and combat:

### 1. Cabin: keep the train running

- Add coal into the furnace to build and maintain heat
- Avoid overheating, because excessive heat damages the pipes
- Use the hammer to repair or maintain the pipes by hitting them when needed

### 2. Roof: defend the train

- Switch to the roof and shoot monsters chasing the train
- Prevent enemies from overwhelming you or damaging your progress

Success depends on balancing both tasks efficiently.

## VR Controls

- **Switch position (Cabin ↔ Roof):** `A` button on the right controller
- **Grab / Interact:** default VR grab/interact input
- **Shoot:** VR trigger

If your build includes in-game prompts, follow them.

## How to Play

### Start of a run

1. Launch the game in VR.
2. Start the run.

### In the Driver's Cabin

1. Find the coal and the furnace.
2. Add coal to generate and maintain heat.
3. Watch for overheating:
   - overheat lowers pipe durability over time
4. Maintain the pipes:
   - grab the hammer and hit the pipes to restore or preserve durability
5. Keep in mind the main maintenance failure condition:
   - if pipe durability gets too low, coal will stop increasing heat, and the train will no longer move

### On the Wagon Roof

1. Press the `A` button on the right controller to switch to the roof.
2. Use your weapon to shoot monsters.
3. Return to the cabin whenever heat or pipe maintenance needs attention.

## Goal and Failure Conditions

- **Goal:** survive as long as possible and keep the train moving
- **You lose if:**
  - the train can no longer be maintained and stops moving
  - threats overwhelm you during the run

## Tips

- Don't focus on only one role — the game requires both maintenance and combat
- If the train starts slowing down, inspect the pipes first
- Short cycles are the safest strategy:
  - **Cabin** → add coal and repair pipes
  - **Roof** → clear monsters
  - repeat

## Running the Game

### Packaged build

1. Unzip the packaged build folder.
2. Run `TrainDrain.exe` (or the provided launcher).
3. Start your VR runtime if required by your setup, such as Oculus or SteamVR.

### Project details

- **Engine:** Unreal Engine 5.5
- **VR:** project is configured to start in VR
- **XR stack:** OpenXR plugins are enabled

## Repository Notes

This repository contains the Unreal Engine project source for TrainDrain. To open and work on the project, use the included `.uproject` file in Unreal Engine 5.5.