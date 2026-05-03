# Slovinsko · Itálie · Rakousko — Itinerář léto 2026

Interaktivní rodinný itinerář, **dvě paralelní verze** na termín 20.7. – 2.8.2026.

➡️ **Live web:** https://ethyawneu.github.io/slovinsko-2026/

## Verze

| Verze | URL | Charakter |
|---|---|---|
| **Plný okruh** | [`/`](https://ethyawneu.github.io/slovinsko-2026/) (`index.html`) | Vídeň → Bled → Grado → Neziderské jezero, 5 základen, ~1 730 km |
| **Chill** | [`/chill.html`](https://ethyawneu.github.io/slovinsko-2026/chill.html) | 7 nocí v privátní vile s bazénem v Goriški Brdě, krátké přejezdy okolo |

Obě verze sdílejí stejnou estetiku (Fraunces + IBM Plex, papírová textura) a vzájemně na sebe odkazují přes topbar.

## Co stránky obsahují

**Společné**
- 🗺️ Interaktivní Leaflet mapa s markery
- ⛽ Kalkulačka spotřeby paliva pro **VW Passat 2.0 TDI Combi** s reálnými cenami nafty 4 zemí (květen 2026)
- 📊 Chart.js grafy rozpočtu
- ✅ Ověřené ceny vstupů 2026 (Postojna, Vintgar, Vogel, Bled hrad, Schönbrunn ZOO, Family Park…)

**Plný okruh navíc**
- 9 konkrétních strategií úspor s vyčíslenou částkou
- 🆕 Dva přidané tipy: Vršič pass + Soča údolí (celodenní okruh z Bledu), Piran daytrip z Grada

**Chill verze navíc**
- ★ Manifest sekce (bazén · gril · víno · hudba)
- 🏠 Karty kandidátů vily ve třech regionech (Brda, Vipava+Kras, Slovinská Istrie) + záloha chorvatská Istrie
- 🌿 Volitelné výlety od bazénu (Trieste, Aquileia, Piran, Cividale, Soča…)
- ✓ Checklist co ověřit u vily před rezervací

## Tech

- Static HTML, bez build kroku
- Leaflet 1.9 (OSM/CARTO dlaždice, bez API klíče)
- Chart.js 4.4 (donut, bar, stacked bar, comparison)
- Editorial paper aesthetic — Fraunces + IBM Plex Sans/Mono
