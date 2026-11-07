# BUTEX CGPA Calculator

A fast, single-file GPA and CGPA calculator for B.Sc. in Textile Engineering students at the Bangladesh University of Textiles (BUTEX). No install, no build step, no dependencies.

## Features

- **Four departments:** Apparel (default), Wet Process, Fabric and Yarn Engineering, with preloaded courses and credits for all 8 terms.
- **Term GPA:** pick any term, enter results per subject, and see the GPA update live.
- **Flexible input:** enter marks %, grade points or letter grades.
- **CGPA:** combine all terms or any subset (by term or level), with a separate projection that includes expected GPAs for upcoming terms.
- **Direct GPA entry:** type a term GPA straight in when you don't have subject-level results.
- **Validation:** invalid entries are highlighted and left out of the calculation.
- **Light and dark mode:** follows your device and can be toggled manually.
- **Auto-save:** progress is stored in your browser, separately for each department.
- **Responsive:** works on phones, tablets and desktops.

## Usage

Open `index.html` in any modern browser, or host it on GitHub Pages.

1. Choose your department.
2. In **Term GPA**, select a term and enter your results.
3. In **CGPA**, choose which terms to include and read your overall result.

## Grade scale

| Marks | Grade | Point |
|-------|-------|-------|
| 80–100 | A+ | 4.00 |
| 75–79 | A | 3.75 |
| 70–74 | A− | 3.50 |
| 65–69 | B+ | 3.25 |
| 60–64 | B | 3.00 |
| 55–59 | B− | 2.75 |
| 50–54 | C+ | 2.50 |
| 45–49 | C | 2.25 |
| 40–44 | D | 2.00 |
| 0–39 | F | 0.00 |

GPA is the sum of (grade point × credit) divided by the sum of credits.

## Data notes

- Fabric Engineering Level 4 has no subject list in the source curriculum, so those terms use direct GPA entry.
- Yarn Engineering Level 4 Term 1 lists 20 credits in the course table but 17 in the summary. The calculator uses the course table.

## Tech

Plain HTML, CSS and JavaScript in one file. Data is saved with `localStorage`.

## Disclaimer

An unofficial tool. Course data is transcribed from the supplied curriculum, so check results against your official transcript.
