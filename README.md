# Small mods & tweaks for Dark Chronicle/Dark Cloud 2

Here is a few mods that are more QoL, silly stuff or just bringing back unused stuff rather than a big thing.

I'm making these to serve as a base for my Dark Chronicle/Dark Cloud 2 randomizer project.

#### Table of Contents


- [Installation](#installation)
    - [Using release](#release)
    - [Using .cfg files](#cfg)
- [Mods currently available](#list)
    - [Demo item names](#demon)
    - [Macho sword re-implementation](#macho)
    - [Absolute macho](#toomacho)


<a name="installation" />

## Mod installation

<a name="release" />

### Using release

1. Download the .xdelta file corresponding to the mod you want in the [releases section](https://github.com/Enignmeman/-DC2-Small-mods-tweaks/releases).
2. Go get DeltaPatcher [here](https://github.com/marco-calautti/DeltaPatcher/releases/).
3. Apply the patch to a legally-acquired Dark Chronicle or Dark Cloud 2 iso of the same region and version as the patch.
4. Play using your preferred way of playing PS2 games!

<a name="cfg" />

### Using .cfg files

> You will need a DATA.DAT unpacker and repacker tool compatible with your copy of DC2, an hex editor and a way to extract the contents of an iso file.

1. Extract the game files from the a legally-acquired Dark Chronicle or Dark Cloud 2 iso.
2. Unpack DATA.DAT.
  - You want to keep a copy of the original DATA.DAT available for later.
3. Download the mod folders you're interested with.
4. Paste the content of this/these folders in the folder containing the files extracted from DATA.DAT.
5. Repack your modified DATA.DAT.
6. Make a copy of the iso file of step 1.
7. Using your hex editor, locate the beginning of the original DATA.DAT in the copy of the iso.
8. Replace the DATA.DAT data in the iso with the DATA.DAT data from your modified DATA.DAT.
9. Use the modified iso to play, using your preferred way of playing PS2 games!

<a name="list" />

## Mods currently available

<a name="demon" />

### Demo item names
###### Status: Untested

Replaces the name of many things with the names they have in the Dark Cloud 2 Demo.
> Only english is affected by this mod.

<a name="macho" />

### Macho sword re-implementation
###### Status: Tested, works

Re-implements the unused Macho sword, and puts it back into the sword build-up progression.

<details>
  <summary><strong>All changes: <i>(contains ⚠️Spoilers⚠️)</i></strong></summary>
  
  <ul>
    <li><b>Macho sword</b> reimplemented to <i>ID 53</i>.</li>
    <li><b>Wrench</b> (the introduction weapon) stats changed to <b>Battle Wrench</b> stats.</li>
    <li><b>Ruler's Sword</b> builds up to <b>Macho sword</b>.</li>
    <li><b>7 Branch Sword</b> builds up to <b>Macho sword</b>.</li>
    <li><b>Macho Sword</b> builds up to <b>Sword of Zeus</b>.</li>
    <li><b>Macho Sword</b> builds up to <b>Atlamillia sword</b>.</li>
    <li><b>Macho Sword</b> builds up to <b>7th Heaven</b>.</li>
    <li><b>Macho Sword</b> requires <b>Blumo</b>, <b>Iron head</b> and <b>Zucky</b> to be defeated in order to build up to it.</li>
    <li><i>111 Attack, 120 Fire, Smash, Beast and 80 Cyclone</i> are required to build up to <b>Macho sword</b>.</li>
    <li><b>Macho Sword</b>'s maximum stats are <i>211 Attack, 99 Durable and 155 for everything else</i>.</li>
    <li><b>Macho Sword</b> has the <b>Strong</b> attribute.</li>
    <li><i>147 Attack, 150 Lightning, Smash, Exorcism and Beast</i> instead of <i>147 Attack, 150 Smash, Exorcism Beast and Scale</i> are required to build up to <b>Sword of Zeus</b>.</li>
    <li><b>Sword of Zeus</b>' maximum stats are <i>300 Attack, 99 Durable, 230 Lightning, 250 Smash, 210 Exorcism, 220 Beast and 200 for everything else</i> instead of <i>300 Attack, 99 Durable, 250 Smash, 210 Exorcism, 220 Beast, Scale and 200 for everything else</i>.</li>
  </ul>
</details>

#### Known issues

- Macho Sword has no description.

<a name="toomacho" />

### Absolute Macho
###### Status: Untested, might not work

This mod applies the exact same effects as [Macho sword re-implementation](#macho) but also replaces all items' name, icon and model to the macho sword (except some special items like clothing and ridepod parts)

> This mod is evil, I don't recommand trying it