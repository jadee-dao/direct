# DIRECT: When and Where Should You Allocate Test-Time Compute in Embodied Planners?

Project page for **DIRECT**, a routing framework that allocates test-time compute per task
for embodied VLM planners — matching a stronger model's success at up to **65% lower latency**
across chain-of-thought depth, model size, and memory history.

By Jadelynn Dao\*, Milan Ganai\*, Yasmina Abukhadra, Ajay Sridhar, Mozhgan Nasr Azadani,
Katie Luo, Clark Barrett, Jiajun Wu, Chelsea Finn, and Marco Pavone
(Stanford University, University of Waterloo, NVIDIA). \*Equal contribution.

> Paper submitted to CoRL 2026. Paper (arXiv) and code links coming soon.

🔗 Live site: https://jadee-dao.github.io/direct/

## What's on the page

- **Video overview** — narrated walkthrough of the method and results, with a collapsible transcript.
- **Abstract** — the paper's abstract.
- **Three Axes, Three Distinct Gains** — chain-of-thought, model size, and memory.
- **How DIRECT Works** — the lightweight router and its inference pipeline.
- **Key Results** — simulation (VLABench, RoboMME) and hardware (Franka DROID) results.
- **Hardware Demos** — link to the interactive demos at https://jadee-dao.github.io/direct/video-demos-html/

## Repository layout

- `index.html` — the full single-page site.
- `static/css/` — styles (`index.css` plus Bulma and component CSS).
- `static/js/` — page scripts (carousel, slider, etc.).
- `static/videos/` — the video overview (`direct_corl_2026_video.mp4`) and its `transcript.txt`.
- `static/images/` — figures, hero graphic, and social preview image.

## Local development

It's a static site — open `index.html` directly, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

Hosted on GitHub Pages from this repository; pushing to `master` publishes the site.

## Acknowledgments

Built from the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template),
adapted from the [Nerfies](https://nerfies.github.io/) project page.

## License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
