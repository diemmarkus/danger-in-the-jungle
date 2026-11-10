# Abenteuer

Our games page. The start page (`index.html`, glittering magenta) lets you pick a game:

| Game | Folder | Status |
|---|---|---|
| Danger in the Jungle | [`danger-in-the-jungle/`](danger-in-the-jungle/) | playable |
| Danger in the Jungle 2 | [`danger-in-the-jungle-2/`](danger-in-the-jungle-2/) | playable |
| Kobolde | [`kobolde/`](kobolde/) | level 1 playable |

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
  - **Level 4:** your partner sleeps on her branch by the nest. When you win levels 4 and 5 she wakes up and the two of you fly loops up the tree together.
  - **Level 5:** the intro shows your partner laying three eggs (plop, plop, plop) before she falls asleep; they wobble now and then. Once per level you can fly to your partner to wake her — she throws one perfect nut.
  - **Level 6:** the intro shows the eggs wobbling, cracking and the chicks popping out and cheeping; then the babies have been kidnapped into a cage on the ground, and each climber can throw one net at you. Take the key and free them — then you fly the chicks home, your partner wakes up and the whole family cuddles in the nest. **Difficulty:** Easy, Medium, Hard. Reached levels and the best time for a full run are kept per difficulty.
- Languages: EN, DE, FR, ES, IT, PT.

Single self-contained `danger-in-the-jungle/index.html` — no build step. GitHub Pages deploys from `main`.

---

## Danger in the Jungle 2

The parrot leaves the small clearing and flies through a huge, scrolling jungle (the camera follows in both directions; a map strip at the top shows the nest, the six missions and you).

- **Title screen:** same controls as part 1 — difficulty, start at any mission 1–6 or straight at the nest (boss fight), language (DE/EN), rules (**?**).
- **Intro:** the family in the nest, then the camera pans to the monkey in the net (“HILFE!”).
- **Six missions**, far apart: between two animals there's a long flight through the jungle (past plain jungle trees). Each mission is the same idea and gets harder:
  1. fly to the right tree and **pick** a nut, mango or coconut with your beak,
  2. fly above the worker who carries the tool and **drop** it on his head with the round button (a dotted line shows where it falls; it turns yellow when you're on target) — **BONK!**, he sees stars,
  3. while he's dizzy, **snatch the tool** from his hip (knife, key or scissors),
  4. fly to the animal and **free it**.
- | # | Animal | Trap | Tool | Fruit | Crew |
  |---|---|---|---|---|---|
  | 1 | Monkey | net hanging from a branch | knife | nut (high up) | 1 guard |
  | 2 | Toucan | cage hanging from a branch | key | mango | + 1 rope thrower |
  | 3 | Sloth | tied up under a branch | knife | coconut | + 1 net thrower |
  | 4 | Jaguar cub | cage on a cart | key | nut | foreman (2 hits) + 2 throwers |
  | 5 | Baby elephant | rope to a stake | scissors | mango | + 2 throwers |
  | 6 | Baby gorilla | big cage | key | coconut | foreman (2 hits) + 3 throwers |
- Throwers follow you and throw ropes, nets, landing nets and baskets; fly too close to a worker who isn't dizzy and he grabs you. **Caught** = that mission starts over from its checkpoint. A yellow arrow always points to the next thing to do, with a hint at the top.
- **Home:** after all six you fly back to the nest. You and your purple partner are both awake, hug and clack your beaks — then the **boss** comes and climbs your tree (a bit faster than in part 1). **Break a dry branch** off your tree (they glow), fly above him and drop it on his head. He has **3 lives**; each hit knocks him down the trunk. If he reaches the nest, the boss fight starts over. Broken branches grow back after a few seconds.
- **Ending:** the boss falls and runs away, all six animals come to the tree and cheer, the family cuddles in the nest.

Single self-contained `danger-in-the-jungle-2/index.html` — the characters (parrots, workers, boss, thrown things) reuse the drawing code from part 1.

---

## Kobolde

A soft, pastel fairytale-forest game (Hotel-Transylvania-style cartoon characters) in an old European forest. The main characters are **Lilly** (red hair with two buns, freckles, pink T-shirt with turquoise stripes, jeans, grey shoes, a green camping backpack with a sleeping mat on top and shoes hanging underneath) and, later, **Ria** (a faun girl). The kobolds show up later in the game — and they are not nice.

- **Level 1**
  - **Night:** Lilly sleeps alone in her sleeping bag deep in the forest. A blue and a purple parrot look after their three eggs in a nest above her. One egg wobbles, falls out and lands on her sleeping bag.
  - **The hand:** a round button with a hand appears — tap it (or `Space`/`Enter`). Lilly sits up and holds the egg up, the blue parrot fetches it and puts it back in the nest. "Danke!" — and Lilly falls asleep again.
  - **Morning:** walk through the forest with the same joystick as in Danger in the Jungle (keyboard: arrow keys / A, D).
  - **The gate:** at the end of the path stands a gate with a big sign: **BETRETEN VERBOTEN**. Tap right on the gate (or `Space`/`Enter` when you're close) and it creaks open. Lilly walks through… and something with glowing eyes watches from behind it.
- Languages: DE, EN (shares the language choice with the other games).

Single self-contained `kobolde/index.html` — the parrots reuse the drawing code from Danger in the Jungle.
