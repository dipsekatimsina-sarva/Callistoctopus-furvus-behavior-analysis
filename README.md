# Skin Patterning and Behavioral Ecology of *Callistoctopus furvus* in South Caicos

**Institution:** School for Field Studies, Center for Marine Resource Studies  
**Location:** South Caicos, Turks and Caicos Islands, British West Indies  
**Supervisor:** Dr. C.E. O'Brien  
**Co-authors:** Izzy Desjardins (Dickinson College), Maddie Marquardt (Davidson College)  
**Date:** November - December 2023

Field and video-based study investigating the relationships between skin patterning, substrate, behavior, and light color in a recently described nocturnal octopus species.

[View full research paper (PDF)](paper/Maddie_Dipseka_Izzy_CFurvusPaper.docx%20-%20Google%20Docs....pdf)

---

## Overview

*Callistoctopus furvus* is a nocturnal octopus species inhabiting the shallow waters of the Western Atlantic. It was only recently distinguished from *C. macropus* in the Eastern Atlantic, meaning very little is known about its behavior and ecology. This study examined how skin patterning in *C. furvus* relates to substrate type and behavior, and whether red light produces less behavioral disturbance than white light during nocturnal observation.

*C. furvus* is a mesopredator that acts as a trophic bridge in marine ecosystems -- preying on benthic species while being preyed upon by larger pelagic organisms. Understanding its behavior is important for interpreting its ecological role and for developing better methods of studying nocturnal marine animals.

---

## Research Questions

1. How do various substrates relate to the skin patterning of *C. furvus*?
2. How do different behaviors relate to skin patterning?
3. How does *C. furvus* react to red versus white light?

---

## Field Methods

Dives were conducted nightly from approximately 19:30 to 21:00 at 9 sites around South Caicos. Video footage from previous research seasons (July 2020 to April 2023) was also included in the analysis, bringing the total to 14 research sites.

Researchers used Nikon CoolPix W300 underwater cameras with 5000K SeaDragon lights. The dive team searched in a diamond formation using white light until *C. furvus* was located, then switched to red light for filming. Dives ranged from 40 to 70 minutes.

---

## Data Analysis

Videos were analyzed second-by-second, documenting behavior, skin pattern, and substrate for each second of footage. All videos were reviewed by two researchers independently, then compared and reconciled.

Six skin patterns were classified: Stippled, Mottle, Brick Red with White Arm Spots, Brick Red and White Elements, Racing Stripe, and Polka Dots.

Nine behaviors were coded: Stationary, Crawling, Jetting, Parachute Attack, Bipedal Locomotion, Burrowing, Entering Hole, Arm Capture, and Arm Exploration.

Statistical analysis was performed in R using chi-square goodness of fit tests, post-hoc binomial tests (EMT package, Holm correction), Welch t-tests, and Wilcoxon tests.

```r
library(EMT)      # post-hoc binomial tests
library(ggplot2)  # stacked bar charts
```

---

## Key Findings

**Substrate and skin pattern:** Certain skin patterns appeared significantly more often on specific substrates. On Bedrock or Boulder, Stippled and Brick Red with White Arm Spots were overrepresented. On Green Algae, Mottle and Polka Dot were overrepresented. These patterns suggest *C. furvus* actively adjusts its coloration to match or contrast with its environment depending on context.

**Behavior and skin pattern:** Mottle was significantly overrepresented during Burrowing and Parachute Attack. Polka Dot and Brick Red and White Elements appeared most during Jetting, consistent with deimatic behavior. Brick Red with White Arm Spots was significantly associated with Entering Holes.

**Red vs. white light:** Stationary behavior was significantly more prevalent under red light (70.7%) compared to white light (28.6%), suggesting red light is less disruptive to natural foraging behavior.

---

## Implications

The results suggest that *C. furvus* makes moment-to-moment decisions about skin patterning based on substrate and behavioral context, using both crypsis and deimatic displays as survival strategies. Red light is a more appropriate tool for observing natural octopus behavior in future field research.

---

## Tools

- **R** (v4.2.2) -- statistical analysis
- **ggplot2** -- data visualization
- **EMT** -- post-hoc binomial tests
- **Nikon CoolPix W300** -- underwater video collection
- **SeaDragon 5000K lights** -- white and red light filming

---

## Author

**Dipseka Timsina**  
School for Field Studies, Marine Resource Studies Study Abroad, Fall 2023  
[dipsekatimsina75@gmail.com](mailto:dipsekatimsina75@gmail.com) | [LinkedIn](https://www.linkedin.com/in/dipsekatimsina/)

---

## Acknowledgments

This work was made possible by the School for Field Studies. Special thanks to Dr. C.E. O'Brien, Camille Dedeaux, Kort Alexander, Clarence Stringer, Heidi Hertler, John DeBuysser, Natalie Ritter, Miranda Williams, Bill Bigelow, and Norman Alterado for their academic, logistical, and waterfront support.

---

## License

This project is open-source under the [MIT License](LICENSE).
