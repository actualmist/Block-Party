# Block Party

Online co-op for GTA San Andreas (PC): play the story, free roam, missions and
side jobs together with up to four players.

## Download

Get **BlockParty.exe** from the [latest release](https://github.com/actualmist/Block-Party/releases/latest).
That one file is the whole thing. Put it anywhere and open it.

- It finds your San Andreas folder (Steam or retail). If it doesn't, choose the
  folder under Settings.
- Every time you open it, it checks this page for a newer release, downloads it,
  checks that the release is signed with Block Party's release key, and restarts
  into it. A file that fails the check is not installed.
- Block Party plays from its own **Block Party** folder next to your game
  folder. Your game folder, its exe and any mods you have there are only read,
  never changed, and Block Party doesn't load your mods. The game's big files
  (audio, models) are hard links, so the folder takes almost no extra space.

Windows may warn about an unknown publisher the first time (the exe is not
code-signed). Choose **More info**, then **Run anyway**.

## Playing

1. One player picks **Host a game** and presses **Host & play**. Once their game
   is up, the launcher copies an invite code (`bp://XXXX-XXXX-XXXX`) for them to
   send.
2. The others pick **Join a friend**, paste the code and press **Join & play**.

No port forwarding or VPN is needed: the games open the way through both
routers themselves. A few connections (some mobile hotspots, providers that
share one public IP between customers) block that; there, the host can forward
UDP port 7788 and send their IP instead.

## Credits and licences

Block Party is built on these projects. Their licences are in the
`coop\licenses` folder the launcher installs.

- [SA-COOP](https://github.com/Karimov-Akbar/sa-coop) by Karimov-Akbar (MIT): the co-op engine Block Party extends.
- [SilentPatch](https://github.com/CookiePLMonster/SilentPatch) by Silent (MIT), installed unmodified.
- [Widescreen Fix](https://github.com/ThirteenAG/WidescreenFixesPack) by ThirteenAG (GPL-3.0), installed unmodified;
  its source is at that link.
- [Project2DFX](https://github.com/ThirteenAG/III.VC.SA.IV.Project2DFX) by ThirteenAG (GPL-3.0), installed unmodified;
  its source is at that link.
- [Framerate Vigilante](https://github.com/GTAmodding/FramerateVigilante) by Junior_Djjr (MIT): its frame-rate fixes
  are rewritten into Block Party's plugin.
- [Open Limit Adjuster](https://github.com/ThirteenAG/III.VC.SA.LimitAdjuster) (MIT), installed unmodified with a few
  settings changed (peds, vehicles and the script space stay at the game's own sizes).
- [ENet](http://enet.bespin.org/) (MIT), [MinHook](https://github.com/TsudaKageyu/minhook) (BSD-2), [Font Awesome](https://fontawesome.com/) (OFL/MIT).
- [Inter](https://github.com/rsms/inter) by The Inter Project Authors (SIL OFL 1.1): the launcher's text. The tagline
  is lettered in Pricedown by [Typodermic Fonts](https://typodermicfonts.com/) (an image; the font isn't included).

Grand Theft Auto San Andreas is a trademark of Take-Two Interactive. Block Party
is a fan project, not affiliated with Rockstar Games or Take-Two. You need your
own copy of the game.
