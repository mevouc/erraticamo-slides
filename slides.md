layout: true

background-image: url(resources/camo-8000px-transparent.png)
background-size: 2000px, 2000px

---

background-color: #111111
class: center, middle, white-text

# Procedural Generation in C++ vs. Photoshop:
## Learn, Benchmark, and Prove Nothing

06/12/2018

Meven 'mevouc' Courouble

???

# Learn
## The project: ErratiCamo
### Purpose: use Perlin noise to produce camo texture
### Perlin noise
### Treshold & layers
### Color & tresholds tweaking

# Benchmark
## Time spent
### Prepare & setup
### Code / script
## Run time
## Ease to improve & customize

# Prove nothing = Conclusion
## Use tools made for what you want to do

## Github link

---

# Idea

### What I wanted

- Learn Ruby
- Play with a new image processing library
- Do a side-project with procedural generation

--

### What I actually did

- C++ project with OpenCV library (for the secont time)
- Learned procedural generation
- Lost my time
- Did another version using Photoshop

---

background-color: #111111
class: center, middle, white-text

# Learn

---

background-color: #111111
class: center, middle, white-text

# ErratiCamo

---

# The project

- Generate multi-layers camo textures

.right[TODO IMAGE OF RESULT]

---

# Perlin noise

- Gradient noise
- Developed by Ken Perlin in 1983 (published in 1985)
- Used in texture, world-maps, clouds generation

---

# Perlin noise

TODO IMAGE OF RANDOM 1D NOISE
TODO IMAGE OF 1D PERLIN NOISE

---

# Perlin noise

TODO IMAGE OF 2D PERLIN NOISE

---

# Perlin noise

TODO IMAGE OF 2D PERLIN NOISE WITH OCTAVES (cloud like)

---

# Binarize perlin noise

TODO IMAGE OF PERLIN NOISE BINARIZED

---

# Layering

TODO SUCCESIVE IMAGES OF LAYERED PERLIN NOISED BINARIZED

---

# Tweaking

- Change tresholds so layers do not cover the same surface
- Change colors to have camo-like look

---

---

background-color: #111111
class: center, middle, white-text

# Questions?

---

background-color: #111111
class: center, middle, white-text

<img src="resources/shepard.jpg" alt="Plating" width="600px">
