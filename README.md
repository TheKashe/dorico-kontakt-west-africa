# Dorico configuration to work with Kontakt - West Africa VST

## Installation

1. In Dorico setup, create a new player and click "Import Kit" and import percussion-kit-djembe.doricolib

2. Create another player and import kit percussion-kit-dunun.doricolib

3. In Play menu, go to play->Percussion maps and import percussion-map-djembe.doricolib and percussion-map-dunun.doricolib

4. Create Kontakt VST player, load your instruments

5. Map player instruments to kontakt, picking the right channel

6. Click settings next to Kontakt VST

7. Depending on Djembe/one of the Dununs, select the right map to use

## Example project

See kontakt-west-africa-example for usage (complete installation steps 1-3 before opening the project!)

## Overview

### Djembe

Dorico comes with Djembe, but it has no playing techniques for it. Kontakt - West Africa has (L & R) Bass, Tone and Slap (and some others which are not mapped in this version).

To support playing techniques, Djembe is added as a Percussion Kit, although it is a single instrument.

## Dunun

A single percussion kit is used for Dundunba, Sangban and Kenkeni. As Dununs have bells, they are represented as percussion kit consisting of a bell (Bongo Bell (Low)) and a Bass drum.

Dunun supports Bass (natural) and Muffled playing techniques.

## Todo

Map additional playing techniques and add support for L/R hand.