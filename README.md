# Akil Srirama – portfolio site

A single-page portfolio. No build step: `index.html` is the whole site.

## Put it online with GitHub Pages

1. Create a new public repository on GitHub named `YOUR-USERNAME.github.io`.
2. Upload everything in this folder (`index.html`, the `assets` folder, this README) to the repository.
3. In the repository, open **Settings → Pages**, set the source to **Deploy from a branch**, pick `main` and `/ (root)`, and save.
4. After a minute or two the site is live at `https://YOUR-USERNAME.github.io`.

## What's interactive

- **"What are you hiring for?"** Visitors pick a role type (automation, quality, manufacturing, design, project coordination). The intro changes to match, and the related experience, projects and skills get marked in yellow further down.
- **Chessboard demo:** "Play a move" runs the CXRA's six steps on a small board.

To change the intro for a role, edit the `PITCH` text near the bottom of `index.html`.
To change what gets marked for a role, edit the `data-tags` on that bullet, project or skill.
Colours are the first block in the `<style>` section.

## Add photos or videos to projects

Each project shows a line drawing until you add real media. Drop a file into `assets/` with one of these names and it replaces the drawing automatically.
Video (`.mp4`) is used if present, otherwise an image (`.jpg`, `.png`, or `.webp`).
For CXRA, a photo or video appears above the simulation, and the simulation stays.

| Project | File name |
|---|---|
| Chess eXecution Robotic Assembly | `cxra.mp4` or `cxra.jpg` |
| PLC-based smart home automation | `plc-home` |
| Mini smart home and security system | `mini-home` |
| Custom industrial tooling | `tooling` |
| Robotic prototyping | `robots` |
| Circuitry and signal analysis | `circuits` |
| Sump pump water level sensor | `sump` |

Keep videos short and small (under about 10 MB) so the page loads quickly.

## Edit the content

Open `index.html` in any text editor. The text is in plain HTML in the order it appears on the page.
Colours and fonts are set at the top of the `<style>` block under "Tokens".

## Update the resume

Replace `assets/Akil_Srirama_Resume.pdf` with a new file of the same name.
The copy here leaves out the phone number, since the site is public.
