# 🦕 Data Dino

> *A Claude skill that interprets your data through the lens of dinosaurs and prehistoric events.*

---

## What it does

Data Dino turns dry data patterns into vivid paleontological storytelling.

Instead of "revenue declined in Q3", you get:

> *"Your revenue line is a **Brachiosaurus** that survived a **near-extinction event** in Q2 — and came back stronger."*

Every metric gets two things: a **dinosaur character** (what kind of creature this data is) and a **prehistoric event** (what happened to it). The result is short, punchy, and surprisingly accurate — and you'll never look at a drop in your data the same way again.

---

## Dinosaur roster

| Dinosaur | What it means |
|---|---|
| 🦖 **T-Rex** | Dominant peak. Towers over everything else in the dataset. |
| 🦕 **Brachiosaurus** | Slow, sustained, upward growth. The long game. |
| 🫎 **Velociraptor** | High volatility. Fast, unpredictable swings. Pack behaviour. |
| 🌵 **Stegosaurus** | Regular, rhythmic peaks. Cyclical data with a clear beat. |
| 🛡️ **Triceratops** | Holding its ground under pressure. Stable but stressed. |
| 🦅 **Pterodactyl** | An outlier that doesn't obey the ground-level trend. Flies above the data. |
| 🪨 **Ankylosaurus** | Flat. Armoured. Resilient but going nowhere. |
| 🔔 **Diplodocus** | Normal distribution. That arching body is basically a bell curve. |
| ❓ **Spinosaurus** | A metric everyone thinks they understand — until the data shifts again. |
| 📡 **Parasaurolophus** | The leading indicator. Announces what's coming before the others notice. |

---

## Prehistoric event glossary

| Event | Trigger |
|---|---|
| **Extinction event** | Sudden, catastrophic drop |
| **Ice age** | Slow, sustained decline |
| **Near-extinction event** | Sharp drop that didn't quite finish the job |
| **Post-extinction radiation** | Recovery and growth after a crash |
| **Evolutionary adaptation** | Steady, consistent improvement |
| **Migration season** | Cyclical, wave-like pattern |
| **Living fossil period** | Long plateau — exists, unchanged |
| **Cambrian explosion** | Rapid chaotic spike, everything at once |
| **Predator vs. prey dynamics** | Two competing trends pushing against each other |
| **Fossil record gap** | Missing data — a gap in the geological layers |

---

## How to use it

### 1. Install the skill
Download `data-dino.skill` from this repo and install it into your Claude skills directory.

### 2. Upload your data
Data Dino accepts:
- CSV files
- Excel files (.xlsx)
- Pasted tables
- JSON

### 3. Let the dig begin
Data Dino will greet your dataset, show you what it found (columns, row count, data types), and ask which columns to excavate — up to 2 (one for X axis, one for Y axis).

### 4. Read your field report
You'll get a single short paragraph — max 4 lines — with your dinosaur character and prehistoric event **bolded** so you always know exactly what's been interpreted.

---

## Example output

**Input**: Monthly revenue data with a mid-year crash and recovery.

**Output**:
> *Your revenue line is a **Brachiosaurus** that stumbled into a **near-extinction event** mid-2023 — crashing from a steady climb all the way down to a skeleton crew in September. But this species is resilient: what followed was a textbook **post-extinction radiation**, clawing back toward its evolutionary peak by early 2024, and still climbing.*

---

## Why I built this

Data storytelling is one of the hardest things to do well. Numbers don't stick — stories do. Data Dino is an experiment in using AI to create *memorable* interpretations of data, not just accurate ones.

The metaphors are designed to be earned, not bolted on. A **Triceratops** isn't just "stable" — it's stable *under pressure*, horns forward, refusing to fall. A **Velociraptor** isn't just "volatile" — it's fast, unpredictable, and hunting in packs.

If someone reads your Data Dino output and thinks *"that's actually exactly right"* — that's the goal.

---

## Contributing

Found a data pattern that needs a new dinosaur? Open an issue or submit a PR with your proposed addition to the character dictionary. The Mesozoic era is large — there's room for more specimens.

---

## License

MIT — free to use, share, and remix. Just don't cause a **mass extinction event** with it.
