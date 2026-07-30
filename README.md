<div align="center">
  <img src="assets/logo.png" alt="MongeCAD logo" width="96" height="96">

  # MongeCAD

  Desktopová CAD aplikace pro deskriptivní geometrii

  [![Latest release](https://img.shields.io/github/v/release/Munfajra/MongeCAD-releases?label=verze)](../../releases/latest)
  [![Downloads](https://img.shields.io/github/downloads/Munfajra/MongeCAD-releases/total)](../../releases)
</div>

---

**MongeCAD** umožňuje rýsování v Mongeově promítání, kótovaném promítání, axonometrii a v rovině.

Tento repozitář slouží čistě k distribuci instalátorů. Aktuální verzi najdete vždy v sekci **[Releases](../../releases/latest)**.

## Stažení a instalace

### Windows

Stáhněte instalátor `MongeCAD-<verze>-setup.exe` z posledního release a spusťte ho.

Alternativně stáhněte portable verzi `MongeCAD-<verze>-portable_windows.zip`, rozbalte a spusťte `MongeCAD\bin\MongeCAD.exe`.

### Linux (Debian / Ubuntu)

Stáhněte balíček `mongecad_<verze>_amd64.deb` a nainstalujte:

```bash
sudo apt install ./mongecad_<verze>_amd64.deb
```

Aplikaci pak spustíte příkazem `mongecad` nebo z nabídky aplikací.

### Linux (portable)

Alternativně stáhněte `MongeCAD-<verze>-portable_linux.zip`, rozbalte a spusťte:

```bash
unzip MongeCAD-<verze>-portable_linux.zip
./MongeCAD/bin/MongeCAD
```

## Požadavky

- 64bit systém (Windows 10/11, Linux x86_64)
- Grafická karta s podporou OpenGL 3.3+

## Licence

MongeCAD je bezplatný software. Smíte jej zdarma používat pro osobní, školní, výukové
i nekomerční účely a bezplatně jej dále šířit v nezměněné podobě. Úplné podmínky jsou
v souboru [LICENSE](LICENSE).

Aplikace obsahuje knihovny, písma a ikony třetích stran, které se řídí vlastními
licencemi (Apache-2.0, MIT, BSD-3-Clause, ISC, SIL OFL 1.1, GUST Font License,
Bitstream Vera) a běhové prostředí OpenJDK pod licencí GPL-2.0 s Classpath Exception.
Úplný přehled je v souboru [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md), znění
licencí ve složce [legal/licenses/](legal/licenses). Tytéž soubory jsou součástí
každého instalátoru.

---

<div align="center">© 2024–2026 Jiří Hlaváček</div>
