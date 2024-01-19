# Personal WaspScripts
 ```pascal
 _  ___ _    _    _           _ _
| |/ (_) |__| |__(_)__ _ _ __(_) |___
| ' <| | (_-< '_ \ / _` | '_ \ | (_-<
|_|\_\_|_/__/_.__/_\__, | .__/_|_/__/
                   |___/|_| THE PROFESSOR
 ```

# Current Public Scripts:
<details>
<summary>[CLICK] Reanimate_Kilsbigpils.simba</summary>
<br>
I recommend for you to watch this video before you use this script:<br> https://www.youtube.com/watch?v=2eP6WPHqPBk
 
## Features:
```
- Uses a Custom World Hopper Handler (**TLDR:** You can choose your desired world regions or you can use your own CUSTOM list):
  -- You can Enable/Disable World Hopping.
  -- You can Enable/Disable Total Level World Hopping.
  -- Regions: EU, NAEast, NAWest, AUS.
  -- Configurable CUSTOM World List.

- Automatically:
  -- Detects if the user has a anti-fire shield equiped to fight Ensouled Dragon Heads.
  -- Detects if the user is wearing a Serpentine helm to fight Ensouled Kalphite Heads.
     --- In case the user is not wearing it it will withdraw the Antipoison you specified in the settings.
  -- Uses the correct Prayer Protection if it's enabled in the settings.
     --- Make sure you have the required Prayer level to use Protect from Melee and/or Protect from Missile (if you don't it will also detect this).
  -- Detect most stuff that you might do wrong and stop the script, telling you what was the cause.
  -- Teleports to the bank you specified in the settings if your health is bellow 30%.

- [3] Supported Bank locations:
  -- Castle Wars, Ferox Enclave, Grand Exchange.

- [2] Supported Travel methods:
  -- Arceus Library and Fairy Ring (Requires Ardougne Cape 1..4);
    --- Automatically detects if you have Elite Lumbridge Diaries before using the Fairy Ring travel method.
      ---- You also require to have pre-purchased the fairy ring unlock. (Check the osrs wiki if you are unsure).

- You can Enable/Disable use of Food and/or Prayer pots.
  -- You can also specify what food to use and the amount.

- Experimental Summoning spot (Works best with 1 tile sized Monsters).

- For biger monsters it will use a different method of tile clicking to Summon the Ensouled Heads to avoid issues. (ONLY if ExperimentalSummonSpot is disable).

- You can make extra changes if you know what you are doing inside of the "Init" procedure. 
```
## Requirements:
```
- Start in one of the supported bank locations.
- Set EXP Bar to PRAYER ONLY. NOT TOTAL SKILLS (If you want accurate Exp/Hr reports).
- Have your equipment and weapon pre-equiped.
- Have your desired Ensouled Head in your bank.
- Have the Fairy ring near the altar unlock if using it (Search for it on reddit/youtube if needed).
- Have a Ring of Dueling if using the Castle Wars/Ferox Enclave bank, alternatively, a Ring of Wealth if using the Grand Exchange.
- Script Settings are located between:
{............-= [   -SETTINGS START-   ] =-............}
{.............-= [   -SETTINGS END-   ] =-.............}
- Instructions/Descriptions for each element is also present after each "//".
```

## Recommendation:
```
- Ferox is the best bank due to the Rejuv. Pool.
- If you are fighting something like Abyssal demons use the experimental spot. Gives the best results.
- Big monsters like Dragons and Kalphites might be a bit buggy due to their size.
- Check the official OSRS Wiki for more info:
https://oldschool.runescape.wiki/w/Pay-to-play_Prayer_training#Reanimating_ensouled_heads 
```

## Credits/Script Signature
```
 _  ___ _    _    _           _ _
| |/ (_) |__| |__(_)__ _ _ __(_) |___
| ' <| | (_-< '_ \ / _` | '_ \ | (_-<
|_|\_\_|_/__/_.__/_\__, | .__/_|_/__/
                   |___/|_| THE PROFESSOR
        Dark Altar Reanimate

            -[Credits]-
   @SimonK, @Skunkworks, @Student,
@Club XJ, @sebastiaan, @CanadianJames, @TazE

- A big thanks to all the amazing wasp devs who answered my #chat questions!
- Ty to SimonK for letting me rebuild/remake his old reanimate script!
- Ty to Majora for collecting the osrs world numbers per region.
- Ty to Torwent and Olly for the procedure/function recommendations, specialy with the ferox pool.
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
Hey Seb nice mole pet btw
```
</details>

# More info:
* <b>WaspScripts</b> - https://waspscripts.com/ <br>
* <b>Wasplib</b> - https://github.com/Torwent/WaspLib <br>
* <b>SRL-T</b> - https://github.com/Torwent/SRL-T <br>
* <b>SRL</b> - https://github.com/Villavu/SRL-Development <br>

