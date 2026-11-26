# Object Field Guide

How objects are joined, touched, proportioned and shaped. With reasons.

A field guide identifies species in the wild. This one does the same with the parts of objects. Each part (a joint, a snap-fit, a button, a knob, a proportion, a form) is treated as a species, with the same fields every time, so any two can be compared line by line. Open `index.html` for the front page: the volumes and an A–Z index of terms.

A companion to the [Sound Field Guide](https://github.com/rhzuccarelli/SoundFieldGuide). Like it, every volume is a single HTML file with no build step and no dependencies. Open it in a browser, or serve the folder with GitHub Pages.

## Volumes

| | Volume | File | Status |
|---|---|---|---|
| I | Joints | — | in preparation |
| II | Snap-fits | — | in preparation |
| III | Actuators | `actuators.html` | Rev. A |
| IV | Buttons | — | in preparation |
| V | Proportions | `proportions.html` | Rev. A |
| VI | Forms | `forms.html` | Rev. A |

## Actuators — `actuators.html`

How a person asks an object to do something, and how the object answers.

1. **How to read this volume.** The species card and what `[verify]` means.
2. **Four questions.** What does the finger do? Does it stay where you leave it? Steps or continuous? Can you use it without looking? Includes an interactive identification key that names the species.
3. **Eight species:** momentary push button, latching push button, toggle, rocker, slider, rotary with detents, continuous rotary and wheel.
4. **Lab: feel and sound.** Four synthesised actuators (push, toggle, rotary with switchable detents, slider) with Web Audio clicks, to compare what happens at the end of each gesture.
5. **Quick reference.** One table comparing all species.

## Proportions — `proportions.html`

Choosing dimensions without deciding each one.

1. **Three questions.** Does it have to fit something? Does it come in sizes? Is it only about how it looks?
2. **Six systems:** module (Lego, Gridfinity, Eurorack, 19-inch racks), √2, simple ratios (and their musical intervals), the golden ratio (with a warning), Renard preferred numbers and human scale.
3. **Lab: snap a dimension.** Type a size and get the nearest R10 and R20 values and the nearest multiple of your module; draw a face in any ratio.
4. **Quick reference.**

## Forms — `forms.html`

Edges, corners and volumes. Chosen for the hand and for light.

1. **Three questions.** Where does the light go? Where does the hand go? How is it made?
2. **Seven species:** primitive, constant radius, continuous curvature (G2), superellipse, chamfer, sharp edge and draft.
3. **Lab: corners.** What an outer radius does to a wall of a given thickness, and the superellipse from circle to square.
4. **Quick reference.**

## The species card

Every entry has the same fields:

- **Identify.** How to recognise it on an object.
- **Use when / Avoid when.** The reasoning.
- **Proportion / Numbers.** Rules and starting dimensions. Values marked `[verify]` come from common practice and should be tested on a printed sample.
- **Make / In CAD.** How it is built, or how to apply it in Onshape.
- **Feel and sound / What it says / Light.** The sensory field changes by volume: sound for actuators, character for proportions, light for forms.
- **Look-alikes.** Which species it is confused with, and the difference.
- **Habitat.** Real products where it lives, with designer and year.
- **In my work.** Where it appears in my own projects.

Drawings are schematic line drawings made for the guide, not photographs of the referenced products.

## Design

Set in the zuccarelli design system: Schibsted Grotesk for words, OCR-B for anything a machine would read (indices, codes, values), a √2 type scale on a 14 px base (56 / 14 / 10), ink on paper, no accent colour. OCR-B is the free, MIT-licensed redraw from the OCR-Bitcoin project; its licence is in `assets/fonts/OCR-B-LICENSE.txt`.
