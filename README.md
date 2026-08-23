# MindCube: Spatial Mental Modeling from Limited Views

Project page for the paper **"MindCube: Spatial Mental Modeling from Limited Views"** (arXiv:2506.21458), live at [mind-cube.github.io](https://mind-cube.github.io/).

MindCube is a spatial reasoning benchmark that asks whether Vision-Language Models (VLMs) can imagine a full scene from just a few views, the way humans form spatial mental models of unseen space. The benchmark contains **21,154 questions across 3,268 multi-view images**, testing three abilities from limited views: representing positions (cognitive mapping), orientations (perspective-taking), and dynamics (mental simulation for "what-if" movements). Existing VLMs perform near-randomly on it. Jointly training a model to first generate a cognitive map of the scene and then reason over it ("map-then-reason") lifts accuracy from 37.8% to 57.8%, and adding reinforcement learning pushes it to 61.3%.

## Links

- Paper: <https://arxiv.org/abs/2506.21458>
- Code: <https://github.com/mll-lab-nu/MindCube>
- Dataset: <https://huggingface.co/datasets/MLL-Lab/MindCube>
- Model checkpoints: <https://huggingface.co/MLL-Lab/models>
- MindCube Challenge (CVinW Workshop @ CVPR 2026): <https://mind-cube.github.io/challenge>
- LLM-facing summary: <https://mind-cube.github.io/llms.txt>

## Citation

```bibtex
@misc{wang2025mindcube,
  title={MindCube: Spatial Mental Modeling from Limited Views},
  author={Qineng Wang and Baiqiao Yin and Pingyue Zhang and Jianshu Zhang and Kangrui Wang and Zihan Wang and Jieyu Zhang and Keshigeyan Chandrasegaran and Han Liu and Ranjay Krishna and Saining Xie and Jiajun Wu and Li Fei-Fei and Manling Li},
  year={2025},
  eprint={2506.21458},
  archivePrefix={arXiv},
  primaryClass={cs.AI},
  url={https://arxiv.org/abs/2506.21458},
}
```

## About

MindCube is a project of the [MLL Lab](https://mll-lab-nu.github.io) at Northwestern University (PI: [Manling Li](https://limanling.github.io/)), with collaborators at Stanford University, New York University, and the University of Washington.

## Website development

This site is built with [Astro](https://astro.build). All commands are run from the root of the project:

| Command           | Action                                       |
| :---------------- | :------------------------------------------- |
| `npm install`     | Install dependencies                         |
| `npm run dev`     | Start local dev server at `localhost:4321`   |
| `npm run build`   | Build the production site to `./dist/`       |
| `npm run preview` | Preview the build locally, before deploying  |
