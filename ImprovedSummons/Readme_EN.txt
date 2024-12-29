

				Improved Summons V2.04
				by Wu Min(wumin0706@hotmail.com)


----------------
What Changed
----------------
V2.04 Changes:
	* Added BG2EE/EET Compatibility. (Thanks to Deratiseur)
V2.03 Changes:
	* Added Spanish translation. (Thanks to Lisandro)
V2.02 Changes:
	* Added Russian translation. (Thanks to Prowler)
V2.01 Changes:
	* Added French translation. (Thanks to Galathee (from the d'Oghmatiques))
V2.0 Changes:
	* Weakened Angelic Summons and Demonic Summons.
	* Summoned beholders won't cast Anti-Magic Ray any more.
	* Slightly weakened the summoned vampires.
	* Slightly weakened Monster Summons.
	* Slightly improved Animal Summons.
	* Casters can use IWD version Mordenkainen's Sword from level 21 now.
	* Added the new Elemental Summons component, and merged the original Elemental Princes component into this one.
	* Removed the one bug fix about tactics mod. 
	* Removed the replacement of death spell animation.
	* Improved efreet, djinni, aerial servant, invisible stalker.

V1.3 Changes:
	* Use Weidu version from V1.3.
	* Some AI bugs have been fixed.
	* Deva, Planetar, Solar (Fallen or not) have been slightly improved.
	* Demonic Summons have been greatly changed (Read the details in section VI).
	* Animate Dead Change: Clerics now summon Skeleton Warrior/Boneguard/Banshee at lvl15/lvl25/lvl35, while mages now summon them at lvl15/lvl20/lvl25.
	* Call Woodland Being Change: Casters now summon Dryad/Sirine at lv14/lv15.
	* Elemental Princes have been slightly improved, and spell duration has been extended to 120s.
	* Allow Strength bonus to the IWD version Mordenkainen Sword.
	* Replaced Carrion Summons with Summon Beholder spell.
	* Replaced Wyvern Call with Summon Vampire spell.

V1.2 Changes:
	* Paladin can no longer summon a Solar.
	* Your caster class need at least 6M exp to summon a Solar/Fallen Solar.
	* Smarter Deva, Planetar, Solar (Fallen or not).
	* Your caster class need at least 4M exp to summon a Doom Guard, and at least 5M exp to summon a Marilith.
	* Wizard Animate Dead is a little different with priest one.
	* Random male/female gender of Deva, Planetar, Solar (Fallen or not).
	* Really one Deva, Planetar, Solar (Fallen or not). Your projected image can no longer summon multiple angelic creatures.


----------------
I.Matters Need Attention
----------------
1> About Compatibility
    This mod may not be compatible with Spell-50 mod. 
    If you play Tactics mod, please install this mod AFTER Tactics mod and uninstall this mod BEFORE Tactics mod.

2> About Demonic Summons
    Most of your enemies regard your summoned devil/demon as a enemy of you(not a enemy of themselves), because the Enemy/Ally value of your devil/demon is ENEMY by default. So they will not attack your devil/demon actively or cast any spell on it(This is AI setting), which is extremely unbalanced. 
    Now I use script to change the Enemy/Ally value of your devil/demon between ENEMY and GOODBUTRED dynamically. Whenever it becomes GOODBUTRED, your enemies will attack your devil/demon actively and cast their spells on it normally. 
    You can still summon multi devils/demons. But if you summon a Baatezu and a Tanar'ri at the same time, they will attack each other. So don't be surprised at it, because Blood War never ends.

3> A Tactics-Mod bug be Fixed
    In the first one of the final battles of SOA, there is a Sword of Greed. The Sword of Greed can be killed by Death Magic spell, because its Gender value is SUMMONED. The death variable of a ceature killed by a Death Magic spell will not be set to TRUE. So The Sword of Greed will not be regarded as dead if you kill it with a Death Magic spell. And then you will be stuck in hell, because the second battle will never come.
    This is a Tactics-Mod bug, and I have reported it, but there is no reply. I don't want anyone of you stuck in hell, so I decided to fix the bug in my mod temporarily. If the next version Tactics Mod fix this bug, I will remove my fix from my mod.
    The fix is optional, it is in the "Others" pack.


----------------
II.Installation
----------------
1> If you have an old version of this mod installed, please uninstall and delete it first. 
2> Copy "ImprovedSummons" folder, "Setup-ImprovedSummons.tp2", "Setup-ImprovedSummons.exe" into BG2 main directory.
3> Run "Setup-ImprovedSummons.exe".


----------------
III.Reinstallation or Uninstallation
----------------
Run "Setup-ImprovedSummons.exe".


----------------
IV.Thanks
----------------
Thanks to NearInfinity and Weidu.
Special thanks to Bioware.


----------------
V.About
----------------
    Some mods are tough, while your PC or NPCs can use the special equips or items gained in these mods to improve themselves. But your summons have no way to improve themselves, they relatively become weak, and become TRUE cannon fodders. So, I made this tiny mod, I call which "Improved Summons".

1> Call Woodland Being
Before lvl14, caster can still summon a Nymph. (NO CHANGE)
At lvl14, caster can summon a Dryad. She is immune to normal weapon .
From lvl15, caster can summon a Sirine. She is immune to +1 weapon and less, and can't be kill by Death Magic spell.

2> Animate Dead
Clerics can summon Skeleton Warrior/Boneguard/Banshee at lvl15/lvl25/lvl35, while mages can summon them at lvl15/lvl20/lvl25. 
Boneguard is immune to +1 weapon and less. 
Banshee is immune to +2 weapon and less, and with each hit makes victim doomed(save vs death,not bypass magic resistance) for 3 rounds. A Banshee can summon two Skeleton Warriors to protect herself.

3> Mordenkainen's Sword
Before lvl21, caster can still summon a Magical Sword. (NO CHANGE)
From lvl21, caster can summon an IWD version Mordenkainen's Sword in his/her hand to attack the victim from a long distance.
Weapon Ability:
--2d10 slashing damage + 1d10 magic damage
--to hit +14
--enchantment 4
--allow strength bonus
--increase number of attacks by 1

4> Angelic Summons
Deva/Fallen Deva/Planetar/Dark Planetar all have been improved.
Divine caster can summon a Solar/Fallen Solar at lvl35.
Arcane caster can summon a Solar/Fallen Solar at lvl26.
You can only summon one angelic creature at a time, even by projected image.

5> Demonic Summons
Baatezu and Tanar'ri will attack each other on sight. All the Baatezu have fear aura and immunity to fire, while all the Tanar'ri have immunity to electricity.
(1)Cacofiend: 50% chance to summon a Cornugon(Baatezu), while 50% chance to summon a Glabrezu(Tanar'ri). Cornugon casts Blur, Fireball at will, while Glabrezu casts Mirror Image, Lightning Bolt, Power Word:Stun at will.
(2)Summon Fiend: 50% chance to summon a Gelugon(Baatezu), while 50% chance to summon a Marilith(Tanar'ri). Gelugon casts Fireball, Ice Storm at will, while 
Marilith casts Cloudkill at will.
(3)Gate: 50% chance to summon a Pit Fiend(Baatezu), while 50% chance to summon a Balor(Tanar'ri). Pit Fiend casts Improved Invisibility, Sunfire, Power Word:Kill at will, while Balor casts Dispel Magic, Fire Storm, Implosion at will. Balor uses a vorpal longsword which has 5% chance vorpal hit(bypass mr & no save).

6> Elemental Summons
Elemental Princes have been slightly improved, and spell duration has been extended to 120s. Air prince casts Chain Lightning at will, while fire prince casts Flame Strike at will. When HP less than 50%, fire prince summons 3 fire elemental to aid him, while earth prince summon 3 earth elemental to aid him. The other elementals has also been improved.

7> Monster Summons
Monster Summoning I: Ettercap/Hobogoblin Elite/Ogre Berserker
Monster Summoning II: Yuan-Ti/Greater Yuan-Ti
Monster Summoning III: Fire Salamander/Ice Salamander

8> Animal Summons
Animal Summoning I:Wolf/Panther/Brown Bear
Animal Summoning II:Dire Wolf/Lion/Cave Bear
Animal Summoning III:Winter Wolf/Polar Bear

9> Summon Beholder
Replaced Carrion Summons with Summon Beholder. At a lower level, the wizard can only summon a Gauth, but after 20th level the wizard will summon a dreadful Beholder.

10> Summon Vampire
Replace Wyvern Call with Summon Vampire. At a lower level, the wizard can only summon a Fledgling Vampire, but after 20th level the wizard will summon a powerful Vampire.
Vampires have high regeneration but hate to fight in sunshine.

11> Others
Improved efreet, djinni, aerial servant, invisible stalker.


----------------
VI.Contact
----------------
If you have any advices, please email me at wumin0706@hotmail.com

Enjoy!