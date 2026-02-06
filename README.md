# NEON SERPENT

### Ultimatni hadova hra | Jeden HTML soubor | Zadne zavislosti

<div align="center">

```
    ███╗   ██╗███████╗ ██████╗ ███╗   ██╗
    ████╗  ██║██╔════╝██╔═══██╗████╗  ██║
    ██╔██╗ ██║█████╗  ██║   ██║██╔██╗ ██║
    ██║╚██╗██║██╔══╝  ██║   ██║██║╚██╗██║
    ██║ ╚████║███████╗╚██████╔╝██║ ╚████║
    ╚═╝  ╚═══╝╚══════╝ ╚═════╝ ╚═╝  ╚═══╝
    ███████╗███████╗██████╗ ██████╗ ███████╗███╗   ██╗████████╗
    ██╔════╝██╔════╝██╔══██╗██╔══██╗██╔════╝████╗  ██║╚══██╔══╝
    ███████╗█████╗  ██████╔╝██████╔╝█████╗  ██╔██╗ ██║   ██║
    ╚════██║██╔══╝  ██╔══██╗██╔═══╝ ██╔══╝  ██║╚██╗██║   ██║
    ███████║███████╗██║  ██║██║     ███████╗██║ ╚████║   ██║
    ╚══════╝╚══════╝╚═╝  ╚═╝╚═╝     ╚══════╝╚═╝  ╚═══╝   ╚═╝
```

**Kyberpunková neonová hra Had s procedurálním zvukem, více herními módy, achievementy a vizuálními efekty.**

**Vše v jednom HTML souboru. Žádné buildování. Žádné závislosti. Stačí otevřít a hrát.**

[Jak hrát](#jak-hrat) | [Funkce](#funkce) | [Herní módy](#herni-mody) | [Ovládání](#ovladani)

</div>

---

## Funkce

| Funkce | Popis |
|--------|-------|
| **4 herní módy** | Classic, Maze, Time Attack, Endless |
| **Procedurální zvuk** | Web Audio API syntezátor - jedení, smrt, power-upy, level up, ambientní hudba |
| **6 power-upů** | Speed, Ghost, Double Points, Magnet, Shield, Freeze |
| **15 achievementů** | Sledovatelné cíle s toast notifikacemi |
| **5 skinů hada** | Neon, Fire, Ice, Galaxy, Matrix |
| **Portály** | Teleportační portály se objevují na vyšších levelech |
| **Combo systém** | Řetěz jedení pro násobič skóre s milníkovými efekty |
| **Jedovaté jídlo** | Vyhýbej se červeným zónám nebo použij Shield |
| **Zlaté jablko** | Vzácné - masivní body + dočasný shield |
| **Local Storage** | High score, achievementy a nastavení se ukládají mezi sezeními |
| **CRT efekt** | Volitelný retro scanline overlay |
| **Podpora mobilu** | Ovládání swipem + D-pad |
| **Žádné závislosti** | Jeden HTML soubor, funguje offline |

## Herní módy

### Classic
Klasický had. Zdi zabíjejí. Překážky se objevují od levelu 3+. Portály od levelu 5+. Jak daleko se dostaneš?

### Maze
Naviguj se skrz zdi a chodby, které se mění s každým levelem. Těsné prostory vyžadují přesné ovládání.

### Time Attack
90 sekund na hodinkách. Průchozí okraje (žádná smrt od zdí). Posbírej co nejvíc jídla, než vyprší čas.

### Endless
Žádné zdi - had prochází přes okraje. Rychlost se neustále zvyšuje. Žádný limit levelů. Čisté přežití.

## Ovládání

| Klávesa | Akce |
|---------|------|
| `W` `A` `S` `D` / `Šipky` | Pohyb |
| `Mezerník` | Pauza / Pokračování |
| `Escape` | Pauza |
| `M` | Zapnout/vypnout hudbu |

**Mobil:** Swipni po herní ploše nebo použij D-pad na obrazovce.

## Power-upy

| Ikona | Název | Efekt | Doba trvání |
|-------|-------|-------|-------------|
| ⚡ | **Speed** | Pohyb o 40% rychlejší | 5s |
| 👻 | **Ghost** | Průchod zdmi a vlastním tělem | 6s |
| ×2 | **Double** | Dvojnásobné body | 8s |
| 🧲 | **Magnet** | Jídlo se přitahuje k tobě | 7s |
| 🛡 | **Shield** | Přežiješ jednu kolizi | 10s |
| ❄ | **Freeze** | Zpomalení času | 6s |

## Jak hrát

1. **Stáhni** `index.html` (nebo naklonuj repo)
2. **Otevři** soubor v libovolném moderním prohlížeči
3. **Vyber** herní mód
4. **Hraj!**

```bash
# Nebo naklonuj a otevři
git clone https://github.com/Lukedaca/neon-serpent.git
cd neon-serpent
# Otevři index.html v prohlížeči
start index.html        # Windows
open index.html         # macOS
xdg-open index.html     # Linux
```

> Žádný server. Žádný npm install. Žádný build. Stačí prohlížeč.

## Technologie

- **HTML5 Canvas** - Vykreslování hry
- **Web Audio API** - Procedurální syntéza zvuku
- **CSS3** - UI, animace, backdrop filtry
- **localStorage** - Persistence dat
- **Vanilla JavaScript** - Žádné frameworky

## Podpora prohlížečů

Funguje ve všech moderních prohlížečích:
- Chrome / Edge / Brave
- Firefox
- Safari
- Opera

## Nastavení

Přístup z hlavního menu:
- **Sound FX** - Zapnout/vypnout zvukové efekty
- **Music** - Ambientní synth drone
- **Volume** - Hlavní hlasitost
- **Snake Skin** - 5 barevných motivů
- **CRT Effect** - Retro scanline overlay

## Achievementy

15 achievementů k odemčení:

| Achievement | Podmínka |
|-------------|----------|
| First Blood | Sněz první jídlo |
| Hungry | Sněz 50 v jedné hře |
| Starving | Sněz 100 v jedné hře |
| Combo x5 | Dosáhni x5 combo |
| Combo King | Dosáhni x10 combo |
| Combo God | Dosáhni x20 combo |
| Speed Demon | Dosáhni level 5 |
| Veteran | Dosáhni level 10 |
| Collector | Sesbírej všech 6 typů power-upů |
| Portal Master | Použij portál 5x |
| Centurion | Skóre 1000+ |
| Legend | Skóre 5000+ |
| Survivor | Přežij 2 minuty |
| Endurance | Přežij 5 minut |
| Shield Hero | Shield tě zachrání před smrtí |

---

<div align="center">

**Vytvořeno pomocí Claude Code**

</div>
