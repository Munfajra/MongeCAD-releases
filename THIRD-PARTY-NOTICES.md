# Licence komponent třetích stran – MongeCAD

MongeCAD obsahuje a distribuuje níže uvedené komponenty třetích stran. Každá z nich
podléhá vlastní licenci. Úplná znění licencí jsou v adresáři [`legal/licenses/`](legal/licenses/)
(v nainstalované aplikaci ve složce `legal/`).

Licence třetích stran mají v rozsahu, v jakém se vztahují na příslušnou komponentu,
přednost před licenčním ujednáním aplikace MongeCAD (soubor `LICENSE`).

Poslední aktualizace: 30. 7. 2026 (verze aplikace 1.3.0).

---

## 1. Běhové prostředí Javy

| Komponenta | Verze | Licence |
|---|---|---|
| Eclipse Temurin / OpenJDK (běhové prostředí přibalené k aplikaci) | 21 | GPL-2.0 s Classpath Exception |

Instalační balíček a přenosný ZIP obsahují ořezané běhové prostředí Javy vytvořené
nástrojem `jpackage`. Toto prostředí je šířeno pod licencí **GNU General Public License
verze 2 s výjimkou Classpath Exception**. Úplná znění licencí a upozornění jsou součástí
instalace ve složce `lib/runtime/legal/`.

**Nabídka zdrojového kódu:** odpovídající zdrojový kód přibaleného běhového prostředí je
veřejně dostupný na <https://github.com/adoptium/temurin21-binaries> a
<https://github.com/openjdk/jdk21u>. Na vyžádání jej autor MongeCADu poskytne
i jiným způsobem (kontakt viz soubor `LICENSE`).

Classpath Exception umožňuje spojit toto běhové prostředí s aplikací, která není šířena
pod GPL. Omezení uvedená v čl. 3 licenčního ujednání MongeCADu (zákaz úprav a zpětného
překladu) se **nevztahují** na přibalené běhové prostředí ani na jiné komponenty třetích
stran.

---

## 2. Knihovny (Java/Kotlin)

### Apache License 2.0

Úplné znění: [`legal/licenses/Apache-2.0.txt`](legal/licenses/Apache-2.0.txt)

| Komponenta | Verze | Autor / držitel práv |
|---|---|---|
| Kotlin standardní knihovna (`kotlin-stdlib`, `-jdk7`, `-jdk8`, `-common`) | 2.2.21 / 2.1.21 | JetBrains s.r.o. |
| kotlinx-coroutines-core | 1.9.0 | JetBrains s.r.o. |
| kotlinx-serialization-core / -json | 1.7.3 | JetBrains s.r.o. |
| kotlinx atomicfu | 0.23.2 | JetBrains s.r.o. |
| JetBrains Java Annotations | 23.0.0 | JetBrains s.r.o. |
| Compose Multiplatform (`org.jetbrains.compose.*`) | 1.9.3 | JetBrains s.r.o. |
| Compose Material Icons Extended | 1.7.3 | The Android Open Source Project |
| Jetpack Compose Runtime (`androidx.compose.runtime`) | 1.9.4 | The Android Open Source Project |
| AndroidX Lifecycle / SavedState / Collection / Annotation | 2.9.4 / 1.3.3 / 1.5.0 / 1.9.1 | The Android Open Source Project |
| JetBrains AndroidX Lifecycle / SavedState | 2.9.6 / 1.3.6 | JetBrains s.r.o. |
| Skiko | 0.9.22.2 | JetBrains s.r.o. |
| JetBrains Runtime API (`jbr-api`) | 1.5.0 | JetBrains s.r.o. |
| JSpecify | 1.0.0 | The JSpecify Authors |
| colorpicker-compose | 1.1.2 | Jaewoong Eum (skydoves) |
| EJML (ejml-simple, -core, -ddense, -fdense, -zdense, -cdense, -dsparse, -fsparse) | 0.41 | Peter Abeles |
| Apache PDFBox, Apache FontBox | 2.0.30 | The Apache Software Foundation |
| Apache Commons Logging | 1.2 | The Apache Software Foundation |
| exp4j | 0.4.8 | Frank Asseg |
| imgui-java (binding, lwjgl3, natives) | 1.86.10 | SpaiR |
| Java Native Access – JNA, jna-platform | 5.15.0 | Timothy Wall a přispěvatelé |

**Apache PDFBox** – povinné upozornění (NOTICE):
[`legal/licenses/NOTICE-Apache-PDFBox.txt`](legal/licenses/NOTICE-Apache-PDFBox.txt).
PDFBox obsahuje mj. Adobe Glyph List (© Adobe Systems Incorporated), Zapf Dingbats
Glyph List (© Adobe Systems Incorporated), Bidi Mirroring Glyph Property (© Unicode, Inc.)
a části TwelveMonkeys ImageIO (© Harald Kuhr).

**JNA** je nabízena dvojlicenčně (Apache-2.0 **nebo** LGPL-2.1-or-later).
MongeCAD ji používá a šíří **pod licencí Apache License 2.0**.

### MIT License

| Komponenta | Verze | Autor / držitel práv | Znění licence |
|---|---|---|---|
| Dear ImGui (C++ knihovna uvnitř nativních knihoven imgui-java) | 1.86 | © 2014–2026 Omar Cornut | [`MIT-Dear-ImGui.txt`](legal/licenses/MIT-Dear-ImGui.txt) |
| JOML | 1.10.5 | © 2015–2022 JOML | [`MIT-JOML.txt`](legal/licenses/MIT-JOML.txt) |
| lwjgl3-awt | 0.2.3 | © 2015 Kai Burjack | [`MIT-lwjgl3-awt.txt`](legal/licenses/MIT-lwjgl3-awt.txt) |
| FileKit (filekit-core) | 0.8.8 | © Vincent Guillebaud | [`MIT-FileKit.txt`](legal/licenses/MIT-FileKit.txt) |
| dbus-java (core, transport-native-unixsocket) | 5.1.0 | © 2005–2006 Matthew Johnson, © 2017–2021 David M. | [`MIT-dbus-java.txt`](legal/licenses/MIT-dbus-java.txt) |
| SLF4J (slf4j-api, slf4j-nop) | 2.0.13 | © 2004–2022 QOS.ch Sarl | [`MIT-SLF4J.txt`](legal/licenses/MIT-SLF4J.txt) |

### BSD 3-Clause

| Komponenta | Verze | Autor / držitel práv | Znění licence |
|---|---|---|---|
| LWJGL (lwjgl, -opengl, -glfw, -nanovg, -jawt + nativní knihovny) | 3.3.6 | © 2012–dosud Lightweight Java Game Library | [`BSD-3-Clause-LWJGL.txt`](legal/licenses/BSD-3-Clause-LWJGL.txt) |
| Skia (vykreslovací jádro uvnitř knihovny Skiko) | – | © 2011 Google Inc. | [`BSD-3-Clause-Skia.txt`](legal/licenses/BSD-3-Clause-Skia.txt) |

---

## 3. Písma

| Písmo | Soubory | Licence | Držitel práv |
|---|---|---|---|
| DejaVu Sans (Book, Bold, Oblique, BoldOblique, ExtraLight, Condensed …) | `DejaVuSans*.ttf` | Bitstream Vera Fonts License / Arev Fonts License; změny DejaVu ve volném díle | © 2003 Bitstream, Inc.; glyfy Arev © Tavmjong Bah |
| Latin Modern Roman (Regular, Italic) | `lmroman10-regular.otf`, `lmroman10-italic.otf` | GUST Font License (LPPL 1.3c) | © GUST e-foundry (B. Jackowski, J. M. Nowacki) |
| Latin Modern Math | `latinmodern-math.otf`, `latinmodern-math.ttf` | GUST Font License (LPPL 1.3c) | © GUST e-foundry |
| STIX Two Math, STIX Two Text | `STIXTwoMath-Regular.ttf`, `STIXTwoText-Italic-VariableFont_wght.ttf` | SIL Open Font License 1.1 | © 2001–2021 The STIX Fonts Project / Tiro Typeworks |

Úplná znění: [`Bitstream-Vera-DejaVu.txt`](legal/licenses/Bitstream-Vera-DejaVu.txt),
[`GUST-Font-License-Latin-Modern.txt`](legal/licenses/GUST-Font-License-Latin-Modern.txt),
[`OFL-1.1-STIX-Two.txt`](legal/licenses/OFL-1.1-STIX-Two.txt).

Poznámky k dodržení podmínek:

- **Bitstream Vera / DejaVu** – písma se smějí šířit jako součást většího softwarového
  balíku (což je případ MongeCADu), nesmějí však být prodávána samostatně. Písma nejsou
  MongeCADem upravena; jejich názvy zůstávají nezměněny.
- **STIX Two** (OFL 1.1) – "STIX" je Reserved Font Name. Písma nejsou upravena ani
  přejmenována a nejsou prodávána samostatně.
- **Latin Modern** (GFL/LPPL) – soubor `latinmodern-math.ttf` je formátový převod
  originálního `latinmodern-math.otf`. GUST Font License u odvozených děl *žádá* (nikoli
  právně nevyžaduje) přejmenování; převod formátu bez úpravy obrysů se za odvozené dílo
  běžně nepovažuje. Obrysy ani metriky písma nebyly změněny.

---

## 4. Ikony

| Sada | Použití | Licence | Držitel práv |
|---|---|---|---|
| Tabler Icons | 24 ikon v `resources/icons/` | MIT | © 2020–2026 Paweł Kuna |
| Lucide Icons | 14 ikon v `resources/icons/` | ISC | © Lucide Icons and Contributors (odvozeno z Feather Icons, © 2013–2023 Cole Bemis) |
| Phosphor Icons | ikony ve formátu 256×256 (`check.svg`, `eye.svg`, `moon.svg`, `home.svg`, `eraser.svg`, `sun-dim.svg`, `cursor.svg` aj.) | MIT | © 2023 Phosphor Icons |
| Google Material Symbols | `3d_rotation_24dp_…svg` | Apache-2.0 | © Google LLC |
| Vlastní ikony MongeCADu (geometrické symboly, logo, `ikonaMC.svg`) | ostatní | © Jiří Hlaváček, všechna práva vyhrazena | – |

Úplná znění: [`MIT-Tabler-Icons.txt`](legal/licenses/MIT-Tabler-Icons.txt),
[`ISC-Lucide-Icons.txt`](legal/licenses/ISC-Lucide-Icons.txt),
[`MIT-Phosphor-Icons.txt`](legal/licenses/MIT-Phosphor-Icons.txt),
[`Apache-2.0.txt`](legal/licenses/Apache-2.0.txt).

---

## 5. Nástroje použité při sestavení

Následující nástroje se používají k sestavení a zabalení aplikace. Jejich kód se
(s výjimkou zaváděcí části instalátoru) do distribuovaného balíku nedostává.

| Nástroj | Licence | Poznámka |
|---|---|---|
| Gradle | Apache-2.0 | sestavovací systém |
| Compose Multiplatform Gradle plugin, `jpackage` (OpenJDK) | Apache-2.0 / GPL-2.0 s Classpath Exception | tvorba app image, MSI a DEB |
| WiX Toolset v3 | Microsoft Reciprocal License (MS-RL) | jpackage jej používá pro MSI |
| Inno Setup 6 | licence Inno Setup (jrsoftware.org) | tvorba EXE instalátoru |

Licence Inno Setup umožňuje volné i komerční použití. Vyžaduje, aby v šířených binárních
souborech zůstala zachována všechna uvedená autorská upozornění a webové adresy Inno Setup –
v generovaném souboru `MongeCAD-<verze>-setup.exe` nejsou nijak odstraňovány ani měněny.
Uvedení Inno Setup v dokumentaci je vítané, nikoli povinné; tímto se tak činí.

---

## 6. Zjištění a kontrola

Seznam byl sestaven z rozpadu závislostí `runtimeClasspath` (Gradle) a z kontroly
souborů v prostředcích aplikace. Stejné soubory jsou součástí každé instalace
MongeCADu ve složce `lib/app/resources/legal/`.

Zjistíte-li v tomto seznamu chybu nebo chybějící komponentu, napište na
supportmongecad@gmail.com.
