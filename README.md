# isometric cubes ASK // py5

generative art sketches written in python/py5

refactored/adapted from ASK's original p5.js >> [https://editor.p5js.org/asymptoticSystemKey/full/bWa1wvK3r](https://editor.p5js.org/asymptoticSystemKey/full/bWa1wvK3r)

| version | behaviour                                                                                                                                    |   |
| ------- | -------------------------------------------------------------------------------------------------------------------------------------------- | - |
| **v1**  | randomly spawns grid-aligned isometric cubes in a muted purple ASK color palette                                                             |   |
| **v2**  | randomly spawns grid-aligned isometric cubes in a muted purple ASK color palette // cubes spawn within a radius centered around mouse cursor |   |

---

## minimal install >> macOS / Linux / Windows

```bash
# 1/ create + activate a fresh env // recommended
conda create -n py5env python=3.10 -y -c conda-forge
conda activate py5env

# 2/ make sure Java 17 is present // py5 needs it
conda install -c conda-forge openjdk=17 -y

# 3/ install py5 // pre‑release is where the cool features live
pip install --pre py5
```

that’s it! run either sketch >>

```bash
python isometric_cubes_v1.py   # full random
python isometric_cubes_v2.py   # mouse‑centred
# click anywhere in the window >> PNG output saved beside the script

```

> **heads‑up:** on the first launch, py5 will download the Processing 5 core // be patient, it’s automatic

---

## running without Conda

if you’d rather stay in system Python, just be sure you have >>

* **Python ≥ 3.8**
* **Java Runtime 17** // set `JAVA_HOME` or put `java` on your PATH

then:

```bash
pip install --pre py5
```

---

## license

Apache 2.0 >> see the header in each `.py` file for details