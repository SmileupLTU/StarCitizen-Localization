# StarCitizen-Localization 🌎

[![Discord](https://img.shields.io/discord/1185135396112322620?logo=discord&label=discord)](https://discord.gg/Gbvz9fTmZU)
![GitHub all releases](https://img.shields.io/github/downloads/Dymerz/StarCitizen-Localization/total)
![GitHub Workflow Status (with event)](https://img.shields.io/github/actions/workflow/status/Dymerz/StarCitizen-Localization/.github%2Fworkflows%2Fvalidate-global-ini.yaml?event=push&label=INI%20Validation&link=https%3A%2F%2Fgithub.com%2FDymerz%2FStarCitizen-Localization%2Factions%2Fworkflows%2Fvalidate-global-ini.yaml)


- 🇬🇧 [Instructions in English.](README.md).
- 🇫🇷 [Instruction en Français](README_fr.md).
- 🇩🇪 [Anleitung auf Deutsch](README_de.md).
- 🇱🇹 [Instrukcija Lietuviškai](README_ltu.md).
- 🇪🇸 [Instrucciones en Español](README_es.md).
- 🇮🇹 [Istruzioni in Italiano](README_it.md).
- 🇧🇷 [Instrução em Português](README_ptbr.md).

**Turinys:**
  - [Palaikomos kalbos](#supported-languages)
  - [Diegimo vadovas](#installation-guide)
  - [Lokalizacijos failų atnaujinimas](#contributing)
  - [Prisidėjimas](#contributing)
  - [Atsakomybės apribojimas](#Disclaimer)

---
## Palaikomos kalbos

| Kalba | Palaikoma | Šaltinis |
|---|---|---|
| Anglų | ![Static Badge](https://img.shields.io/badge/3.23.1a-LIVE-brightgreen) | Importuota iš žaidimo failų |
| Prancūzų - Prancūzija | ![Static Badge](https://img.shields.io/badge/3.23.1a-LIVE-brightgreen) | Generuota iš [circuspes.fr](https://traduction.circuspes.fr) ir [SPEED0U/StarCitizenFrenchTranslation](https://github.com/SPEED0U/StarCitizenFrenchTranslation) |
| Vokiečių - Vokietija | ![Static Badge](https://img.shields.io/badge/3.23.1a-LIVE-brightgreen) | Čia |
| Lietuvių - Lietuva | ![Static Badge](https://img.shields.io/badge/3.23.1a-LIVE-brightgreen) | Čia |
| Italų - Italija | ![Static Badge](https://img.shields.io/badge/3.23.0-LIVE-yellow) | [GattoMatto](https://robertsspaceindustries.com/citizens/GattoMatto) ir [MrRevo](https://robertsspaceindustries.com/citizens/MrRevo) |
| Portugalų - Brazilija | ![Static Badge](https://img.shields.io/badge/3.23.1a-LIVE-brightgreen)| Čia |
| Ispanų - Lotynų Amerika | ![Static Badge](https://img.shields.io/badge/x.xx.x-LIVE-darkred) |
| Ispanų - Ispanija | ![Static Badge](https://img.shields.io/badge/3.23.1a-LIVE-brightgreen) | Čia |
---
## Įdiegimo vadovas

### Automatinis įdiegimas
1. Atsisiųskite [install_localization.ps1](https://github.com/Dymerz/StarCitizen-Localization/releases/latest/download/install_localization.ps1) skriptą.
2. Dešiniuoju pelės mygtuku spustelėkite atsisiųstą failą (**install_localization.ps1**) ir pasirinkite `Run with PowerShell`.
  > ℹ️ Šis skriptas automatiškai atsisiųs naujausią lokalizacijos failų versiją, įdiegs juos į `Localization` aplanką ir sukonfigūruos `user.cfg` failą.
3. Paleiskite žaidimą ir mėgaukitės vertimu!


### Rankinis įdiegimo instrukcija

Kadangi lietuvių kalba nėra oficialiai palaikoma kalba, mums teko pakeisti. 
Pasirinkome anglų kalbą, todėl reikia įdėti  `global.ini` (Lietuvių vertimo) failą į anglų kalbos aplanką Star Citizen kataloge (pavyzdžiui: `StarCitizen\LIVE\data\Localization\english\global.ini`). Be to, pridėkite eilutę `g_language = english` į `user.cfg` failą.

1. Atsisiųskite [Localization.zip](https://github.com/Dymerz/StarCitizen-Localization/releases/latest/download/Localization.zip) failą.
2. Išskleiskite atsisiųstą failą į `\StarCitizen\LIVE\data\`. (pvz., `C:\Program Files\Roberts Space Industries\StarCitizen\LIVE\data\`)
3. Įdėkite lietuvišką `global.ini` (Lietuvių vertimo) failą į anglų kalbos aplanką Star Citizen kataloge. (pvz., `C:\Program Files\Roberts Space Industries\StarCitizen\LIVE\data\Localization\english\global.ini`)
4. Sukurkite arba redaguokite šį failą: `\StarCitizen\LIVE\user.cfg`. (pvz., `C:\Program Files\Roberts Space Industries\StarCitizen\LIVE\user.cfg`)
5. Priklausomai nuo norimos naudoti kalbos, pridėkite vieną iš šių eilučių į failą:

    | Kalba |   |
    |---|---|
    | Anglų | `g_language = english` |
    | Prancūzų - Prancūzija | `g_language = french_(france)` |
    | Vokiečių - Vokietija | `g_language = german_(germany)` |
    | Lietuvių - Lietuva | `g_language = english` |
    | Italų - Italija | `g_language = italian_(italy)` |
    | Portugalų - Brazilija | `g_language = portuguese_(brazil)` |
    | Ispanų - Lotynų Amerika | `g_language = spanish_(latin_america)` |
    | Ispanų - Ispanija | `g_language = spanish_(spain) ` |

5. Išsaugokite failą ir paleiskite žaidimą. 🚀

---
## Lokalizacijos failų atnaujinimas
Norėdami atnaujinti lokalizacijos failus, prašome vėl vadovautis [Diegimo vadovu](#installation-guide).

---
## Prisidėjimas
[Žiūrėti CONTRIBUTING.md](CONTRIBUTING.md)

---
## Prisidėję asmenys
<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/ROBdk97"><img src="https://avatars.githubusercontent.com/u/9892024?v=4?s=100" width="100px;" alt="ROBdk97"/><br /><sub><b>ROBdk97</b></sub></a><br /><a href="#translation-ROBdk97" title="Translation">🌍</a> <a href="#projectManagement-ROBdk97" title="Project Management">📆</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Autovot"><img src="https://avatars.githubusercontent.com/u/87210193?v=4?s=100" width="100px;" alt="Autovot"/><br /><sub><b>Autovot</b></sub></a><br /><a href="#translation-Autovot" title="Translation">🌍</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/electronicfreak"><img src="https://avatars.githubusercontent.com/u/11193801?v=4?s=100" width="100px;" alt="electronicfreak"/><br /><sub><b>electronicfreak</b></sub></a><br /><a href="#translation-electronicfreak" title="Translation">🌍</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Jack-mk"><img src="https://avatars.githubusercontent.com/u/22667101?v=4?s=100" width="100px;" alt="Jack"/><br /><sub><b>Jack</b></sub></a><br /><a href="#translation-Jack-mk" title="Translation">🌍</a> <a href="#projectManagement-Jack-mk" title="Project Management">📆</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Auhrus"><img src="https://avatars.githubusercontent.com/u/57270834?v=4?s=100" width="100px;" alt="Auhrus"/><br /><sub><b>Auhrus</b></sub></a><br /><a href="#translation-Auhrus" title="Translation">🌍</a> <a href="#projectManagement-Auhrus" title="Project Management">📆</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Nxzzin"><img src="https://avatars.githubusercontent.com/u/148262077?v=4?s=100" width="100px;" alt="Nxzzin"/><br /><sub><b>Nxzzin</b></sub></a><br /><a href="#translation-Nxzzin" title="Translation">🌍</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/InterPlay02"><img src="https://avatars.githubusercontent.com/u/23037423?v=4?s=100" width="100px;" alt="InterPlay"/><br /><sub><b>InterPlay</b></sub></a><br /><a href="#translation-InterPlay02" title="Translation">🌍</a></td>    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Brill65"><img src="https://avatars.githubusercontent.com/u/8363399?v=4?s=100" width="100px;" alt="Manu"/><br /><sub><b>Manu</b></sub></a><br /><a href="#review-Brill65" title="Reviewed Pull Requests">👀</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/danidomen"><img src="https://avatars.githubusercontent.com/u/5998908?v=4?s=100" width="100px;" alt="Daniel Martin (dmartin-webimpacto)"/><br /><sub><b>Daniel Martin (dmartin-webimpacto)</b></sub></a><br /><a href="#translation-danidomen" title="Translation">🌍</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

---
## Atsakomybės apribojimas
Tai neoficialus Star Citizen gerbėjų puslapis, nesusijęs su Cloud Imperium įmonių grupe. Visas šioje svetainėje esantis turinys, kuris nėra sukurtas jos šeimininkų ar naudotojų, priklauso jų atitinkamiems savininkams. Star Citizen®, Roberts Space Industries® ir Cloud Imperium® yra registruoti Cloud Imperium Rights LLC prekių ženklai.