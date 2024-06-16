# ChickenGun 

The ChickenGun plugin for Rust gives players the ability to use any gun with unlimited ammo, does no damage, and spawns chickens where bullets hit. Players can toggle this feature on and off using commands. This plugin requires players to have a specific permission to use the chicken gun.

## Author

Plugin made by: herbs.acab

## Features

- Any gun with unlimited ammo
- Gun does no damage
- Spawns chickens at bullet hit locations
- Chickens despawn after 5 seconds
- Toggle feature on/off with commands
- Permission-based usage

## Commands

- `/chook` - Enables the chicken gun. Displays the message: "Activated chicken gun, fowl play mode activated!"
- `/nochook` - Disables the chicken gun. Displays the message: "Chicken Gun disabled!"

## Permissions

- `chickengun.use` - Allows the player to use the chicken gun.

## Installation

1. Download the `ChickenGun.cs` file and place it into your `oxide/plugins` directory.
2. Reload the plugin using the command:
   ```sh
   oxide.reload ChickenGun
