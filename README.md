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
- Your original game files are not changed. The Steam `gta-sa.exe` and the
  mission files stay as they are; the launcher adds its own files next to them.

Windows may warn about an unknown publisher the first time (the exe is not
code-signed). Choose **More info**, then **Run anyway**.

## Playing

1. One player picks **Host a game**, presses **Host & play** and sends the
   others the invite (**Copy invite**).
2. The others pick **Join a friend**, paste the invite and press **Join & play**.

The host may need port 7788 (UDP) open on their router; the launcher tries UPnP
for that by itself.

## Credits and licences

Block Party is built on these projects. Their licences are in the
`coop\licenses` folder the launcher installs.

- [SA-COOP](https://github.com/Karimov-Akbar/sa-coop) by Karimov-Akbar (MIT): the co-op engine Block Party extends.
- [SilentPatch](https://github.com/CookiePLMonster/SilentPatch) by Silent (MIT), installed unmodified.
- [Widescreen Fix](https://github.com/ThirteenAG/WidescreenFixesPack) by ThirteenAG (GPL-3.0), installed unmodified;
  its source is at that link.
- [ENet](http://enet.bespin.org/) (MIT), [MinHook](https://github.com/TsudaKageyu/minhook) (BSD-2), [Font Awesome](https://fontawesome.com/) (OFL/MIT).

Grand Theft Auto San Andreas is a trademark of Take-Two Interactive. Block Party
is a fan project, not affiliated with Rockstar Games or Take-Two. You need your
own copy of the game.
