# Table of contents
1. [Download](#download)
2. [Features](#features)
3. [Supported card list](#cards)
4. [Settings](#settings)
5. [FAQ](#faq)
6. [Winrate](#winrate)
7. [Decks](#dicks)
8. [Vmware gudie](#vmware)
9. [How to register full version](#register)

# Introduction <a name="introduction"></a>
*Gwent-daily* is a bot for gwent the witcher CCG card game. Bot is based on robust image detection / OCR. It helps complete daily quests and smooth new player experience. Bot farms almost 4 packs and some scraps over night.

# Why dorfs?
This deck has polarizing matchups and easy to pilot. We are either lose or win hard.

# Features <a name="features"></a>
* No injecting. Its safer to use and harder to detect
* Bot plays minions with position in mind. For example gold cards to the right, regular ones to the left
* Emotes support
* Farms 370 ore and 145 scraps over 6 hours
* Up to 25-50% win rate. It depends on your casual MMR, account level and deck used
* Pass on round win without wasting extra cards
* Human like mouse movement
* Will GG after match
* Close defeat / victory / dc / forfeit screens
* Restart gwent every few hours (memory leaks)
* Random sleep timers and coordinates for clicking
* Smart mulligan
* Random bot exe/window name

# Download <a name="download"></a>
Get last setup.exe 

```diff
- Demo limit 25 runs x 10 days x few games each session (BOT WILL CRASH AFTER)
```

https://github.com/vadash/gwent-daily-demo/releases/latest

```diff
- Demo limit 25 runs x 10 days x few games each session (BOT WILL CRASH AFTER)
```

Bot is updated for OBT **0.9.x** patch, many happy users

![alt text](https://lh3.googleusercontent.com/-U5TxtkQsGAo/WT0D4gYqT7I/AAAAAAAARAw/WR11q7-R32sJJalo1HDFStWD3RhADhx5QCHM/s0/Discord_2017-06-11_11-47-08.png "discord")

# Supported cards (DO NOT use *animated* cards) <a name="cards"></a>
**Bronze**: Mahakam Defender, Mahakam Guard, First Light, Dwarven Skirmisher, Vrihedd Dragoon, Dol Blathanna Archer, Thunderbolt potion, Wardancer, Hawker Healer, Immune Boost

**Silver**: Barclay Els, Yarpen Zigrin, Dennis Cranmer, King of Beggars, Morenn, Olgierd, Roach, Toruviel OR Sheldon, Alzur cross, Commanders Horn (only with extreme melee stacking)

**Gold**: Geralt (starter gold), Royal Decree (starter gold, use only with 4 starter golds), Dragon saskia (starter gold), Triss (starter gold), Ragnaroog, Human saskia, Yennefer: The Conjurer, Ithline, Avallach, Triss Butt, Milva

**Leader**: Brouver Hoog only

Bot can play unsuported cards too. Keep it minimum and simple like Tremors

# Gwent settings <a name="settings"></a>
## general

![alt text](https://lh3.googleusercontent.com/-j3mRUs9mH7A/WSgeINPQgBI/AAAAAAAAQKI/7mGVKLE8SsU176zYujmZtMBuR6vZ0g3zwCHM/s0/Gwent_2017-05-26_15-22-51.png "gwent settings")

## non 1920x1080 resolution (1440p, 4k etc)
Set gwent like this and start bot. It will remove gwent's window title, change size to 1920x1080 and move it to top left. You can skip it for 1080p and bot with fullscreen

![alt text](https://lh3.googleusercontent.com/-PMuQcCzcyBI/WPsgFKsmE_I/AAAAAAAAPa4/NGGzHUB_OB4/s0/Gwent_2017-04-22_12-19-00.png "!1080")

## scaling (skip with 100% windows scaling)
1) Find gwent game exe (not gog)

![alt text](https://lh3.googleusercontent.com/-Riow_0Aq0t8/WYNSnp25eTI/AAAAAAAAR3o/n2S9JfBVz1gW3nGxFVOBsaugfoMsUp_gACHMYCw/s0/explorer_2017-08-03_19-43-08.png "scaling1")

2) Change scaling mode 

![alt text](https://lh3.googleusercontent.com/-Bzd5Y2jgwIg/WYNSy0QV1II/AAAAAAAAR3s/57RYhR55x8YaGcx6a_9uKq7kVut7UDAmACHMYCw/s0/explorer_2017-08-03_19-43-53.png "scaling2")

3) Change windows scaling

![alt text](https://lh3.googleusercontent.com/-Fk6Ip4vRqw8/WYNS8FxeqmI/AAAAAAAAR3w/0B8tKmYcF78jFDzcGCX3kiGSG3iLQ-XNwCHMYCw/s0/ApplicationFrameHost_2017-08-03_19-44-30.png "scaling3")

4) Reboot PC

# FAQ <a name="faq"></a>
Q: Any dependency ?

A: vcredist 2015 x64 and net 4.5.2 (skip for win 10)

Q: Game and windows settings ?

A: ENGLISH language, 100% scaling in windows, 1920x1080 or more (1680x1050 limited support), Monitor#1, windows 7sp1-10 x64, no cyrillic/special symbols/spaces in windows username
![alt text](https://lh3.googleusercontent.com/-4_dBitPoZac/WQsKqZOmw2I/AAAAAAAAPkw/IOaJhpuZWiIETTlinj2ZrmPdVomIixIPQCHM/s0/ApplicationFrameHost_2017-05-04_14-04-06.png "Scaling")

Q: How fast bot can complete X daily tiers ?

A: Assuming 44 games over 8.5 hours, 45% winrate => 11.6 minutes average game, 0.85 rounds for lose (sometimes enemy will 2-0 you)

2 tiers = 18 / (0.45 * 2 + 0.55 * 0.85) * 11.6 = **155** minutes

3 tiers = 42 / (0.45 * 2 + 0.55 * 0.85) * 11.6 = **360** minutes

4 tiers (max) = 66 / (0.45 * 2 + 0.55 * 0.85) * 11.6 = **560** minutes

![alt text](https://lh3.googleusercontent.com/-AnNGBw1EgWw/WTEVcei-yPI/AAAAAAAAQis/wTjXMTfXNc81LMRnkQ2TBYjK4rVLanx8QCHM/s0/chrome_2017-06-02_10-36-14.png "Daily rewards")

Q: WTF is HWID?

A: Its HardWare IDentification key. Its generated based on CPU serial number and Motherboard serial. Looks like this
![alt text](https://lh3.googleusercontent.com/-GCnSAawXp0w/WN-QGuFfdWI/AAAAAAAAPCw/RwX7whsUIu8/s0/Bg110fBHacjE1c_2017-04-01_14-33-43.png "HWID")

Q: How does the bot determine which deck to use?

A: Anyone banned yet ?

Q: No bans reported so far

A: Yes. Ingame works too.

Q: Can I run bot in background?

A: Nope, its both for safety and impossible since we dont inject in game. People bot over night or with vmware (check guide below).

Q: Do I need additional key for virtual machine ?

A: Yep

Q: Can I use gwent tracker with bot ?

A: Yes but make sure it doesnt cover important parts of screen (aka "Deck selection", "Play card" in right corner, scores, "Your turn", etc)

Q: What virtual machine should I use ?

A: Vmware 12+ pro + vmware tools

# Winrate examples (OBT) <a name="winrate"></a>

![alt text](https://lh3.googleusercontent.com/-vfgF5xnkXmw/WUxO0rhi25I/AAAAAAAARYk/2KUOSI6X3Ws3m-h7IKJpJsAxgJgOnXVmACHMYCw/s0/BotWinrate.png "old")

![alt text](https://lh3.googleusercontent.com/-n3cUZ3Oz5Yg/WXRdx4w0viI/AAAAAAAARpM/bF7_jzdOgJ8lKJgmZ7cPg_aR_dIYIiWawCHMYCw/s0/Gwent_2017-07-23_11-26-43.png "7/23/2017")

# Decks (better decks in discord) <a name="dicks"></a>
ST starter OBT (up to 500 scraps)
![alt text](https://lh3.googleusercontent.com/-ZHAjwRchU7Q/WSZZdepoXnI/AAAAAAAAQFY/GXYyccFTF2E6oS-nCVzpiDRxBlmEitlDwCHM/s0/Gwent_2017-05-25_07-11-29.png "ST 0")

# Vmware guide <a name="vmware"></a>
## Important
Changing number of cores in vmware will change HWID too!

## Links
vmware http://www.vmware.com/go/tryworkstation-win

vmware serial https://www.google.com/webhp?q=keys+for+vmware+12.5

Windows 7 X64 EN image (original) 

https://rutracker.org/forum/viewtopic.php?t=5121311 or

magnet:?xt=urn:btih:AF0CF9EA0673B98BF10DB89637C1A8389C968878&tr=http%3A%2F%2Fbt.t-ru.org%2Fann%3Fmagnet&dn=Microsoft%20Windows%207%20with%20SP1%20Updated%2012.05.2011%20English%20%5B%D0%92%D1%81%D0%B5%20%D1%80%D0%B5%D0%B4%D0%B0%D0%BA%D1%86%D0%B8%D0%B8%5D

Select "en_windows_7_enterprise_with_sp1_x64_dvd_u_677651.iso"

## Vmware settings
SSD settings: 1600 (win 7 lite)-1800 (win 7) - 2000 (win 10 lite) - 2500 (win 10) RAM / 1000-2400 pagefile (total ram + pagefile should be ~4 GB) / 512 (win 7) - 1024 (win 10) MB VRAM / 1-2 cpu cores / 15-20 gb HDD

For HDD increase RAM to 2500-3000 and VRAM to 1000-1500.

![alt text](https://lh3.googleusercontent.com/-Vxtj8GqpQfM/WTUiID5LHeI/AAAAAAAAQqE/nR8DJvOqbAgABeziy3t69p1lJWf-ciz7QCHM/s0/vmware_2017-06-05_12-19-25.png "SSD botting")

## Guest OS power options (inside vmware)

![alt text](https://lh3.googleusercontent.com/-2OaB7Pa4DH8/WTUg103kXPI/AAAAAAAAQp8/3KN-4eUc5ukW9HyoexRuuQDyCiGBZB6fACHM/s0/explorer_2017-06-05_12-13-56.png "Power options")

## Dxtory (optional)
This app limits fps to reduce vmware load by 20-30%. I use 20 fps limit. Here is version with serial

magnet:?xt=urn:btih:8EF2E1828CA03C1567DF7A31A3AD3F1AA28986B7&tr=http%3A%2F%2Fbt4.t-ru.org%2Fann%3Fmagnet&dn=Dxtory%202.0.122%20x86%2Bx64%20%5B2013%2C%20ENG%5D

![alt text](https://lh3.googleusercontent.com/-r-YzgiCQlzY/WQOEhbsUvUI/AAAAAAAAPeQ/_qSZ9TQQpP8EpA41rfB1nPvhR3k_Di3hgCHM/s0/vmware_2017-04-28_21-05-53.png "dxtory")

## Detailed guide in pictures
https://goo.gl/photos/vC2aA8zfiBoqUcPw7

# Full version
DM me @ discord:
dlr5668#5210

# How to register bot after you buy it <a name="register"></a>

1. Right click "GwentBot" desktop shortcut and press "Open file location".

![alt text](https://lh3.googleusercontent.com/-jopxphPl6Ao/WRnI_uXu0tI/AAAAAAAAPyw/ATvgPUBFPxQ5uDKYXmUzmxOrnsZnhSR_gCHM/s0/2017-05-15_18-27-55.png "desktop shortcut")

2. Rename license file to **lic** (no file name extension) and paste it here.

Bot **wont find** lic file if it doesnt have this exact name ("9DF9-F123-10E1-C82F-36AB.lic" - wrong name, "lic.lic" - wrong, "lic" - right).

![alt text](https://lh3.googleusercontent.com/-ECHfLApeYBg/WTvV-WoCK8I/AAAAAAAAQ-Q/rtxMKHLGgvMU2ESLfpsPGcRs0xyaE09dQCHM/s0/explorer_2017-06-10_14-20-22.png "where to place file")

3. Restart bot. 

PS Avast auto sandbox mode will change your HWID too. Disable it (sandbox) for bot.