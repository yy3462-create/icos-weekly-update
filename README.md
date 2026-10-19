# ICOS weekly update · 7 Oct 2026

Interactive weekly update for the ICOS modular legged robot. Open `index.html` (or the GitHub Pages link) in a browser; it has four tabs:

1. **Whole robot** (`robot.html`): the body with the same quick-release dock on all 20 faces, its electronics and four V83 legs; 14 assembly steps, exploded view, move a leg to another face, size checks.
2. **Quick release** (`release.html`): how a leg goes on and what holds it, in 12 animated steps (two printed spring bolts in the leg root, two stop walls printed with the body). Starts at 2× speed.
3. **Process** (`process.html`): how the dock changed from V79 to V83 (30 Sep to 3 Oct), what was checked, what the reviews found, and the first printed parts (5 to 7 Oct). Its pictures are inside the file; the 7 Oct video is `video_safety_clip_20261007.mp4`.
4. **Earlier weeks**: the animations and pages of the earlier updates and the intermediate versions, as they were then:
   - `robot_v81.html` (3 Oct, dock on all 20 faces) and `robot_v80.html` (2 Oct, triangular dock): assembly benches, English;
   - `assembly.html` (1 Oct, V79 latch in 9 steps) and `robot_v79.html` (1 Oct, whole robot with V79 legs);
   - `assembly_v70.html` (24 Sep, V70 latch), `media/print_test_v70.mp4` (24 Sep, first printed dock) and `leg.html` (24 Sep, leg V70 next to V69).
   The two latch animations start at 2× speed.

Everything is static HTML. The 3D views use three.js r128 (`vendor/three.r128.min.js`, MIT licence). Links like `index.html#release` or `index.html#earlier=robot_v80` open a tab directly.

To update: replace the files on github.com (*Add file → Upload files*), then *Commit changes*. Pages rebuilds in about a minute.


## V83 spring-bolt assembly guide (19 October 2026)

- `assembly-v83-spring-bolt/`: focused spring / sliding bolt / M2×6 stop-screw assembly animation.
- Includes a 54-second GIF and a standalone offline ZIP. The two existing tray assembly pages are unchanged.
- CAD meshes and nominal dimensions illustrate the assembly; this is not physical fit or durability qualification.
