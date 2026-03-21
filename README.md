
![Title](https://raw.githubusercontent.com/meldurson/Taming_Tools/main/Pics/Title.png)
##  

Rewrite of the items and tools, extracted and expanded from **AllTameable**.

 ### ❗Note: This is in beta, so there may be some bugs
---

## ✨ Features

* 🍖 Food that creatures eat to **speed up taming**
* 🍺 Meads for players to drink to **speed up taming**


---

## 📦 What is this mod?

**Taming Tools** is the tools and items from **AllTameable** that make taming and using tames more enjoyable, redesigned to be:

* More modular
* Easier to configure
* Cleaner to maintain


This mod focuses purely on **items and features for taming**. If you want the full overhaul experience that **AllTameable** added, check out:

### [🐗 Let Me Tame You:](https://thunderstore.io/c/valheim/p/Meldurson/LetMeTameYou/) 
* Adds the ability to tame almost any creature.

### 🐉 Creature Genetics: 
* Advanced breeding and genetic changes



---


## Items:
![Items](https://raw.githubusercontent.com/meldurson/Taming_Tools/main/Pics/Banner.png)
There are currently only 4 consumables added by this mod (but plans to increase this). The recipes can be modified in the config file.
<details>
  <summary>Default Recipes</summary>
  
| Item      | ID | Required Items | Crafting Station |
| ----------- | ----------- | ----------- |----------- |
| Basic Taming Food     | TT_T1Food       |1 Tasty Mead, 3 Yellow Mushroom, 1 Leather Scraps | Cauldron lvl 1
| Superior Taming Food X 3     | TT_T2Food       |6 Medium Health Potion, 10 Barley Flour, 1 Dragon Tear | Prep Table lvl 1
| Excellent Taming Food     | TT_T3Food       |4 Minor Eitr Mead, 2 Major Health Potion, 1 Anglerfish, 5 MageCap | Cauldron lvl 5
| Mead Base Speed Tame     | MeadBaseSpeedTame       |3 Wolf Trophy, 5 Barley Flour, 5 Raw Meat, 10 Honey | Mead Cauldron lvl 1
| Taming Potion X 4     | MeadSpeedTame       |1 Mead Base Speed Tame | Fermenter

</details>

### 🍺Taming Potion
* The **Taming Potion** works similar to the *Brew of animal whispers* except you need to be within 25 units.
* As it stack with the brew, I added that to make it a little more difficult.

### 🍖Taming Food:
**❗The way the Taming food now works is as such:**
1. A hungry creature will eat the taming food and **stay hungry**
2. It will then have a buff that decreases taming time for 10 minutes **(once it is fed)**
3. If it now eats standard food the buff will be activated

**While the buff is active it multiplies the reduction from all sources.**
* Basic is 18%
* Superior is 49%
* Excellent is 100%

### Example:
* A creature has a base taming time of 1800 seconds (30 minutes)
* The base reduction is **1 every second**
* Two players nearby have the Speed Tame Buff (From the Taming Potion) which adds another **2 per second**
* The total so far is 1+2=**3 per second**
* If the creature has eaten a Superior Taming Food it would then be **multiplied by 1.49**
* Giving 3*1.49=**4.47 reduction every second**
* This would mean it would take 1800/4.47=403 seconds to tame **(6 minutes 43 seconds)**

## 🚧 Planned Features

* Adding the rest of the AllTameable Items
* Better command options
---



## ❓Contact:
The most reliable way to reach out would be to ping me in the [Valheim Modding Discord](https://discord.com/invite/GUEBuCuAMz) under @Meldurson. or dm me on Discord.

If you want to support me you can do so through my Ko-fi account:

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/B0B3NARM0)
