# Culturia

**Hands-only WebXR adventure where every answer is a spell.**
**Aventure WebXR jouée uniquement aux mains : chaque réponse est un sort.**

Built for the Meta VR Start Developer Competition 2026 (Productivity / Education).

## The story
The village of Kéla vanished because nobody could read the signs: the flood, the stars, the chronicles. The only survivor, Kaïro, learns he can travel back in time, but the clock is broken into five shards, each guarded by a mage. Here nobody fights with weapons. You fight with answers.

## How to play
- **Touch a tablet** with your index finger to give your answer. Kaïro, the hero you embody, calls the spell out loud.
- **Right answer:** the spell hits the mage and the matching skill grows (History, Geography, Sciences, Arts & Letters). Skills unlock more serenity (health) and stronger magic.
- **Wrong answer:** you lose serenity and the question comes back later.
- **Parry** the red spells with your hands while you think.
- 5 chapters: four mages, then the Sorcerer of Time. Progress is saved in the browser.

No controllers needed: the whole game works with hand tracking only.

## Run it
1. Open the GitHub Pages link of this repository in the **Meta Quest Browser**.
2. Press **Mixed reality (hands)** or **VR room (hands)**. Turn on hand tracking in the headset settings if prompted.
3. No headset? Press **Play in 3D preview** and tap the tablets and spells.

## Tech
Single-file WebXR app: three.js r128 (CDN), WebXR Device API with `hand-tracking`, procedural 3D models, procedural audio (Web Audio), no external assets.

## Honest limitations
Hand-tracking input was written to the WebXR standard and verified by simulation, but it needs more testing on real headsets. Questions are in French; the question format is easy to extend.

## Roadmap
More chapters (Africa-focused history, science, languages), custom decks for teachers, multiplayer duels.

---

## Résumé en français
**Culturia** est un jeu d'aventure en réalité virtuelle et mixte, joué uniquement avec les mains. Kaïro a perdu son village faute de savoir ; pour remonter le temps, il affronte cinq mages en répondant à des questions de culture générale. Chaque bonne réponse invoque un pouvoir et fait grandir ses compétences.
