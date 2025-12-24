<div align="center" style="padding-top: 10px">
    <img src="./assets/logo.png" alt="anilayer2d-logo" height="140px">
</div>

<div align ="center">
    <a href="https://huggingface.co/datasets/PicoTrex/AniLayer2D"><img alt="HuggingFace" src="https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Dataset-FFA116?style=for-the-badge&logoColor=white"/></a>
</div>

<p align="center">
    <img src="https://i.imgur.com/waxVImv.png" alt="AniLayer2D">
</p>

## 📖 Overview

<div align="center" style="">
    <img src="./assets/flag.png" alt="anilayer2d-flag">
</div>

> [!NOTE]
>
> **AniLayer2D** is a layered image dataset tailored for Live2D models, featuring **multi-layer assets**, **semantic label**, and **descriptive captions**.
> Originally inspired by the emergence of **LayerDiffusion**, we recognized the potential of such technology in Live2D production. Constrained by computational resources at the time, we chose to contribute by building this dataset.
> Although completed in *February 2025* , the release was delayed. The recent launch of Qwen-Image-Layered has reignited our belief that fully automated Live2D generation is on the horizon. Consequently, we have organized and released this dataset to the community.
> **If you find this helpful, please give us a Star ⭐!**

## 🛠️ TODO List

- [x] Upload data labeling results
- [x] Upload **``part``** image dataset
- [ ] Upload data using sample code

## 📦 Dataset Format

```markdown
AniLayer2D_Data_Root
    ├── <model_name>           
    │   ├── <model_type>
    │   │   ├── part
    │   │   ├── label_inf.json
```

- 🧾 **label_inf.json:** A `json` file containing the category of each layer and the mapping of image sequence numbers, label name and character caption.

## 🎁 Acknowledgements

### Model

- live2d: https://github.com/imuncle/live2d
- live2d-models: https://github.com/oh-my-live2d/live2d-models
- live2d-model-assets: https://github.com/zenghongtu/live2d-model-assets

### Code

- live2d-v2: https://github.com/EasyLive2D/live2d-v2
**Greatly appreciated for the support provided by [Arkueid](https://github.com/Arkueid) !!!**

## ☎️ Community & Contact

This dataset was created on a whim, with limited knowledge in this field. Future plans include integrating multi-layer processing for moc/moc3/spine data. If interested or experienced, feel free to reach out. Guidance in this area would be greatly appreciated.

- E-mail: [Corporate Email](huangzlong5@mail2.sysu.edu.cn) / [Google Email](zilong.huang.ayaka@gmail.com)
