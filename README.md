# MongeCAD – ke stažení

**MongeCAD** je desktopová CAD aplikace pro deskriptivní geometrii – Mongeovo promítání (půdorys + nárys), axonometrie, kótované promítání a rýsování v rovině.

Toto repo slouží čistě k distribuci instalátorů. Aktuální verzi najdete vždy v sekci **[Releases](../../releases/latest)**.

## Stažení a instalace

### Windows

Stáhněte instalátor `MongeCAD-<verze>-setup.exe` z posledního release a spusťte ho.

### Linux (Debian / Ubuntu)

Stáhněte balíček `mongecad_<verze>_amd64.deb` a nainstalujte:

```bash
sudo apt install ./mongecad_<verze>_amd64.deb
```

Aplikaci pak spustíte příkazem `mongecad` nebo z nabídky aplikací.

### Linux (portable)

Alternativně stáhněte `MongeCAD-<verze>-portable.zip`, rozbalte a spusťte:

```bash
unzip MongeCAD-<verze>-portable.zip
./MongeCAD/bin/MongeCAD
```

## Požadavky

- 64bit systém (Windows 10/11, Linux x86_64)
- Grafická karta s podporou OpenGL 3.3+ (pro 3D vizualizaci)
- Java není potřeba – běhové prostředí je součástí balíčku

---

© Jiří Hlaváček
