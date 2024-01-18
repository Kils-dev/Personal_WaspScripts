# Personal WaspScripts
 This is my rep. for simba scripts.

# Current Public Scripts:
<details>
<summary>Reanimate_Kilsbigpils.simba</summary>
 
## Features:

* Uses a Custom World Hopper Handler (**TLDR:** You can choose your desired world regions or you can use your own CUSTOM list):
  * You can Enable/Disable World Hopping.
  * You can Enable/Disable Total World Hopping.
  * Regions: EU, NAEast, NaWest, AUS.
  * Configurable CUSTOM World List.
* Automatically detects if the user has a anti-fire shield equiped to fight Ensouled Dragon Heads.
* Automatically detects if the user is wearing a Serpentine helm to fight Ensouled Kalphite Heads.
  * In case the user is not wearing it it will withdraw the Antipoison you specified in the settings.
* Automatically uses the correct Prayer Protection if it's enabled in the settings.
  * Make sure you have the required Prayer level to use Protect from Melee and/or Protect from Missile (if you don't it will also detect this).
* You can Enable/Disable use of Food and/or Prayer pots.
  * You can also specify what food to use and the amount.
* Experimental Summoning spot (Works best with 1 tile sized Monsters).
* (3) Supported Bank locations:
  * Castle Wars, Ferox Enclave, Grand Exchange.
* (2) Supported Travel methods:
  * Arceus Library and Fairy Ring (Requires Ardougne Cape 1..4);
    * Automatically detects if you have Elite Lumbridge Diaries before using the Fairy Ring travel method.
      * You also require to have pre-purchased the fairy ring unlock. Check the osrs wiki if you are unsure.
* For biger monsters it will use a custom method of Summoning the Ensouled Heads to avoid issues (ONLY if ExperimentalSummonSpot is disable).
* Will automatically teleport to the bank you specified in the settings if your health is bellow 30%.
* You can make extra changes if you know what you are doing inside of the "Init" procedure. 
* It will automatically detect most stuff that you might do wrong and stop the script, telling you what was the cause.

## Requirements:
```
- Have your equipment and weapon pre-equiped.
- 
- Set EXP Bar to PRAYER ONLY. NOT TOTAL SKILLS. (If you want accurate EXP/Hr reports)
- Make sure to already have your armour + weapon equiped before starting.
- Check the Script requirements before making a post about issues.
- Check the official OSRS Wiki for more info:
https://oldschool.runescape.wiki/w/Pay-to-play_Prayer_training#Reanimating_ensouled_heads
```
</details>
<hr>
<details>
<summary>????.simba</summary>
 
## Easter Egg:
![alt text](https://cdn.discordapp.com/attachments/795609366270574603/1191089170484047992/image.png?ex=65b6a03b&is=65a42b3b&hm=e8013c78bb444683759ce75ec1c8841cf630b345688aff8a7eaa2e78d9fe41b8&)
</details>

# Current Paid Scripts:
<details>
<summary>Sarachnis_Kilsbigpils.simba</summary>
 
## Requirements:
```pascal
SoonTM
```
</details>

# More info:
* <b>WaspScripts</b> - https://waspscripts.com/ <br>
* <b>Wasplib</b> - https://github.com/Torwent/WaspLib <br>
* <b>SRL-T</b> - https://github.com/Torwent/SRL-T <br>
* <b>SRL</b> - https://github.com/Villavu/SRL-Development <br>

