# Roadmap

## Future / Other Tools
- Retro Classix by Data East
  In title\title_Data\StreamingAssets folder
- Brave Battle Saga - The Legend of The Magic Warrior

### Uses BPList/Mbundle
- Samuari Shodown Collection
  https://github.com/ValadAmoleo/sf30ac-extractor

### Uses .PSB.M/.BIN File Container?
- Contra Anniversary Collection
  https://github.com/farmerbb/RED-Project/wiki/Contra-Anniversary-Collection
  Key is in executable at 0x272AF0, 13 bytes
- Castlevania Advance Collection
  https://github.com/farmerbb/RED-Project/wiki/Castlevania-Advance-Collection - needs audio fix
  Key is in executable at 0x224FA4, 13 bytes
- Castlevania Anniversary Collection
  https://github.com/farmerbb/RED-Project/wiki/Castlevania-Anniversary-Collection
  Key is in executable at 0x251CF0, 13 bytes
- Namco Museum Archives (Vol 1 and Vol 2)
  https://github.com/farmerbb/RED-Project/wiki/Namco-Museum-Archives
  Key is in executable at 0x1DC894, 13 bytes   (in both!)

### Uses dotemu2mame.js
- Raiden Legacy
  https://github.com/farmerbb/RED-Project/wiki/Raiden-Legacy

## Owned / Under Investigation
- Teenage Mutant Ninja Turtles: The Cowabunga Collection (August 30th, 2022)
  Assets are jammed into one file, but that file appears to be encrypted or compressed. Notes in #17.
- Capcom Arcade Stadium 1
  Current versions have an odd archive format (unlike the CAS1_Old ZIP version).
  PLACEHOLDER ADDED. See #18.
- Capcom Arcade Stadium 2
  Current versions have an odd archive format (unlike the CAS1_Old ZIP version).
  PLACEHOLDER ADDED. See #18.
- Mega Man Zero / ZX Collection
- Mega Man X Legacy Collection 2
- Mega Man Legacy Collection 
- Arcade Collection Anniversary Classics
  Mostly working, but 2 titles remain...
- Psiyko Shooter Collector's Bundle https://store.steampowered.com/bundle/18805/PSIKYO_SHOOTER_Collectors_Bundle/


## Not Yet Owned / Future Investigation
- Neo Geo Pocket Color Selection Vol. 1
- ColecoVision Flashback
  https://github.com/ZetTheLegendaryHero/Colecovision-Flashback-40-Game-Pack-ROM-Extractor
- 8-bit Adventure Anthology: Volume I	(Shadowgate, The Uninvited, Deja Vu)
  https://gitlab.com/vaiski/romextract/-/blob/master/supported.csv
- R-Type Dimensions EX
- CAVE: Mushihimesama
  Recommended in #15.
- CAVE: DoDonPachi Resurrection
  Recommended in #15.
- CAVE: Deathsmiles
  Recommended in #15.
- CAVE: Deathsmiles I + II
  Recommended in #15.
- Darius Cozmic Collection Arcade

## Upcoming Releases
- Atari 50th: Anniversary Collection (Winter 2022)

## Not Complete ROMs (may add partial extraction later)
- Mortal Kombat Kollection
  Audio ROMs were replaced with a different audio solution.
- Dungeons & Dragons: Chronicles of Mystara
  Maincpu and Gfx ROMs are there, but audio is completely reworked.
- Midway Arcade Treasures Vol. 1 (PS2)
  Audio ROMs replaced. For example, Smash TV has all the game ROMs, but none of the sound ROMs.
  Klax
    - Missing OKI sound roms
    - Missing Pals
    - pfrom.klx
      split
      0x00000 0x1000 136075-2010.17x
      0x10000 0x1000 136075-2012.12x
      0x20000 0x1000 136075-2014.17y
      0x30000 0x1000 136075-2009.17u
      0x40000 0x1000 136075-2011.12u
      0x50000 0x1000 136075-2013.17w
    - fixedcpu.klx
      cut in half
      deinterleave each, 1 byte
      136075-6006.3k
      136075-6005.1k
      136075-6008.3k
      136075-6007.1k

## Not ROMs
- Phoenix Wright Ace Attorney Trilogy
  Appears to be a Unity port
- Mortal Kombat 1+2+3 (GOG)
  DOS Version
- Mortal Kombat Trilogy (GOG)
  Windows Version
- Earthworm Jim 1 and 2 (Steam, GOG)
  DOS Version

