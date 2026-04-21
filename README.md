# Yamamori — The Edo Forest Keeper

A pixel-art arcade game set in 1657 Japan, the year of the Great Fire of
Meireki. Play a shogunate forest warden defending ancient cedar groves
from fire, poachers, and blight across four escalating seasonal waves.
Grounded in Jared Diamond's *Collapse* — a playable argument that
conserving existing forests beats planting new ones.

**Play:** [rohanvmehra.com/yamamori](https://rohanvmehra.com/yamamori)

## Run locally

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

Single-file HTML5 Canvas — no build step, no dependencies.

## Controls

| Key            | Action                                     |
|----------------|--------------------------------------------|
| WASD / Arrows  | Move                                       |
| SPACE          | Act (douse fire · tend tree · chase poacher) |
| River 川       | Stand in it to refill bucket               |
| ESC            | Pause                                      |
| M              | Mute                                       |

## Mechanics

- **Three tree species** with different timber values: sugi 杉 (cedar, 15) ·
  matsu 松 (pine, 20) · hinoki 檜 (cypress, 40).
- **Four waves** of escalating intensity — 春 Haru · 夏 Natsu · 秋 Aki · 冬 Fuyu
  (75 seconds each; 5 minutes total).
- **Scripted Meireki wind event** ignites multiple fires at the start of summer.
- **Kinokuniya's crew** — tougher autumn poachers named for the real
  Edo-era merchant who profited from city fires by buying up Kiso timber.
- **Nōgyō zensho scrolls** (農業全書) — five collectible buffs named for
  Miyazaki Antei's 1697 silviculture treatise: rain, bucket upgrade,
  shogun seal, swift geta, heal-all-sick.
- **Wind direction** biases fire spread.

## Historical sources

- Diamond, Jared. *Collapse: How Societies Choose to Fail or Succeed*,
  ch. 9 (Viking, 2005).
- Totman, Conrad. *The Green Archipelago: Forestry in Preindustrial
  Japan* (UC Press, 1989).
- Moomaw, W. R. et al. (2019). "Intact Forests in the United States:
  Proforestation Mitigates Climate Change." *Frontiers in Forests and
  Global Change*, 2:27. https://doi.org/10.3389/ffgc.2019.00027
- Wikipedia: [Great Fire of Meireki](https://en.wikipedia.org/wiki/Great_fire_of_Meireki).

## Moral

After the 1657 Meireki fire (100,000 dead, half of Edo burned), Japan's
runaway timber consumption threatened collapse. By 1666 the shogun had
issued a nationwide conservation proclamation; by 1697 Miyazaki Antei's
*Nōgyō zensho* codified the world's first sustainable silviculture.
Between 1721–1828, the population barely rose and timber decline
reversed — led not by planting but by protecting what stood.

Modern science confirms the logic: mature forests sequester up to
**30× more carbon per hectare per year** than new plantings.
*Conservation beats new planting.*
