# Realtime Filter — PoseNet Prototype

A webcam filter exercise exploring nose-landmark detection.

**Repository created:** 2022-03-11  
**Project status:** Learning project / historical snapshot  
**Earliest recorded commit (author date):** 2022-03-10

## Features and implementation

- P5.js camera canvas.
- Ml5 PoseNet initialization.
- Nose-coordinate logging.
- Snapshot export.

## Technologies

HTML, CSS, JavaScript, Bootstrap, jQuery, p5.js, ml5.js, PoseNet.

## Project structure

| File | Purpose |
| --- | --- |
| [`index.html`](index.html) | Main page and user interface |
| [`main.js`](main.js) | Project-specific JavaScript |
| [`style.css`](style.css) | Page styling |

Key functions in the source:
- `main.js`: `gotPoses()`, `take_snapshot()`.

## Run or explore locally

```bash
git clone https://github.com/Avenger-Sonic123/Project-113.git
cd Project-113
python -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) in your browser. The local server requires Python 3; browser-based dependencies may also require internet access.

Allow camera access, inspect the landmark logs and use the snapshot control.

## Current status and limitations

The mustache overlay is not loaded or rendered; the pose guard also needs attention.

## Related project snapshots

Other repositories in this project family:
- [project-114](https://github.com/Avenger-Sonic123/project-114) — repository created 2022-03-11
- [mustache-thingy](https://github.com/Avenger-Sonic123/mustache-thingy) — repository created 2022-06-22

---

Source reference: [`0b5f0990`](https://github.com/Avenger-Sonic123/Project-113/tree/0b5f0990457e7cce80ffd6a41414ad1defa242cb) on `main`, verified against GitHub on 2026-11-24. Documentation is based on static source review; runtime behavior has not been tested.
