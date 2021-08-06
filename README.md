# Illusion of Gaia Randomizer - Weight Vault

This repo was created to keep some example of weight files for the mystery settings of the Illusion of Gaia Randomizer

You can find the randomizer at [https://iogr.app](https://iogr.app)

## Format

The files are simple json files with the following entries :

Example using the Beginner file
```json
{
   "Difficulty":{
      "Easy":50, 
      "Normal":50, 
      "Hard":0,
      "Extreme":0 
   },
   "Goal":{
      "Dark gaia":80,
      "RJH":20,
      "Apo Gaia":0,
      "Random Gaia":0
   },
   "Statues":{
      "0":0,
      "1":0,
      "2":0,
      "3":10,
      "4":10,
      "5":10,
      "6":10,
      "Random":0
   },
   "StartingLocation":{
      "South Cape":80,
      "Safe":20,
      "Unsafe":0,
      "Forced Unsafe":0
   },
   "Logic":{
      "Completable":90,
      "Beatable":10,
      "Chaos":0
   },
   "OpenWorld":{
      "On":20,
      "Off":80
   },
   "Zelda3Mode":{
      "On":10,
      "Off":90
   },
   "AllowGlitches":{
      "On":0,
      "Off":100
   },
   "HealthVariant":{
      "None":100,
      "Red Jewel Madness":0,
      "One Hit KO":0
   },
   "EarlyFirebird":{
      "On":80,
      "Off":20
   },
   "Enemizer":{
      "None":100,
      "Limited":0,
      "Balanced":0,
      "Full":0,
      "Insane":0
   },
   "BossShuffle":{
      "On":0,
      "Off":100
   },
   "EntranceShuffle":{
      "None":100,
      "Coupled":0,
      "Uncoupled":0
   },
   "OverworldShuffle":{
      "On":0,
      "Off":100
   },
   "Spoiler":{
      "On":50,
      "Off":50
   }
}
```

Each option is described in the IoGR website.

The different weights MUST be positive or 0. 
And you need at least 1 value superior to 0 per category.

## Description of the files

### [Beginner](Vault/Beginner.json)

This file was made to be fun for beginners to the randomizer, no hard mode was added, and the number of statues required should always allow the player to get an easy fight against Dark Gaia.

A small quantity of alternate mode can give a bit of freshness between seeds.

### [No Weights](Vault/NoWeight.json)

Everything is at 1, good luck :)

### [Neo's Favorite](Vault/NeosFavorite.json)

This file was made by Neomatamune using his favorite weights. (The creator of this vault)

### [Weekly_S1](Vault/Weekly_S1.json)

Those setting are the result of a cooperative effort in the IoGR community to get each player preferences a shot. They are the settings used by default on the [mystery webpage](https://iogr.app/mystery) and are the settings used to roll the weekly seeds of the community.
Those were the setting used for the first season of the weeklies.

### [Weekly_S2](Vault/Weekly_S2.json)

Those are the settigns used for the 2nd season of the weeklies. (Finished August 6 2021)

### [Weekly_S3](Vault/Weekly_S3.json)

Those are the settigns used for the 3rd season of the weeklies.

## How to contribute ?

If you want to add your settings to the vault you can make a PR, if your settings are well formatted they should be added quickly.

