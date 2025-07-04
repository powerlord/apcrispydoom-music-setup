# APDoom / CrispyDoom / CrispyHeretic Music Setup
This is documentation and configuration files to set up APDoom / APHeretic / CrispyDoom / CrispyHeretic with modded music.

These instructions exist as a simpler alternative to the [Chocolate Doom Digital music packs](https://www.chocolate-doom.org/wiki/index.php/Digital_music_packs) creation.

Note:  Crispy Hexen isn't included here as the Chocolate Doom website already has a [Crispy Hexen Music pack](https://www.chocolate-doom.org/music-packs/hexen-music-ogg.zip).

# Acquiring music files
I recommend the excellent [Roland SC-55 Music Packs](https://sc55.duke4.net/) created by Brandon Blume, aka MusicallyInspired.  The configuration files included in this repository are specifically for the OGG music packs from this website.

The included configuration files are for thse packs:

* [Doom/Ultimate Doom](https://sc55.duke4.net/games.php#doom) OGG Pack
* [Doom II](https://sc55.duke4.net/games.php#doom) V1.2 OGG Pack (either version)
* [Final Doom/TNT](https://sc55.duke4.net/games.php#doom) OGG Pack (either version)
* Final Doom/Plutonia Experiment (uses [Doom/Doom II](https://sc55.duke4.net/games.php#doom) OGG packs)
* [Heretic](https://sc55.duke4.net/games.php#heretic) OGG Pack

We will cover each in the following sections.

# Unzipping the music packs

Before you can unzip the music packs, you need to locate the proper directory to install these two.

1. Launch `crispy-setup.exe`, `crispy-doom-setup.exe`, `crispy-heretic-setup.exe`, or `cripsy-hexen-setup.exe`.
2. Choose `Configure Sound`
3. Set the music type to `Native MIDI`
4. Press `M` to open the Music Packs folder

On Windows, this is `%APPDATA%\crispy-doom\music-packs`

In the `music-packs` folder: 

* Doom/Ultimate Doom - Create a `doom-music` folder and unzip `doom_sc55_ogg.zip` **or** `doom_sc55_ogg_raw.zip` into it
* Doom II - Create a `doom2-music` folder and unzip `doom2_sc55_ogg_v1.2.zip` **or** `doom2_sc55_ogg_raw_v1.2.zip` into it
* TNT - Create a `tnt-music` folder and unzip `tntevilution_sc55_ogg.zip` **or** `tntevilution_sc55_ogg_raw.zip` into it
* Heretic - Create a `heretic-music` folder and unzip `heretic_sc55_ogg.zip` into it
* Plutonia Experiment - Follow the directions below

# Unzipping the config files

1. Download `apcrispydoom-music-setup.zip` from the Releases page.
2. Unzip `apcrispydoom-music-setup.zip` into the `music-packs` folder.

# Plutonia Experiment Specific Instructions

Plutonia Experiment reuses the music from Doom and Doom 2 instead of having original music.  This requies an extra setup step.

On the Roland SC-55 Music Packs site, there is a Plutonia Experiment script.  This uses the zip files of Doom and Doom 2 music to generate a Plutonia music zip.  Directions on the script's use is on the [Doom music page](https://sc55.duke4.net/games.php#doom) under "The Plutonia Experiment".

Once the script is run and the zip file is created:

* Create a `plutonia-music` folder and unzip `plutonia_sc55_ogg.zip` into it
