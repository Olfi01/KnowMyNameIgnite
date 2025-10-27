KnowMyName for Paper
===================

Mods like Optifine or Continuity enable resourcepack creators to change the texture of a block depending on it's custom name. xali's Enhanced Vanilla for example, retextures barrels to have different variants depending on their name.

This does not work with multiplayer servers out of the box, because after re-joining or for a different player then the one placing the barrel, the server does not tell the client the custom name of that barrel. This mod fixes this problem.

Code and this description are largely based on [PssbleTrngle/KnowMyName](https://github.com/PssbleTrngle/KnowMyName).

Installation
===================
Download and install the Ignite loader for paper as described [here](https://github.com/vectrix-space/ignite?tab=readme-ov-file#install). Then simply download the [latest release](https://github.com/Olfi01/KnowMyNameIgnite/releases) and drag it into the `mods` folder of your server (if it doesn't exist, create it). ***Make sure you always run your server using Ignite or this mod will not work!***

<details>
<summary>Technical details</summary>

Ignite enables modders to modify (to a certain extent) the Java code of Minecraft itself, while still letting paper manage the server itself. This is necessary to modify the chunk data packets sent to the client and to include the names of containers.
</details>
