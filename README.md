# [PixTalk: Controlling Photorealistic Image Processing and Editing with Language (ICCV 2025)](https://openaccess.thecvf.com/content/ICCV2025/html/Conde_PixTalk_Controlling_Photorealistic_Image_Processing_and_Editing_with_Language_ICCV_2025_paper.html)

**[Marcos V. Conde](https://mv-lab.github.io/)**, [Zihao Lu](), [Radu Timofte](https://scholar.google.com/citations?user=u3MwH5kAAAAJ&hl=en)

*Computer Vision Lab, University of Wuerzburg*

[![paper](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)](https://openaccess.thecvf.com/content/ICCV2025/html/Conde_PixTalk_Controlling_Photorealistic_Image_Processing_and_Editing_with_Language_ICCV_2025_paper.html
)
[![Hugging Face](https://img.shields.io/badge/Demo-%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/spaces/marcosv/InstructIR) 
[![Replicate](https://img.shields.io/badge/Demo-%F0%9F%9A%80%20Replicate-blue)](https://replicate.com/mv-lab/instructir) - Demos upcoming


### TL;DR: quickstart

> Text-guided image generation and editing is emerging as a fundamental problem in computer vision. However, most approaches lack control, and the generated results are far from professional photography quality standards. In this work, we propose the first approach that introduces language and explicit control into the image processing and editing pipeline. PixTalk is a vision-language multi-task image processing model, guided using text instructions. Our method is able to perform over 40 transformations --the most popular techniques in photography--, delivering results as professional photography editing software. Our model can process 12MP images on consumer GPUs in real-time (under 1 second). As part of this effort, we propose a novel dataset and benchmark for new research on multi-modal image processing and editing.

<br>

<a href="https://mv-lab.github.io/"><img src="ICCV PixTalk Poster.png" alt="PixTalk ICCV 2025" width=100%></a>

<br>

## Other relevant stuff

- **[A Tour Through AI-powered Photography and Imaging, ICCV 2025 Tutorial](https://mv-lab.github.io/neuralisp-iccv25/)**
- [InstructIR: High-Quality Image Restoration Following Human Instructions (ECCV 2024)](https://github.com/mv-lab/InstructIR)
- [Bokehlicious: Photorealistic Bokeh Rendering with Controllable Apertures (ICCV 2025)](https://arxiv.org/abs/2503.16067)
- [Towards Unified Image Deblurring using a Mixture-of-Experts Decoder (2025)](https://arxiv.org/abs/2508.06228)

### Repo updates

- [ ] HuggingFace demo using Gradio
- [ ] Full code release
- [ ] Dataset request form

(we are currently in Hawaii at ICCV 2025, getting feedback before the big release )

### Contacts
For any inquiries contact Marcos V. Conde: marcos.conde[at]uni-wuerzburg.de

This work has been patented worldwide at the European Patent Office (EPO). If you would like to use this work in commercial applications, please contact us :)
There are no limitations for open non-profit research and academic research.

### Citation

If you find our work interesting, you use our ideas or dataset, please cite properly our works.

```
@InProceedings{Conde_2025_ICCV,
    author    = {Conde, Marcos V. and Lu, Zihao and Timofte, Radu},
    title     = {PixTalk: Controlling Photorealistic Image Processing and Editing with Language},
    booktitle = {Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)},
    month     = {October},
    year      = {2025},
    pages     = {19269-19279}
}
```

PixTalk is inspired in InstructIR (ECCV 2024).

```
@inproceedings{conde2024high,
  title={InstructIR: High-Quality Image Restoration Following Human Instructions},
  author={Conde, Marcos V and Geigle, Gregor and Timofte, Radu},
  booktitle    = {Proceedings of the European Conference on Computer Vision (ECCV)},
  year={2024}
}
```
