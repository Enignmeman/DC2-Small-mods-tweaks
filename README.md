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


<a name="installation" />

## Installation

<a name="release" />

### Using release

1. Download the .bps file corresponding to the mod you want in the [releases section](https://github.com/Enignmeman/-DC2-Small-mods-tweaks/releases).
2. Go to https://www.marcrobledo.com/RomPatcher.js/
3. Apply the patch to a legally-acquired Dark Chronicle or Dark Cloud 2 iso of the same region as the patch.
4. Play using your preferred way of playing PS2 games!

<a name="cfg" />

### Using .cfg files

- With hex editor
1. Open your legally-acquired Dark Chronicle or Dark Cloud 2 iso with your favorite hex editor.
2. Find where there is data that seems similar to the data in the files you want from this repository (exact location varies demending on game version or game region)
3. Replace the data (there is always some zeros at the end, be careful to count these, too) (the size of your iso should be the same before and after applying the patch)
4. Save to a new iso file (or save over your iso file)
5. Play using your preferred way of playing PS2 games!

- With a DATA.DAT file extractor and repacker
1. Extract the game files.
2. Navigate to `[folder where DATA.DAT was extracted]/menu/cfg7/`
3. Replace the files there with the files you want from this repository.
4. Repack the game files.
5. Play using your preferred way of playing PS2 games!

<a name="list" />

## Mods currently available

<a name="demon" />

### Demo item names

Replaces the name of many things with the names they have in the Dark Cloud 2 Demo.
> Only english is supported for this mod.

<a name="macho" />

### Macho sword re-implementation

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