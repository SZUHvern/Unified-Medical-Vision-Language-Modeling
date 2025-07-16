# Medical Vision-Language Modeling with Semantic Interaction and Adaptive Refinement Prompting for Bias Mitigation
The official code of article ”Medical Vision-Language Modeling with Semantic Interaction and Adaptive Refinement Prompting for Bias Mitigation”


## Key Features

In this study, we propose a unified medical vision-language model applicable for a variety of clinical tasks, including report generation, VQA, and pixel-level image segmentation. Within the model, we propose a semantic interaction mechanism aimed at enhancing pixel-level vision and language representation learning. To mitigate the impact of biased data distributions, we explicitly develop an adaptive refinement prompting method involving the iterative re-prompting of hard samples. The proposed method is thoroughly validated through experiments on eight datasets and comparisons with nine state-of-the-art methods.

## Dataset Links

- [PubMedVision](https://huggingface.co/datasets/FreedomIntelligence/PubMedVision)
- [IMed-361M](https://huggingface.co/datasets/General-Medical-AI/IMed-361M) 
- [MIMIC-CXR v2](https://physionet.org/content/mimic-cxr/2.0.0/)
- [PMC-VQA](https://huggingface.co/datasets/RadGenome/PMC-VQA)
- [SLAKE](https://huggingface.co/datasets/BoKelvin/SLAKE)
- [VQA-RAD](https://huggingface.co/datasets/flaviagiammarino/VQA-RAD)


## Pretrained Model Links
- [Qwen2.5-VL-7B-Instruct](https://huggingface.co/Qwen/Qwen2.5-VL-7B-Instruct)
- [IMIS-Net](https://github.com/uni-medical/IMIS-Bench/tree/main)


## Getting Start
### Preprocess
1. To install the required environment packages, please use the following code. It is recommended to install them in a new conda virtual environment:
```bash
pip install -r requirements.txt
```

2. Download the models, including the Qwen2.5-VL-7B-Instruct weight and IMIS-Net weitght.

3. Download all datasets according to the "Dataset Links".

4. Please replace all instances of "path/to/.." in the code with the specific paths to your files.

