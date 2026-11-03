# Abenteuer

Our games page. The start page (`index.html`, glittering magenta) lets you pick a game:

| Game | Folder | Status |
|---|---|---|
| Danger in the Jungle | [`danger-in-the-jungle/`](danger-in-the-jungle/) | playable |
| Danger in the Jungle 2 | — | coming soon |

At the bottom, **Mehr Spiele** links to Jonas' start page ([Jonas' Spiele](https://diemmarkus.github.io/maze/)).

Play: https://diemmarkus.github.io/danger-in-the-jungle/

---

## Danger in the Jungle

A painted, 2D-animation-style jungle game for the phone. You're a blue parrot having breakfast when you hear rumbling, whistling and sawing — workers are cutting down your jungle. Get the key from the boss and free your friend.

- **Title screen:** the house button goes back to Abenteuer; a wooden sign hanging in the jungle; pick difficulty and any of the 6 levels (all are open from the start), switch language (globe), read the rules (**?**).
- **Intro:** a short letterboxed scene with subtitles; skip it with the button or a tap.
- **Fly** with the joystick on the ground: touch anywhere in the bottom strip and it jumps under your thumb, then drag in any direction. It is analog — a small push flies slowly, a full push at full speed. Keyboard: arrow keys or WASD, `Esc`/`P` pauses.
- **Camera:** on a phone the view is zoomed in and follows the parrot; arrows at the screen edge point to workers (with a count), the boss and the door when they're off screen.
- The boss's six workers follow you along the ground and throw **ropes, nets, landing nets and baskets**. A raised arm and a red **!** means a throw is coming. Don't fly too close — they grab you.
- **Lure all 6 workers** to the left of the log. The six helmets at the top light up as they cross.
- Then fly to the **boss** and snatch the key from his neck (he shoos you away until all six are lured). The crew is stunned: fly through the **door** in the big tree, unlock the cage and free your friend. The workers leave and the forest grows back.
- **Caught?** You have to do the level again. Pause menu: resume, restart, menu.
- **Levels 1–3 (the clearing):** lure, snatch the key, free a friend — faster and more throws each level. The friend from level 3 is your purple partner from then on.
- **Levels 4–6 (the tall tree):** the camera scrolls up and down a huge tree with your nest at the top. Workers climb up the trunk and the vines; a round **drop button** (or `Space`) drops nuts and fruit (sticks in level 6). One hit knocks a worker down; after all 6 the boss climbs up and needs 3 hits. When he falls, fly down and take the key ring from his hip. If anyone reaches the nest, the level starts over.
  - **Level 4:** your partner sleeps on her branch by the nest.
  - **Level 5:** the intro shows your partner laying three eggs (plop, plop, plop) before she falls asleep; they wobble now and then. Once per level you can fly to your partner to wake her — she throws one perfect nut.
  - **Level 6:** the intro shows the eggs wobbling, cracking and the chicks popping out and cheeping; then the babies have been kidnapped into a cage on the ground, and each climber can throw one net at you. Take the key and free them — then you fly the chicks home, your partner wakes up and the whole family cuddles in the nest. **Difficulty:** Easy, Medium, Hard. Reached levels and the best time for a full run are kept per difficulty.
- Languages: EN, DE, FR, ES, IT, PT.

Single self-contained `danger-in-the-jungle/index.html` — no build step. GitHub Pages deploys from `main`.
