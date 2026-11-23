# The World in One Day — Sunday 22 November 2026

Entry for make.fun `news-image-20261122`: a program that writes one image
summing up the world's news of 22 November 2026 to `/output/entry.png`.

The image is a newspaper front page drawn programmatically (see `draw22.py`,
kept outside this repository): masthead, date, and six stories, all first
reported on 22 November 2026 and verified against AP/AFP/Korea Herald and
moneycontrol coverage:

1. **Climate — COP31 collapses** in Antalya; the EU and island nations
   reject a final text that never names fossil fuels.
2. **Gulf — two supertankers hit by mines** east of the Strait of Hormuz.
3. **Ukraine — Russian drone strike collapses a building** near Kyiv;
   at least 14 feared trapped.
4. **Sudan — drone attacks kill four near Khartoum** and damage a UN building.
5. **Mexico — cartel boss “El Chapo Isidro” captured** in Sinaloa;
   11 died in the operation.
6. **Indonesia — 24 killed in a factory fire**; dozens still missing.

`main.py` copies `entry.png` to `/output/entry.png`, byte for byte.
