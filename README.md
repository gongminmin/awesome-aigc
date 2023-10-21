# Awesome AIGC

A list of awesome AIGC works.

- [Text](#text)
  - [Text to Text](#text-to-text)
  - [Text to Image](#text-to-image)
  - [Text to Video](#text-to-video)
  - [Text to Mesh](#text-to-mesh)
  - [Text to Voice](#text-to-voice)
  - [Text to Music](#text-to-music)
- [Image](#image)
  - [Image to Text](#image-to-text)
  - [Image to Image](#image-to-image)
  - [Image to Mesh](#image-to-mesh)
  - [Image to Video](#image-to-video)
- [Enhancement](#enhancement)

We are using Technology Readiness Level (TRL) to evaluate the maturity of each technology. It's defined close to [NASA's TRL concept](https://en.wikipedia.org/wiki/Technology_readiness_level). The TRLs are scaled from 1 to 9, with 9 being the most mature technology.

1. Basic principles reported
2. Technology concept and/or application formulated
3. Critical function proof-of concept
4. Research work available
5. Research prototype validated
6. Prototype operated by professional users
7. Prototype operated by end-users
8. Actual product completed and validated by end-users
9. Actual product proven by massive end-users for daily basis

Most technologies in this list should fall into 4 or above.

## Text

This category takes text as input.

### Text to Text

| Name | TRL | More Links |
|-|-|-|
| [Brad](https://www.bradai.chat) | 5-6 | |
| [ChatGPT](https://chatgptonline.net/) | 8-9 | [[API]](https://platform.openai.com/docs/guides/chat) [[Paper]](https://s3-us-west-2.amazonaws.com/openai-assets/research-covers/language-unsupervised/language_understanding_paper.pdf) |
| [Claude](https://claudeai.tech/) | 5-6 | [[Paper]](https://claudeai.tech/constitutional.pdf) |
| [Copilot](https://github.com/features/copilot) (Code only) | 8-9 | |
| [GPT-4](https://openai.com/product/gpt-4) | 7-8 | [[API]](https://openai.com/waitlist/gpt-4-api) [[Paper]](https://arxiv.org/abs/2303.08774) |
| [LLaMA](https://docs.google.com/forms/d/e/1FAIpQLSfqNECQnMkycAp2jP4Z9TFX0cGR4uf7b_fBxjY_OjhJILlKGA/viewform) | 6-7 | [[Paper]](https://research.facebook.com/publications/llama-open-and-efficient-foundation-language-models/) [[Code]](https://github.com/facebookresearch/llama) |
| [New Bing](https://www.bing.com/new) | 7-8 | |
| [StableLM](https://stability.ai/blog/stability-ai-launches-the-first-of-its-stablelm-suite-of-language-models) | 5-6 | [[Code]](https://github.com/stability-AI/stableLM/) |

### Text to Image

| Name | TRL | More Links |
|-|-|-|
| [DALL·E 2](https://openai.com/dall-e-2/) | 7-8 | [[API]](https://platform.openai.com/docs/guides/images/usage) [[Paper]](https://arxiv.org/abs/2204.06125) |
| [MidJourney](https://www.midjourney.com) | 8-9 | |
| [Stable Diffusion](https://ommer-lab.com/research/latent-diffusion-models/) | 7-8 | [[Paper]](https://arxiv.org/abs/2112.10752) [[Code]](https://github.com/CompVis/stable-diffusion) |
| [TEXTure](https://texturepaper.github.io/TEXTurePaper/) (Texture only) | 4-5 | [[Paper]](https://arxiv.org/pdf/2302.01721.pdf) [[Code]](https://github.com/TEXTurePaper/TEXTurePaper) [[Demo]](https://huggingface.co/spaces/TEXTurePaper/TEXTure) |

### Text to Video

| Name | TRL | More Links |
|-|-|-|
| [Fliki](https://fliki.ai/) | 8-9 | [[API]](https://fliki.ai/resources/api) |
| [Make-A-Video](https://makeavideo.studio/) | 4-5 | [[Paper]](https://arxiv.org/abs/2209.14792) |
| [Phenaki](https://phenaki.video/) | 4-5 | [[Paper]](https://openreview.net/forum?id=vOEXS39nOF) |

### Text to Mesh

| Name | TRL | More Links |
|-|-|-|
| [DreamFusion](https://dreamfusion3d.github.io/index.html) | 4-5 | [[Paper]](https://arxiv.org/abs/2209.14988) [[3rd Party Code]](https://github.com/ashawkey/stable-dreamfusion) |
| [DreamFields](https://ajayj.com/dreamfields) | 4-5 | [[Paper]](https://arxiv.org/abs/2112.01455) [[Code]](https://github.com/google-research/google-research/tree/master/dreamfields) |
| [Magic3D](https://research.nvidia.com/labs/dir/magic3d/) | 4-5 | [[Paper]](https://arxiv.org/abs/2211.10440) |
| [Text2Mesh](https://threedle.github.io/text2mesh/) | 4-5 | [[Paper]](https://arxiv.org/abs/2112.03221) [[Code]](https://github.com/threedle/text2mesh) |
| [MTN](https://texaser.github.io/MTN-projectpage/) | 4-5 | [[Paper]](https://arxiv.org/abs/2309.14600) [[Code]](https://github.com/Texaser/MTN) |
### Text to Voice

| Name | TRL | More Links |
|-|-|-|
| [Murf](https://murf.ai/) | 7-8 | [[API]](https://murf.ai/text-to-speech-api) |

### Text to Music

| Name | TRL | More Links |
|-|-|-|
| [Mubert](https://mubert.com/) | 8-9 | [[API]](https://pitch.com/public/fd02c60f-00a4-4a74-8772-423d4a607b94) |

## Image

This category takes single image or multiple images as input.

### Image to Text

| Name | TRL | More Links |
|-|-|-|
| [BLIP-2](https://huggingface.co/blog/blip-2) | 4-5 | [[Paper]](https://arxiv.org/abs/2301.12597) [[Code]](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |

### Image to Image

| Name | TRL | More Links |
|-|-|-|
| [img2img](https://huggingface.co/spaces/fffiloni/stable-diffusion-img2img) | 6-7 | [[Paper]](https://arxiv.org/abs/2112.10752) [[Code]](https://huggingface.co/spaces/fffiloni/stable-diffusion-img2img/tree/main) |

### Image to Mesh

| Name | TRL | More Links |
|-|-|-|
| [GET3D](https://nv-tlabs.github.io/GET3D/) | 4-5 | [[Paper]](https://nv-tlabs.github.io/GET3D/assets/paper.pdf) [[Code]](https://github.com/nv-tlabs/GET3D) |
| [nvdiffrec](https://nvlabs.github.io/nvdiffrec/) | 5-6 | [[Paper]](https://nvlabs.github.io/nvdiffrec/assets/paper.pdf) [[Code]](https://github.com/NVlabs/nvdiffrec) |
| [pix2pix3D](http://www.cs.cmu.edu/~pix2pix3D/) | 5-6 | [[Paper]](https://arxiv.org/abs/2302.08509) [[Code]](https://github.com/dunbar12138/pix2pix3D) |

### Image to Video

| Name | TRL | More Links |
|-|-|-|
| [Make-A-Video](https://makeavideo.studio/) | 4-5 | [[Paper]](https://arxiv.org/abs/2209.14792) |

## Enhancement

This category contains enhancement methods to other AIGCs.

| Name | TRL | More Links |
|-|-|-|
| [ControlNet](https://github.com/lllyasviel/ControlNet) | 5-6 | [[Paper]](https://arxiv.org/abs/2302.05543) |
| [GPTCache](https://gptcache.readthedocs.io/en/latest/) | 5-6 | [[Code]](https://github.com/zilliztech/gptcache) |

## Contributing

Contributions are super welcome. When you do it, please follow the [contribution guidelines](CONTRIBUTING.md).
