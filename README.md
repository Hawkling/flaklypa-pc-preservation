# Flåklypa Grand Prix (2000-2002) Preservation Project

Digital preservation and compatibility project for the original PC releases of *Flåklypa Grand Prix* (2000-2002). (English: *Pinchcliffe Grand Prix*).

Covers only the original release (2000), Anniversary Edition (2001), and Gold Edition (2002).

These games have not been commercially available for many years.

---

## Legal Notice

*Flåklypa Grand Prix / Pinchcliffe Grand Prix* and related intellectual property remain the property of their respective rights holders.

This is an unofficial preservation project and is not affiliated with, endorsed by, or sponsored by any rights holder.

The repository does **not** include the original game, installation media, or copyrighted game assets. Links to third-party sources are provided for documentation and preservation purposes only. Availability and legality of third-party sources may vary by jurisdiction.

Users are responsible for ensuring they have the legal right to use any software referenced by this project.

---

## Repository Contents

* Installation guides for modern systems.
* Official updates for 2000-2002 releases.
* Compatibility-focused replacement executable for modern Windows systems.
* References to external preservation resources, including Archive.org.
* dgVoodoo2 configuration notes.
* Links to my other projects: Norwegian Game Preservation and industry exposure.

---

## 🇬🇧 English Documentation

### Preserving Norwegian Game History and digital cultural heritage

This is a personal effort to document and preserve part of Norway's digital gaming heritage. Many older Norwegian PC games are no longer commercially available and risk being lost without community documentation, public archives, or institutional preservation efforts. 

Games that can no longer be purchased should be publicly archived through institutions such as the National Library of Norway (*Nasjonalbiblioteket*), rather than relying solely on volunteers and Archive.org.

More interest in projects like the [GOG Dreamlist](https://www.gog.com/dreamlist/game/pinchcliffe-grand-prix-2000) can help demonstrate continued interest in preserving these games. Better availability of older versions could also generate renewed interest in modern re-releases and remakes such as *[Pinchcliffe Grand Prix (2021)](https://store.steampowered.com/app/3352670)*.

If official re-releases become available on platforms such as GOG or Steam, purchasing those versions is the best way to support the rights holders. Re-releases, remasters, official preservation initiatives or personal projects like this should all be welcome to preserve our digital cultural heritage.

---

### Obtaining the Game

The original games are no longer commercially available. For cultural preservation, community-preserved archival copies can be found on Archive.org:

* [Gold edition (2002)](https://archive.org/details/flaklypagullutgave)
* [Other versions and new uploads](https://archive.org/search?query=Fl%C3%A5klypa+Grand+Prix)

### Installation Guide: Gold Edition (2002)

1. Mount the CD files with [WinCDEmu](https://wincdemu.sysprogs.org/) (or extract with [Universal Extractor](https://github.com/bioruebe/uniextract2)) and install in this order:
    * FGPGULL1.mdf (CD1 Hvit, white)
    * FGPGULL2.mdf (CD2 Svart, black)
    * FGPGULL1.mdf (CD1 Hvit, white) again.
2. Update with `FGPGOLD_UPD12.exe` - sourced from [FlåklypaFix](https://sites.google.com/view/flaklypafix/).
3. Replace `FGP.exe` in `C:\Program Files (x86)\Flåklypa Grand Prix` with the modern compatibility [replacement executable](https://github.com/Hawkling/Flaklypa-Grand-Prix_2000-2002_Preservation-Project/releases).

> **Basic installation complete. You can play now.** Create a desktop shortcut if desired. 
>
> If the game does not start, enable Windows XP [compatibility mode](https://imgur.com/pPUNzuL) on the executable.

#### Recommended: Borderless Fullscreen with dgVoodoo2

4. [Download dgVoodoo2](https://dege.freeweb.hu/dgVoodoo2/dgVoodoo2/).
5. Copy `dgVoodooCpl.exe`, `dgVoodoo.conf`, and files from the `MS\x86` folder (including `DDraw.dll`) to the game folder.
6. Open `dgVoodooCpl.exe`:
    * **General:** Scaling mode: *Unspecified* (for 16:9) or *Keep aspect ratio* (for 4:3).
    * **[DirectX](https://imgur.com/BzplWw1):** Select your desired resolution and turn off "dgVoodoo Watermark."
    * **[GeneralExt](https://imgur.com/mnglcos):** Right-click and select "Show all sections of the configuration." Enable *Borderless*, *Fullscreen size*, and *Fake*.

Recommended setup is now complete.

---

## 🇳🇴 Norsk informasjon (Norwegian)

### Bevaring av norsk spillhistorie og digital kulturarv

Dette prosjektet er et personlig initiativ for å dokumentere og bevare en del av norsk digital spillhistorie. Mange eldre norske PC-spill er ikke lenger kommersielt tilgjengelige og risikerer å gå tapt uten dokumentasjon, offentlige arkivløsninger eller institusjonelle bevaringstiltak. 

Spill som ikke lenger er tilgjengelige for salg burde bli offentlig arkivert gjennom institusjoner som Nasjonalbiblioteket, fremfor å være avhengige av frivillige initiativer og Archive.org alene.

Større interesse for prosjekter som [GOG Dreamlist](https://www.gog.com/dreamlist/game/pinchcliffe-grand-prix-2000) kan vise at det fortsatt finnes interesse for å bevare disse spillene. Bedre tilgjengelighet av eldre versjoner kan også bidra til økt interesse for moderne nyutgivelser, eller remakes som *[Flåklypa Grand Prix (2021)](https://store.steampowered.com/app/3352670)*.

Hvis offisielle nyutgivelser eller remastere blir tilgjengelige på GOG eller Steam, er kjøp av disse den beste måten å støtte rettighetshaverne på. Nyutgivelser, remastere, offisiell arkivering, eller personlige prosjekter som dette burde alle være velkommen for å bevare vår digitale kulturarv.

### Tilgang til spillet

De originale spillene er ikke lenger kommersielt tilgjengelige. For bevaring av kulturarv, er det bevart fellesskapsarkiverte kopier på Archive.org:

* [Gullutgave (2002)](https://archive.org/details/flaklypagullutgave)
* [Andre versjoner og nye opplastinger](https://archive.org/search?query=Fl%C3%A5klypa+Grand+Prix)

### Installasjonsguide: Gullutgave (2002)

1. Monter CD-filene med [WinCDEmu](https://wincdemu.sysprogs.org/) (eller pakk dem ut med [Universal Extractor](https://github.com/bioruebe/uniextract2)) og installer i denne rekkefølgen:
    * FGPGULL1.mdf (CD1 Hvit)
    * FGPGULL2.mdf (CD2 Svart)
    * FGPGULL1.mdf (CD1 Hvit) igjen.
2. Oppdater med `FGPGOLD_UPD12.exe` - kilde er [FlåklypaFix](https://sites.google.com/view/flaklypafix/)
3. Erstatt `FGP.exe` i `C:\Program Files (x86)\Flåklypa Grand Prix` med den moderne kompatibilitetsversjonen: [replacement executable](https://github.com/Hawkling/Flaklypa-Grand-Prix_2000-2002_Preservation-Project/releases).

> **Grunnleggende installasjon fullført. Du kan spille nå.** Lag gjerne en snarvei til skrivebordet. 
>
> Hvis spillet ikke starter, bruk Windows XP [kompatibilitetsmodus](https://imgur.com/pPUNzuL) på `.exe`-filen.

#### Anbefalt: Borderless fullscreen med dgVoodoo2

4. [Last ned dgVoodoo2](https://dege.freeweb.hu/dgVoodoo2/dgVoodoo2/)
5. Kopier `dgVoodooCpl.exe`, `dgVoodoo.conf` og filer fra `MS\x86` (inkl. `DDraw.dll`) til spillmappen.
6. Åpne `dgVoodooCpl.exe`:
    * **General:** Scaling mode: *Unspecified* (16:9) eller *Keep aspect ratio* (4:3).
    * **[DirectX](https://imgur.com/BzplWw1):** Velg ønsket oppløsning og slå av "dgVoodoo Watermark".
    * **[GeneralExt](https://imgur.com/mnglcos):** Høyreklikk, velg "Show all sections of the configuration", og aktiver *Borderless*, *Fullscreen size* og *Fake*.

Anbefalt oppsett er nå fullført.

---

## Troubleshooting & Known Issues

* **[PCGamingWiki](https://www.pcgamingwiki.com/wiki/Pinchcliffe_Grand_Prix)** (for other issues see the glossary pages for potential workarounds. Also includes: shortcuts, [minigame location guide]([url](https://imgur.com/gallery/Y44AtiM)), savegame location, cheats)
* **Alt-Tabbing** without dgVoodoo 2 has lots of issues due to it being a fullscreen exclusive game, including windows monitor setup being moved around, getting color issues ingame when you tab back into the game, and more
* **Multiple Monitors:** Use dgVoodoo2 to force the game into a borderless windowed mode.
* **Steam Overlay/Controllers:** If you add the game as a non-steam game to use controller configurations, the Windows XP compatibility setting causes the `.exe` to run as administrator. This requires **Steam to also run as administrator** for the overlay and controller input to be detected.

---

## External resources

* [PCGamingWiki Page](https://www.pcgamingwiki.com/wiki/Pinchcliffe_Grand_Prix)
* [FlåklypaFix](https://sites.google.com/view/flaklypafix/): Primary source for official updates.
* [Guide for minigame locations](https://imgur.com/gallery/norwegian-game-fl-klypa-grand-prix-2000-guide-to-find-all-minigames-activities-https-www-reddit-com-r-norge-comments-1te4r5i-Y44AtiM)

### Wiki References

* [English Wikipedia (Franchise)](https://en.wikipedia.org/wiki/The_Pinchcliffe_Grand_Prix)
* [Norwegian Wikipedia (PC Game)](https://no.wikipedia.org/wiki/Fl%C3%A5klypa_Grand_Prix_(PC-spill))
* [Norwegian Dub Wiki](https://norske-dubber.fandom.com/no/wiki/Fl%C3%A5klypa_Grand_Prix_(Spill))

### Norwegian Game Preservation and industry exposure Projects

* [List of PC games with Norwegian support](https://www.reddit.com/r/norge/comments/1tctxoi/) (Project/Report form: [Link](https://docs.google.com/forms/d/e/1FAIpQLSf8JcEtqf-u4Zv1LU3e7uycHVuK311ZcRte9n_gU3zFocXjMg/viewform))
* [List of PC games with Norwegian support (English)](https://www.reddit.com/r/Norway/comments/1tcpetk/huge_list_of_video_games_available_in_norwegian/)
* [List of Norwegian-developed games](https://www.reddit.com/r/Norway/comments/1tbbiv4/saw_the_games_of_norway_event_decided_to_look_for/) (Including non-Norwegian language titles)
* [Steam Search Filters Proposal](https://www.reddit.com/r/gamingsuggestions/comments/1timalt/looking_for_more_story_games_without_text_or/) ("No Language Required" initiative)

---

## Credits and Contributions

Thanks to everyone who has contributed information, research, compatibility fixes, and preservation efforts for Norwegian PC games. Corrections, historical documentation, compatibility reports, and technical research are welcome.

## License

* **Documentation & Preservation:** Released under **[The Unlicense](https://unlicense.org/)**.
* **Third-party software and tools:** Remain subject to their respective licenses.
* **Replacement or modified executables:** Provided solely for interoperability and preservation purposes and are not affiliated with the original rights holders.
