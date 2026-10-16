# IB Chemistry Practice: Nomenclature, Isomers & Equations

A practice app for IB Diploma Chemistry, in a single web page. It has revision notes and auto-marked questions for:

| Unit | Syllabus | What it covers |
|------|----------|----------------|
| 01 Nomenclature | S3.2 | Stems, functional groups, numbering and the full IUPAC naming algorithm |
| 02 Isomers | S3.2.6, S3.2.7 (HL) | Chain, position and functional group isomers; primary/secondary/tertiary alcohols, halogenoalkanes and amines; counting isomers; cis-trans (alkenes, C3/C4 rings); optical isomers with wedge-dash drawings |
| 03 Equations & amounts | R2.1, R3.1.7, R3.2.4, R1.3, S3.1.5, S1.4 | Balancing equations (with a live atom tally), predicting products and salt formulas, moles, concentration, gas volumes, limiting reactant, % yield, % error, atom economy |

There is also an **Ions** section for drilling the ions you're expected to know.

## Getting it

You don't need to install anything. The whole app is the one file `index.html`, and it needs no internet connection once you have the file.

**Option 1: download the file**
1. On GitHub, open `index.html` in this repository.
2. Click the **Download raw file** button (the download arrow at the top right of the file view).
3. Double-click the downloaded `index.html`. It opens in your web browser.

**Option 2: download the whole repo**
1. On the repository's main page, click the green **Code** button, then **Download ZIP**.
2. Unzip it and double-click `index.html`.

**Option 3: clone with git**
```bash
git clone https://github.com/allencallum51-coder/chemistry-organic-naming-practice-IB.git
cd chemistry-organic-naming-practice-IB
open index.html        # macOS  (Windows: start index.html, Linux: xdg-open index.html)
```

**Option 4: put it online (optional)**
To get a link that works on any device, including your phone: in the repository go to **Settings → Pages**, set the source to **Deploy from a branch**, choose `main` and `/ (root)`, and save. After a minute or two the app will be at
`https://allencallum51-coder.github.io/chemistry-organic-naming-practice-IB/`.

It runs in any modern browser (Chrome, Edge, Firefox, Safari), on a computer, tablet or phone.

## Using it

The bar at the top has four sections:

- **Home**: an overview of the units and where to start.
- **Notes**: revision notes, grouped by unit. Use **Previous / Next** to move through the chapters. Questions in the tests link back to the notes they test ("Read the notes on this →").
- **Test**: practice questions.
  - Pick a unit with the tabs, then pick one or more topics and press **Start topic practice**.
  - **Practise weak areas** gives you more questions from the topics you've been getting wrong.
  - Answer, press **Check**, read the feedback, then go to **Next question**. You get a score summary at the end, and **Run it again** starts another round.
  - In balancing questions, the atom tally shows whether each element balances on both sides. You can hide it if you want more of a challenge.
  - The data panel in calculation questions shows the relative atomic masses (Ar) from the data booklet and the formulas you need.
- **Ions**: drills on the ions you need to know: charge only, type the formula yourself, or a mixed drill that includes the easily confused pairs.

**SL / HL switch:** use the SL/HL buttons to choose your level. With **SL** selected, HL-only content (marked HL) is hidden. With **HL** selected, you get everything.

### Saving your progress

Your scores, weak areas and SL/HL choice are saved in your browser (`localStorage`) on the device you use. They stay there between visits. They do **not** carry over to another browser or device, and they're lost if you clear your browser data or use a private/incognito window.

## Updating

When a new version is pushed, download `index.html` again, or run `git pull` if you cloned the repo. If you use GitHub Pages, the site updates on its own. Your saved progress is kept as long as you open the app from the same place in the same browser.
