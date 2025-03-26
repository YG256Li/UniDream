# UniDream
UniDream: Unifying Diffusion Priors for Relightable Text-to-3D Generation
## 🏠 <a href="https://yg256li.github.io/UniDream/" target="_blank">Project Page</a> | <a href="https://arxiv.org/abs/2312.08754" target="_blank">Paper</a>

![img:teaser](image/teaser.png)

Abstract: Recent advancements in text-to-3D generation technology have significantly advanced the conversion of textual descriptions into imaginative well-geometrical and finely textured 3D objects. Despite these developments, a prevalent limitation arises from the use of RGB data in diffusion or reconstruction models, which often results in models with inherent lighting and shadows effects that detract from their realism, thereby limiting their usability in applications that demand accurate relighting capabilities. To bridge this gap, we present UniDream, a text-to-3D generation framework by incorporating unified diffusion priors. Our approach consists of three main components: (1) a dual-phase training process to get albedo-normal aligned multi-view diffusion and reconstruction models, (2) a progressive generation procedure for geometry and albedo-textures based on Score Distillation Sample (SDS) using the trained reconstruction and diffusion models, and (3) an innovative application of SDS for finalizing PBR generation while keeping a fixed albedo based on Stable Diffusion model. Extensive evaluations demonstrate that UniDream surpasses existing methods in generating 3D objects with clearer albedo textures, smoother surfaces, enhanced realism, and superior relighting capabilities.

## 🔨 Method Overview

![img:pipeline](image/unidream_pipeline.png)

## 🤝 Codebase
The codebase of UniDream is coming soon.

```
@inproceedings{liu2024unidream,
  title={Unidream: Unifying diffusion priors for relightable text-to-3d generation},
  author={Liu, Zexiang and Li, Yangguang and Lin, Youtian and Yu, Xin and Peng, Sida and Cao, Yan-Pei and Qi, Xiaojuan and Huang, Xiaoshui and Liang, Ding and Ouyang, Wanli},
  booktitle={European Conference on Computer Vision},
  pages={74--91},
  year={2024},
  organization={Springer}
}
```