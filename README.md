# Particle Workshop

A Neos Mod loader mod for creating particles with color and alpha over time in [Neos VR Metaverse Engine](https://store.steampowered.com/app/740250/Neos_VR/).
Created by Gareth48 with some huge help from badhaloninja and Cyro!

## Installation
1. Install [NeosModLoader](https://github.com/zkxs/NeosModLoader).
1. Place [ParticleWorkshop.dll](https://github.com/Epimonster/ParticleWorkshop/releases/latest/download/ParticleWorkshop.dll) into your `nml_mods` folder. This folder should be at `C:\Program Files (x86)\Steam\steamapps\common\NeosVR\nml_mods` for a default install. You can create it if it's missing, or if you launch the game once with NeosModLoader installed it will create the folder for you.
1. Start the game. If you want to verify that the mod is working you can check your Neos logs.

## Cool Features
1. Anyone can use this editor so long as the client hosting the mod spawns the dialogue in a session and doesn't leave it
2. Any existing particlestyle with color and alpha over lifetime can be dragged into the appropritate field and the GUI will read them and instantiate itself appropriatley

## What to do once you're in game
1. Open the dev "Create New" dialogue
3. Navigate to Editor > Particle Workshop Editor
4. Create a new particle system with the dev "Create New" dialogue
5. Drag the ParticleStyle component into the "Particle Style" field
6. Now you or anyone in your session can begin editing the particle!

## How this works
1. If it helps, think of this plugin like an inventory editor
1. Using it, we can create objects that Neos technically supports but that we have no way to generate at the moment
1. An example of color over time in the base game is the particle spray tip! It's rainbow effect is acheived in this way
1. All this plugin does is provide a GUI for you to edit those values

## Known issues
1. You cannot add duplicate color or alpha transitions
1. You can only add up to 8 unique color transitions AND 8 unique alpha transitions. This is a Unity particle limitation
2. The Particle Editor is non-persistent due to a bit of binding code that allows it to funtion. However, if you place a particle with existing transitions the editor will read those and represent them in the GUI, so you can pick up editing

## Contribution Guidelines
1. Please send any bugs or suggestions you have to Gareth48 in Neos, or report them via the github
1. If you would like, open an issue stating your problem or motivation and a suggested solution. 
1. Create a pull request which links to your issue.
