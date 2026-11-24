# Miss Honey Couldn't Find Her Honey

An illustrated science story exploring how artificial light at night disrupts glow-worm mating, adapted from an assessed University of Sheffield MSc Science Communication print feature.

- **Live illustrated web story:** [zyangcomm.github.io/Miss-Honey](https://zyangcomm.github.io/Miss-Honey/)
- **Portfolio case study:** [zyangcomm.wordpress.com/science-communication/#glow-worms](https://zyangcomm.wordpress.com/science-communication/#glow-worms)

## Overview

*Miss Honey Couldn't Find Her Honey* follows a lost female common glow-worm (*Lampyris noctiluca*) named Honey as she tries to signal to a mate beneath harsh park and street lighting. Originally written and designed in Adobe InDesign for the MSc Science Communication programme at the University of Sheffield (where the print edition earned a Distinction), it was later adapted into this standalone web edition.

The story translates five peer-reviewed studies on light pollution and firefly biology for non-specialist and younger readers, turning research findings on light colour, exposure duration, and distance into plot obstacles for Honey.

## Story Structure and Science Translation

Carried over from the three-tier layout of the print original, the page separates narrative, research evidence, and reader prompts so each layer supports the next:

1. **Story narrative:** A first-person night walk introduces Honey, explaining why wingless females rely on a green-yellow glow to attract flying males and how artificial lights interfere with that signal.
2. **Science notes (`Did you know?` and `What scientists found`):** Marginalia and callout bands unpack sensory biology and experimental findings in everyday terms, linking directly to the cited studies:
   - **Colour vision and energy budgets:** How fireflies' long-wavelength receptor limits colour vision, and why non-feeding adult glow-worms run on a tight energy budget (like a torch on fading batteries).
   - **Light colour:** Field experiments testing model glow-worms across white, yellow, red, blue, and unlit traps (600+ males caught), showing red and yellow light disrupt mating far less than white or blue.
   - **Exposure duration:** Controlled exposure across 88 females under streetlight brightness, where the share stopping glowing after three days rose from 3% (no exposure) to 15% (short) and 90% (long).
   - **Mating delay and distance:** Field tracking of 51 females (1 night to mate in the dark vs. a median of 6 and up to 15 nights under lights) and shielded-LED trials showing a 1-in-20 male catch ratio at 10 metres and roughly twice as many males in dark traps even 55 metres away.
3. **Reader questions and answers (`Question 1` to `Question 5`):** Five prompts invite readers to look around at night-time lighting and predict research outcomes before checking the summary answers at the end.

## Technical Implementation

- **Static HTML and CSS:** Single-page semantic HTML5 (`<main>`, `<header>`, `<section>`, `<figure>`, `<ol>`) paired with a dark night-sky stylesheet (`Baloo 2`, `Nunito`, and `IBM Plex Mono`) and print styles (`@media print`).
- **Accessibility:** Includes `lang="en"`, screen-reader labels (`.sr-only`) for distinct reference link names, decorative SVG attributes (`aria-hidden="true"`), descriptive `alt` text on all seven illustrations, `44px` reference link targets, `:focus-visible` outlines (including `#refs` target focus), and `0` violations across 23 automated WCAG 2.2 AA checks (`axe-core`, `320px` reflow, `200%` zoom, text spacing, and focus indicators; standalone screen-reader testing not conducted).
- **Hosting:** Deployed directly from the `main` branch via **GitHub Pages**.

## Repository Structure

```text
.
├── README.md   # Project overview and documentation
├── index.html  # Illustrated web story, references, and further reading
└── 1.png..7.png # Seven bespoke story illustrations
```

## Research References

- Elgert, C. et al. (2021) 'The duration of artificial light defines sexual signalling in the common glow-worm', *Behavioral Ecology and Sociobiology*, 75(11). [doi:10.1007/s00265-021-03093-2](https://link.springer.com/article/10.1007/s00265-021-03093-2)
- Kivelä, L. et al. (2023) 'The color of artificial light affects mate attraction in the common glow-worm', *The Science of the Total Environment*, 857, 159451. [doi:10.1016/j.scitotenv.2022.159451](https://www.sciencedirect.com/science/article/pii/S0048969722065500)
- Owens, A. C. S. et al. (2022) 'Behavioral responses of bioluminescent fireflies to artificial light at night', *Frontiers in Ecology and Evolution*, 10. [doi:10.3389/fevo.2022.946640](https://www.frontiersin.org/articles/10.3389/fevo.2022.946640/full)
- Stewart, A. J. A., Perl, C. D. and Niven, J. E. (2020) 'Artificial lighting impairs mate attraction in a nocturnal capital breeder', *Journal of Experimental Biology*, 223(19). [doi:10.1242/jeb.229146](https://journals.biologists.com/jeb/article/223/19/jeb229146/225852/Artificial-lighting-impairs-mate-attraction-in-a)
- Van den Broeck, M. et al. (2021) 'Blinded by the light: Artificial light lowers mate attraction success in female glow-worms (*Lampyris noctiluca* L.)', *Insects*, 12(8), 734. [doi:10.3390/insects12080734](https://www.mdpi.com/2075-4450/12/8/734)

## Author

- **Creator:** Zinan (Sylvan) Yang ([GitHub](https://github.com/zyangcomm) | [Portfolio](https://zyangcomm.wordpress.com/)), MSc Science Communication, University of Sheffield
