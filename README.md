# Love Adventure 💗

A mobile-first interactive story game built from layered scenes, collectibles, memory moments, mini-games, and cinematic transitions.

## Felt-book engine

The experimental `felt-book-lab.html` scene uses a reusable layered-stage approach:

- background and environment layers
- character layer
- interactive object/hotspot layer
- foreground occlusion for depth
- effects and dialogue layers
- simple state changes for cinematic moments
- touch-friendly movement and actions

The goal is to create the feeling of an animated storybook while keeping the interaction lightweight and reliable on phones and tablets.

## Project structure direction

As the layered engine is integrated, reusable pieces will be organized with clear project-facing names such as `scene-engine`, `layers`, `characters`, `memory-scenes`, and `effects`.

Development notes and temporary implementation artifacts stay out of the player-facing experience.
