# Awesome-Diffusion-Memorization-Replication
:fire::fire: This repository contains a collection of papers on **memorization and replication** in diffusion models. We divide the phenomenon of memorization and replication into 3 aspects: **unveiling**, **understanding**, and **mitigation**. We also provide papers discussing such phenomena in **medical imaging**.

*Note that some papers may cover more than 1 aspect.*

# Contact

If we miss your awesome paper(s) on memorization and replication in diffusion models, please feel free to open an issue or contact Wenhao Wang (wangwenhao0716@gmail.com).

# Citation
```
@article{wang2024memorization,
  title={Memorization and Replication in Diffusion Models: A Survey and Outlook},
  author={Wang, Wenhao and Sun, Yifan and Hu, Zhengdong and Tan, Zhentao and Yang, Yi},
  journal={arXiv preprint arXiv:xxxx.xxxxx},
  year={2024}
}
```

# Contents

# Unveiling
![image](https://github.com/WangWenhao0716/Awesome-Diffusion-Memorization-Replication/blob/main/unveil.png)

## Prompting
### Specific
**Diffusion Art or Digital Forgery? Investigating Data Replication in Diffusion Models**\
[[CVPR 2023](https://openaccess.thecvf.com/content/CVPR2023/papers/Somepalli_Diffusion_Art_or_Digital_Forgery_Investigating_Data_Replication_in_Diffusion_CVPR_2023_paper.pdf)]
[[Code](https://github.com/somepago/DCR)] 

**Not with my name! Inferring artists’ names of input strings employed by Diffusion Models**\
[[ICIAP 2023](https://link.springer.com/chapter/10.1007/978-3-031-43148-7_31)]
[[Code](https://github.com/ictlab-unict/not-with-my-name)]

**Extracting Training Data from Diffusion Models**\
[[Usenix 2023](https://www.usenix.org/system/files/usenixsecurity23-carlini.pdf)]

**A Reproducible Extraction of Training Images from Diffusion Models**\
[[Arxiv 2023](https://arxiv.org/abs/2305.08694)]
[[Code](https://arxiv.org/abs/2305.08694)]

**Understanding (Un)Intended Memorization in Text-to-Image Generative Models**\
[[Arxiv 2023](https://arxiv.org/abs/2312.07550)]

**The Stronger the Diffusion Model, the Easier the Backdoor: Data Poisoning to Induce Copyright Breaches Without Adjusting Finetuning Pipeline**\
[[NeurIPSW 2023](https://openreview.net/forum?id=20FxHX25aq)]

**Unsafe Diffusion: On the Generation of Unsafe Images and Hateful Memes From Text-To-Image Models**\
[[CCS 2023](https://dl.acm.org/doi/10.1145/3576915.3616679)]
[[Code](https://github.com/YitingQu/unsafe-diffusion)]

**Distilling Adversarial Prompts from Safety Benchmarks: Report for the Adversarial Nibbler Challenge**\
[[ACLW 2023](https://aclanthology.org/2023.artofsafety-1.3/)]

**On the Proactive Generation of Unsafe Images From Text-To-Image Models Using Benign Prompts**\
[[Arxiv 2023](https://arxiv.org/abs/2305.13873)]

**Social Biases through the Text-to-Image Generation Lens**\
[[AIES 2023](https://dl.acm.org/doi/abs/10.1145/3600211.3604711)]

### Implicit
**Understanding (Un)Intended Memorization in Text-to-Image Generative Models**\
[[Arxiv 2023](https://arxiv.org/abs/2312.07550)]

**On Copyright Risks of Text-to-Image Diffusion Models**\
[[Arxiv 2023](https://arxiv.org/abs/2311.12803)]

**Hard Prompts Made Easy: Gradient-Based Discrete Optimization for Prompt Tuning and Discovery**\
[[NeurIPS 2023](https://openreview.net/forum?id=VOstHxDdsN)]


## Membership inference

### White-box
**An Efficient Membership Inference Attack for the Diffusion Model by Proximal Initialization**\
[[ICLR 2024](https://openreview.net/forum?id=rpH9FcCEV6)]
[[Code](https://github.com/kong13661/PIA)]

**Loss and Likelihood Based Membership Inference of Diffusion Models**\
[[ISC 2023](https://link.springer.com/chapter/10.1007/978-3-031-49187-0_7)]

**Membership Inference Attacks against Diffusion Models**\
[[SPW 2023](https://ieeexplore.ieee.org/document/10188618)]

**White-box Membership Inference Attacks against Diffusion Models**\
[[Arxiv 2023](https://arxiv.org/abs/2308.06405)]
[[Code](https://github.com/py85252876/GSA)]

**Membership Inference Attacks on Diffusion Models via Quantile Regression** \
[[Arxiv 2023](https://arxiv.org/abs/2312.05140)]

### Black-box
**Membership Inference Attacks against Diffusion Models**\
[[SPW 2023](https://ieeexplore.ieee.org/document/10188618)]

**Membership Inference Attacks Against Text-to-image Generation Models**\
[[Arxiv 2022](https://arxiv.org/pdf/2210.00968)]

**A Probabilistic Fluctuation based Membership Inference Attack for Diffusion Models**\
[[Arxiv 2023](https://arxiv.org/abs/2308.12143)]

**Set–Membership Inference Attacks using Data Watermarking**\
[[Arxiv 2023](https://arxiv.org/abs/2307.15067)]

**Generated Distributions Are All You Need for Membership Inference Attacks Against Generative Models**\
[[WACV 2024](https://openaccess.thecvf.com/content/WACV2024/papers/Zhang_Generated_Distributions_Are_All_You_Need_for_Membership_Inference_Attacks_WACV_2024_paper.pdf)]

**Black-box Membership Inference Attacks against Fine-tuned Diffusion Models**\
[[Arxiv 2023](https://arxiv.org/abs/2312.08207)]

**Towards More Realistic Membership Inference Attacks on Large Diffusion Models**\
[[WACV 2024](https://openaccess.thecvf.com/content/WACV2024/papers/Dubinski_Towards_More_Realistic_Membership_Inference_Attacks_on_Large_Diffusion_Models_WACV_2024_paper.pdf)]


## Similarity retrieval

### Content similarity

**Diffusion Art or Digital Forgery? Investigating Data Replication in Diffusion Models**\
[[CVPR 2023](https://openaccess.thecvf.com/content/CVPR2023/papers/Somepalli_Diffusion_Art_or_Digital_Forgery_Investigating_Data_Replication_in_Diffusion_CVPR_2023_paper.pdf)]
[[Code](https://github.com/somepago/DCR)] 

**Generation or Replication: Auscultating Audio Latent Diffusion Models**\
[[ICASSP 2024](https://ieeexplore.ieee.org/document/10447705)]
[[Project](https://www.merl.com/research/highlights/auscultating-diffusion)]

**Frame by Familiar Frame: Understanding Replication in Video Diffusion Models**\
[[Arxiv 2024](https://arxiv.org/abs/2403.19593)]

**CopyScope: Model-level Copyright Infringement Quantification in the Diffusion Workflow**\
[[Arxiv 2023](https://arxiv.org/abs/2311.12847)]

**DeepfakeArt Challenge: A Benchmark Dataset for Generative AI Art Forgery and Data Poisoning Detection**\
[[Arxiv 2023](https://arxiv.org/abs/2306.01272)]
[[Code](https://github.com/h-aboutalebi/DeepfakeArt)]

**CGI-DM: Digital Copyright Authentication for Diffusion Models via Contrasting Gradient Inversion**\
[[CVPR 2024](https://arxiv.org/abs/2403.11162)]
[[Code](https://github.com/Nicholas0228/Revelio)]

### Style similarity
**Measuring Style Similarity in Diffusion Models**\
[[Arxiv 2024](https://arxiv.org/abs/2404.01292)]
[[Code](https://github.com/learn2phoenix/CSD)]

**AnyPattern: Towards In-context Image Copy Detection**\
[[Arxiv 2024](https://arxiv.org/abs/2404.13788)]
[[Project](https://anypattern.github.io/)]

**Measuring the Success of Diffusion Models at Imitating Human Artists**\
[[ICMLW 2023](https://arxiv.org/abs/2307.04028)]

## Watermarking
**DIAGNOSIS: Detecting Unauthorized Data Usages in Text-to-image Diffusion Models**\
[[ICLR 2024](https://openreview.net/forum?id=f8S3aLm0Vp)]
[[Code](https://github.com/ZhentingWang/DIAGNOSIS)]

**DiffusionShield: A Watermark for Copyright Protection against Generative Diffusion Models**\
[[Arxiv 2023](https://arxiv.org/abs/2306.04642)] 

**FT-SHIELD: A Watermark Against Unauthorized Fine-tuning in Text-to-Image Diffusion Models**\
[[Arxiv 2023](https://arxiv.org/abs/2310.02401)]

**Steal My Artworks for Fine-tuning? A Watermarking Framework for Detecting Art Theft Mimicry in Text-to-Image Models**\
[[Arxiv 2023](https://arxiv.org/abs/2311.13619)]

## Proactive replication

### Fine-tuning
**DreamBooth: Fine Tuning Text-to-Image Diffusion Models for Subject-Driven Generation**\
[[CVPR 2023](https://openaccess.thecvf.com/content/CVPR2023/papers/Ruiz_DreamBooth_Fine_Tuning_Text-to-Image_Diffusion_Models_for_Subject-Driven_Generation_CVPR_2023_paper.pdf)]
[[Code](https://github.com/google/dreambooth)]

**An Image is Worth One Word: Personalizing Text-to-Image Generation using Textual Inversion**\
[[ICLR 2023](https://openreview.net/pdf?id=NAQvF08TcyG)]
[[Project](https://textual-inversion.github.io/)]

**A Neural Space-Time Representation for Text-to-Image Personalization**\
[[SIGGRAPH Asia 2023](https://dl.acm.org/doi/10.1145/3618322)]
[[Project](https://neuraltextualinversion.github.io/NeTI/)]

**Domain-Agnostic Tuning-Encoder for Fast Personalization of Text-To-Image Models**\
[[SIGGRAPH Asia 2023](https://dl.acm.org/doi/abs/10.1145/3610548.3618173)]
[[Project](https://datencoder.github.io/)]

**ZipLoRA: Any Subject in Any Style by Effectively Merging LoRAs**\
[[Arxiv 2023](https://arxiv.org/abs/2311.13600)]
[[Project](https://ziplora.github.io/)]

**Subject-driven Text-to-Image Generation via Apprenticeship Learning**\
[[NeurIPS 2023](https://openreview.net/forum?id=wv3bHyQbX7)]
[[Project](https://open-vision-language.github.io/suti/)]

**Inversion-Based Style Transfer with Diffusion Models**\
[[CVPR 2023](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_Inversion-Based_Style_Transfer_With_Diffusion_Models_CVPR_2023_paper.pdf))
[[Code](https://github.com/zyxElsa/InST)]

**Customizing Text-to-Image Models with a Single Image Pair**\
[[Arxiv 2024](https://arxiv.org/pdf/2405.01536)]

**Multi-Concept Customization of Text-to-Image Diffusion**\
[[CVPR 2023](https://openaccess.thecvf.com/content/CVPR2023/papers/Kumari_Multi-Concept_Customization_of_Text-to-Image_Diffusion_CVPR_2023_paper.pdf)]
[[Code](https://github.com/adobe-research/custom-diffusion)]

**Encoder-based Domain Tuning for Fast Personalization of Text-to-Image Models**\
[[ACM Transactions on Graphics](https://dl.acm.org/doi/abs/10.1145/3592133)]
[[Project](https://tuning-encoder.github.io/)]

### Training-free

**Subject-Diffusion: Open Domain Personalized Text-to-Image Generation without Test-time Fine-tuning**\
[[Arxiv 2023](https://arxiv.org/pdf/2307.11410)]
[[Project](https://oppo-mente-lab.github.io/subject_diffusion/)]

**Subject-Diffusion: Open Domain Personalized Text-to-Image Generation without Test-time Fine-tuning**\
[[Arxiv 2023](https://arxiv.org/pdf/2307.11410)]
[[Project](https://oppo-mente-lab.github.io/subject_diffusion/)]

## Novel perspectives

### Magnitude of noise

**Detecting, Explaining, and Mitigating Memorization in Diffusion Models**\
[[ICLR 2024](https://openreview.net/forum?id=84n3UwkH7b)]
[[Code](https://github.com/YuxinWenRick/diffusion_memorization)]

### Training data attribution
**Evaluating Data Attribution for Text-to-Image Models**\
[[ICCV 2023](https://openaccess.thecvf.com/content/ICCV2023/papers/Wang_Evaluating_Data_Attribution_for_Text-to-Image_Models_ICCV_2023_paper.pdf)]

**The Journey, Not the Destination: How Data Guides Diffusion Models**\
[[ICMLW 2023](https://openreview.net/pdf?id=9hK9NbUAex)]
[[Code](https://github.com/MadryLab/journey-TRAK)]

### Cross attention
**Unveiling and Mitigating Memorization in Text-to-image Diffusion Models through Cross Attention**\
[[Arxiv 2024](https://arxiv.org/abs/2403.11052)]

### Fine-tune to leak
**Shake to Leak: Fine-tuning Diffusion Models Can Amplify the Generative Privacy Risk**\
[[Arxiv 2024](https://arxiv.org/abs/2403.09450)]

### Overfitted MAE
**Detecting Generative Parroting through Overfitting Masked Autoencoders**\
[[CVPRW 2024](https://arxiv.org/abs/2403.19050)]

### Property inference
**Property Existence Inference against Generative Models**\
[[USENIX 2024](https://www.usenix.org/system/files/sec24fall-prepub-2868-wang-lijin.pdf)]
[[Code](https://github.com/wljLlla/PEI_Code)]




**Red-Teaming the Stable Diffusion Safety Filter**\
[[NeurIPSW 2022](https://arxiv.org/abs/2210.04610)]



**Detecting, Explaining, and Mitigating Memorization in Diffusion Models**\
[[ICLR 2024](https://openreview.net/forum?id=84n3UwkH7b)]
[[Code](https://github.com/YuxinWenRick/diffusion_memorization)]

**Membership Inference Attacks Against Text-to-image Generation Models**\
[[Arxiv 2022](https://arxiv.org/pdf/2210.00968)]

**Membership Inference of Diffusion Models**\
[[Arxiv 2023](https://arxiv.org/abs/2301.09956)]

**Membership Inference Attacks against Diffusion Models**\
[[SPW 2023](https://ieeexplore.ieee.org/document/10188618)]

**Are Diffusion Models Vulnerable to Membership Inference Attacks?**\
[[ICML 2023](https://proceedings.mlr.press/v202/duan23b/duan23b.pdf)]
[[Code](https://proceedings.mlr.press/v202/duan23b/duan23b.pdf)]

**Towards More Realistic Membership Inference Attacks on Large Diffusion Models**\
[[WACV 2024](https://openaccess.thecvf.com/content/WACV2024/papers/Dubinski_Towards_More_Realistic_Membership_Inference_Attacks_on_Large_Diffusion_Models_WACV_2024_paper.pdf)]

**An Efficient Membership Inference Attack for the Diffusion Model by Proximal Initialization**\
[[ICLR 2024](https://openreview.net/forum?id=rpH9FcCEV6)]
[[Code](https://github.com/kong13661/PIA)]

**Membership Inference Attacks on Diffusion Models via Quantile Regression** \
[[Arxiv 2023](https://arxiv.org/abs/2312.05140)]

**Set–Membership Inference Attacks using Data Watermarking**\
[[Arxiv 2023](https://arxiv.org/abs/2307.15067)]

**Loss and Likelihood Based Membership Inference of Diffusion Models**\
[[ISC 2023](https://link.springer.com/chapter/10.1007/978-3-031-49187-0_7)]

**Extracting Training Data from Diffusion Models**\
[[Usenix 2023](https://www.usenix.org/system/files/usenixsecurity23-carlini.pdf)]

**A Reproducible Extraction of Training Images from Diffusion Models**\
[[Arxiv 2023](https://arxiv.org/abs/2305.08694)]
[[Code](https://arxiv.org/abs/2305.08694)]

**DIAGNOSIS: Detecting Unauthorized Data Usages in Text-to-image Diffusion Models**\
[[ICLR 2024](https://openreview.net/forum?id=f8S3aLm0Vp)]
[[Code](https://github.com/ZhentingWang/DIAGNOSIS)]

**Generation or Replication: Auscultating Audio Latent Diffusion Models**\
[[ICASSP 2024](https://ieeexplore.ieee.org/document/10447705)]
[[Project](https://www.merl.com/research/highlights/auscultating-diffusion)]

**On Copyright Risks of Text-to-Image Diffusion Models**\
[[Arxiv 2023](https://arxiv.org/abs/2311.12803)]

**The Journey, Not the Destination: How Data Guides Diffusion Models**\
[[ICMLW 2023](https://openreview.net/pdf?id=9hK9NbUAex)]
[[Code](https://github.com/MadryLab/journey-TRAK)]

**The Stronger the Diffusion Model, the Easier the Backdoor: Data Poisoning to Induce Copyright Breaches Without Adjusting Finetuning Pipeline**\
[[NeurIPSW 2023](https://openreview.net/forum?id=20FxHX25aq)]

**Unveiling and Mitigating Memorization in Text-to-image Diffusion Models through Cross Attention**\
[[Arxiv 2024](https://arxiv.org/abs/2403.11052)]

**Frame by Familiar Frame: Understanding Replication in Video Diffusion Models**\
[[Arxiv 2024](https://arxiv.org/abs/2403.19593)]

**DreamBooth: Fine Tuning Text-to-Image Diffusion Models for Subject-Driven Generation**\
[[CVPR 2023](https://openaccess.thecvf.com/content/CVPR2023/papers/Ruiz_DreamBooth_Fine_Tuning_Text-to-Image_Diffusion_Models_for_Subject-Driven_Generation_CVPR_2023_paper.pdf)]
[[Code](https://github.com/google/dreambooth)]

**An Image is Worth One Word: Personalizing Text-to-Image Generation using Textual Inversion**\
[[ICLR 2023](https://openreview.net/pdf?id=NAQvF08TcyG)]
[[Project](https://textual-inversion.github.io/)]

**A Neural Space-Time Representation for Text-to-Image Personalization**\
[[SIGGRAPH Asia 2023](https://dl.acm.org/doi/10.1145/3618322)]
[[Project](https://neuraltextualinversion.github.io/NeTI/)]

**Subject-Diffusion: Open Domain Personalized Text-to-Image Generation without Test-time Fine-tuning**\
[[Arxiv 2023](https://arxiv.org/pdf/2307.11410)]
[[Project](https://oppo-mente-lab.github.io/subject_diffusion/)]

**Domain-Agnostic Tuning-Encoder for Fast Personalization of Text-To-Image Models**\
[[SIGGRAPH Asia 2023](https://dl.acm.org/doi/abs/10.1145/3610548.3618173)]
[[Project](https://datencoder.github.io/)]

**ZipLoRA: Any Subject in Any Style by Effectively Merging LoRAs**\
[[Arxiv 2023](https://arxiv.org/abs/2311.13600)]
[[Project](https://ziplora.github.io/)]

**Subject-driven Text-to-Image Generation via Apprenticeship Learning**\
[[NeurIPS 2023](https://openreview.net/forum?id=wv3bHyQbX7)]
[[Project](https://open-vision-language.github.io/suti/)]

**InstantBooth: Personalized Text-to-Image Generation without Test-Time Finetuning**\
[[Arxiv 2023](https://arxiv.org/abs/2304.03411)]
[[Project](https://jshi31.github.io/InstantBooth/)]

**Inversion-Based Style Transfer with Diffusion Models**\
[[CVPR 2023](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_Inversion-Based_Style_Transfer_With_Diffusion_Models_CVPR_2023_paper.pdf))
[[Code](https://github.com/zyxElsa/InST)]

**Customizing Text-to-Image Models with a Single Image Pair**\
[[Arxiv 2024](https://arxiv.org/pdf/2405.01536)]

**Multi-Concept Customization of Text-to-Image Diffusion**\
[[CVPR 2023](https://openaccess.thecvf.com/content/CVPR2023/papers/Kumari_Multi-Concept_Customization_of_Text-to-Image_Diffusion_CVPR_2023_paper.pdf)]
[[Code](https://github.com/adobe-research/custom-diffusion)]

**Encoder-based Domain Tuning for Fast Personalization of Text-to-Image Models**\
[[ACM Transactions on Graphics](https://dl.acm.org/doi/abs/10.1145/3592133)]
[[Project](https://tuning-encoder.github.io/)]

**DiffusionShield: A Watermark for Copyright Protection against Generative Diffusion Models**\
[[Arxiv 2023](https://arxiv.org/abs/2306.04642)] 

**Steal My Artworks for Fine-tuning? A Watermarking Framework for Detecting Art Theft Mimicry in Text-to-Image Models**\
[[Arxiv 2023](https://arxiv.org/abs/2311.13619)]

**Measuring Style Similarity in Diffusion Models**\
[[Arxiv 2024](https://arxiv.org/abs/2404.01292)]
[[Code](https://github.com/learn2phoenix/CSD)]

**AnyPattern: Towards In-context Image Copy Detection**\
[[Arxiv 2024](https://arxiv.org/abs/2404.13788)]
[[Project](https://anypattern.github.io/)]

**CopyScope: Model-level Copyright Infringement Quantification in the Diffusion Workflow**\
[[Arxiv 2023](https://arxiv.org/abs/2311.12847)]

**On the Proactive Generation of Unsafe Images From Text-To-Image Models Using Benign Prompts**\
[[Arxiv 2023](https://arxiv.org/abs/2305.13873)]

**FT-SHIELD: A Watermark Against Unauthorized Fine-tuning in Text-to-Image Diffusion Models**\
[[Arxiv 2023](https://arxiv.org/abs/2310.02401)]

**Distilling Adversarial Prompts from Safety Benchmarks: Report for the Adversarial Nibbler Challenge**\
[[ACLW 2023](https://aclanthology.org/2023.artofsafety-1.3/)]

**Understanding (Un)Intended Memorization in Text-to-Image Generative Models**\
[[Arxiv 2023](https://arxiv.org/abs/2312.07550)]

**Black-box Membership Inference Attacks against Fine-tuned Diffusion Models**\
[[Arxiv 2023](https://arxiv.org/abs/2312.08207)]

**A Probabilistic Fluctuation based Membership Inference Attack for Diffusion Models**\
[[Arxiv 2023](https://arxiv.org/abs/2308.12143)]

**White-box Membership Inference Attacks against Diffusion Models**\
[[Arxiv 2023](https://arxiv.org/abs/2308.06405)]
[[Code](https://github.com/py85252876/GSA)]

**Generated Distributions Are All You Need for Membership Inference Attacks Against Generative Models**\
[[WACV 2024](https://openaccess.thecvf.com/content/WACV2024/papers/Zhang_Generated_Distributions_Are_All_You_Need_for_Membership_Inference_Attacks_WACV_2024_paper.pdf)]

**Hard Prompts Made Easy: Gradient-Based Discrete Optimization for Prompt Tuning and Discovery**\
[[NeurIPS 2023](https://openreview.net/forum?id=VOstHxDdsN)]

**Not with my name! Inferring artists’ names of input strings employed by Diffusion Models**\
[[ICIAP 2023](https://link.springer.com/chapter/10.1007/978-3-031-43148-7_31)]
[[Code](https://github.com/ictlab-unict/not-with-my-name)]

**Measuring the Success of Diffusion Models at Imitating Human Artists**\
[[ICMLW 2023](https://arxiv.org/abs/2307.04028)]

**DeepfakeArt Challenge: A Benchmark Dataset for Generative AI Art Forgery and Data Poisoning Detection**\
[[Arxiv 2023](https://arxiv.org/abs/2306.01272)]
[[Code](https://github.com/h-aboutalebi/DeepfakeArt)]

**AI Imagery and the Overton Window**\
[[Arxiv 2023](https://arxiv.org/abs/2306.00080)]

**Unsafe Diffusion: On the Generation of Unsafe Images and Hateful Memes From Text-To-Image Models**\
[[CCS 2023](https://dl.acm.org/doi/10.1145/3576915.3616679)]
[[Code](https://github.com/YitingQu/unsafe-diffusion)]

**Social Biases through the Text-to-Image Generation Lens**\
[[AIES 2023](https://dl.acm.org/doi/abs/10.1145/3600211.3604711)]

**Exploiting Cultural Biases via Homoglyphs in Text-to-Image Synthesis**\
[[JAIR 2023](https://arxiv.org/abs/2209.08891)]
[[Code](https://github.com/LukasStruppek/Exploiting-Cultural-Biases-via-Homoglyphs)]

**What ChatGPT and generative AI mean for science**\
[[Nature 2023](https://www.nature.com/articles/d41586-023-00340-6)]

**Shake to Leak: Fine-tuning Diffusion Models Can Amplify the Generative Privacy Risk**\
[[Arxiv 2024](https://arxiv.org/abs/2403.09450)]

**On the Challenges and Opportunities in Generative AI**\
[[Arxiv 2024](https://arxiv.org/abs/2403.00025)]

**Detecting Generative Parroting through Overfitting Masked Autoencoders**\
[[Arxiv 2024](https://arxiv.org/abs/2403.19050)]

**Property Existence Inference against Generative Models**\
[[USENIX 2024](https://www.usenix.org/system/files/sec24fall-prepub-2868-wang-lijin.pdf)]
[[Code](https://github.com/wljLlla/PEI_Code)]

**CGI-DM: Digital Copyright Authentication for Diffusion Models via Contrasting Gradient Inversion**\
[[CVPR 2024](https://arxiv.org/abs/2403.11162)]
[[Code](https://github.com/Nicholas0228/Revelio)]

**Evaluating Data Attribution for Text-to-Image Models**\
[[ICCV 2023](https://openaccess.thecvf.com/content/ICCV2023/papers/Wang_Evaluating_Data_Attribution_for_Text-to-Image_Models_ICCV_2023_paper.pdf)]

## Understanding

**On Provable Copyright Protection for Generative Models**\
[[ICML 2023](https://openreview.net/forum?id=qRAHZVnQNY)]

**Diffusion Art or Digital Forgery? Investigating Data Replication in Diffusion Models**\
[[CVPR 2023](https://openaccess.thecvf.com/content/CVPR2023/papers/Somepalli_Diffusion_Art_or_Digital_Forgery_Investigating_Data_Replication_in_Diffusion_CVPR_2023_paper.pdf)]
[[Code](https://github.com/somepago/DCR)] 

**Understanding Data Replication in Diffusion Models**\
[[ICMLW 2023](https://openreview.net/forum?id=F9qCNPSzSY)]

**Diffusion Probabilistic Models Generalize when They Fail to Memorize**\
[[ICMLW 2023](https://openreview.net/forum?id=shciCbSk9h)]

**Detecting, Explaining, and Mitigating Memorization in Diffusion Models**\
[[ICLR 2024](https://openreview.net/forum?id=84n3UwkH7b)]
[[Code](https://github.com/YuxinWenRick/diffusion_memorization)]

**A Reproducible Extraction of Training Images from Diffusion Models**\
[[Arxiv 2023](https://arxiv.org/abs/2305.08694)]
[[Code](https://arxiv.org/abs/2305.08694)]

**Generalization in diffusion models arises from geometry-adaptive harmonic representations**\
[[ICLR 2024](https://openreview.net/forum?id=ANvmVS2Yr0)]
[[Code](https://github.com/LabForComputationalVision/memorization_generalization_in_diffusion_models)]

**On Memorization in Diffusion Models**\
[[Arxiv 2023](https://arxiv.org/abs/2310.02664)]
[[Code](https://github.com/sail-sg/DiffMemorize)]

**On the Generalization Properties of Diffusion Models**\
[[NeurIPS 2023](https://openreview.net/forum?id=hCUG1MCFk5)]

**On the Generalization of Diffusion Model**\
[[Arxiv 2023](https://arxiv.org/abs/2305.14712)]

**The Emergence of Reproducibility and Consistency in Diffusion Models**\
[[Arxiv 2023](https://arxiv.org/abs/2310.05264)]

**Memory Triggers: Unveiling Memorization in Text-To-Image Generative Models through Word-Level Duplication**\
[[Arxiv 2023](https://arxiv.org/abs/2312.03692)]

**Unveiling and Mitigating Memorization in Text-to-image Diffusion Models through Cross Attention**\
[[Arxiv 2024](https://arxiv.org/abs/2403.11052)]

**Towards Memorization-Free Diffusion Models**\
[[Arxiv 2024](https://arxiv.org/abs/2404.00922)]

**The Files are in the Computer: Copyright, Memorization, and Generative AI**\
[[Arxiv 2024](https://arxiv.org/abs/2404.12590)]

**Outliers Memorized Last: Trends in Memorization of Diffusion Models Based on Training Distribution and Epoch**\
[[Openreview 2024](https://openreview.net/forum?id=6ZuDeSHzjj)]

**Understanding and Mitigating Copying in Diffusion Models**\
[[NeurIPS 2023](https://openreview.net/forum?id=HtMXRGbUMt)]
[[Code](https://github.com/somepago/DCR)]

**The Economics of Copyright in the Digital Age**\
[[CESifo](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4608809)]

**Generative AI meets copyright**\
[[Science](https://www.science.org/doi/abs/10.1126/science.adi0656)]

**Generative Artificial Intelligence and Copyright Law**\
[[CRS Report](https://crsreports.congress.gov/product/pdf/LSB/LSB10922)]

**AI Art and its Impact on Artists**\
[[AIES 2023](https://dl.acm.org/doi/10.1145/3600211.3604681)]

**Talkin' 'Bout AI Generation: Copyright and the Generative-AI Supply Chain**\
[[CSLAW 2024](https://dl.acm.org/doi/10.1145/3614407.3643696)]

**Report of the 1st Workshop on Generative AI and Law**\
[[Arxiv 2023](https://arxiv.org/abs/2311.06477)]

**Dual Governance: The intersection of centralized regulation and crowdsourced safety mechanisms for Generative AI**\
[[Arxiv 2023](https://arxiv.org/abs/2308.04448)]

**Can Copyright be Reduced to Privacy?**\
[[Arxiv 2023](https://arxiv.org/abs/2305.14822)]

**Foundation Models and Fair Use**\
[[Arxiv 2023](https://arxiv.org/abs/2303.15715)]

**Stable Bias: Evaluating Societal Representations in Diffusion Models**\
[[NeurIPS 2023](https://openreview.net/forum?id=qVXYU3F017)]

**Analyzing Bias in Diffusion-based Face Generation Models**\
[[Arxiv 2023](https://arxiv.org/abs/2305.06402)]

**Measuring Forgetting of Memorized Training Examples**\
[[ICLR 2023](https://openreview.net/forum?id=7bJizxLKrR)]

**A Pathway Towards Responsible AI Generated Content**\
[[IJCAI 2023](https://www.ijcai.org/proceedings/2023/803)]

**Art and the science of generative AI**\
[[Science 2023](https://www.science.org/doi/10.1126/science.adh4451)]

**AI and Law: The Next Generation**\
[[SSRN 2023](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4580739)]

**How Generative AI Turns Copyright Upside Down**\
[[SSRN 2023](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4517702)]

**Generative AI Art: Copyright Infringement and Fair Use**\
[[SSRN 2023](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4483539)]

**Copyright Safety for Generative AI**\
[[SSRN 2023](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4438593)]

**Can There be Art Without an Artist?**\
[[NeurIPSW 2022](https://arxiv.org/abs/2209.07667)]

**Auditing Gender Presentation Differences in Text-to-Image Models**\
[[Arxiv 2023](https://arxiv.org/abs/2302.03675)]
[[Project](https://salt-nlp.github.io/GEP/)]

**Feature Likelihood Divergence: Evaluating the Generalization of Generative Models Using Samples**\
[[NeurIPS 2023](https://proceedings.neurips.cc/paper_files/paper/2023/hash/68b138608ef80b08d65b1bd9594d9559-Abstract-Conference.html)]

**Stable Diffusion Exposed: Gender Bias from Prompt to Image**\
[[Arxiv 2023](https://arxiv.org/abs/2312.03027)]

**Can AI Be as Creative as Humans?**\
[[Arxiv 2024](https://arxiv.org/abs/2401.01623)]
[[Project](https://ai-relative-creativity.github.io/)]

**Generative Artificial Intelligence in Product Design Education: Navigating Concerns of Originality and Ethics**\
[[IJIMAI 2024](https://www.ijimai.org/journal/bibcite/reference/3426)]

**Rethinking Artistic Copyright Infringements in the Era of Text-to-Image Generative Models**\
[[Arxiv 2024](https://arxiv.org/abs/2404.08030)]

**A Good Score Does not Lead to A Good Generative Model**\
[[Arxiv 2024](https://arxiv.org/abs/2401.04856)]

**Analyzing Copyright Infringement by Artificial Intelligence: The Case of the Diffusion Model**\
[[AJHSS 2023](https://francis-press.com/papers/10096)]

**Understanding the Influence of Artificial Intelligence Art on Transaction in the Art World**\
[[Theses 2023](https://repository.ihu.edu.gr/xmlui/handle/11544/30356)]

**AI Art: Artists’ Best Friend or Mortal Enemy?**\
[[Essay 2023](https://digitalcommons.augustana.edu/libraryprize/13/)]

## Mitigation

**Differential Privacy vs Detecting Copyright Infringement: A Case Study with Normalizing Flows**\
[[ICMLW 2024](https://genlaw.org/CameraReady/60.pdf)]

**Differentially Private Diffusion Models Generate Useful Synthetic Images**\
[[Arxiv 2023](https://arxiv.org/abs/2302.13861)]

**Differentially Private Diffusion Models**\
[[TMLR 2023](https://openreview.net/forum?id=ZPpQk7FJXF)]
[[Project](https://research.nvidia.com/labs/toronto-ai/DPDM/)]

**Safe Latent Diffusion: Mitigating Inappropriate Degeneration in Diffusion Models**\
[[CVPR 2023](https://openaccess.thecvf.com/content/CVPR2023/papers/Schramowski_Safe_Latent_Diffusion_Mitigating_Inappropriate_Degeneration_in_Diffusion_Models_CVPR_2023_paper.pdf)]
[[Code](https://github.com/ml-research/safe-latent-diffusion)]

**Algorithms for Optimal Adaptation of Diffusion Models to Reward Functions**\
[[ICMLW 2023](https://openreview.net/forum?id=WRpRPsU0VT)]

**Detecting, Explaining, and Mitigating Memorization in Diffusion Models**\
[[ICLR 2024](https://openreview.net/forum?id=84n3UwkH7b)]
[[Code](https://github.com/YuxinWenRick/diffusion_memorization)]

**Extracting Training Data from Diffusion Models**\
[[Usenix 2023](https://www.usenix.org/system/files/usenixsecurity23-carlini.pdf)]

**Erasing Concepts from Diffusion Models**\
[[ICCV 2023](https://openaccess.thecvf.com/content/ICCV2023/papers/Gandikota_Erasing_Concepts_from_Diffusion_Models_ICCV_2023_paper.pdf)]
[[Project](https://erasing.baulab.info)]

**On the De-duplication of LAION-2B**\
[[Arxiv 2023](https://arxiv.org/abs/2303.12733)]
[[Code](https://github.com/ryanwebster90/snip-dedup)]

**Ablating Concepts in Text-to-Image Diffusion Models**\
[[ICCV 2023](https://openaccess.thecvf.com/content/ICCV2023/papers/Kumari_Ablating_Concepts_in_Text-to-Image_Diffusion_Models_ICCV_2023_paper.pdf)]
[[Code](https://github.com/nupurkmr9/concept-ablation)]

**Forget-Me-Not: Learning to Forget in Text-to-Image Diffusion Models**\
[[Arxiv 2023](https://arxiv.org/abs/2303.17591)]
[[Code](https://github.com/SHI-Labs/Forget-Me-Not)]

**Ambient Diffusion: Learning Clean Distributions from Corrupted Data**\
[[NeurIPS 2023](https://openreview.net/pdf?id=wBJBLy9kBY)]

**Training Data Protection with Compositional Diffusion Models**\
[[Arxiv 2023](https://arxiv.org/abs/2308.01937)]

**Reinforcement Learning from Diffusion Feedback: Q\* for Image Search**\
[[Arxiv 2023](https://arxiv.org/abs/2311.15648)]

**EraseDiff: Erasing Data Influence in Diffusion Models**\
[[Arxiv 2024](https://arxiv.org/abs/2401.05779)]

**Dynamical Regimes of Diffusion Models**\
[[Arxiv 2024](https://arxiv.org/abs/2402.18491)]

**MPCPA: Multi-Center Privacy Computing with Predictions Aggregation based on Denoising Diffusion Probabilistic Model**\
[[Arxiv 2024](https://arxiv.org/abs/2403.07838)]

**Unveiling and Mitigating Memorization in Text-to-image Diffusion Models through Cross Attention**\
[[Arxiv 2024](https://arxiv.org/abs/2403.11052)]

**DP-RDM: Adapting Diffusion Models to Private Domains Without Fine-Tuning**\
[[Arxiv 2024](https://arxiv.org/abs/2403.14421)]

**Frame by Familiar Frame: Understanding Replication in Video Diffusion Models**\
[[Arxiv 2024](https://arxiv.org/abs/2403.19593)]

**Towards Memorization-Free Diffusion Models**\
[[Arxiv 2024](https://arxiv.org/abs/2404.00922)]

**Consistent Diffusion Meets Tweedie: Training Exact Ambient Diffusion Models with Noisy Data**\
[[Arxiv 2024](https://arxiv.org/abs/2404.10177)]

**Unified Concept Editing in Diffusion Models**\
[[WACV 2024](https://openaccess.thecvf.com/content/WACV2024/papers/Gandikota_Unified_Concept_Editing_in_Diffusion_Models_WACV_2024_paper.pdf)]
[[Project](https://unified.baulab.info)]

**Mitigate Replication and Copying in Diffusion Models with Generalized Caption and Dual Fusion Enhancement**\
[[ICASSP 2024](https://ieeexplore.ieee.org/document/10446820)]
[[Code](https://github.com/HowardLi0816/dual-fusion-diffusion)]

**Understanding and Mitigating Copying in Diffusion Models**\
[[NeurIPS 2023](https://openreview.net/forum?id=HtMXRGbUMt)]
[[Code](https://github.com/somepago/DCR)]

**Glaze: Protecting Artists from Style Mimicry by Text-to-Image Models**\
[[USENIX 2023](https://www.usenix.org/system/files/usenixsecurity23-shan.pdf)]

**IMPRESS: Evaluating the Resilience of Imperceptible Perturbations Against Unauthorized Data Usage in Diffusion-Based Generative AI**\
[[NeurIPS 2023](https://openreview.net/forum?id=RRSltzPc7w)]

**Raising the Cost of Malicious AI-Powered Image Editing**\
[[ICML 2023](https://openreview.net/pdf?id=mSKJS7YbwU)]
[[Code](https://github.com/MadryLab/photoguard)]

**SemDeDup: Data-efficient learning at web-scale through semantic deduplication**\
[[Arxiv 2023](https://arxiv.org/abs/2303.09540)]

**DiffusionShield: A Watermark for Copyright Protection against Generative Diffusion Models**\
[[Arxiv 2023](https://arxiv.org/abs/2306.04642)]

**Destruction-Restoration Suppresses Data Protection Perturbations against Diffusion Models**\
[[ICTAI 2023](https://www.computer.org/csdl/proceedings-article/ictai/2023/427300a586/1T3deWq7u1y)]

**Anti-DreamBooth: Protecting users from personalized text-to-image synthesis**\
[[ICCV 2023](https://openaccess.thecvf.com/content/ICCV2023/papers/Van_Le_Anti-DreamBooth_Protecting_Users_from_Personalized_Text-to-image_Synthesis_ICCV_2023_paper.pdf)]
[[Project](https://anti-dreambooth.github.io/)]

**Can Protective Perturbation Safeguard Personal Data from Being Exploited by Stable Diffusion?**\
[[Arxiv 2023](https://arxiv.org/abs/2312.00084)]

**VA3: Virtually Assured Amplification Attack on Probabilistic Copyright Protection for Text-to-Image Generative Models**\
[[Arxiv 2023](https://arxiv.org/abs/2312.00084)]
[[Project](https://github.com/South7X/VA3)]

**Navigating Privacy and Copyright Challenges Across the Data Lifecycle of Generative AI**\
[[CAIN 2024](https://arxiv.org/abs/2311.18252)]

**Steal My Artworks for Fine-tuning? A Watermarking Framework for Detecting Art Theft Mimicry in Text-to-Image Models**\
[[Arxiv 2023](https://arxiv.org/abs/2311.13619)]

**WIP: Auditing Artist Style Pirate in Text-to-image Generation Models**\
[[NDSS](https://www.ndss-symposium.org/ndss-paper/auto-draft-534/)]

**MetaCloak: Preventing Unauthorized Subject-driven Text-to-image Diffusion-based Synthesis via Meta-learning**\
[[CVPR 2024](https://arxiv.org/pdf/2311.13127)]
[[Code](https://github.com/liuyixin-louis/MetaCloak)]

**Adversarial Example Does Good: Preventing Painting Imitation from Diffusion Models via Adversarial Examples**\
[[ICML 2023](https://proceedings.mlr.press/v202/liang23g.html)]
[[Code](https://github.com/psyker-team/mist)]

**On the Proactive Generation of Unsafe Images From Text-To-Image Models Using Benign Prompts**\
[[Arxiv 2023](https://arxiv.org/abs/2305.13873)]

**Salun: Empowering machine unlearning via gradient-based weight saliency in both image classification and generation**\
[[ICLR 2024](https://openreview.net/forum?id=gn0mIhQGNM)]
[[Code](https://github.com/OPTML-Group/Unlearn-Saliency)]

**To Generate or Not? Safety-Driven Unlearned Diffusion Models Are Still Easy To Generate Unsafe Images ... For Now**\
[[Arxiv 2023](https://arxiv.org/abs/2310.11868)]
[[Code](https://github.com/OPTML-Group/Diffusion-MU-Attack)]

**Ring-A-Bell! How Reliable are Concept Removal Methods For Diffusion Models?**\
[[ICLR 2024](https://openreview.net/forum?id=lm7MRcsFiS)]
[[Code](https://github.com/chiayi-hsu/Ring-A-Bell)]

**Improving Adversarial Attacks on Latent Diffusion Model**\
[[Arxiv 2023](https://arxiv.org/pdf/2310.04687)]

**Prompting4Debugging: Red-Teaming Text-to-Image Diffusion Models by Finding Problematic Prompts**\
[[Arxiv 2023](https://arxiv.org/abs/2309.06135)]
[[Code](https://github.com/joycenerd/P4D)]

**Catch You Everything Everywhere: Guarding Textual Inversion via Concept Watermarking**\
[[Arxiv 2023](https://arxiv.org/abs/2309.05940)]

**My Art My Choice: Adversarial Protection Against Unruly AI**\
[[Arxiv 2023](https://arxiv.org/abs/2309.03198)]

**DUAW: Data-free Universal Adversarial Watermark against Stable Diffusion Customization**\
[[ICLRW 2024](https://openreview.net/forum?id=XYD342nKy8)]

**Degeneration-Tuning: Using Scrambled Grid shield Unwanted Concepts from Stable Diffusion**\
[[ACM MM 2023](https://dl.acm.org/doi/10.1145/3581783.3611867)]

**Towards Safe Self-Distillation of Internet-Scale Text-to-Image Diffusion Models**\
[[ICMLW 2023](https://openreview.net/forum?id=6zALFeqxY0)]
[[Code](https://github.com/nannullna/safe-diffusion)]

**Generative Watermarking Against Unauthorized Subject-Driven Image Synthesis**\
[[Arxiv 2023](https://arxiv.org/abs/2306.07754)]

**Stable Diffusion is Unstable**\
[[NeurIPS 2023](https://openreview.net/forum?id=tesBViWnbx)]
[[Code](https://github.com/duchengbin8/Stable_Diffusion_is_Unstable)]

**Unlearnable Examples for Diffusion Models: Protect Data from Unauthorized Exploitation**\
[[Arxiv 2023](https://arxiv.org/abs/2306.01902)]

**Mist: Towards Improved Adversarial Examples for Diffusion Models**\
[[Arxiv 2023](https://arxiv.org/abs/2305.12683)]
[[Code](https://github.com/psyker-team/mist)]

**Inventing art styles with no artistic training data**\
[[Arxiv 2023](https://arxiv.org/pdf/2305.12015v2)]

**Selective Amnesia: A Continual Learning Approach to Forgetting in Deep Generative Models**\
[[NeurIPS 2023](https://openreview.net/forum?id=BC1IJdsuYB)]
[[Code](https://github.com/clear-nus/selective-amnesia)]

**Towards Prompt-robust Face Privacy Protection via Adversarial Decoupling Augmentation Framework**\
[[Arxiv 2023](https://arxiv.org/abs/2305.03980)]

**MACE: Mass Concept Erasure in Diffusion Models**\
[[CVPR 2024](https://arxiv.org/pdf/2403.06135)]

**Implicit Concept Removal of Diffusion Models**\
[[Arxiv 2023](https://arxiv.org/pdf/2310.05873)]

**Receler: Reliable Concept Erasing of Text-to-Image Diffusion Models via Lightweight Erasers**\
[[Arxiv 2023](https://arxiv.org/pdf/2311.17717)]

**All but One: Surgical Concept Erasing with Model Preservation in Text-to-Image Diffusion Models**\
[[Arxiv 2023](https://arxiv.org/pdf/2312.12807)]

**UnlearnCanvas: A Stylized Image Dataset to Benchmark Machine Unlearning for Diffusion Models**\
[[Arxiv 2024](https://arxiv.org/abs/2402.11846)]

**Removing Undesirable Concepts in Text-to-Image Generative Models with Learnable Prompts**\
[[Arxiv 2024](https://arxiv.org/pdf/2403.12326)]

**Rickrolling the Artist: Injecting Backdoors into Text Encoders for Text-to-Image Synthesis**\
[[ICCV 2023](https://openaccess.thecvf.com/content/ICCV2023/papers/Struppek_Rickrolling_the_Artist_Injecting_Backdoors_into_Text_Encoders_for_Text-to-Image_ICCV_2023_paper.pdf)]
[[Code](https://github.com/LukasStruppek/Rickrolling-the-Artist)]

**DP-LDMs: Differentially Private Latent Diffusion Models**\
[[Arxiv 2023](https://arxiv.org/abs/2305.15759)]

**CommonCanvas: An Open Diffusion Model Trained with Creative-Commons Images**\
[[NeurIPSW 2023](https://neurips.cc/virtual/2023/74893)]

**Dataset Deduplication with Datamodels**\
[[MIT Thesis 2022](https://dspace.mit.edu/handle/1721.1/144905)]

**Mitigating Inappropriateness in Image Generation: Can there be Value in Reflecting the World’s Ugliness?**\
[[ICMLW 2023](https://openreview.net/forum?id=hl9tJX9Fdx)]

**Toward effective protection against diffusion-based mimicry through score distillation**\
[[ICLR 2024](https://openreview.net/forum?id=NzxCMe88HX)]\
[[Code](https://github.com/xavihart/Diff-Protect)]

**Instructing Text-to-Image Generation Models on Fairness**\
[[Arxiv 2023](https://arxiv.org/pdf/2302.10893)]

**PriSampler: Mitigating Property Inference of Diffusion Models**\
[[Arxiv 2023](https://arxiv.org/abs/2306.05208)]

**Privacy-Preserving Low-Rank Adaptation for Latent Diffusion Models**\
[[Arxiv 2024](https://arxiv.org/abs/2402.11989)]
[[Code](https://github.com/WilliamLUO0/StablePrivateLoRA)]

**Imperceptible Protection Against Style Imitation from Diffusion Models**\
[[Arxiv 2024](https://arxiv.org/abs/2403.19254)]

**Concept Arithmetics for Circumventing Concept Inhibition in Diffusion Models**\
[[Arxiv 2024](https://arxiv.org/abs/2404.13706)]
[[Project](https://cs-people.bu.edu/vpetsiuk/arc/)]

**Watermark-embedded Adversarial Examples for Copyright Protection against Diffusion Models**\
[[Arxiv 2024](https://arxiv.org/abs/2404.09401)]

**SimAC: A Simple Anti-Customization Method for Protecting Face Privacy against Text-to-Image Synthesis of Diffusion Models**\
[[Arxiv 2024](https://arxiv.org/pdf/2312.07865)]
[[Code](https://github.com/somuchtome/SimAC)]

**Perturbing Attention Gives You More Bang for the Buck: Subtle Imaging Perturbations That Efficiently Fool Customized Diffusion Models**\
[[Arxiv 2024](https://arxiv.org/abs/2404.15081)]

**PAG: Protecting Artworks from Personalizing Image Generative Models**\
[[ICONIP 2023](https://link.springer.com/chapter/10.1007/978-981-99-8070-3_33)]

**Training Data Attribution for Diffusion Models**\
[[Arxiv 2023](https://arxiv.org/abs/2306.02174)]

**Circumventing Concept Erasure Methods For Text-To-Image Generative Models**\
[[ICLR 2024](https://openreview.net/forum?id=ag3o2T51Ht)]

**Towards Test-Time Refusals via Concept Negation**\
[[NeurIPS 2023](https://openreview.net/forum?id=d4X0QWS2Ln)]

**Machine Unlearning for Image-to-Image Generative Models**\
[[ICLR 2024](https://openreview.net/forum?id=9hjVoPWPnh)]
[[Code](https://github.com/jpmorganchase/i2i-generator-unlearning)]

**Espresso: Robust Concept Filtering in Text-to-Image Models**\
[[Arxiv 2024](https://arxiv.org/pdf/2404.19227)]

**Not All Similarities Are Created Equal: Leveraging Data-Driven Biases to Inform GenAI Copyright Disputes**\
[[ACM CSLAW 2024](https://arxiv.org/abs/2403.17691)]

**Separable Multi-Concept Erasure from Diffusion Models**\
[[Arxiv 2024](https://arxiv.org/abs/2402.05947)]

**Editing Massive Concepts in Text-to-Image Diffusion Models**\
[[Arxiv 2024](https://arxiv.org/abs/2403.13807)]
[[Project](https://silentview.github.io/EMCID/)]

**CPR: Retrieval augmented generation for copyright protection**\
[[CVPR 2024](https://arxiv.org/abs/2403.18920)]

**©Plug-in Authorization for Human Content Copyright Protection in Text-to-Image Model**\
[[Arxiv 2024](https://arxiv.org/abs/2404.11962)]

**SAFEGEN: Mitigating Unsafe Content Generation in Text-to-Image Models**\
[[Arxiv 2024](https://arxiv.org/abs/2404.06666)]

**Robust Concept Erasure Using Task Vectors**\
[[Arxiv 2024](https://arxiv.org/abs/2404.03631)]

**Get What You Want, Not What You Don't: Image Content Suppression for Text-to-Image Diffusion Models**\
[[ICLR 2024](https://openreview.net/forum?id=zpVPhvVKXk)]
[[Code](https://github.com/sen-mao/SuppressEOT)]

**IMMA: Immunizing text-to-image Models against Malicious Adaptation**\
[[Arxiv 2023](https://arxiv.org/abs/2311.18815)]

**An Economic Solution to Copyright Challenges of Generative AI**\
[[Arxiv 2024](https://arxiv.org/abs/2404.13964)]

## Medical Imaging

**Investigating Data Memorization in 3D Latent Diffusion Models for Medical Image Synthesis**\
[[MICCAIW](https://dl.acm.org/doi/abs/10.1007/978-3-031-53767-7_6)]

**Effect of Training Epoch Number on Patient Data Memorization in Unconditional Latent Diffusion Models**\
[[BVMW](https://link.springer.com/chapter/10.1007/978-3-658-44037-4_27)]

**Beware of diffusion models for synthesizing medical images -- A comparison with GANs in terms of memorizing brain MRI and chest x-ray images**\
[[Arxiv 2023](https://arxiv.org/abs/2305.07644)]

**Unconditional Latent Diffusion Models Memorize Patient Imaging Data**\
[[Arxiv 2023](https://arxiv.org/abs/2402.01054)]

**Brain tumor segmentation using synthetic MR images - a comparison of GANs and diffusion models**\
[[Scientific Data](https://www.nature.com/articles/s41597-024-03073-x)]

**Privacy Distillation: Reducing Re-identification Risk of Diffusion Models**\
[[MICCAIW](https://dl.acm.org/doi/abs/10.1007/978-3-031-53767-7_1)]


