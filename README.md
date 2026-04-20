# riscvthai/games

**RISC-V Educational Games Suite** — simple browser and CLI games for learning RISC-V concepts. No install, no framework, runs anywhere.

Hub at: https://games.riscvthai.org/  
Part of the [RISC-V International Academic \& Training SIG](https://lists.riscv.org/g/sig-academia-training) educational initiative.

\---

## Design principles

* **Runs anywhere** — static HTML/JS or pure C CGI. Phone, laptop, village hotspot.
* **Forkable** — content lives in plain JS arrays or C structs. Translate, extend, adapt.
* **Practical, not esoterica** — games teach concepts students will use, not facts they should look up on the green card.
* **Peer learning** — knowledge flows both ways. Games work in a classroom or alone.

\---

## Games

### Live

|game|url|teaches|status|
|-|-|-|-|
|pseudobingo|[pseudo.riscvthai.org](https://pseudo.riscvthai.org/)|pseudo vs. real instructions|live|
|rvcbingo|[rvcbingo.riscvthai.org](https://rvcbingo.riscvthai.org/)|RVC compressed instructions|live|
|jumpviz|[jumpviz.riscvthai.org](https://jumpviz.riscvthai.org/)|JAL/JALR control flow|live|
|regpressure|[regpressure.riscvthai.org](https://regpressure.riscvthai.org/)|the register file — GPR through PMP, all 7 layers|live|

### In development

|game|teaches|mechanic|
|-|-|-|
|fridge|instruction field layout — why, not memorize|drag-and-drop magnet builder|
|icebox|instruction format constraints|slotted field validator|
|toolchain-snake|.c → ELF pipeline, de-mystify the tools|worm/snake, each segment is a tool|

### Proposed

|game|teaches|mechanic|source|
|-|-|-|-|
|fence/|memory ordering, when to use which fence|turn-based puzzle|—|
|physical|32-bit encodings as wearable objects|shoelaces, bracelets, jewelry|SIG meeting Mar 2026|

\---

## How to fork any game

1. Clone the individual repo (not this one)
2. Edit the JS content array or C data table
3. Translate UI strings if needed
4. Deploy — static files, any web server

See `TEMPLATE-README.md` for the new game starter template.

## How to contribute a new game

1. Copy `TEMPLATE-README.md` to your new repo
2. Fill in the pedagogy table — what does it teach, why is it practical?
3. Open an issue or post to the [SIG mailing list](https://lists.riscv.org/g/sig-academia-training)

No coding required to propose an idea. Physical games, CLI games, browser games all welcome.

\---

## Repository map

```
github.com/riscvthai/
  games/          ← this repo, suite index
  pseudobingo/    ← pseudo.riscvthai.org
  rvcbingo/       ← rvcbingo.riscvthai.org
  jump-viz/       ← jumpviz.riscvthai.org
  regpressure/    ← regpressure.riscvthai.org
  fridge/         ← fridge.riscvthai.org (in dev)
  icebox/         ← icebox.riscvthai.org (in dev)
```

\---

## History

* Feb 2025 — pseudobingo debuts at World RISC-V Days, San Jose
* Mar 2026 — SIG Academia \& Training adopts games as deliverable direction
* Mar 2026 — rvcbingo live; fridge/icebox in prototype
* Apr 2026 — regpressure debuts at Andes Technology RISC-V deepdive, San Jose — register file breakout game, GPR through PMP, 7 levels

## License

MIT throughout. Fork freely.

## Contact

Paul Sherman — Chair, RISC-V International Academic \& Training Committee  
https://riscvthai.org

